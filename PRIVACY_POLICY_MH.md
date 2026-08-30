# Privacy Policy for VisionTime

**Last Updated:** August 30, 2026

## Overview

VisionTime ("the App") is a personal entertainment tracking application for Meta Horizon OS, available on Meta Quest 2, Meta Quest Pro, Meta Quest 3, and Meta Quest 3S. Meshy-SC ("we", "our", "us") is committed to protecting your privacy and being transparent about how the App handles your data.

## Data Collection

VisionTime does **not** collect, store, or transmit any user data to our servers. We operate no servers, no databases, and no back end of any kind, and we have no access to your information.

All data — including the content you track (movies, shows, watch progress, ratings, notes, favorites, followed people and studios, achievements, and app preferences) — is stored **entirely on your headset**, in a private database inside the App's sandboxed storage.

### We Do NOT Collect

- Personal identification information
- Location data
- Usage analytics or telemetry
- Advertising identifiers
- Crash reports
- Any data whatsoever

## Data Storage

Your data lives on the headset itself and stays there:

1. Your library, watch progress, and preferences are written to a private database inside the App's sandboxed storage.
2. There is **no cloud sync**. Android automatic backup and device-to-device transfer are disabled in the App manifest — nothing leaves the headset unless you export it yourself.
3. You can produce a portable backup file at any time from **Settings → Backup → Export Library**, and restore that same file later from **Settings → Backup → Import Backup**.

We have **zero access** to your data.

## Third-Party Services

VisionTime relies on a small number of third-party services to fetch catalog data and to run on the host operating system. Each is used strictly to deliver the features described below.

### The Movie Database (TMDb)

VisionTime uses TMDb's public API to display information about movies and TV shows. When you search for a title, open a detail page, or refresh episode data:

- Your search query or the requested TMDb identifier is sent to TMDb's servers over HTTPS.
- Poster, backdrop, still, and profile images are fetched from TMDb's image servers over HTTPS.

TMDb's privacy policy applies to those requests:
[themoviedb.org/privacy-policy](https://www.themoviedb.org/privacy-policy)

### YouTube (trailers)

Where TMDb lists a trailer, VisionTime displays a thumbnail served by `img.youtube.com`. Tapping a trailer opens the video in the headset's system browser, at which point YouTube's own privacy policy applies:
[policies.google.com/privacy](https://policies.google.com/privacy)

### Meta Horizon Platform

VisionTime uses the Meta Horizon Platform SDK to:

- Verify that your copy of the App is entitled through the Meta Horizon Store (a store-required check).
- Post release and achievement notifications through the headset's own notification tray.

Those calls are handled by Meta's software running on your headset. Meta's own privacy policy applies to that layer:
[meta.com/legal/privacy-policy](https://www.meta.com/legal/privacy-policy/)

## Data Sharing

We do **not**:

- Sell your data.
- Share your data with third parties beyond the specific TMDb, YouTube, and Meta Horizon requests described above.
- Use your data for advertising.
- Track your behaviour across apps or sessions.

## Your Rights

You can:

- **Delete your data** by uninstalling the App — every local copy is removed immediately, and there is no cloud copy to worry about.
- **Export your data** at any time from **Settings → Backup → Export Library** as a portable JSON file, and re-import it later.
- **Revoke notification permission** at any time from the headset's system Settings.

## Permissions Requested

- **Internet access** — required to fetch content information and images from TMDb, and to perform the Horizon Store entitlement check.
- **Notifications** — optional; used only for release alerts and achievement unlocks. If you decline, the App continues to work silently.

VisionTime does not request access to the camera, microphone, location, contacts, files outside its own sandbox, or any advertising identifier.

## Children's Privacy

VisionTime does not knowingly collect data from children under 13.

## Changes to This Policy

We may update this policy from time to time. The "Last Updated" date at the top of this document reflects the most recent revision. Continued use of the App after changes are published constitutes acceptance.

## Contact

For privacy questions, please contact us:

- **Email:** [davinci.dalhi@gmail.com](mailto:davinci.dalhi@gmail.com)
- **GitHub Issues:** [github.com/Meshy-SC/VisionTime/issues](https://github.com/Meshy-SC/VisionTime/issues)

We aim to respond within 48 hours.

---

*VisionTime uses the TMDb API but is not endorsed or certified by TMDb.*
*VisionTime is not affiliated with Meta Platforms, Inc.*
