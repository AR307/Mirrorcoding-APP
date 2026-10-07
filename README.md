# MirrorCoding Android

Release channel for the MirrorCoding Android companion (PI Mobile).

Install new builds from
[Releases](https://github.com/AR307/Mirrorcoding-APP/releases/latest).

Version **0.16.2** adds in-app update checks, APK downloads and Android system
installation. Install this version manually once; subsequent versions can be
downloaded from **Account → Check for updates**. Covering upgrades retain the
existing application ID, signing identity, login, pairings and local history.

The updater reads `mobile-update.json` from this repository's latest formal
GitHub Release. Each release uploads that generated manifest and its named APK
together. Application source lives in
[`AR307/PI-Desktop`](https://github.com/AR307/PI-Desktop) under `apps/mobile`.

Account pairing discovers every computer that explicitly enables account
sharing. Loaded history remains available offline without the previous
500-message limit, and desktop restarts resume through durable changes.
Use PI Desktop 0.16.2 and the corresponding MC account-sync service.

Android 7.0 or newer is required. This distribution uses application ID
`xyz.mirrorcoding.pi.mobile` and versionCode **6**.

Do not attach signing keys or account tokens to a release.
