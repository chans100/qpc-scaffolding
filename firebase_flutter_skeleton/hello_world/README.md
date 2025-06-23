# Flutter + Firebase Skeleton

This is a minimal Flutter project skeleton pre-configured for Firebase (Android only).

## Setup Instructions

1. **Create a Firebase Project**
   - Go to [Firebase Console](https://console.firebase.google.com/).
   - Click "Add project" and follow the prompts.

2. **Register Your Android App**
   - In the Firebase Console, click the Android icon to add an app.
   - Enter your app's package name (see `android/app/src/main/AndroidManifest.xml`).
   - (Optional) Enter an app nickname and SHA-1 (not required for basic setup).
   - Click "Register app".

3. **Download `google-services.json`**
   - After registering, download the `google-services.json` file.
   - Place it in: `android/app/google-services.json`

4. **Install Dependencies**
   - Run `flutter pub get` in the `hello_world` directory.

5. **Run the App**
   - Use `flutter run` to launch the app on an Android device or emulator.

## Firebase Features Included
- Core (`firebase_core`)
- Authentication (`firebase_auth`)
- Firestore Database (`cloud_firestore`)
- Storage (`firebase_storage`)
- Messaging (`firebase_messaging`)
- Analytics (`firebase_analytics`)

---

**This skeleton is ready for further development!**

## To run the Hello World demo:
```sh
flutter run
```
## To run the Hello World demo showing Arabic:
```sh
flutter run lib/arabic.dart
```
