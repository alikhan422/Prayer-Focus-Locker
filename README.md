# Prayer Focus Locker

An open-source Android app that helps you put the phone down at prayer time.
At each prayer time the apps you choose are locked, and they unlock only after you
perform a live **Ruku (bowing)** scan with the front camera.

Android 8.0 or newer. Not available for iPhone.

## Features
- Prayer-time alarm (works on the lock screen, home screen, or inside another app) with your own ringtone
- Locks the apps you select; phone calls, emergency calls, the clock app and your whitelist are never blocked
- Live Ruku scan using on-device pose detection (standing, then bowing, then holding)
- Manual jamaat time per prayer, and on/off per prayer
- Hidden emergency bypass with your own passcode (3 wrong tries disable it until the next scan)
- Reset Cycle in Settings, prayer history, Excused mode
- Urdu and English interface

## Install
See [INSTALL.md](INSTALL.md) and download the APK from the [Releases](../../releases/latest) page.

## Privacy
- Everything runs on your phone. Camera frames are processed in memory and are never saved or uploaded.
- Accessibility is used only to detect which app is in the foreground. The app is configured so it cannot read screen content, messages or passwords.
- The source code is here so you can check this yourself.

## Limits (please read)
- This is a self-discipline tool, not an unbreakable security system. Someone who really wants to can disable it in phone settings.
- Some phones (Xiaomi, Oppo, Vivo, Huawei, Samsung) close background apps aggressively. Follow the battery/autostart steps in INSTALL.md.
- Ruku detection needs good light, a side view and the full body in frame.

## Build from source
Needs JDK 17+ and the Android SDK:
`./gradlew assembleDebug`
Release builds need your own signing key in `keystore.properties` (not included in this repo).

## Support the developer (optional)
Settings -> Support inside the app. Totally optional; no feature depends on it.

## License
MIT. See [LICENSE](LICENSE).
