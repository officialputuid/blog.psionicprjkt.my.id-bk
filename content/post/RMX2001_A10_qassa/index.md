---
title: QASSA v2.1 (Android-10) for RMX2001
description: Custom ROM for Realme 6, 6s, 6i and Narzo (RMX2001/02/03)
date: 2022-09-15
slug: ROM/RMX2001/QASSA-ROM/A10
image: main.png
categories:
    - UNOFFICIAL
tags:
    - ROM
---

## About ROM
#keepQASSA
You already know what Q mean!

## Whats Working
F-I | F-II | S-I | S-II
---------|---------|---------|---------
SELinux | Video/Screen/Audio REC | ✓ | ✓
RIL (Data,SMS,Calls) | Audio | ✓ | ✓
Userdata encryption[FDE] | GPS | ✓ | ✓
Fingerprint sensor | NFC | ✓ | ✓ (EU)
WiFi (2.4Ghz/5Ghz) | Sensors | ✓ | ✓
Bluetooth | Video Playback | ✓ | ✓
Camera | VoLTE | ∂ (Partial) | ✓

### Known Issues
* IMS (ViLTE, VoWiFi)
* Extra cameras

## Latest Changelog
* 2022-09-15
  * Fix VoLTE
  * Enable Dex2oat
  * Cleanup early SF configurations (smooth improve)


## Downloads
[⬇️ Download](https://sourceforge.net/projects/psionicprjkt/files/RMX2001/QASSA-A10/qassa-v2.1-RMX2001-20220914-1620-GApps.zip/download) | [🌆 Screenshot](https://photos.app.goo.gl/QB6zgWwj5A6LmSuj8) | [XDA Thread](https://forum.xda-developers.com)

```
FILE: qassa-v2.1-RMX2001-20220914-1620-GApps.zip
MD5SUM: 5f0fa62f6ad30f4da505e81befb8b4e8
FILESIZE: 950 MB (GApps)
```

## Info & Sources
* Device Info
  * Kernel: 4.14.x
  * Chipset: Mediatek MT6785 Helio G90T - ARMv8.2-A (64-bit)

* Sources
  * [psionicprjkt](https://github.com/psionicprjkt)
  * [officialputuid](https://github.com/officialputuid)

### Support Group
[psionicprjktchat](https://t.me/psionicprjktchat) | [psionicprjkt channel](https://t.me/psionicprjkt) | [psionicprjktlogs](https://t.me/psionicprjktlogs) managed by [officialputuid](https://t.me/officialputuid)

## Old Changelog
* 2022-09-13
  * September 2022 ASB
  * SELinux Enforcing
  * Passes SafetyNet out-of-the-box
  * AES-256-XTS File Based Encryption (FBE)
  * Added & Fixed Engineer Mode
  * Updated ImsService from phh/stableQ
  * Updated Camera Go v3.8.466520855
  * Updated blobs and configs from B.65_0650_202108181729
  * Fixed Double Tap To Wake (on/off)
