# PI Mobile release channel

This repository distributes the Android companion APK and its update manifest.
React, Capacitor and native Android source are maintained in AR307/PI-Desktop,
under apps/mobile. MC handles account/device authorization and online relay;
the desktop remains the authority for agent execution and full history.

## 0.16.2 - 2026-10-07

Publish in-app updates, account-wide discovery and durable offline history.
Retain the existing package identity and signing certificate, with versionCode
6. Include the generated mobile-update.json alongside pi-mobile-v0.16.2.apk.
Controlled client acceptance and production MC integration are separate results.
