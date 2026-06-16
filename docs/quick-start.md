[Home](../README.md) | [Quick Start](../docs/quick-start.md) | [Overview](../docs/overview.md) | [Features](../docs/features.md) | [Installation](../docs/installation/README.md) | [Settings](../docs/settings/README.md) | [Troubleshooting](../docs/troubleshooting.md) | [FAQ](../docs/faq.md)

---

# ⚡ Quick Start Guide

## 1. Install the App
Before configuring anything, ensure you have the correct version installed for your platform. 
* Refer to the [Full Installation Guides](installation/README.md) to get the application up and running.

---

## 2. First App Open & Profile Setup
When launching Nuvio for the very first time, your immediate step will be creating a profile.
* **Primary Profile:** Note that the **first profile you create will be designated as the Primary profile**. 
* For details on managing multiple accounts or tweaking restrictions, see the [Profile Settings Section](settings/profiles.md).

---

## 3. Connect Features & Integrations
To populate your dashboard and enable metadata enrichment, configure your external accounts.

### Trakt Configuration
1. Navigate to **Settings** > **Trakt** and click **Connect Trakt**.
2. Complete the external authentication, then return to the Nuvio Trakt settings screen.
3. Select your preferred **Library Source**.
4. Set your watch progress tracking options. You can sync between Trakt or Nuvio, but selecting **Nuvio Sync** is highly recommended for the most accurate watch progress.
5. Toggle **Comments On** if you want to view community discussions.

### Metadata Enrichment
Go to **Settings** > **Integrations** to add your developer API keys:
* **TMDB Enrichment:** Toggle this feature **On** and input your personal **TMDB API Key** to fetch rich asset metadata.
* **MDBList:** Toggle this feature **On** and input your **MDBList API Key** to bring in rating data.

---

## 4. Recommended Playback Settings
Optimize how your player handles streams, episodes, and specialty content formats under **Settings** > **Player**.

* **Intro Skip:** Turn this option on to automatically bypass TV show introductions.
* **Anime Skip:** Toggle this feature on and enter your unique **Client ID**. For step-by-step instructions on acquiring your ID, check the [Player Settings Section](settings/player.md).
* **Auto-Play Next Episode:** Turn this on to seamlessly transition to the next episode in a series without returning to the menu.
* **Auto Stream Selection:** Change this setting to **Auto-play first source** to bypass manual link picking and let Nuvio instantly launch the top scraped result.
* **Advanced Subtitle Rendering:** Turn on **Use libass for ASS/SSA subtitles** to ensure high-styled typesetting layout styles render correctly. For deep technical details, see the [Full Settings Wiki](settings/README.md).
* **TV Device Enhancements:** If you are running Nuvio on an Android TV or television box, turn on the **Auto Switch Feature for Anime** specifically optimized for the MPV internal player backend.

### Subtitles and Audio Defaults
Tailor your default language tracks so you do not have to change them every time you launch a stream:
* **Preferred Audio Language:** Set your default voice/audio track language.
* **Preferred Subtitle Language:** Choose your primary text language. 
* *Tip:* If you prefer streams to launch completely clean without overlays, **set this to None to keep default subtitles off**.

---

## 5. Addons & Plugins

By default, Nuvio comes with **Cinemeta** and **Open Subtitles** installed out of the box. While these provide basic metadata and subtitle support, Nuvio is effectively an empty shell upon first launch. 

**You will need to configure your own add-ons and plugins to make the app useful and populate it with playable content.**

For mire detail on addons: [Addons Guide](addons/README.md).

## Navigation & Installation

The menus to access your Addons and Plugins differ depending on the device you are using:

### On Mobile Devices
1. Navigate to **Settings**.
2. Select **Content and Discovery**.
3. From here, choose either the **Addons** or **Plugins** section to add your manifest URLs or manage existing installations.

### On TV Devices
*   **Addons:** Accessible directly from the main **Sidebar** menu.
*   **Plugins:** Navigate to **Settings** > **Plugins**.
