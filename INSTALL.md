# Installing Prayer Focus Locker (Android 8.0 or newer)

## 1. Download
Open the Releases page and download ONE file:
- `PrayerFocusLocker-v1.0.0-arm64-v8a.apk`   -> most phones (recommended)
- `PrayerFocusLocker-v1.0.0-armeabi-v7a.apk` -> older 32-bit phones
- `PrayerFocusLocker-v1.0.0-universal.apk`   -> if unsure (bigger file, works on all)

## 2. Install
1. Open the downloaded file.
2. If asked, allow your browser or file manager to "Install unknown apps".
3. If Google Play Protect shows a warning, tap **More details -> Install anyway**.
   The app is new and open source, and it uses Accessibility and overlay permissions,
   which Play Protect is cautious about. You can read the code on GitHub.
   If there is no such option: Play Store -> profile icon -> Play Protect -> settings gear ->
   turn off "Scan apps with Play Protect", install, then turn it back on.

## 3. First launch (the app guides you)
Allow, in order: Notifications, Full-screen notifications (Android 14+), Accessibility,
Display over other apps, Camera, and Battery "No restrictions".

### Accessibility on Android 13 and newer ("restricted setting")
1. Try to turn on Accessibility once (a "restricted" message appears -> OK).
2. Settings -> Apps -> Prayer Focus Locker -> top-right menu (3 dots) -> **Allow restricted settings**.
3. Settings -> Accessibility -> Prayer Focus Locker -> turn it ON.

### Xiaomi / Oppo / Vivo / Realme / Samsung / Huawei
Turn on **Autostart**, set battery to **No restrictions**, and **lock the app in the Recents screen**
so "Clear all" does not stop it.

## 4. Set up inside the app
1. Settings: check the prayer calculation method and your location (if available) so times match your city.
2. Settings: set your emergency passcode.
3. Choose the apps to lock.
4. Pick a ringtone and, if you want, your masjid's jamaat times.
5. Test with a prayer time that is a few minutes away.

## Verify the file (optional)
In PowerShell: `Get-FileHash file.apk -Algorithm SHA256`
and compare the result with `SHA256SUMS.txt` from the same release.

## Updating
Install the new APK over the old one. Your settings are kept.
