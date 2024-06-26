# TripKit SDK for Android

Using the TripKit SDK, you can quickly integrate SkedGo's award-winning trip planning platform with your own application
in a matter of minutes.

## Setup

To begin, you'll need an API key to use our web service. You can get an API key from our [Developer Page](https://developer.tripgo.com).

First, add the Maven repository to the list in `build.gradle`:

```kotlin
repositories {  
    maven { url "https://jitpack.io" }
}
```

TripKit supports Android apps running Android 4.0.3 and above. To make sure that it works in your Android app, please specify `minSdkVersion` in your `build.gradle` file:

```kotlin
android {
  defaultConfig {
    minSdkVersion 16
  }
}
```

Get a Google Maps API key from [Google Maps Platform](https://developers.google.com/maps/documentation/android-sdk/get-api-key) and make sure to enable the [Places API](https://console.cloud.google.com/apis/library/places-backend.googleapis.com?_gl=1*15naeh9*_ga*MjA2NzAyMTMwNS4xNjMwNTg4ODYw*_ga_NRWSTWS78N*MTY3MjkwNzQ4Ni40LjEuMTY3MjkwNzQ4OC4wLjAuMA..&project=mrwa-0001). Then add the Google Maps API key on your project's [Manifest](https://developer.android.com/guide/topics/manifest/manifest-intro)

```XML
<manifest package="....
  ....
  <application...

    <meta-data
          android:name="com.google.android.geo.API_KEY"
          android:value="YOUR_API_KEY_HERE" />

    ....

    </application>
</manifest>
```


Then, you'll need to add your TripGo API key. TripKit expects the key to be provided as `R.string.skedgo_api_key`,
so you can either add it to your `strings.xml` file, or use `resValue` in Gradle, or perhaps another way. 

Finally, add libraries to your dependencies. Check with SkedGo for the latest version number.

## For TripKit only

```kotlin
dependencies {
// ...
    implementation 'com.github.skedgo:tripkit-android:<insert-newest-version-here>'
}
```

### Create TripKit instance to access TripKit's services

We recommend to have an `Application` subclass. Next, in the `onCreate()` method, you can initiate following setup:

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
    implementation 'com.github.skedgo:tripkit-android-ui:<insert-newest-version-here>'
}
```

### Create TripKitUI instance to access both TripKitUI and TripKit services

We recommend to have an `Application` subclass. Next, in the `onCreate()` method, you can initiate following setup:

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
