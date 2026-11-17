# Privacy Policy for VisionTime

**Last Updated:** November 17, 2026

## Overview

VisionTime ("the App") is a personal entertainment tracking application for Meta Horizon OS, available on Meta Quest 2, Meta Quest Pro, Meta Quest 3, and Meta Quest 3S. Meshy-SC ("we", "our", "us") is committed to protecting your privacy and being transparent about how the App handles your data.

## Data the App Collects and Processes

VisionTime collects and processes the following data, only to provide its features:

- **Your library**, which you enter in the App: the movies and shows you track, your watch progress, ratings, notes, favorites, followed people and studios, achievements and app preferences. It is stored on your headset (see Data Storage).
- **Your searches and the titles you open**: your search text, or the TMDb identifier of the title you open, is sent to The Movie Database (TMDb) to fetch information and images (see Third-Party Services).
- **Ownership check**: when the App starts, Meta Horizon OS answers yes or no to whether your Meta account is entitled to VisionTime.
- **Notifications**: if you allow them, the App shows release and achievement notifications on your headset.
- **Crash reports**: if the App crashes, Meta Horizon OS may report it to Meta, and Meta's developer dashboard then shows us the technical details (headset model, Meta Horizon OS and app versions, and where in the code the crash happened). We use them only to fix the problem.
- **Emails you send us**: your email address, your message and anything you include, used only to answer you or handle your request, and kept only while we do.

VisionTime requests no Meta Horizon platform features through Meta's Data Use Checkup (no Meta user ID, profile, age group or in-app purchases). It contains no advertising, analytics or tracking code. Meshy operates no servers, databases or back end of any kind for VisionTime.

## Data Storage

Your library lives on the headset itself:

1. Your library, watch progress, and preferences are written to a private database inside the App's sandboxed storage.
2. There is **no cloud sync**. Android automatic backup and device-to-device transfer are disabled in the App manifest, so your library is copied off the headset only when you export it yourself.
3. You can produce a portable backup file at any time from **Settings → Backup → Export Library**, and restore that same file later from **Settings → Backup → Import Backup**.

Your library is stored only in these places: on your headset, and in any export file you create.

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

## Requesting Data Deletion

**All users, in every country, can delete their data or ask us to delete it at any time. It is free, and you do not have to give a reason.**

- **Data on your headset:** uninstalling VisionTime permanently deletes your library and preferences from your headset, immediately. Delete any export file you made, too.
- **Ask us:** email **davinci.dalhi@gmail.com** with the subject **"Data deletion request"**. Within **30 days** we delete all data we hold about you (any emails you have sent us), guide you through deleting the data on your headset, and confirm the deletion to you by email. We will not refuse a deletion request.
- **Data held by others:** requests sent to TMDb and YouTube, and the ownership check and crash reports handled by Meta, are covered by their own privacy policies (linked above), which describe how to ask them for deletion.

## Your Other Rights

You can also:
- **Export your data** at any time from **Settings → Backup → Export Library** as a portable JSON file, and re-import it later.
- **Revoke notification permission** at any time from the headset's system Settings.

## Permissions Requested

- **Internet access** — required to fetch content information and images from TMDb, and to perform the Horizon Store entitlement check.
- **Notifications** — optional; used only for release alerts and achievement unlocks. If you decline, the App continues to work silently.

VisionTime does not request access to the camera, microphone, location, contacts, files outside its own sandbox, or any advertising identifier.

## Children's Privacy

VisionTime is a general-audience app. It processes the same data (see Data the App Collects and Processes) for every user, whatever their age, and asks no one for personal details. A parent or guardian can request deletion of a child's data as described in Requesting Data Deletion.

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
