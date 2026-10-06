# DLO FIT installers

This repository publishes public Android APK installers built from the [DLO_FIT_APP project](https://github.com/delorian43/DLO_FIT_APP).

## Latest installers

| Platform | Version | Download |
| --- | --- | --- |
| Android phone | 0.92.9 | [DLO_FIT_v0.92.9.apk](https://github.com/delorian43/Installers/raw/refs/heads/main/DLO_FIT_v0.92.9.apk) |
| Wear OS watch | 0.3.9 | [DLO_FIT_Wear_v0.3.9.apk](https://github.com/delorian43/Installers/raw/refs/heads/main/DLO_FIT_Wear_v0.3.9.apk) |

The APKs are stored with Git LFS to keep large binary files out of Git history. Both are debug-signed with the Firebase-registered key (SHA-1 `4aaf8abc8df00a0baaa02accc14f98c493f9de7c`). Check the SHA-256 before installing:

- Phone `DLO_FIT_v0.92.9.apk`: `f61e89dd6d806e86b7db31e4900b7da297ab6611b58914b7a7635eba47c80bf4`
- Wear OS `DLO_FIT_Wear_v0.3.9.apk`: `c47af344ab417afd67a9d62863739beca9b2b8dca82d4bf76a98a404899190de`

These builds include retryable phone/watch event delivery, watch workout recovery after process interruption, watch step counting across sensor resets, and a saved watch language setting. Source commit: [0e7b16c](https://github.com/delorian43/DLO_FIT_APP/commit/0e7b16c74247641ad8a4a7a1dbcbaef5ddbc4576) on `release-0.92`.

## Previous public release

- [v0.89 release — phone 0.89 / Wear OS 0.3.3](https://github.com/delorian43/Installers/releases/tag/v0.89)
- [v0.88 Firebase fix — phone 0.88 / Wear OS 0.3.2](https://github.com/delorian43/Installers/releases/tag/v0.88-firebase-fix)

## Source project

- [DLO_FIT_APP repository](https://github.com/delorian43/DLO_FIT_APP)
- [Phone installer source folder](https://github.com/delorian43/DLO_FIT_APP/tree/release-0.92/phone/install)
- [Wear OS installer source folder](https://github.com/delorian43/DLO_FIT_APP/tree/release-0.92/wear-os/install)
