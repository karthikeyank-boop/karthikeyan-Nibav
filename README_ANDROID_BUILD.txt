NIBAV FLEET FUEL MANAGER - ANDROID PROJECT


What this is
-------------
This is an Android Studio project wrapping the current Fleet Fuel Manager HTML app in an Android WebView. The HTML application is bundled locally and can operate offline. The Android wrapper enables JavaScript and persistent WebView DOM storage, supports selecting a JSON backup for restore, and includes basic download handoff.


Build the APK
--------------
1. Install Android Studio on a Windows PC/Mac/Linux computer.
2. Open Android Studio and choose File > Open.
3. Select this extracted folder: NibavFleetFuelManager
4. Allow Gradle sync to complete. If prompted, install Android SDK Platform 35 and the compatible Android Build Tools.
5. Select Build > Build Bundle(s) / APK(s) > Build APK(s).
6. When build completes, click Locate. The APK will be under app/build/outputs/apk/debug/app-debug.apk.
7. Transfer the APK to your Android phone and install it. If Android prompts, allow installation from this source.


Important data notes
--------------------
- Data is stored locally in the WebView/browser storage on the phone. It does not sync automatically with your PC or other phones.
- Use the in-app Backup option regularly and keep the JSON backup in a safe location.
- This project is a build-ready wrapper, not a precompiled APK. The current work environment does not have Android SDK/Gradle installed, so a signed/compiled APK cannot be produced here.
- Backup/restore and file downloads should be tested on the target Android version after the APK is built.


Project details
--------------
Package: com.nibav.fleetfuelmanager
App name: Nibav Fleet Fuel Manager
Version: 1.0
Min Android: 6.0 (API 23)
Target/compile Android SDK: 35
