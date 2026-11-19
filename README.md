# Kaza Namazım Android

Offline-first Android WebView wrapper for the Kaza Namazım tracker.

## Build APK locally
- Install Android Studio and Android SDK (API 35), Java 17.
- Open this folder as a Gradle project.
- Run `gradle assembleDebug` (or use Android Studio's Build APK option).
- APK: `app/build/outputs/apk/debug/app-debug.apk`

## Build via GitHub Actions
Upload this project to a GitHub repository, then open Actions and run **Build Kaza Namazim APK**. Download the generated artifact.

No network permissions are requested. Tracking data uses browser local storage inside the WebView.
