# YAMLA

**Yet Another Morse Learning App**

YAMLA is an application for learning and practising Morse code reception.

It is designed around progressive listening practice, helping the user recognise Morse characters by sound rather than by counting dots and dashes.

## Features

- Progressive Morse code reception training
- Character-based learning progression
- Adjustable character speed
- Farnsworth timing
- Practice and listening modes
- Local learning progress and statistics
- Completely offline operation

## Offline and private

YAMLA is designed to work completely offline.

The application does not require an Internet connection and does not use:

- telemetry
- analytics
- advertising
- online accounts
- cloud services
- automatic update checks

Learning data and settings remain on the device.

YAMLA does not contact GitHub or any other service to check for new versions.

## Supported platforms

YAMLA is currently distributed for **Android**.

Other platforms may be considered in the future.

## Installation

Official builds of YAMLA are distributed through the **Releases** section of this repository.

To install YAMLA on Android:

1. Download the APK for the desired YAMLA release.
2. Verify its SHA-256 checksum if desired.
3. Open the downloaded APK on the Android device.
4. Android may ask for permission to install applications from this source.
5. Allow the installation for the application you used to open the APK, then continue with the installation.

This permission can be disabled again after YAMLA has been installed.

YAMLA is not installed through Google Play, so Android may display additional warnings when installing it manually.

## Updating YAMLA

YAMLA does not check for updates automatically.

To update an existing installation:

1. Download a newer official APK from the **Releases** section.
2. Optionally verify its SHA-256 checksum.
3. Open the APK and install it over the existing version.

Provided that the APK is an official YAMLA build signed with the same application signing key, Android will update the existing application rather than install a separate copy.

Application data and learning progress should be preserved during a normal update.

Uninstalling YAMLA before installing a newer version is neither necessary nor recommended, as uninstalling an application normally removes its local data.

## Verifying a download

Each official release provides a SHA-256 checksum for its APK.

After downloading the APK, calculate its SHA-256 hash and compare it with the value published with the release.

On Linux:

```bash
sha256sum YAMLA-*.apk
```

On Windows PowerShell:

```powershell
Get-FileHash .\YAMLA-*.apk -Algorithm SHA256
```

The calculated value must exactly match the checksum published with the release.

## Releases

Official YAMLA versions are published in the **GitHub Releases** section of this repository.

Each release will include the application package and its corresponding SHA-256 checksum.

Updates are intentionally manual: YAMLA itself never connects to GitHub to discover or download new versions.

## Source code

This repository is used for the public presentation and distribution of YAMLA.

It does **not** contain the application's source code.

## License

No license is currently granted for the application or its distributed binaries unless explicitly stated otherwise.
