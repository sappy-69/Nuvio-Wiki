## New Releases - 2026-07-14

### Nuvio TV (0.7.16-beta)
#### Catch Your Favorite Shows Without a Hitch
- Got a problem watching your favorite series on Trakt? We've got some good news: you can now ignore old playback markers and the series icons should appear back on the Home screen.
- Trakt users, rejoice! Your movie history is now organized in neat little pages, thanks to some behind-the-scenes pagination work.
- Keeping track of your Trakt credentials is now easier, and they'll even sync across different clients, so you don't have to worry about signing in everywhere.
- Need a reminder about what's new on your favorite platform? Periodic refresh supports mean you'll stay in the loop.
- Got a problem with the loading indicator not working right? That's fixed!
- Poster prefetch requests won't get stuck on empty images anymore, so you can see what's playing in style.
- Some of you might have been watching Dolby Vision content without even knowing it. Now, only Dolby Vision tracks can override MIME types, so you get the best picture quality.
- Stream chip loading badges now look consistent across your Nuvio experience.
- Ever had a problem with our diagnostics tools? Now they'll send you more detailed reports so you can figure out what's going on.

### Localization
#### We're Speaking Your Language!
- French translations just got a lot more polished!
- Hebrew fans rejoice! We've got new translations just for you!
- Get ready for the latest Spanish translations, straight from Latin America!
- Greek and Italian translations are joining the party – expect more updates coming soon!

### Nuvio Mobile (0.2.23)
#### Make Your Nuvio Experience Pop!
- Want to customize how your favorite cards look? You can now choose from various depth effects!
- Oh no, your profile settings just got reset! Don't worry, this super-important fix makes sure that won't happen again.

### Nuvio Desktop (0.1.13-alpha)
#### Nuvio at Your Service
- Fixed a tricky bug that made our windows webview go haywire – now everything should look just right.

### Nuvio Web (0.3.13-beta)
#### Keeping Things Smooth
- Expect a smoother experience with the latest bug fixes. We're constantly working to make Nuvio Web the best it can be.
---
## New Releases - 2026-07-13

### Nuvio TV (0.7.16-beta)

- **Trakt Time**: We've fixed some pesky Trakt problems. Our system now ignores out-of-date play history and makes sure watched series markers appear on the Home screen. We've also updated the way we fetch watched movies, so everything should load faster and more smoothly. 
- **Credentials Sorted**: Now, your Trakt login is synced across all Nuvio devices, so you only need to log in once.
- **Updates Galore**: We've added some sweet features like periodic refresh support, which updates your content in the background. We've also fixed the loading screen startup issue and made the stream chip loading badge look better on your TV.
- **Tech Talk**: Behind the scenes, we've enabled Sentry tombstone reporting for faster diagnostic help.

### Localization

- **Bonjour France!** We've added a bunch of missing French translations to Nuvio TV, so everything should be more readable and friendly for our French friends.
- **Shalom Hebrew!** We've added new Hebrew translations and updated some of the existing ones to make Nuvio TV more accessible and fun for Hebrew speakers.
- **Hola Amigos!**: We've updated the Latin American Spanish localization strings and added more Italian translations to make Nuvio TV a global player.

### Nuvio Mobile (0.2.23)

- **New Card Style**: We've added customizable card depth effects on Nuvio Mobile, so you can choose your favorite style and make it pop on your mobile screen.
- **Settings Saved**: We've fixed a critical bug that could reset your synced profile settings. Your settings should now stay saved and be ready for next time.

### Nuvio Desktop (0.1.12-alpha)

- **Fixes Galore**: We've fixed a bunch of issues on Nuvio Desktop, including restoring unaired episodes and preventing settings sync reset.
- **Card Customization**: You can now customize your card depth on Nuvio Desktop, so it looks exactly how you like it.
- **Runtimes and Sync**: We've improved the way player runtimes work on Nuvio Desktop and added foreground sync, so you can enjoy your favorite shows and movies without interruptions.
- **Debrid Resolution**: We've prioritized debrid resolution in player sources, so you should get the best possible video quality.
- **Playback Pro**: We've fixed the playback proxy issue and made sure everything runs smoothly.

### Nuvio Web (0.3.12-beta)

