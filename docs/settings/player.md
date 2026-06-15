## Nuvio Player Settings

Nuvio offers many player settings options. This section will discuss:

- [Intro and Outro Skip](#Intro-and-Outro-Skip)
- [Stream Selection and Stream Auto Play](#Stream-Selection-and-Stream-Auto-Play)
- [Next Episode](#Next-Episode)
- [Subtitle and Audio](#Subtitle-and-Audio)
- Player and Decoder Options
- MPV


## Intro and Outro Skip

Nuvio uses 3 seperate databases for intro and outro skip in this order: IntroDB -> AniSkip -> Anime Skip. Anime Skip requires and ID to use. IntroDB and Anime Skip can be toggled on or off. Anime Skip is the only one that **requires** configuration to use.

To toggle these on go to:

1. Settings
2. Playback
3. Skip Segments

To obtain a free AnimeSkip ClientID

1. Go to [Anime Skip](https://anime-skip.com)
2. Create an Account
3. Once logged in, go to your profile
4. Select API Clients
5. Select Add a New Client
6. Enter the app name "Nuvio" and a description of "Nuvio"
7. Select Create
8. This will create a ClientID that is a long string of numbers and letters. Copy it.
9. Go back into Nuvio and paste the ClientID and hit save

Nuvio also has the ability to submit Intros and Outros to IntroDB's community sourced database. To do this you need to configure and API key.

1. Go to [Intro DB](https://introdb.app)
2. Create an Account
3. Once logged in, go to account settings
4. Select Generate Key
5. Copy the Key
6. Go back into Nuvio and paste the API key in and hit save

## Stream Selection and Stream Auto Play

### Stream Selection

Stream selection has two options within it

1. Reuse last link
    - With this on, when you resume something you were watching, Nuvio will to use the same stream you selected before you stopped watching
2. Last Link Cache Duration
    - This tells Nuvio how long to hold onto the last link with the options for: 1, 6, and 12 hours. As well as 1, 2, 3, and 7 days.
      >[!NOTE]
      >Debrid service links are typically only valid for a certain time period. Selecting too long of a time period can cause Nuvio to attempt to play a link that is no longer valid.

### Stream and Auto-Play

This section dictates how the application behaves when you click on a media item—whether it automatically launches a stream or lets you choose your own link.

Selection Mode: Determines the logic used to handle available streams.

- Options: Auto-play first source, Manual, Regex
    - Auto-play first source: The app will automatically scan for media streams and instantly play the very first valid source it encounters without prompting you.
    - Manual: Displays a comprehensive list of all discovered streams, allowing you to manually review and pick the specific quality, file size, or source you prefer.
    - Regex (Regular Expression): An advanced filtering mode that scans stream titles or metadata for specific text patterns (like 1080p, 4K, HEVC, or specific release groups) and prioritizes or filters matches based on your custom expressions.

Stream Selection Timeout: Sets the maximum duration the application will wait for addons, or plugins to return their results before proceeding.

- Options: Instant, 5s to 30s (in 5-second increments), Unlimited
    - If a timeout is hit, it stops looking and either plays the best option found so far (in auto-play) or presents the partial list (in manual). Choosing Unlimited ensures the app waits until every single provider has finished searching, regardless of how long it takes.

Source & Addon Filtering: These configurations control exactly which addons or plugins are allowed to search for and supply streams during the selection process.
Auto-play Source Scope

Auto-play Source Scope
- Options: All sources, Select addons, Plugins only
- Description: Narrows down the pool of providers when using an automated playback mode. You can let the system pull from every available connection, or restrict auto-play exclusively to a trusted subset of addons or internal plugins.

Allowed Addons
- Options: All addons, Custom Selection
- Description: Gives you granular control over your installed extensions. You can choose to allow All addons to participate in the source selection process or pick specific ones.

Allowed Plugins
- Options: All enabled plugins, Custom Selection
- Description: Controls the plugins used during the search process. You can dictate whether the system leverages all currently active plugins or restrict it to a specific list of plugins.

## Next Episode

Next Episode has a variety of options: Auto-Play Next Episode, Prefer Binge Group, Resue Binge Group, Next Episode Threshold Mode.

**Auto-Play Next Episode**

1. With this toggled on, Nuvio will start source selecting process as soon as the prompt appears.
2. This is trigged by whatever occurs first:
    - Outro skip is trigged from skip outro
    - Next episode Threshold is met

**Prefer Binge Group**

This option will try the same source profile first for next episode before any other options. E.g. If you were watching Big Buck Bunny obtained from Aiostreams, Nuvio will attempt to find the next episode using Aiostreams with the same quality as the previous one. If it does not find one, it will fallback to another option.

**Reuse Binge Groups**

With this on, Nuvio will ensure that when you return toa TV series, the app automatically remembers and prioritzes the exact same stream source or relase group you were previously watching

1. If you select a specfiic 1080p stream, Nuvio anchors your session to that specific release profile or "binge group"
2. When you resume the show later, from continue watching or the series details page, it won't default back to auto-selecting a result or have you pick a new source. It looks for the next episde from that exact same release group.

**Next Episdoe Threshold Mode**

This will be used as a fallback if no outro skip is present. This can be set in increments of .5% from 100% to 97%. 

1. At 100%, if no outro skip exists, Nuvio will not begin the source selecting process until the show or movie is **completely** finished.
2. At 97%, if no outro skip exists, Nuvio will begin the source selecting process when the show is 97% complete. E.g. IF the show is 30 minutes long, Nuvio will begin selecting next source at 29 minutes and 6 seconds.

### Subtitle and Audio

Audio Settings

These settings determine the default spoken language tracks selected when you start a stream.

1. Preferred Audio Language: The primary spoken language you want the application to automatically select if the media file contains multiple audio tracks.
2. Secondary Audio Language: Your fallback audio track. If a stream does not have an audio track in your Preferred Audio Language, the system will automatically default to this secondary option.

Subtitle Preferences

These configurations control which text translations are displayed on screen and how the menus are filtered.

1. Preferred Language: The primary language you want for your subtitles.
2. Secondary Preferred Language: Your fallback subtitle language. If your primary choice is unavailable, the application will attempt to load subtitles in this language instead.

Use Forced Subtitles: When enabled, the player prioritizes "forced" subtitles that match your preferred language settings. Forced subtitles are meant to be turned on even if you don't use regular subtitles, as they translate foreign languages, alien dialogue, or on-screen text while the rest of the movie is in your primary spoken language. 

- Options: Toggle (On/Off)

Show Only Preferred Languages: Acts as a filter to clean up your subtitle menu. When enabled, it hides all subtitle tracks except the ones that exactly match your Preferred and Secondary Preferred Language settings.
Addon Subtitle Startup

- Options: Toggle (On/Off)

Addon Subtitle Startup

This setting controls how aggressively Nuvio searches for external subtitles when a video begins playing, balancing load times against subtitle availability.
Options: Fast startup, Preferred only, All subtitles

1. Fast startup: Prioritizes getting the video playing immediately. It skips the automatic process of fetching external addon subtitles. You will need to manually request them from within the video player if you want them. 
2. Preferred only: A balanced approach. The system fetches subtitles from your addons during the initial load but only pulls the ones that match your specific language preferences.
3. All subtitles: The most comprehensive option. It fetches and loads every single available addon subtitle for the video, giving you the maximum number of choices at the cost of a slightly longer loading time. 
