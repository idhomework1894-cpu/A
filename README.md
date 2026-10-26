# Android website app

Native Java WebView app generated with Applet.

## Build an APK

1. Install Android Studio and open this folder.
2. Use JDK 17 and install Android SDK 35. This project uses Android Gradle Plugin 8.7.3 and Gradle 8.9.
3. If Android Studio asks for a Gradle distribution, select Gradle 8.9. Wrapper scripts and the wrapper JAR are not bundled: let Android Studio configure Gradle or install Gradle 8.9 and run gradle wrapper.
4. Sync Gradle. Choose Build > Generate App Bundles or APKs > Generate APKs.
5. The debug APK is in app/build/outputs/apk/debug/. For publishing, generate a signed release in Android Studio.

Requires Android 8.0+. Website must support HTTPS and WebView. Camera, uploads, downloads, push notifications, and native permissions require additional implementation. The website controls its own authentication and content. No signing keys are included.
