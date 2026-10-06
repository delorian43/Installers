# DLO FIT installers

This repository publishes public Android APK installers built from the [DLO_FIT_APP project](https://github.com/delorian43/DLO_FIT_APP).

## Latest published installers

| Platform | Version | Download |
| --- | --- | --- |
| Android phone | 0.89 | [DLO_FIT_v0.89.apk](https://github.com/delorian43/Installers/releases/download/v0.89/DLO_FIT_v0.89.apk) |
| Wear OS watch | 0.3.3 | [DLO_FIT_Wear_v0.3.3.apk](https://github.com/delorian43/Installers/releases/download/v0.89/DLO_FIT_Wear_v0.3.3.apk) |

Both APKs are attached to the [v0.89 release](https://github.com/delorian43/Installers/releases/tag/v0.89). Check its release notes and SHA-256 checksums before installing. These debug-signed builds are compatible with the corrected v0.88 Firebase-fix installers.

## Phone 0.92.3 — prepared, not yet published

The 0.92.3 phone APK has been prepared on the private source branch `release-0.92`, but it is not yet attached to a public Installers release. Until a new release is published here, v0.89 remains the latest publicly downloadable version.

Changes documented for 0.92.3:

- Resized and recompressed 54 exercise thumbnails, the app logo, and launcher icon; the release APK is reported as about 97 MB (previously about 120 MB).
- Includes the workout-session logic and bilingual-string tests added in 0.92.2.
- Legacy local-password login and migration to Firebase are scheduled to stop on **30 June 2027**. On or after that date, local password hashes and salts for accounts not migrated to Firebase are cleared at app startup. Accounts and workout data remain on the device, but affected users must sign in with Google or register again.

The date-based legacy-login cutoff is a significant account-access change. Review the release notes and migration guidance before making this APK public.

## Previous release

- [v0.88 Firebase fix — phone 0.88 / Wear OS 0.3.2](https://github.com/delorian43/Installers/releases/tag/v0.88-firebase-fix)

## Source project

- [DLO_FIT_APP repository](https://github.com/delorian43/DLO_FIT_APP)
- [Phone installer source folder](https://github.com/delorian43/DLO_FIT_APP/tree/main/phone/install)
- [Wear OS installer source folder](https://github.com/delorian43/DLO_FIT_APP/tree/main/wear-os/install)
