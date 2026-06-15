## Nuvio Player Settings

Nuvio offers many player settings options. This section will discuss:

[Intro and Outro Skip](#Intro-and-Outro-Skip)

[Next Episode](#Next-Episdoe)

Subtitle and Audio
Stream Selection

Decoder Options

MPV


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

## Next Episdoe

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
