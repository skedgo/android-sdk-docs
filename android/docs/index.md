!!! note
    This documentation reflects the initial version of the TripKit SDK for Android. It is not finalized.
    
# Introduction

Using the TripKit SDK, you can quickly integrate SkedGo's award-winning trip planning platform with your own application
in a matter of minutes.

## Setup

To begin, you'll need both an SDK token as well as an API key to use our web service.

Sales will have given you your SDK token, and you can get an API key from our [Developer Page](https://developer.tripgo.com).

First, add our two Maven repositories to the list in `build.gradle`. Replace **MAVEN_TOKEN** with the token that you received
from us.

```kotlin
repositories {
    maven {
        credentials {
            username skedgo-developer
            password MAVEN_TOKEN
        }
        url "https://www.myget.org/F/skedgo/maven/"
    }
    maven { url "https://jitpack.io" }
}
```

Then, you'll need to add your TripGo API key. TripKit expects the key to be provided as `R.string.skedgo_api_key`,
so you can either add it to your `strings.xml` file, or use `resValue` in Gradle, or perhaps another way. 

Finally, add the two TripKit libraries to your dependencies. Check with SkedGo for the latest version number.

```kotlin
dependencies {
// ...
    implementation "com.skedgo.tripkit:TripKitAndroid:2.x"
    implementation "com.skedgo.tripkit:TripKitAndroidUI:2.x"
}
```
