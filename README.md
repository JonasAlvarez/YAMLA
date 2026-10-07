# YAMLA

**Yet Another Morse Learning App**

YAMLA is an offline Android application for learning and practising Morse code reception by listening.

It is designed around progressive listening practice, helping the user recognise Morse characters by sound rather than by counting dots and dashes.

**Current stable version: YAMLA 1.0.0**

[Download YAMLA 1.0.0](https://github.com/JonasAlvarez/YAMLA/releases/latest)

## Features

- Progressive Morse code reception training
- Five selectable learning orders: YAMLA, LCWO.net, Koch, G4FON, and alphabetical / numeric
- Adaptive practice that gives more weight to characters that need more work
- Per-character knowledge tracking and practice statistics
- Practice with individual characters and progressively longer groups
- Continuous listening mode
- Adjustable Morse speed and Farnsworth timing
- Letters, numbers and common Morse symbols
- Option to practise or listen using all characters independently of the current learning progression
- Real-text listening and practice
- Background audio support on Android
- Configurable learning and session settings
- English and Spanish interface
- Completely offline operation

## Learning approach

YAMLA introduces characters progressively and tracks performance independently for each character.

Practice is adaptive: characters with less consolidated knowledge are selected more often, while already well-known characters continue to be reviewed.

Statistics are preserved when changing learning order, so previously acquired knowledge is retained even when a character appears at a different point in another curriculum.

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

## Download and installation

Official builds of YAMLA are distributed through the [Releases](https://github.com/JonasAlvarez/YAMLA/releases) section of this repository.

YAMLA 1.0.0 provides three Android APKs:

- **arm64-v8a** — recommended for most current Android phones and tablets
- **armeabi-v7a** — for older 32-bit ARM Android devices
- **x86_64** — primarily for x86_64 devices and emulators

If you are unsure which version to use, **arm64-v8a is normally the right choice for a modern Android device**.

To install YAMLA on Android:

1. Download the appropriate APK from the latest release.
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

Each official release provides a `SHA256SUMS.txt` file containing the SHA-256 checksums for its APKs.

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

## Background listening

On some Android devices, aggressive battery optimisation may interrupt long listening sessions while the screen is off. If this occurs, disabling battery optimisation for YAMLA may help.

## Releases

Official YAMLA versions are published in the [GitHub Releases](https://github.com/JonasAlvarez/YAMLA/releases) section of this repository.

Updates are intentionally manual: YAMLA itself never connects to GitHub to discover or download new versions.

## Source code

This repository is used for the public presentation and distribution of YAMLA.

It does **not** contain the application's source code.

## License

No license is currently granted for the application or its distributed binaries unless explicitly stated otherwise.
