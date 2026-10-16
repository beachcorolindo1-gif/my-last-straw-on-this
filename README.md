# Discord LAN Voice - Android Background Game Overlay APK

## New Features in v3.0:
1. **Foreground Service (`VoiceBackgroundService.java`):** Holds `WAKE_LOCK` and `WIFI_MODE_FULL_HIGH_PERF` so audio never disconnects when switching to games or when the screen turns off.
2. **Floating Game Overlay (`SYSTEM_ALERT_WINDOW`):** Floating Discord bubble rendered directly over any full-screen game (Mobile Legends, PUBG, Genshin, Roblox, etc.) with speaking indicator and quick Mute controls.
3. **Optimized Lightweight Build:** Zero heavy third-party bloat; builds cleanly into a fast ~2.5 MB APK.

## How to compile on GitHub:
1. Extract this ZIP and upload files directly to the root of your GitHub repository:
   - `build.gradle`
   - `settings.gradle`
   - `gradle.properties`
   - `.github/workflows/build-apk.yml`
   - `app/`
2. Go to the **Actions** tab on your GitHub repository.
3. Download `DiscordVoice-Installable-APK` and install `app-debug.apk` on your Android phone.
4. On your phone, tap "Allow Display over other apps" when prompted to enable the in-game floating overlay!
