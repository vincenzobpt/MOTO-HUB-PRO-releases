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

<img src="https://raw.githubusercontent.com/vincenzobpt/MOTO-HUB/main/media/tft-ride-dashboard.png" alt="MOTO-HUB ADVANCED Ride Dashboard on the motorcycle TFT" width="700">

[MOTO-HUB](https://github.com/vincenzobpt/MOTO-HUB) (free, open source) connects your bike: pairing, the T-Box link, Android Auto, mirroring, handlebar buttons.<br>
**ADVANCED** (free, this page) builds everything else on top of the rider's own GPS: a native **Ride Dashboard**, motorcycle **Navigation**, **Trips** with replay and analysis, **AI place discovery**, **group intercom** and more.

<br>

[![Get MOTO-HUB ADV-SOLO](https://img.shields.io/badge/Get%20MOTO--HUB%20ADV--SOLO-the%20app%20that%20replaces%20ADVANCED-e10600?style=for-the-badge&logo=android&logoColor=white)](https://github.com/vincenzobpt/MOTO-HUB-ADV-SOLO-releases/releases/latest)

<sub>The rest of this page describes ADVANCED as it was. Everything here, and more, is in ADV-SOLO.</sub>

<br>

### 💬 Come and ride with us

**Every rider here is on Discord** — support when a dashboard misbehaves, help getting your bike working, early builds, and the place where the next features get decided.

[![Join the MOTO-HUB Discord](https://img.shields.io/badge/JOIN%20THE%20MOTO--HUB%20DISCORD-support%20·%20community%20·%20new%20builds-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/FzhXZtPhC8)

</div>

**This repository contains no source code.** MOTO-HUB ADVANCED's source is closed and private. Only signed release APKs are published here, under the [Releases](../../releases) tab.

## What ADVANCED adds

| | [MOTO-HUB](https://github.com/vincenzobpt/MOTO-HUB) | MOTO-HUB ADVANCED |
| --- | :---: | :---: |
| T-Box pairing, garage, connection | ✅ | uses MOTO-HUB |
| Android Auto on the TFT | ✅ | delegated to MOTO-HUB |
| Screen mirroring | ✅ | ✅ |
| Handlebar button control | ✅ | ✅ |
| **Ride Dashboard** — native GPS scene on the TFT | — | ✅ |
| **Navigation** — search, motorcycle routing, rich route preview | — | ✅ |
| **Route intelligence** — weather along the route, fuel prices, speed cameras | — | ✅ |
| **Trips** — full-telemetry recording, replay, analysis, GPX | — | ✅ |
| **Riding Coach** — post-ride AI evaluation | — | ✅ |
| **AI place discovery** | — | ✅ |
| **Group intercom** — rider-to-rider voice | — | ✅ |
| **Audio notes** pinned to your trips | — | ✅ |
| **OBD-II diagnostics suite** — hidden somewhere in the app 🤫 | — | 🥚 |

### 🏍️ Ride Dashboard

A native, configurable riding scene rendered straight on the TFT: GPS speed, live map, trip stats, weather, phone status — every panel is a widget you choose, and panels can rotate through a carousel. The main panel is yours too: put the **live map** there, run **Android Auto embedded** inside it, or switch it to a full **OBD gauge cluster** with live engine data and gear estimation (ELM327 Bluetooth adapter required). Turn-by-turn guidance from Waze or Google Maps shows up in the Navigation widget.

<div align="center">
  <img src="https://raw.githubusercontent.com/vincenzobpt/MOTO-HUB/main/media/tft-dashboard-aa.png" alt="Android Auto embedded inside the Ride Dashboard map panel" width="560">
</div>

### 🗺️ Navigation, built for motorcycles

Search, motorcycle routing (including *curvy roads*), waypoints, and a route preview that is a full briefing: **where the curves are** and what the twisty line costs you against the fast one, **the shape of the ride** (ascent, turns, elevation profile), **weather along the route** (rain cells with the time you'll meet them, crosswind, ice risk), **live fuel prices** on your path in 🇮🇹 🇪🇸 🇫🇷 🇵🇹, **speed camera alerts** (off by default, disabled where the law forbids them), and **Mapillary street-level imagery** with a tap on the route line.

<div align="center">
  <img src="https://raw.githubusercontent.com/vincenzobpt/MOTO-HUB/main/media/phone-nav-preview-1.png" alt="Route preview showing where the curves are and the Fast or Piega route choice" width="230">
  &nbsp;
  <img src="https://raw.githubusercontent.com/vincenzobpt/MOTO-HUB/main/media/phone-nav-preview-2.png" alt="Route briefing with ascent, turns, elevation profile and petrol prices on the route" width="230">
  &nbsp;
  <img src="https://raw.githubusercontent.com/vincenzobpt/MOTO-HUB/main/media/phone-nav-preview-3.png" alt="Weather along the route with temperature and crosswind at each stage" width="230">
  <br>
  <sub>Where the curves are and what they cost you in time &middot; ascent, turns, elevation and petrol on the way &middot; the weather you will actually meet.</sub>
</div>

### 📈 Trips — record, relive, improve

Full sensor telemetry on every ride: replay it on the map, in a **3D chase-cam POV**, or as a **Google Earth KMZ** flyover; analyze speed, altitude, lean angle and G-forces; get a **Riding Coach** AI evaluation; pin **audio notes** to the exact point of the trip; export GPX.

<div align="center">
  <img src="https://raw.githubusercontent.com/vincenzobpt/MOTO-HUB/main/media/phone-trips-archive.png" alt="Trips archive" width="230">
  &nbsp;
  <img src="https://raw.githubusercontent.com/vincenzobpt/MOTO-HUB/main/media/phone-trip-replay.png" alt="Trip replay in 3D POV" width="230">
  &nbsp;
  <img src="https://raw.githubusercontent.com/vincenzobpt/MOTO-HUB/main/media/phone-trip-analysis.png" alt="Post-ride telemetry analysis" width="230">
</div>

### 🤖 AI place discovery &nbsp;·&nbsp; 🎙️ Group intercom

Ask for "a scenic pass with a café at the top" and let the AI tab rank real OpenStreetMap places — bring your own OpenAI-compatible API key, stored encrypted on the phone. And when you ride with a friend, **group intercom** carries voice between two phones over the rider's own hotspot — no accounts, no servers.

<div align="center">
  <img src="https://raw.githubusercontent.com/vincenzobpt/MOTO-HUB/main/media/phone-ai.png" alt="AI place discovery" width="230">
  &nbsp;
  <img src="https://raw.githubusercontent.com/vincenzobpt/MOTO-HUB/main/media/phone-intercom.png" alt="Group intercom" width="230">
</div>

### 🥚 …and one secret left to find

ADVANCED hides one more toy: a complete **OBD-II diagnostics suite**, tucked behind a door that appears on no menu. How to open it stays a secret — but riders who find it get **live engine data** (revs, throttle, load, temperatures from a standard ELM327 Bluetooth adapter), **fuel & air** readings (trims, oxygen sensors, manifold, timing), **stored trouble codes** explained by a built-in catalogue, and a **full scan** of every PID your motorcycle supports, shareable as a report.

<div align="center">
  <img src="https://raw.githubusercontent.com/vincenzobpt/MOTO-HUB/main/media/phone-obd-live-data-1.png" alt="Live data: engine speed, throttle, load and temperatures with one-minute traces" width="230">
  &nbsp;
  <img src="https://raw.githubusercontent.com/vincenzobpt/MOTO-HUB/main/media/phone-obd-live-data-2.png" alt="Fuel and air: fuel trims, oxygen sensors, manifold pressure and timing" width="230">
  &nbsp;
  <img src="https://raw.githubusercontent.com/vincenzobpt/MOTO-HUB/main/media/phone-obd-live-data-3.png" alt="Full scan: every PID the vehicle claims to support, answered and logged" width="230">
  <br>
  <sub>Live data &middot; fuel and air &middot; full scan. No, we won't tell you where the door is. Happy hunting. 🔎</sub>
</div>

ADVANCED contains no GPL-3.0/AGPL-3.0 code of its own. It reaches MOTO-HUB's T-Box transport and Android Auto receiver exclusively through a Binder IPC bridge exposed by the MOTO-HUB app, which is why the two are licensed differently.

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

MOTO-HUB is an experimental proof-of-concept, not a production-grade product. Day-to-day development happens on a CFMOTO 700MT-ADV dashboard, but the app is not CFMOTO-only: riders have confirmed it on Benelli TRK 502 / 702 / 702X, Voge DS800X and 800 Rally, Zontes 368E, QJ Motor SRT 550 and CFMOTO 800MT and 675SRR, with more models partly working or still untested. The model-by-model table lives on the MOTO-HUB page — see [Supported Motorcycles](https://github.com/vincenzobpt/MOTO-HUB#supported-motorcycles).

Behavior may differ on other motorcycles, T-Box firmware versions, or phones. Do not depend on it as your only source of critical navigation information. Plan your route before riding, and use the software at your own risk.

> [!NOTE]
> **Riding with an iPhone?** MOTO-HUB for iOS is available now — install it through AltStore Classic or sideload the IPA from [its own releases page](https://github.com/vincenzobpt/MOTO-HUB-IOS-releases). Requires iOS 17 or later.

## Community

<div align="center">

[![Discord](https://img.shields.io/badge/JOIN%20US%20ON%20DISCORD-support%20·%20community%20·%20development-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/FzhXZtPhC8)

</div>

## License

MOTO-HUB ADVANCED is proprietary, closed-source software. Distribution here does not grant any license to the source code. MOTO-HUB itself remains fully open source under AGPL-3.0.
