# VisionTime Support

**Welcome to VisionTime Support.** We are here to help you get the most out of your entertainment tracking experience on Meta Quest.

## Supported Devices

- **Meta Quest 2**
- **Meta Quest Pro**
- **Meta Quest 3**
- **Meta Quest 3S**

VisionTime is a 2D panel app hosted by the Horizon shell — no immersive experience is required. The panel can be moved, resized, minimised, and closed like any other Horizon OS window.

## Frequently Asked Questions

### Getting Started

**How do I add a movie or TV show to my library?**
Use the Search tab to find a title, then tap the "+" button to add it to your library.

**How do I track my watch progress?**
Open a title from your library and mark episodes as watched, or mark a movie as watched from its detail page.

**How do I favorite a title?**
Open the title's detail page and tap the star icon.

**How do I follow an actor or a studio?**
Open a person's or a studio's page and tap the follow icon. Followed people and studios drive personalised recommendations and release alerts.

### Backup and Portability

**Where does my library live?**
On the headset itself. There is no cloud sync — every change is written to a private database inside the App's sandboxed storage.

**How do I move my library to another headset?**
Open **Settings → Backup → Export Library**, save the JSON file somewhere you can retrieve it later, then open the same file on the destination headset from **Settings → Backup → Import Backup**.

**How often does the App back itself up?**
VisionTime keeps a small rolling set of automatic backups under **Settings → Backup**. You can also export a manual backup at any time, which is the copy you can store outside the headset.

### Notifications

**Why do I not see release notifications?**

1. Open the App at least once so it can schedule its periodic release check.
2. Ensure notifications are allowed — VisionTime asks the first time you launch it. You can also flip the permission in the headset's own Settings.
3. Follow at least one show or add a movie with a future release date.
4. Alerts fire in the digest window you picked in **Settings → Notifications** (weekly digest, monthly digest, or as they happen).

**Can I mute or customise alerts for a specific show?**
Yes. Open **Settings → Notifications → TV Shows** to set a per-show mode: Auto (VisionTime decides from your watch progress), All Episodes, New Seasons Only, or Muted. **Settings → Notifications → Movies** does the same for upcoming releases on your Watch Later list.

### Data and Privacy

**What data does VisionTime collect?**
VisionTime only stores the content you track (movies, shows, watch progress, ratings, notes, favorites, follows, and achievements) and your app preferences — all locally on the headset. We do not collect personal information, location data, or analytics. For full details, see our [Privacy Policy](PRIVACY_POLICY.md).

**How do I delete my data?**
Uninstalling the App immediately removes every local copy — there is no cloud copy to remove.

### Troubleshooting

**The App is crashing or not responding.**

1. Force-quit the App from the Horizon shell and reopen it.
2. Ensure your headset is running the latest Horizon OS version.
3. Update VisionTime to the latest version from the Meta Horizon Store.
4. If the issue persists, contact us (see below).

**The system keyboard is not appearing when I tap a text field.**
The Horizon virtual keyboard requires the panel to be in the shell's foreground. Make sure the VisionTime panel is focused; if the keyboard still does not appear, close and reopen the panel.

**Search results are not loading, or episode data looks stale.**
VisionTime uses The Movie Database (TMDb) to fetch content information. Please check your internet connection and try again. Foreground refresh is throttled to at most once per hour and background refresh runs approximately every six hours — force-quit and reopen the panel to trigger a fresh pull. If the problem continues, TMDb service may be temporarily unavailable.

**I found incorrect information about a movie or show.**
Content information is provided by TMDb. You can help improve their database at [themoviedb.org](https://www.themoviedb.org/).

**A trailer will not play.**
Trailers open in the headset's system browser (they are hosted on YouTube). If nothing happens, make sure a browser is available and the headset has an active internet connection.

## Contact Us

If you need further assistance or have feedback, we would love to hear from you.

- **Email:** [davinci.dalhi@gmail.com](mailto:davinci.dalhi@gmail.com)
- **GitHub Issues:** [github.com/Meshy-SC/VisionTime/issues](https://github.com/Meshy-SC/VisionTime/issues)

When contacting support, please include:

- Your headset model (Meta Quest 2, Quest Pro, Quest 3, or Quest 3S)
- Your Horizon OS version
- The App version (from **Settings → About → Version**)
- A description of the issue
- Screenshots, if applicable

We aim to respond within 48 hours.

---

*VisionTime uses the TMDb API but is not endorsed or certified by TMDb.*
*VisionTime is not affiliated with Meta Platforms, Inc.*
