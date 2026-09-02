# te-apk

Funkin KeyboardMod APK — keyboard + touchscreen work 100%.

## Latest Release

APK too large (866MB) for git, so it's distributed via GitHub Releases:

**Download:** https://github.com/SAFL07-PRIME/te-apk/releases/latest

## File

- `Funkin-KeyboardMod-0.8.7-arm64-WORKING.apk`
- Size: ~866 MB
- Architecture: arm64-v8a
- Android: minSdk 28 (Android 9+), targetSdk 36
- Package: `me.funkin.fnf` (intentionally NOT using original FunkinCrew package to avoid conflicts with the original game)
- Signature: v2 scheme, self-signed (CN=Funkin Keyboard Mod, OU=Mod, O=KeyboardKu, L=Jakarta)

## Install

1. Uninstall any previous version of Funkin first (different signature → install will fail otherwise)
2. Allow "Install from unknown sources" if needed
3. Install the APK

## Notes

- Keyboard support: yes
- Touchscreen support: yes (android.hardware.touchscreen is optional)
- Source: based on FunkinCrew/Funkin with keyboard mod
