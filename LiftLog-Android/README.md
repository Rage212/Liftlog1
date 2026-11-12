# LiftLog Android
Native Android WebView wrapper around the offline LiftLog workout tracker.

## Build without Android Studio
1. Create a new GitHub repository.
2. Upload the contents of this folder to the repository root (including `.github`).
3. Go to Actions → Build LiftLog APK → Run workflow.
4. When it completes, download the `LiftLog-APK` artifact, unzip it, and install `app-debug.apk` on your Android phone.

The debug APK is signed automatically by the Android build process for sideloading. Workout data is stored in the app's local WebView storage. Uninstalling the app can delete its stored data.

## Build with Android Studio
Open this folder as a project and use Build → Build APK(s).
