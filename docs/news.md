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
---
## New Releases - 2026-07-06

**Nuvio TV (0.7.16-beta)**

* We've improved Trakt reliability by ignoring watched movies that are no longer available and making sure that series markers show up on the Home screen. You can now also fetch watched movies more efficiently and have the option to auto-refresh your content.
* Your Trakt login credentials will now sync across all Nuvio clients, so you only need to log in once.
* We've fixed a few visual issues, including the loading indicator, and made sure that posters load properly even if they're not available.

**Localization**

* We've added and updated translations to make Nuvio TV available in even more languages, including French, Hebrew, Latin American Spanish, Greek, and Italian.
* Our translations are now more accurate and consistent, so you can navigate and enjoy Nuvio TV in your native language.

**Nuvio Mobile (0.2.19)**

* We've added support for Hungarian and Italian languages, and updated Hungarian translations to ensure accuracy and consistency.
* Nuvio Mobile now works seamlessly on both iOS and Android, and you can enjoy Now Playing features, including skipping precision and playback settings for a perfect viewing experience.
* We've also fixed some issues, including ignored episodes, backup settings, and stream playback, so you can focus on watching your favorite shows and movies.

**Nuvio Desktop (0.1.10-alpha)**

* We've fixed some visual issues, including the blur panel and dominant color background, to make Nuvio Desktop more stable and visually appealing.
* Your profiles will no longer overlap in the sidebar, and we've updated Compose Multiplatform beta for better performance.

**Nuvio Web (0.3.8-beta)**

* We've fixed playback issues on Samsung Tizen devices by providing a safer fallback to the alternate playback engine, and improved playback reliability for sources that may fail initially.
* You can now easily navigate the P2P consent dialog on TV devices with proper focus movement between Cancel and Enable P2P, and the focus now starts on Enable P2P for a smoother experience.
* We've fixed playback settings persistence issues related to profile sync responses, and improved Supabase proxy handling for better performance on webOS.
* Additional fixes include syncing profile settings, collections, and watched items, and preserving custom addon names when syncing with the remote server.
---
## New Releases - 2026-07-05

### Nuvio TV (0.7.15-beta)

**New Features & Fixes**

- We've made it easier to detect streams, including playlists, so you can find your favorite shows and movies.
- You won't see an accidental logout anymore; we've added a confirmation dialog to make sure you mean to sign out.
- Our crash-reporting tool just got superpowered with optional diagnostic info, which helps us fix bugs faster.
- If a video won't play, the player will now retry, but only a few times, to prevent endless loop frustrations.
- Some stream loading fixes got reversed, and now you won't see that flickering issue anymore.
- You can now personalize the auto-play settings to suit your viewing habits.

**Localization Update**

- We've got some Portuguese (Brazil) translations updated to make sure Nuvio TV feels more at home in Brazil!

### Nuvio Mobile (0.2.18)

**Mobile Improvements**

- You can now customize your auto-play settings for even longer, with the option to set it to hours instead of minutes.
- Our crash-reporting tool is also here on mobile, giving us valuable info to fix issues.

### Nuvio Desktop (0.1.10-alpha)

**Desktop Updates**

- The stream blur issue is fixed now, and you won't see that fuzzy image anymore.
- We've added a cool feature where the background of our app changes color to match the dominant color of your stream.
- The metadata background is stabilized now, so you can enjoy a more seamless experience.
- If you have multiple profiles, they won't overlap anymore in the sidebar.
- We've also updated our beta app to make it better for all users.

### Nuvio Web (0.3.8-beta)

**Web Improvements & Fixes**

- If you're using Samsung Tizen, you should find that playback works better now, even with weird network issues.
- We've fixed some Tizen playback issues so it's more reliable, especially when switching between different playback engines.
- The P2P consent dialog on TV devices just got a lot more navigable, so you can focus on enabling peer-to-peer sharing instead of canceling by accident.
- When setting up P2P sharing, the focus is now on Enable P2P, reducing accidental cancels.
- Some playback settings got stuck on profile sync responses, but we've fixed that, so your settings persist correctly.
- Some webOS sync issues got fixed, especially with those pesky 204, 205, and 304 responses.
- We've made some changes to webOS sync, so it behaves better and is more reliable.
- You can now choose your preferred audio language, including Original Language, on Web TV.
- The player's original content language is now passed along to playback when available.