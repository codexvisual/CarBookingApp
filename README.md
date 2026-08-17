# CarBooking (Taxi Rental App)

Android taxi rental application built with Java and the Android Support Library.

## Features
- Taxi / car rental booking UI
- Maps, places and location integration (Google Play Services)
- Circle image avatars, cards and material design components

## Requirements
- Android Studio
- JDK 8
- Android SDK 25 / Build Tools 25.0.3

## Installation
1. Clone the repository
   ```
   git clone https://github.com/codexvisual/CarBookingApp.git
   ```
2. Open the folder in **Android Studio**
3. Let Gradle sync (this may take a few minutes)
4. Connect a device or start an emulator (min API 16)
5. Click **Run ▶**

## Build (command line)
```
./gradlew assembleDebug
```
The APK will be generated at `app/build/outputs/apk/debug/`.

## Notes
- Requires a Google Maps API key in `AndroidManifest.xml` for map features.