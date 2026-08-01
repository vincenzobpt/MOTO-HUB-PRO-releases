# MOTO-HUB ADVANCED — Releases

Pre-built APK downloads for **MOTO-HUB ADVANCED**, the free closed-source companion app to
[MOTO-HUB](https://github.com/vincenzobpt/MOTO-HUB).

**This repository contains no source code.** MOTO-HUB ADVANCED's source is closed and private.
Only signed release APKs are published here, under the [Releases](../../releases) tab.

> [!IMPORTANT]
> [**JOIN US ON DISCORD TO RECEIVE SUPPORT, HELP THE COMMUNITY AND FOLLOW THE APP DEVELOPMENT**](https://discord.gg/uCUK55nJ5v)

## What MOTO-HUB ADVANCED adds

MOTO-HUB (the open-source app) owns the connection to the motorcycle: pairing, the T-Box
transport, screen mirroring, Android Auto, handlebar buttons. ADVANCED installs alongside it and
adds everything built on top of the rider's own GPS:

| | MOTO-HUB | MOTO-HUB ADVANCED |
| --- | --- | --- |
| T-Box pairing, garage, connection | ✅ | uses MOTO-HUB |
| Screen mirroring | ✅ | ✅ |
| Android Auto on the TFT | ✅ | delegated to MOTO-HUB |
| Handlebar button control | ✅ | ✅ |
| **Ride Dashboard** — native GPS scene on the TFT | — | ✅ |
| **Navigation** — search, motorcycle routing, route preview | — | ✅ |
| **Trips** — recording, history, GPX export | — | ✅ |
| **AI** — assisted place discovery | — | ✅ |

ADVANCED contains no GPL-3.0/AGPL-3.0 code of its own. It reaches MOTO-HUB's T-Box transport and
Android Auto receiver exclusively through a Binder IPC bridge exposed by the MOTO-HUB app, which
is why the two are licensed differently.

## Installation

> [!IMPORTANT]
> **MOTO-HUB must be installed for ADVANCED to work**, and both should be the **same version**.
> The two apps are released together under one version number and talk to each other over an
> interface that changes between releases — a mismatched pair may fail to connect.

1. Install [MOTO-HUB](https://github.com/vincenzobpt/MOTO-HUB/releases/latest) first and pair it
   with your T-Box.
2. Download the ADVANCED APK with the **same version number** from [Releases](../../releases).
3. Enable "Install unknown apps" for your browser or file manager when Android asks.
4. Install the ADVANCED APK.

Both apps can check for updates themselves and will offer the matching release.

## Privacy

MOTO-HUB ADVANCED works without an account and records rides only on the phone. Trips, tracks and
GPX exports stay on the device.

Features that need the Internet disclose only what that request needs, to the service that
answers it and to no MOTO-HUB account: map tiles for the area being displayed, a typed search to
the geocoder, an origin/destination pair to the routing service, destination and arrival time to
the weather service. The AI tab talks to an OpenAI-compatible endpoint using **the rider's own API
key**, which is stored encrypted with the Android Keystore, sent only as an authorization header,
and never logged.

Like MOTO-HUB, official ADVANCED releases report **crashes and errors to Sentry** (EU region) so
that failures which need a motorcycle to reproduce can be diagnosed. Sentry's default PII
collection is switched off, diagnostic messages are redacted and capped per app run, and grouping
tags are deliberately coarse. Screen content, T-Box passwords and recorded positions are never
sent. Turning off `Settings ▸ Diagnostics ▸ Enable logging` stops the diagnostic log and the error
events that come from it; crash reports are handled by the Sentry SDK itself and are not covered
by that switch.

## Status

MOTO-HUB is an experimental proof-of-concept, not a production-grade product. It has been built
and tested with a CFMOTO 700MT-ADV dashboard. Behavior may differ on other motorcycles, T-Box
firmware versions, or phones. Do not depend on it as your only source of critical navigation
information. Plan your route before riding, and use the software at your own risk.

## License

MOTO-HUB ADVANCED is proprietary, closed-source software. Distribution here does not grant any
license to the source code. MOTO-HUB itself remains fully open source under AGPL-3.0.
