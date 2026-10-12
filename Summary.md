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

## 0.18.0 - 2026-10-12

Publish history-read recovery alongside the Windows transcript-index fix.
Retain successful delta pages, buffered live events and conversation controls
after a later page fails; retry only history synchronization, never the prompt.
Use paired PI Desktop 0.18.0. The APK remains non-debuggable and signed with
the existing distribution certificate, versionCode 7. PiMobileQA covering
upgrade from 0.16.2 keeps its installation identity and application data
directory. Actual controlled Electron and Android acceptance passed 55 checks.
Source candidate: 9dbd681498ebf45ed443a89f5705119ea1a388bb.
No production account or paid model request was used for acceptance.
