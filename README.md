# DLO FIT installers

This repository publishes public Android APK installers built from the [DLO_FIT_APP project](https://github.com/delorian43/DLO_FIT_APP).

## Latest installers

| Platform | Version | Download |
| --- | --- | --- |
| Android phone | 0.93 | [DLO_FIT_v0.93.apk](https://github.com/delorian43/Installers/raw/refs/heads/main/DLO_FIT_v0.93.apk) |
| Wear OS watch | 0.3.10 | [DLO_FIT_Wear_v0.3.10.apk](https://github.com/delorian43/Installers/raw/refs/heads/main/DLO_FIT_Wear_v0.3.10.apk) |

The APKs are stored with Git LFS to keep large binary files out of Git history. Both are debug-signed with the Firebase-registered key (SHA-1 `4aaf8abc8df00a0baaa02accc14f98c493f9de7c`). Check the SHA-256 before installing:

- Phone `DLO_FIT_v0.93.apk`: `1e7eab47c6aad1ea4dd2a7bb9ec3218530cc08487b6985cbeadd3fbd533b435c`
- Wear OS `DLO_FIT_Wear_v0.3.10.apk`: `d3494a3da3891d4d3160af981df6bd44ed967d66c95edfcbcf438717624ffba4`

These builds include the localized current-day calendar marker on phone and offline start from a valid cached plan on Wear OS, along with retryable event delivery, watch workout recovery, step-counter reset handling and a saved watch language setting. Source commit: [a764162](https://github.com/delorian43/DLO_FIT_APP/commit/a764162b58afa6431b4f52e3caae3c2cd2d9988f) on `release-0.92`.

Previous installers remain available in this repository: [phone 0.92.9](https://github.com/delorian43/Installers/raw/refs/heads/main/DLO_FIT_v0.92.9.apk) and [Wear OS 0.3.9](https://github.com/delorian43/Installers/raw/refs/heads/main/DLO_FIT_Wear_v0.3.9.apk).

## Previous public release

- [v0.89 release — phone 0.89 / Wear OS 0.3.3](https://github.com/delorian43/Installers/releases/tag/v0.89)
- [v0.88 Firebase fix — phone 0.88 / Wear OS 0.3.2](https://github.com/delorian43/Installers/releases/tag/v0.88-firebase-fix)

## Source project

- [DLO_FIT_APP repository](https://github.com/delorian43/DLO_FIT_APP)
- [Phone installer source folder](https://github.com/delorian43/DLO_FIT_APP/tree/release-0.92/phone/install)
- [Wear OS installer source folder](https://github.com/delorian43/DLO_FIT_APP/tree/release-0.92/wear-os/install)
