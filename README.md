# GMS

Google Mobile Services (GMS) &amp; Google Play Services &amp; GMS Core

# google-play-services


https://www.apkmirror.com/apk/google-inc/google-play-services/google-play-services-11-3-02-release/

## XYZ

> look at the 3-digit sequence (let's use XYZ) in the parentheses:

1. `4` for Android 5.0 and 5.1 before Play Services v8, Android >= 6.0 after
2. `4` for arm64-v8a
3. `0` for universal

> 440


```md
    
App Notes:
To figure out the right version of Google Play services for your Android device, download Play Services info or go to Settings -> Apps -> Google Play services, and look at the 3-digit sequence (let's use XYZ) in the parentheses:

* X defines Android version:

0 for Android <5.0
2 for Android 5.0 and 5.1 starting with Play Services v8
4 for Android 5.0 and 5.1 before Play Services v8, Android >= 6.0 after
5 for Android Wear
7 for Android 5.0
8 for Android TV
* Y defines CPU architecture:

1 for armeabi
3 for armeabi-v7a
4 for arm64-v8a
5 for mips
7 for x86
8 for x86_64
* Z defines DPI:

0 for universal
2 for 160
4 for 240
6 for 320
8 for 480
Notes:

It seems that 7YZ builds became 4YZ with Google Play services v6.5. If you were on 7YZ before, you should now install 4YZ.
It seems that 4YZ builds got split into 2YZ for Lollipop and 4YZ for Marshmallow with Google Play services v8. If you were on 4YZ before, you should now install 2YZ in Lollipop and 4YZ in Marshmallow.
Examples:

014 for Android <5.0 armeabi CPU 240 DPI device
438 for Android 6.0+ armeabi-v7a CPU 480 DPI device
876 for Android TV x86 CPU 320 DPI device
```



# GmsCore

https://github.com/microg/android_packages_apps_GmsCore/wiki/Downloads

https://microg.org/download.html


