> [!CAUTION]
> **MOTO-HUB ADVANCED is deprecated and no longer developed. 1.1.119 is its last release.**
> It is replaced by **[MOTO-HUB ADV-SOLO](https://github.com/vincenzobpt/MOTO-HUB-ADV-SOLO-releases)**: one free app that does the work of ADVANCED and MOTO-HUB CORE together.
> Already using ADVANCED? Update it, and it walks you to ADV-SOLO, which brings over your motorcycles, rides, places, keys and settings.

<div align="center">

<img src="https://raw.githubusercontent.com/vincenzobpt/MOTO-HUB/main/media/logo.png" alt="MOTO-HUB ADVANCED logo" width="120">

# MOTO-HUB ADVANCED

**Deprecated. Replaced by [MOTO-HUB ADV-SOLO](https://github.com/vincenzobpt/MOTO-HUB-ADV-SOLO-releases).**

[![Latest release](https://img.shields.io/github/v/release/vincenzobpt/MOTO-HUB-PRO-releases?label=release&color=e10600)](https://github.com/vincenzobpt/MOTO-HUB-PRO-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/vincenzobpt/MOTO-HUB-PRO-releases/total?color=e10600)](https://github.com/vincenzobpt/MOTO-HUB-PRO-releases/releases)
[![Deprecated](https://img.shields.io/badge/status-deprecated-lightgrey)](https://github.com/vincenzobpt/MOTO-HUB-ADV-SOLO-releases)
[![Android 14+](https://img.shields.io/badge/Android-14%2B-3DDC84?logo=android&logoColor=white)](#installation)
[![Discord](https://img.shields.io/badge/Discord-join%20the%20community-5865F2?logo=discord&logoColor=white)](https://discord.gg/FzhXZtPhC8)
[![Website](https://img.shields.io/badge/website-motohub.techub.eu-111111)](https://motohub.techub.eu)

<img src="https://raw.githubusercontent.com/vincenzobpt/MOTO-HUB-ADV-SOLO-releases/main/media/phone-dash-visor.webp" alt="MOTO-HUB ADV-SOLO: the Visor Ride Dashboard full screen on a phone" width="700">
<br>
<sub>MOTO-HUB ADV-SOLO, the app that replaces ADVANCED: the Ride Dashboard on the bike's TFT, or full screen on the phone.</sub>

ADVANCED was the free companion of [MOTO-HUB CORE](https://github.com/vincenzobpt/MOTO-HUB): CORE connected the bike, ADVANCED added the Ride Dashboard, navigation, trips and the rest.<br>
**ADV-SOLO does all of it in one app**, with no CORE to install, and keeps getting new features.

<br>

[![Get MOTO-HUB ADV-SOLO](https://img.shields.io/badge/Get%20MOTO--HUB%20ADV--SOLO-the%20app%20that%20replaces%20ADVANCED-e10600?style=for-the-badge&logo=android&logoColor=white)](https://github.com/vincenzobpt/MOTO-HUB-ADV-SOLO-releases/releases/latest)

🌐 **[motohub.techub.eu](https://motohub.techub.eu)**: getting started, release notes and the community dashboard gallery.

<br>

### 💬 Come and ride with us

**Every rider here is on Discord** — support when a dashboard misbehaves, help getting your bike working, early builds, and the place where the next features get decided.

[![Join the MOTO-HUB Discord](https://img.shields.io/badge/JOIN%20THE%20MOTO--HUB%20DISCORD-support%20·%20community%20·%20new%20builds-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/FzhXZtPhC8)

</div>

**This repository contains no source code.** MOTO-HUB ADVANCED's source is closed and private. Only signed release APKs are published here, under the [Releases](../../releases) tab; **1.1.119** is the last one.

## Moving to ADV-SOLO

1. **Update ADVANCED to 1.1.119**, the last release. It shows you the way to ADV-SOLO.
2. **Install [ADV-SOLO](https://github.com/vincenzobpt/MOTO-HUB-ADV-SOLO-releases/releases/latest).** On first launch it brings over your motorcycles, rides, audio notes, places, keys and settings from ADVANCED.
3. **Remove ADVANCED and CORE** when ADV-SOLO asks. Android Auto is a module in ADV-SOLO, one tap away in **Settings ▸ Modules**.

Everything ADVANCED did is in ADV-SOLO, plus what came after it, such as the Ride Dashboard full screen on the phone, community dashboards, Bluetooth handlebar remotes and an engine page for every ride. The full list is on the [ADV-SOLO page](https://github.com/vincenzobpt/MOTO-HUB-ADV-SOLO-releases).

## Installation

> [!CAUTION]
> **Don't install ADVANCED on a new phone.** Install [MOTO-HUB ADV-SOLO](https://github.com/vincenzobpt/MOTO-HUB-ADV-SOLO-releases/releases/latest) instead. The steps below are kept only for riders updating an existing ADVANCED to its last release, so it can move them to ADV-SOLO.

> [!IMPORTANT]
> **MOTO-HUB must be installed for ADVANCED to work**, and both must be the **same version**.
> The two apps are released together under one version number and talk to each other over an
> interface that changes between releases — a mismatched pair may fail to connect.

1. Install [MOTO-HUB](https://github.com/vincenzobpt/MOTO-HUB/releases/latest) first and pair it with your T-Box.
2. Download the ADVANCED APK with the **same version number** from [Releases](../../releases).
3. Enable "Install unknown apps" for your browser or file manager when Android asks.
4. Install the ADVANCED APK (blocked by Play Protect? [see below](#app-blocked-to-protect-your-device--google-play-protect)).

Both apps can check for updates themselves and will offer the matching release. ADVANCED requires **Android 14 or newer** (MOTO-HUB itself runs on Android 12+).

### "App blocked to protect your device" — Google Play Protect

On some phones Play Protect refuses the install with only a **Got it** button. **This is not a malware detection.** Google blocks every app installed from a browser, messaging app or file manager if it asks for notification access or accessibility. ADVANCED uses notification access for the Now Playing widget, and it stays off until you grant it yourself.

To install anyway:

1. Open the **Play Store**, tap your profile picture, then **Play Protect** → ⚙️ (top right).
2. Turn off **Scan apps with Play Protect**.
3. Install the ADVANCED APK.
4. Go back and turn **Scan apps with Play Protect** on again.

If an update is blocked the same way, repeat these steps.

## Privacy

MOTO-HUB ADVANCED works without an account and records rides only on the phone. Trips, tracks and GPX exports stay on the device.

Features that need the Internet disclose only what that request needs, to the service that answers it and to no MOTO-HUB account: map tiles for the area being displayed, a typed search to the geocoder, an origin/destination pair to the routing service, destination and arrival time to the weather service. The AI tab talks to an OpenAI-compatible endpoint using **the rider's own API key**, which is stored encrypted with the Android Keystore, sent only as an authorization header, and never logged.

Like MOTO-HUB, official ADVANCED releases report **crashes and errors to Sentry** (EU region) so that failures which need a motorcycle to reproduce can be diagnosed. Sentry's default PII collection is switched off, diagnostic messages are redacted and capped per app run, and grouping tags are deliberately coarse. Screen content, T-Box passwords and recorded positions are never sent. Turning off `Settings ▸ Diagnostics ▸ Enable logging` stops the diagnostic log and the error events that come from it; crash reports are handled by the Sentry SDK itself and are not covered by that switch.

**Diagnostics reports.** After a one-time notice at first launch, ADVANCED also sends a diagnostics report to the developer's own collector — dashboard identity and saved motorcycle profiles (never the Wi-Fi password), phone model and Android version, Android Auto / CORE / ADVANCED versions, and the redacted ADVANCED + CORE diagnostic log — at most once a day, after an update, or after a crash, only over a connection with Internet access. Each report carries a **Support ID** (a one-way hash of Android's per-app installation id and the active motorcycle; shown under `Settings ▸ Diagnostics`, also attached to Sentry events as the user id). Quote it when asking for help. `Settings ▸ Diagnostics ▸ Send diagnostics automatically` turns it off; `Send diagnostics now` sends one on request.

## Status

MOTO-HUB ADVANCED is no longer developed: it receives no fixes and no new features. MOTO-HUB was always an experimental proof-of-concept, not a production-grade product. Do not depend on it as your only source of critical navigation information, and use the software at your own risk.

> [!NOTE]
> **Riding with an iPhone?** MOTO-HUB for iOS is available now — install it through AltStore Classic or sideload the IPA from [its own releases page](https://github.com/vincenzobpt/MOTO-HUB-IOS-releases). Requires iOS 17 or later.

## Community

<div align="center">

[![Discord](https://img.shields.io/badge/JOIN%20US%20ON%20DISCORD-support%20·%20community%20·%20development-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/FzhXZtPhC8)

</div>

News, release notes and the dashboard gallery are on **[motohub.techub.eu](https://motohub.techub.eu)**.

## License

MOTO-HUB ADVANCED is proprietary, closed-source software. Distribution here does not grant any license to the source code. MOTO-HUB CORE itself remains fully open source under AGPL-3.0.

ADVANCED contains no GPL-3.0/AGPL-3.0 code of its own. It reaches MOTO-HUB's T-Box transport and Android Auto receiver exclusively through a Binder IPC bridge exposed by the MOTO-HUB app, which is why the two are licensed differently.
