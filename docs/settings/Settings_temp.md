## Nuvio Player Settings

Nuvio offers a variety of player settings to customize your experience. This section covers:

- [Intro and Outro Skip](#intro-and-outro-skip)
- [Stream Selection and Stream Auto Play](#stream-selection-and-stream-auto-play)
- [Next Episode](#next-episode)
- [Subtitle and Audio](#subtitle-and-audio)
- [Player and Decoder Options](#player-and-decoder-options)
- [MPV (WIP)](#mpv-wip)

---

## Intro and Outro Skip

Nuvio uses three separate databases for intro and outro skipping, prioritized in this order: **IntroDB**, **AniSkip**, and **Anime Skip**. 

* **IntroDB** and **AniSkip** can be toggled on or off directly.
* **Anime Skip** requires an ID and configuration to use.

**To toggle these features:**
1. Go to **Settings**.
2. Select **Playback**.
3. Select **Skip Segments**.

**To obtain a free Anime Skip Client ID:**
1. Go to [Anime Skip](https://anime-skip.com).
2. Create an account.
3. Once logged in, go to your profile.
4. Select **API Clients**.
5. Select **Add a New Client**.
6. Enter the app name "Nuvio" and a description of "Nuvio".
7. Select **Create**.
8. Copy the generated Client ID (a long string of numbers and letters).
9. Go back into Nuvio, paste the Client ID, and select **Save**.

**To submit Intros and Outros to IntroDB:**
Nuvio allows you to submit timestamps to IntroDB's community-sourced database. You will need an API key:
1. Go to [Intro DB](https://introdb.app).
2. Create an account.
3. Once logged in, go to **Account Settings**.
4. Select **Generate Key**.
5. Copy the Key.
6. Go back into Nuvio, paste the API key, and select **Save**.

---

## Stream Selection and Stream Auto Play

### Stream Selection

Stream selection includes two main options:

* **Reuse Last Link:** When resuming a title, Nuvio will attempt to use the exact same stream you selected during your previous session.
* **Last Link Cache Duration:** Determines how long Nuvio holds onto the last selected link. Options include 1, 6, and 12 hours, as well as 1, 2, 3, and 7 days.
    > [!NOTE]
    > Debrid service links are typically only valid for a specific time period. Selecting a duration that is too long can cause Nuvio to attempt playback on an expired, invalid link.

### Stream and Auto-Play

This section dictates how the application behaves when you select a media item—whether it automatically launches a stream or lets you choose your own link.

**Selection Mode**
Determines the logic used to handle available streams:
* **Auto-play first source:** Automatically scans for media streams and instantly plays the first valid source it encounters without prompting you.
* **Manual:** Displays a comprehensive list of all discovered streams, allowing you to manually review and select based on quality, file size, or source.
* **Regex (Regular Expression):** An advanced filtering mode that scans stream titles or metadata for specific text patterns (e.g., 1080p, 4K, HEVC, specific release groups) and prioritizes or filters matches based on your custom expressions.

**Stream Selection Timeout**
Sets the maximum duration the application will wait for addons or plugins to return their results before proceeding:
* **Options:** Instant, 5s to 30s (in 5-second increments), Unlimited.
* *How it works:* If a timeout is hit, Nuvio stops searching and plays the best option found so far (if auto-playing) or presents a partial list (if manual). Choosing **Unlimited** ensures the app waits until every provider has finished searching, regardless of the time it takes.

**Source & Addon Filtering**
These configurations control exactly which addons or plugins are allowed to search for and supply streams.

* **Auto-play Source Scope:** Narrows down the pool of providers when using an automated playback mode.
    * *Options:* All sources, Select addons, Plugins only.
* **Allowed Addons:** Provides granular control over installed extensions during the search process.
    * *Options:* All addons, Custom Selection.
* **Allowed Plugins:** Controls the plugins used during the search process.
    * *Options:* All enabled plugins, Custom Selection.

---

## Next Episode

The Next Episode category includes several settings to optimize continuous viewing:

* **Auto-Play Next Episode:** When toggled on, Nuvio starts the source selection process as soon as the "next episode" prompt appears. This prompt is triggered by either:
    * An Outro skip is triggered.
    * If no Outro skip is present, the Next Episode Threshold is met.
* **Prefer Binge Group:** Nuvio will try to find the next episode using the same source profile before falling back to other options. For example, if you watched an episode via *Aiostreams*, Nuvio will attempt to find the next episode from *Aiostreams* in the same quality before trying other providers.
* **Reuse Binge Groups:** Ensures that when you return to a TV series, the app automatically remembers and prioritizes the exact same stream source or release group you were previously watching. If you selected a specific 1080p release group, your session anchors to that profile. When resuming from "Continue Watching," Nuvio will specifically look for that exact release group rather than auto-selecting a new source.
* **Next Episode Threshold Mode:** Used as a fallback if no outro skip is present. This can be set in 0.5% increments from 100% down to 97%.
    * *At 100%:* Nuvio will not begin the source selection process until the media is completely finished.
    * *At 97%:* Nuvio will begin the source selection process when the media is 97% complete (e.g., for a 30-minute show, selection begins at 29 minutes and 6 seconds).

---

## Subtitle and Audio

### Audio Settings
These settings determine the default spoken language tracks selected when a stream starts.
* **Preferred Audio Language:** The primary spoken language you want the application to automatically select if the media file contains multiple audio tracks.
* **Secondary Audio Language:** Your fallback audio track if the primary choice is unavailable.

### Subtitle Preferences
These configurations control which text translations are displayed on screen and how menus are filtered.
* **Preferred Language:** The primary language for your subtitles.
* **Secondary Preferred Language:** Your fallback subtitle language.
* **Use Forced Subtitles (Toggle On/Off):** Prioritizes "forced" subtitles that match your preferred language. Forced subtitles translate foreign languages, alien dialogue, or on-screen text while the rest of the media remains in your primary spoken language.
* **Show Only Preferred Languages (Toggle On/Off):** Filters the subtitle menu to hide all tracks except those that exactly match your primary and secondary language preferences.

### Addon Subtitle Startup
Controls how aggressively Nuvio searches for external subtitles when a video begins playing, balancing load times against availability.
* **Fast startup:** Prioritizes immediate video playback by skipping the automatic fetch of external addon subtitles. You must manually request them from within the player.
* **Preferred only:** A balanced approach. Fetches subtitles from addons during the initial load, but only pulls those matching your language preferences.
* **All subtitles:** Fetches and loads every available addon subtitle for the video, maximizing choice at the cost of slightly longer loading times.

---

## Player and Decoder Options

### Video Player & Interface
Controls the visual experience and interactions within the media player.

* **Loading Overlay:** Displays a continuous loading screen or graphic to hide buffering, black screens, or transitions. The overlay remains visible until the first frame of the video is ready.
* **Player:** Dictates which video engine handles your streams.
    * *Internal:* Keeps you inside Nuvio using its native player.
    * *External:* Passes the video link to a third-party application installed on your device (e.g., VLC, MX Player).
* **Hold To Speed (Mobile Only):** A touch-screen shortcut for skimming. Pressing and holding anywhere on the video player temporarily increases playback speed. Normal playback resumes when released.
* **Hold Speed (Mobile Only):** Configures the exact playback speed multiplier when using the "Hold To Speed" feature.

### Advanced Processing & Decoding
Technical settings that determine how your device's hardware and software process raw video and audio data.

* **Decoder Priority:** Tells the application how to translate the video file into images.
    * *Prefer device decoders:* Relies on your device's hardware chips. Best for smooth playback and battery conservation.
    * *Prefer app decoders (FFmpeg):* Relies on the app's software to decode video. Useful as a fallback for unusual video formats.
    * *Device decoders only:* Strictly forces hardware decoding, refusing to fall back to software processing.
* **DV7 - HEVC Fallback:** Dolby Vision Profile 7 (DV7) is a premium HDR format. Playing a DV7 file on unsupported hardware often results in distorted colors (e.g., a completely purple or green screen). Enabling this strips the unreadable Dolby Vision data and maps the video down to standard HEVC (H.265) for correct color playback.
* **Tunneled Playback:** An advanced Android TV feature. It allows audio and video streams to bypass standard OS pathways and process directly at the hardware level. This improves audio/video synchronization (lip-sync) and ensures smoother playback for heavy 4K HDR files.

---

## MPV (WIP)
*(This section is currently a work in progress and will be updated in a future release.)*

