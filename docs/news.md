## New Releases - 2026-07-11

### Nuvio TV (0.7.16-beta)

**What's New**

Watchlist woes are now a thing of the past! We've fixed a pesky issue where watched series markers weren't showing up on the main Home page, and made Trakt more reliable by ignoring old watched playback data. You'll also appreciate the new pagination feature for fetching watched movies, Trakt credential syncing across devices, and periodic refresh support.

**Other Fixes and Tweaks**

We've made some behind-the-scenes changes to improve the overall experience:

- The loading indicator now resets properly when you start playback.
- We've squashed a bug that caused zero-size poster requests.
- You can now override Dolby Vision MIME types with ease.
- Our stream chip loading badge is now a consistent size, making it easier to use. 
- And, to make troubleshooting easier, we're now sending diagnostic data when you report issues.

### Localization

**New Translations and Updates**

Language lovers rejoice! We've added:

- New French translations, using formal wording where needed.
- Hebrew translations, with many new and updated strings.
- Latin American Spanish localization strings, so you can find your favorite shows.
- Greek strings, with English placeholders for missing translations.
- Italian translations, so you can enjoy your favorite shows with friends.

### Nuvio Mobile (0.2.21)

**Mobile Fixes and Improvements**

We've been working hard to resolve some issues on your mobile devices:

- Fixed video playback rotation issues on iOS devices.
- Improved memory allocation for better performance.
- We're directing the MPVKit to the latest libmpv binary.
- Our AudioUnit crash guard is now more robust.
- Your Trakt credentials will now sync properly during playback.
- Fixed an issue with stream continue watching metadata enrichment.
- And, to top it off, we've made sure your Home catalog sync keys are preserved.

### Nuvio Desktop (0.1.11-alpha)

**Desktop Fixes and Performance Enhancements**

We've been working hard to improve your desktop experience:

- We've tweaked the buffer cache for better performance.
- Fixed a compiling issue that was causing problems.
- Our loading spinner now works as expected.
- And, to make things easier to navigate, we've added scrollbars to the app.
- Fixed a crash that was happening when browsing entities.
- Wired up deeplinks to work within the desktop app.
- And, to keep you up all night, we've fixed a display sleep issue on Windows.
- Finally, we've aligned your addon and playback networking on desktop.

### Nuvio Web (0.3.9-beta)

**Web Updates and Fixes**

We've been working on some significant updates for our web experience:

- We've aligned our autoplay and source selection with Android TV, so you can find your next episode with ease.
- Fixed an issue where completed episodes would start near the end of playback.
- We've improved embedded subtitle handling on webOS and Tizen devices.
- Fixed subtitle sizing on older Samsung Tizen TVs.
- Improved playback reliability on webOS, so your screensaver can't interrupt you.
- Fixed automatic audio-language selection when metadata was incorrect.
- We've fixed Skip Intro so it stays hidden when you're done with it.
- Restored stream badge preloading and caching for faster loading times.
- Aligned quality sorting with Android TV by ordering streams by resolution, quality, and file size.
- Fixed Trakt credential sync errors and improved synchronization with Nuvio Sync.
- And, to top it off, we've improved Continue Watching synchronization when restoring or selecting profiles.
---
## New Releases - 2026-07-10

### Nuvio TV (0.7.16-beta)

**What's New for Nuvio TV:**

- We've made some great improvements to Trakt, the service you love, to make your experience even better. We've fixed issues where markers didn't appear on Home and some watched series weren't syncing correctly.
- You'll now see watch movies on Trakt, too, so you can keep track of all your favorite flicks. And guess what? We've got pagination, so you won't see them all at once – it's like browsing through your favorite movie catalog!
- Your Trakt credentials will now sync across all your devices, so you won't have to log in every time you switch between your TV and phone.
- If you've got a slow internet connection, don't worry! Your Nuvio TV will automatically refresh the info when it detects a stable connection, ensuring you always have the latest info.
- And, as a bonus, we've improved the loading indicator so it doesn't reset when you start a new media. It's the little things that count, right?
- We've also fixed some pesky bugs that made your posters appear with weird sizes. It's now a nice, clean image – no more squished or stretched posters!
- Dolby Vision lovers, rejoice! We've ensured that only Dolby Vision tracks override the video MIME type, so you get the best audio-visual experience possible.
- Your visual experience just got a little better, with a resized stream chip loading badge for better visual consistency.
- Last but not least, we've made it easier for our developers to fix issues by enabling Sentry tombstone reporting for improved diagnostics.

### Localization

**Language and Translation Updates:**