- **Navigation Navigated**: On Samsung Tizen, we've fixed duplicate Back events that could cause the sidebar to open unexpectedly.
- **Playback Smooth**: We've improved adaptive stream playback on Samsung Tizen, so you get the best possible video quality without buffering.
- **Trailer Tamed**: We've reduced recurring trailer stutters on Samsung Tizen by optimizing the way we load and display trailers.
- **Subtitles Sorted**: We've fixed a problem that made built-in subtitle tracks appear as "Unknown". Now, they should display correctly.
- **Language Labels**: We've improved subtitle language detection for regional variants and updated the subtitle selection menu to look more like Android TV.
- **Hidden Languages**: We've added an option to show only preferred languages, so unrelated subtitle languages are hidden from view.
- **Profile Performance**: We've improved profile startup performance by reusing loaded data and reducing duplicate synchronization passes.
- **Startup Watchdog**: We've improved the startup watchdog by renewing its timeout during boot progress, preventing slow initialization stages from being reported as frozen.
- **Playback Stability**: We've improved webOS playback startup stability by delaying subtitle decoder initialization until the first playback frame.
- **Collection Caching**: We've preloaded focused artwork ahead of the visual update, so backdrops and Hero images load faster.
---
## New Releases - 2026-07-12

**Nuvio TV (0.7.16-beta)**

### Improvements & Fixes
We've got a major update for Nuvio TV to make it a better viewing experience:

- Fixed a pesky bug that was causing watched series markers to disappear on your Home screen. We've also updated Trakt's reliability so that you can trust your watched list.
- Now, you can fetch watched movies with pagination to match recent Trakt API changes, making it easier to browse through your favorite movies.
- Syncing Trakt credentials is now easier and more convenient across all your devices.
- Periodic refreshes keep your Nuvio TV experience fresh and up-to-date.
- We've also fixed some loading indicator and poster prefetch issues, so you can get back to binge-watching your favorite shows.
- Dolby Vision tracks now have their own special MIME type override, so you can enjoy the best picture quality.
- And, we've made some visual tweaks to improve the stream chip loading badge size for a more polished look.

### Localization
Get ready for a world of languages in Nuvio TV!

- We've added and updated French, Hebrew, Italian, and Latin American Spanish translations to make your Nuvio TV experience more enjoyable in your native language.
- Missing Greek strings have been added, with English placeholders for translations that haven't been done yet.
- Now, you can switch between languages with ease, and we'll keep improving our localization to make Nuvio TV a truly global service.

**Nuvio Mobile (0.2.22)**

### Improvements & Fixes
Get the latest update for Nuvio Mobile and enjoy a better mobile experience:

- Introducing Content Warnings, just like on TV! You can now control what you want to see and when.
- We've added support for Vietnamese, making Nuvio Mobile a more inclusive experience.
- Display section spacing in Stream Settings has been fixed to look cleaner and more organized.
- Romanian, Dutch, and Italian translations have been added to make your experience more enjoyable in your native language.
- Sync watch progress source has been fixed, so you won't lose your place while watching your favorite shows.
- And, we've improved navigation and stability on iOS to make Nuvio Mobile a seamless experience.
- Content warnings, new languages, and improved stability mean you can enjoy Nuvio Mobile like never before!

**Nuvio Desktop (0.1.11-alpha)**

### Improvements & Fixes
A new update for Nuvio Desktop brings some great improvements:

- Buffer cache has been adjusted to reduce lag and improve playback.
- We've fixed some desktop compile issues to make sure you can get the latest version of Nuvio Desktop.
- Loading spinner crashes have been fixed, so you can get back to watching your favorite shows without interruption.
- Desktop scrollbars have been improved to make navigation smoother and more enjoyable.
- And, we've fixed some entity browse plural and deep linking issues to ensure that Nuvio Desktop runs smoothly on Windows.
- Your Nuvio Desktop experience just got a whole lot better!

**Nuvio Web (0.3.10-beta)**

### Improvements & Fixes
Get the latest update for Nuvio Web, with improved performance and stability:

- We've added a startup diagnostics screen for early boot failures on webOS and Tizen, making it easier to identify initialization errors.
- Localized "Error Details" text has been added for all supported languages, eliminating missing translation warnings across the app.
- Duplicate subtitles on Samsung Tizen have been fixed, so you no longer see two sets of subtitles at once.
- Live TV details pages now fully initialize when channels are opened from catalogs, and the Play button responds as expected on Samsung Tizen.
- Live TV metadata resolution has been improved, ensuring the correct addon and content type are used when loading details and streams.
- Initial profile settings synchronization has been fixed, so your settings are saved on first use.
- Missing playback setting translations for Next Episode Threshold options have been added, removing related localization warnings.
- The in-app diagnostics console on older webOS and Tizen versions has been improved, with reliable scrolling, page navigation, and legacy input events.
- Hero artwork positioning and gradient rendering on older TV browsers have been fixed to prevent logos from being clipped or gradient issues.
- Stream selection panels now render with transparent backgrounds on older TV browsers, restoring the intended appearance.