# Privacy Policy for VisionTime on Android XR

**Last Updated:** November 5, 2026

## Overview

VisionTime ("the App") is a personal entertainment tracking application for Android XR, available on Android XR headsets and wired XR glasses through Google Play. The App is published by **Meshy** ("we", "our", "us"); the person responsible for your data (the data controller) is **Ahmed Dalhi**, based in France. We are committed to protecting your privacy and being transparent about how the App handles your data.

## Data Collection

VisionTime does **not** collect, store, or transmit any user data to our servers. We operate no servers, no databases, and no back end of any kind, and we have no access to your information.

All data — including the content you track (movies, shows, watch progress, ratings, notes, favorites, followed people and studios, achievements, and app preferences) — is stored **entirely on your device**, in a private database inside the App's sandboxed storage.

### We Do NOT Collect
- Personal identification information
- Location data
- Usage analytics or telemetry
- Advertising identifiers
- Crash reports
- Any data whatsoever

## Data Storage

Your data lives on the device itself and stays there:

1. Your library, watch progress, and preferences are written to a private database inside the App's sandboxed storage.
2. There is **no cloud sync**. Android automatic backup and device-to-device transfer are disabled in the App manifest — nothing leaves the device unless you export it yourself.
3. You can produce a portable backup file at any time from **Settings → Backup → Export Library**, and restore that same file later from **Settings → Backup → Import Backup**. The file is saved where you choose, through the system file picker.

We have **zero access** to your data.

## Third-Party Services

VisionTime relies on a small number of third-party services to fetch catalog data. Each is used strictly to deliver the features described below.

### The Movie Database (TMDb)
VisionTime uses TMDb's public API to display information about movies and TV shows. When you search for a title, open a detail page, or refresh episode data:
- Your search query or the requested TMDb identifier is sent to TMDb's servers over HTTPS.
- Poster, backdrop, still, and profile images are fetched from TMDb's image servers over HTTPS.
- To show regional recommendations and where a title can be streamed, the App sends TMDb a country code, worked out on the device from its time zone (or, failing that, its language settings). No location permission is used.

TMDb's privacy policy applies to those requests:
[themoviedb.org/privacy-policy](https://www.themoviedb.org/privacy-policy)

### YouTube (trailers)
Where TMDb lists a trailer, VisionTime displays a thumbnail served by `img.youtube.com`. Tapping a trailer opens the video in the device's browser or YouTube app, at which point YouTube's own privacy policy applies:
[policies.google.com/privacy](https://policies.google.com/privacy)

### Google Play
VisionTime is distributed through Google Play. Purchases, refunds, and app updates are handled by Google Play, under Google's own terms and privacy policy:
[policies.google.com/privacy](https://policies.google.com/privacy)

The App itself contains no Google analytics, advertising, or crash-reporting SDK.

## Data Sharing

We do **not**:
- Sell your data.
- Share your data with third parties beyond the specific TMDb and YouTube requests described above.
- Use your data for advertising.
- Track your behaviour across apps or sessions.

## Your Rights

You can:
- **Delete your data** by uninstalling the App, or with **Clear storage** in the system's app settings — every local copy is removed immediately, and there is no cloud copy to worry about.
- **Export your data** at any time from **Settings → Backup → Export Library** as a portable JSON file, and re-import it later — in VisionTime on Android XR, Meta Quest, or Apple devices.
- **Revoke notification permission** at any time from the system Settings.

## Permissions Requested

- **Internet access** — required to fetch content information and images from TMDb.
- **Notifications** — optional; used only for release alerts and achievement unlocks. If you decline, the App continues to work silently.

VisionTime does not request access to the camera, microphone, location, contacts, files outside its own sandbox, or any advertising identifier. Jetpack XR, the Android XR framework the App is built on, does not need any of these for the App's panel and navigation.

## Children's Privacy

VisionTime does not knowingly collect data from children under 13.

## Changes to This Policy

We may update this policy from time to time. The "Last Updated" date at the top of this document reflects the most recent revision. Continued use of the App after changes are published constitutes acceptance.

## Contact

For privacy questions, please contact us:

- **Data controller:** Ahmed Dalhi (Meshy), France
- **Email:** [davinci.dalhi@gmail.com](mailto:davinci.dalhi@gmail.com)
- **GitHub Issues:** [github.com/Meshy-SC/VisionTime/issues](https://github.com/Meshy-SC/VisionTime/issues)

We aim to respond within 48 hours.

---

*VisionTime uses the TMDb API but is not endorsed or certified by TMDb.*
*VisionTime is not affiliated with Google LLC. Android XR is a trademark of Google LLC.*
