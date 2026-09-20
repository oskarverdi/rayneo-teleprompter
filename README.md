# Teleprompt for RayNeo X2

An Android teleprompter for RayNeo X2 glasses. Download the signed APK from this repository's Releases section.

## Version 1.1.0

- Import your own UTF-8 `.txt` script using the file picker or USB.
- Read mirrored text on both displays.
- Use adjustable automatic scrolling or offline Russian voice following.
- Adjust text size and operate the menu using the glasses touchpad.
- Long press opens the import and voice menu.

Scripts remain on the device. Microphone access is used only during voice following. Audio is not stored or uploaded. The app does not require an account or internet connection.

## Installation

Download `rayneo-teleprompter-1.1.0-release.apk` from Releases and install it on RayNeo X2. With Android platform tools and USB debugging enabled:

```sh
adb install -r rayneo-teleprompter-1.1.0-release.apk
```

Package: `dev.rayneo.teleprompter`; version code: `3`; architecture: `arm64-v8a`; Android 12 or later.

See `USER-GUIDE-RU.md` for Russian instructions. Release attachments include screenshots captured from the actual app in an Android emulator at 1920 × 1080.

## Verification

The release passed 10 unit tests and 5 Android instrumentation tests. APK signing was verified against the existing release certificate. Physical RayNeo X2 microphone, touch hardware, and optical alignment have not yet been verified.

## Third-party components

Offline speech recognition uses Vosk and its small Russian model. See `THIRD-PARTY-NOTICES.txt` and `APACHE-2.0.txt` for bundled component notices. Those licenses apply to their respective components.

This repository distributes the application release and documentation. Publication here is not a government copyright registration or a statement of RayNeo approval.