- We're thrilled to announce the addition of formal French translations, making your experience even more enjoyable in French. We backfilled missing translations so you can now enjoy Nuvio TV with more precise language.
- Get ready for a richer experience in Hebrew! We've added new translations for a more immersive experience.
- For our Latin American Spanish friends, we've got some new updates: fresh strings to make your experience even smoother.
- We've added missing Greek translations, and when we don't have a translation, we'll now show English placeholders – it's all about making things clear and easy to understand.
- Italian speakers, rejoice! We've got new translations to bring you closer to the action, with the added benefit of clearer placeholders for what we're still working on.

### Nuvio Mobile (0.2.21)

**Mobile Improvements:**

- We've improved iOS player rotation to give you a seamless, distraction-free experience when rotating your device.
- To reduce lag and improve overall performance, we've increased the build memory and implemented a device fallback feature.
- To ensure stability, we've updated our MPVKit to support the latest libmpv release and fixed an issue with AudioUnits.
- To keep your watching experience seamless, we've fixed issues related to the Trakt continue watching sync.
- We've fixed the stream continue watching metadata enrichment, so you get the right information at the right time.
- We've also fixed issues related to preserving home catalog sync keys, ensuring your watchlist is accurate.

### Nuvio Desktop (0.1.11-alpha)

**Your Desktop Just Got a Boost:**

- We've fine-tuned the buffer cache to optimize your media buffering experience.
- To improve desktop stability, we've fixed desktop compile issues and ensured that the actuals are accurate.
- A fix to prevent the desktop loading spinner crashes will give you a smoother experience.
- We've added desktop scrollbars, making it easier to navigate through your watchlist and collections.
- We've fixed issues related to the entity browse plural crash, ensuring that you can browse through your media without issues.
- With this update, you can now wire deeplinks into the desktop app, making it easier to access your favorite content directly.
- We've also fixed an issue where Windows would go to sleep during playback, and we've made sure desktop addon and playback networking are in sync.
- Last but not least, we've fixed an issue where your window's fullscreen state, position, and size wouldn't restore properly on relaunch. 

### Nuvio Web (0.3.8-beta)

**New Features and Improvements:**

- For Samsung Tizen users, we've now got a safer fallback to alternate playback engines when AVPlay fails with network-related startup errors, reducing playback startup failures.
- We've improved Tizen playback reliability for sources that may fail on the first selected engine, making sure you can watch your favorite media without issues.
- To enhance the navigation, we've fixed the P2P consent dialog on TV devices, allowing proper left/right focus movement between Cancel and Enable P2P.
- We've updated the P2P enable flow so the focus starts on Enable P2P, reducing the risk of accidentally confirming Cancel instead of enabling the option.
- For webOS users, we've fixed playback settings persistence issues related to profile sync responses by handling no-content Supabase responses correctly.
- We've fixed Supabase sync failures caused by 204, 205, and 304 responses, and improved the sync by routing proxy requests through the Luna service instead of calling the local media server directly.
- To address webOS sync errors where profile, settings, collections, plugins, addons, library, and watched items could fail, we've made some adjustments to make sure your watchlist and other settings are always up-to-date.
- In this update, we've preserved local custom addon names on Web TV when remote sync data doesn't explicitly include an override, giving you more control over your experience.
- We've also updated the addon name override sync on Web TV to safely support legacy addon sync, making sure you don't lose your favorite plugins.
- To make your experience even better, we've added support for Original Language as a preferred audio language option on Web TV, giving you more control over your media playback.
- We've updated the preferred audio language behavior to be more consistent with Android TV, using TMDB original-language metadata when Original Language is selected.
- To bring you even more info, we've improved the player route metadata to include the original content language from detail pages into playback when available.
- Lastly, we've aligned Web TV profile settings sync with Android TV for the Original Language audio preference, bringing you more consistency across your favorite streaming devices.
---
## New Releases - 2026-07-09

**Nuvio TV (0.7.16-beta)**

**What's New**

Get ready for a smoother viewing experience with these exciting updates:

- **Trakt reliability boost**: We've strengthened the connection between Nuvio TV and Trakt API, ensuring that watched series markers and playback history stay in sync.
- **Watched movies get their turn**: We've added pagination support for fetching watched movies, matching the new updates from the Trakt API.
- **Trakt credentials now sync across clients**: No more worrying about keeping track of multiple Trakt credentials; Nuvio TV will now sync them seamlessly across devices.
- **Periodic refresh keeps things fresh**: Stay up-to-date with the latest changes in the Trakt API, thanks to periodic refreshes.
- **Loading indicators get a new look**: The loading indicators will now behave more consistently, making it easier to know when Nuvio TV is loading.
- **Dolby Vision now shows up correctly**: We've fixed issues with Dolby Vision MIME type overrides, making it easier to access your high-quality video content.
- **Stream chip looks more polished**: The stream chip badge has been resized for better visual consistency.
- **Sentry diagnostics get a boost**: With improved Sentry tombstone reporting in metadata, we'll have better insights for debugging and troubleshooting.

