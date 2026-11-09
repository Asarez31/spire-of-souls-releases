# Spire of Souls releases

Android builds of Spire of Souls, an AFK city-sim where summoned souls live, work and climb a mortal Spire. The source code lives in a private repo. This one only holds the builds and the file the app reads to update itself.

## Install

1. On your phone, open the [latest release](https://github.com/Asarez31/spire-of-souls-releases/releases/latest).
2. Download `SpireOfSouls-<version>-arm64.apk` and open it.
3. Android asks once to allow installs from your browser or file manager.

The app needs a 64-bit ARM phone (nearly every Android phone from the last several years).

## Updates

The app checks this repo when it starts and once a day after that. When there's a new version, it offers "Update to x.y.z". Tap UPDATE and it downloads the APK, checks it, and hands it to Android's installer. Your city stays as it is.

Android only installs an update over a copy signed with the same key, so every release here is signed with Spire of Souls' release key.

## What's in each release

- `SpireOfSouls-<version>-arm64.apk`: the Android app.
- `latest-android.json`: the version, notes, download link and the APK's SHA-256 and MD5. The in-app updater reads it.
