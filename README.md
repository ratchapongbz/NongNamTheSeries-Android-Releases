# NongNamTheSeries — Android APK

This repository contains versioned Android APK releases only. The application source remains private.

## Download

- [NongNamTheSeries 1.2.1 ARM64 APK](https://github.com/ratchapongbz/NongNamTheSeries-Android-Releases/releases/download/v1.2.1/NongNamTheSeries-1.2.1-arm64.apk)
- [SHA-256 checksum](https://github.com/ratchapongbz/NongNamTheSeries-Android-Releases/releases/download/v1.2.1/NongNamTheSeries-1.2.1-arm64.apk.sha256)
- [Latest release page](https://github.com/ratchapongbz/NongNamTheSeries-Android-Releases/releases/latest)

Releases use semantic tags (`vMAJOR.MINOR.PATCH`), matching versioned APK/checksum filenames. Published assets are immutable; updates receive a new version and a higher Android `versionCode`. See [VERSIONING.md](VERSIONING.md).

## Requirements

- Android 7.1 / API 25 or newer
- ARM64 (`arm64-v8a`) device

## Installation

1. Download the versioned `.apk` on the Android device.
2. Open the downloaded file.
3. If Android asks, allow **Install unknown apps** for the browser or file manager used to open it.
4. Confirm installation.

Do not disable Play Protect. Organization-managed devices may block sideloading.

## Integrity

On macOS or Linux, place the APK and checksum file in the same directory and run:

```bash
shasum -a 256 -c NongNamTheSeries-1.2.1-arm64.apk.sha256
```

Each release page records build metadata and known verification limits.
