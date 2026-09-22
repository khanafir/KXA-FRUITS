# KXA Apple Stock — Android Project

This is a native Android Studio project that packages the KXA Apple Stock interface as an installable Android app.

## Included
- Daily Picking
- CA Store dispatch
- Vehicle / Owner
- Free-text Khata field (required)
- Variety: Red Delicious, Delicious, Golden
- Day-by-day totals
- Reports and variety breakdown
- Offline local storage in the app

## Build an APK
1. Open this folder in Android Studio.
2. Let Gradle sync.
3. Select **Build > Build APK(s)**.
4. The debug APK will be under:
   `app/build/outputs/apk/debug/app-debug.apk`

The project uses a WebView wrapper around the offline app UI stored in `app/src/main/assets/index.html`.
