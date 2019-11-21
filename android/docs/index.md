!!! note
    This documentation reflects the initial version of the TripKit SDK for Android. It is not finalized.
    
# Introduction

Using the TripKit SDK, you can quickly integrate SkedGo's award-winning trip planning platform with your own application
in a matter of minutes.

## Setup

To begin, you'll need both an SDK token as well as an API key to use our web service.

Sales will have given you your SDK token, and you can get an API key from our [Developer Page](https://developer.tripgo.com).

First, add our Maven repository to the list in `build.gradle`. Replace **MAVEN_TOKEN** with the token that you received
from us.

```kotlin
repositories {
    mavenLocal()
    maven {
        credentials {
            username skedgo-developer
            password MAVEN_TOKEN
        }
        url "https://www.myget.org/F/skedgo/maven/"
    }
}
```

Then you can add the two TripKit libraries to your dependencies.
```kotlin
dependencies {
// ...
    implementation "com.skedgo.tripkit:TripKitAndroid:2.+"
    implementation "com.skedgo.tripkit:TripKitAndroidUI:2.+"
}
```
