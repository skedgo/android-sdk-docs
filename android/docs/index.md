# TripKit SDK for Android

Using the TripKit SDK, you can quickly integrate SkedGo's award-winning trip planning platform with your own application
in a matter of minutes.

## Setup

To begin, you'll need both an SDK token as well as an API key to use our web service.

Sales will have given you your SDK token, and you can get an API key from our [Developer Page](https://developer.tripgo.com).

First, add Maven repository to the list in `build.gradle`.

```kotlin
repositories {  
    maven { url "https://jitpack.io" }
}
```

TripKit supports for Android apps running Android 4.0.3 and above. To make sure that it works in your Android app, please specify minSdkVersion in your build.gradle file

```kotlin
android {
  defaultConfig {
    minSdkVersion 16
  }
}
```

Then, you'll need to add your TripGo API key. TripKit expects the key to be provided as `R.string.skedgo_api_key`,
so you can either add it to your `strings.xml` file, or use `resValue` in Gradle, or perhaps another way. 

Finally, add libraries to your dependencies. Check with SkedGo for the latest version number.

## For TripKit only
```kotlin
dependencies {
// ...
    implementation 'com.github.skedgo.tripkit-android:TripKitAndroid:<insert-newest-version-here>'
}
```

### Create TripKit instance to access TripKit's services

We recommend to have an Application subclass. Next, in the onCreate() method, you can initiate following setup:

> v2.1.43
```kotlin
class App : Application() {
  override fun onCreate() {
    super.onCreate()
    JodaTimeAndroid.init(this)
    
    TripKitConfigs.builder().context(this)
            .debuggable(true)          
            .key { key }
            .build()

	val httpClientModule = HttpClientModule(null, null, configs)

	val tripKit = DaggerTripKit.builder()
                .mainModule(MainModule(configs))
                .httpClientModule(httpClientModule)
                .build()

    TripKit.initialize(this, tripKit)            
  }
}
```

## For TripKitUI (also includes TripKit)
```kotlin
dependencies {
// ...
    implementation 'com.github.skedgo.tripkit-android-ui:TripKitAndroidUI:<insert-newest-version-here>'
}
```

### Create TripKitUI instance to access both TripKitUI and TripKit services

We recommend to have an Application subclass. Next, in the onCreate() method, you can initiate following setup:

> v2.1.43
```kotlin
class App : Application() {
  override fun onCreate() {
    super.onCreate()

    val baseConfig = TripKitUI.buildTripKitConfig(applicationContext, Key.ApiKey("api_key_here"))
    val httpClientModule = HttpClientModule(null, BuildConfig.VERSION_NAME, baseConfig, getSharedPreferences("data_pref_name", MODE_PRIVATE))

    val appConfigs = TripKitConfigs.builder().from(baseConfig).build()
    TripKitUI.initialize(this, Key.ApiKey("api_key_here"), appConfigs, httpClientModule)       
  }
}
```
