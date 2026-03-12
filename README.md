# TamTalk

TamTalk is an Android-to-VST3 LAN voice streaming tool. It sends microphone audio from Android phones directly into the TamTalk VST plugin in your DAW/mixer.

No PC audio driver is required, so it won’t conflict with dedicated ASIO setups.

TamTalk is intended for users who run applications that can load VST3 plugins (such as DAWs and OBS) with an isolated audio interface or mixer (not configured as the system’s general input device).

## Release binaries

Prebuilt binaries are in the `release` folder:

- `release/vst/*.vst3`

Official releases: https://github.com/NickoCB/TamTalk/releases

Official APK release (Google Play): https://play.google.com/store/apps/details?id=com.nickobalbastro.tamtalk

## Default connection

- UDP port: `9240`
- Android app → TamTalk VST on the same LAN
