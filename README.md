# Rinselio Android test builds

A free laundry companion for everyone. Pick what you need to wash, match the visual care symbols, and get a wash plan. The Atlas-inspired interface uses charcoal, amber and clear typography.

## Install

Get the APK from [Releases](https://github.com/wardgeys1993-web/washwise-releases/releases) on an Android 8 or newer phone. Open the file and review Android's installation prompt. This is a prerelease for testing. Play Store distribution is pending.

## Updates

From version 0.6.0, direct Android builds automatically check signed update information when the app opens or returns to the foreground, at most every six hours after success. Offline failures stay quiet. An available version prompts for a download. For an immediate check, open the account icon, scroll to App updates, and tap Check for updates. Android asks before installing and checks the app's signing identity. Updates installed over the existing app retain its local data. Uninstalling or clearing app data removes the local machine profile and saved plans.

The app does not silently install updates or hash the downloaded APK. SHA256SUMS is included with each release for independent verification. The Play distribution flavour disables this GitHub updater.

## Data and current limits

The basic planner, OCR and saved profiles run on the phone. Photos and raw OCR text are processed locally. Only the brand/model are sent to official manufacturer support sites for manual lookup. Automatic manual lookup currently supports Bosch, Siemens and Samsung. Exact programme extraction depends on the document and can require review. Readable model codes are required; a machine's appearance alone is not recognised.

Choose the dial language and use the separate sticker or panel-photo controls. Manual lookups use regional language pages where supported. A model match does not by itself verify a user manual. Missing programmes stay unmapped, and photo labels need review. Realistic laundry artwork uses original generated assets, with no private photo references.

No account is required. Google sign-in, cloud sync and ads are not connected in this preview. No paid API is used. Update checks contact GitHub. Internet access is needed for new online manuals and update checks.

Validation uses a disposable Android emulator and clearly marked synthetic model labels. Physical-phone camera testing, real appliance-photo recognition and physical laundry outcomes are not verified. Use your actual item's care label and machine manual.

This public repository contains downloads and signed update metadata. Application source is kept separately in a private repository. Signing keys are never included here.
