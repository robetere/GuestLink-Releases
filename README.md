# GuestLink

An independent, lightweight Android utility for authorised access to the Airbus-Guest Wi-Fi network.

[**Download APK releases**](https://github.com/robetere/GuestLink-Releases/releases) · [Licence](LICENSE)

## Downloads

This repository is the distribution channel for GuestLink. It contains release information and, when published, signed Android APKs. The application source code is private.

**Minimum requirement:** Android 9 (API 28).

The first public signed release is being prepared. If the Releases page is empty, no public APK has been published yet.

## Features

- Assisted guest-network registration and sign-in (experimental).
- Optional automatic processing of newly received Airbus credential SMS messages while a registration is pending.
- Manual credential import and import through Android's share menu.
- Adaptive single-SIM and dual-SIM configuration, including active eSIMs reported by Android.
- SIM selection based on configured preference, network service and signal quality.
- Encrypted local credential storage using Android Keystore.
- English and German interfaces, with automatic device-language selection.
- Light, dark and system appearance settings.
- Optional expiry reminders for long-term credentials only.
- Quick Settings shortcut and local connection diagnostics.
- Optional update checks against this repository's public release information.

## Installation and updates

1. Open the [Releases page](https://github.com/robetere/GuestLink-Releases/releases).
2. Choose the latest published stable release and download the `GuestLink-X.Y.Z.apk` asset.
3. Install the APK using Android's system installer. Only grant permissions you need and follow your device's security guidance.
4. Complete the setup wizard using your own registration details.

GuestLink can check for newer releases when opened, or manually from Settings. Installation remains user-controlled.

Official release APKs will use a consistent signing identity. A previous debug-signed test installation may require removal before installing the first permanently signed release. Uninstalling deletes locally stored app data, so retain your own registration details and original credential message if needed.

## Permissions and privacy

GuestLink has no advertising, analytics or dedicated developer-operated backend. Registration details and encrypted login credentials are kept locally and submitted to the authorised Airbus portal as needed.

Optional phone, SMS and notification permissions enable related features. Location permission assists Android Wi-Fi network identification; GuestLink does not track GPS movements. SMS permission may be restricted by Android or the device manufacturer. Manual import remains available without SMS access.

Optional update checks contact the public GitHub API without sending registration details or credentials. VPN settings and device security restrictions are not modified automatically.

## Development status

GuestLink is experimental. The application and its automated builds are under development; live portal compatibility, automatic registration and sign-in behaviour, and compatibility across Android devices still require validation.

## Licence and authorised use

GuestLink is proprietary software distributed under the [Limited Private-Use Licence v1.1](LICENSE). Invited or otherwise authorised recipients may download official releases for free personal use and private testing. Public download availability does not itself grant permission to use the software. Sharing the official release link is permitted; unauthorised redistribution of APK copies, resale and source-code distribution are prohibited. Read the licence before installation or use.

Use GuestLink only for your own authorised network access and in accordance with applicable network terms, employer policies and law.

## Disclaimer

GuestLink is an independent, unofficial utility. It is not an official Airbus product and is not affiliated with, sponsored by or endorsed by Airbus. Airbus and related marks belong to their respective owners.