**Localization Update**

Get ready to explore your favorite shows and movies in even more languages!

- French translations have been backfilled, so you can now enjoy Nuvio TV in French.
- Hebrew and Latin American Spanish got some love, with new and updated translations.
- We've added missing Greek strings and added Italian translations to the mix.
- English placeholders have been included for any still-untranslated strings in Greek.

**Nuvio Mobile (0.2.19)**

**What's New**

Nuvio Mobile just got a whole lot better!

- **Hungarian localization gets a refresh**: We've updated and improved the Hungarian localization to match the latest app string changes.
- **Greek translations arrive**: You can now explore Nuvio Mobile in Greek, with 854 missing UI strings now translated.
- **iOS Now Playing support is here**: You can now enjoy seamless Now Playing support on iOS devices.
- **PlaybackAutoPlaySettings gets an update**: Additional hours have been added to PlaybackAutoPlaySettings, giving you more flexibility.
- **Android backup gets disabled**: Android backups are now disabled by default, so you can better manage your storage.
- **Trakt pagination arrives**: Just like Nuvio TV, Nuvio Mobile now supports pagination for fetching watched movies on Trakt API.
- **Various bug fixes**: We've fixed several bugs, including issues with Trakt progress, availability of episodes, and more.

**Nuvio Desktop (0.1.11-alpha)**

**What's New**

Get ready for a smoother experience with Nuvio Desktop!

- **Buffer cache now works better**: We've fixed the buffer cache, so you can enjoy smoother video playback.
- **Desktop loading spinner now crashes less**: We've fixed an issue that was causing the loading spinner to crash, so you can now expect a smoother experience.
- **Scrollbars arrive on desktop**: You can now easily navigate through the app with new scrollbars across the desktop.
- **Entity browse plural now works better**: We've fixed an issue that was causing plural crashes, so you can now browse entities without issues.
- **Deeplinks now work on desktop**: Deeplinks are now working as expected on the desktop app.
- **Desktop sleep no longer interferes**: We've fixed an issue that was causing the display to sleep during playback, so you can now enjoy uninterrupted video content.
- **Addons and playback networking now work better**: We've fixed several issues related to addons and playback networking, giving you a more seamless experience.

**Nuvio Web (0.3.8-beta)**

**What's New**

We're excited to announce these improvements on the Nuvio Web platform:

- **Samsung Tizen playback just got better**: We've added a safer fallback to the alternate playback engine for Samsung Tizen devices, reducing playback failures related to network startup errors.
- **Tizen playback reliability has been improved**: We've made some significant changes to improve Tizen playback reliability for sources that may fail on the first selected engine.
- **P2P consent dialog navigation just got easier**: You can now navigate the P2P consent dialog more intuitively on TV devices, with proper left/right focus movement.
- **P2P enables flow now works better**: We've simplified the P2P enable flow to reduce accidental cancel confirmations.
- **Playback settings now persist correctly**: We've fixed issues related to playback settings persistence on webOS, ensuring that your profiles sync correctly.
- **Supabase sync failures now resolved**: We've fixed Supabase sync failures caused by invalid Response bodies, improving webOS performance.
- **WebOS Supabase proxy handling has been improved**: We've updated Supabase proxy handling on webOS, reducing sync errors and improving the user experience.
- **Addon name overrides now sync properly**: We've fixed issues with addon name overrides on Web TV, preserving local custom addon names when sync data doesn't explicitly include an override.
- **Original Language now available as a preferred audio option**: You can now select Original Language as a preferred audio language option on Web TV, with TMDB original-language metadata used when available.
- **Web TV preferred audio language behavior now matches Android TV**: We've aligned Web TV preferred audio language behavior with Android TV, using TMDB original-language metadata when Original Language is selected.
- **Player route metadata now includes original content language**: We've improved player route metadata to include the original content language, making it easier to access high-quality video content.
- **Web TV profiles now sync correctly**: We've aligned Web TV profile settings sync with Android TV, ensuring seamless synchronization.
- **Trailers and detail view default behavior now match Android TV**: We've updated the default behavior of the trailer button on Web TV, aligning it with Android TV.
- **Web TV app metadata bumped to version 0.3.8**: We've updated the app metadata to the latest version, ensuring compatibility with the latest webOS features.