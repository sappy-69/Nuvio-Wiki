## New Releases - 2026-07-27

**Nuvio TV (0.7.20-beta)**

Get ready to enjoy your favorite shows and movies with our latest TV update! Here's what we've got in store for you:

* We've improved our language support for Latin American Spanish trailers on TMDB, so you won't miss out on the latest content.
* Some technical fixes were made to prevent duplicate fetch response header values. This should make things run smoother and faster for you.
* We've also tackled some sticky issues, including stuck external auto-next loader and autoplay problems, which should help you avoid frustrations when watching your favorite shows.
* Time left display has been updated for right-to-left (RTL) layouts, making it easier for all users to navigate your shows.
* SurfaceFlinger HWC overlay and VSYNC timing have also been improved for a better viewing experience.
* Your anime ratings from MyAnimeList (MAL) will now be synced with MDBList API, so you can track your progress easily.
* Live search has been enabled while typing, giving you a more interactive and convenient experience.
* We've also fixed some inconsistencies with grid view cards, All tab reshuffling, and meta cache TTL, so everything should look and feel more polished.

**Localization**

Here are some language updates that might interest you:

* Czech, Hebrew, Portuguese (Brazil), and Slovak translations have been updated for better support and a more intuitive experience.
* Slovak language also got some translation improvements, making it easier to explore your content.

**Nuvio Mobile (0.3.1)**

Get the latest mobile updates and enjoy a smoother, more enjoyable experience:

* We've improved navigation and deferred route cleanup until the pop operation completes, giving you a seamless experience when switching between menus.
* Nuvio Engine has been integrated for better performance and stability.
* A recycled bitmap crash in Now Playing metadata has been fixed, so you can watch your shows without interruptions.
* Section headings in settings have been normalized for a more consistent and user-friendly interface.
* We've added a separate upcoming continue watching row for easy access to your next shows.
* Poster depth has been applied to remaining surfaces, enhancing the overall visual appeal.
* A split ABI has been supported for improved performance and compatibility.

**Nuvio Desktop (0.1.14-alpha)**

Our latest desktop update includes some exciting improvements:

* The Parental Guidance API has been updated upstream for better support and accuracy.
* The player subtitle rail has been fixed to prevent horizontal scrolling, giving you a more streamlined viewing experience.
* The app has been fixed to stop freezing when exiting the player, so you can switch between apps seamlessly.
* The player launch has been optimized to prevent hanging the UI thread, making things run smoothly.
* The desktop fullscreen mode has been fixed to remove white border and flash issues, giving you an immersive viewing experience.
* The native player shutdown has been bounded to prevent its windows from being stranded, ensuring a clean exit.

**Nuvio Web (0.3.25-beta)**

Catch up with the latest web update and enjoy a more intuitive and enjoyable experience:

* Loading indicators have been aligned across Web TV with Android TV’s shared 12-segment design, covering various features and menus.
* Buffering feedback has been improved by showing the shared loading indicator immediately when playback stalls, while preserving essential features like startup, seeking, error, and external-player safeguards.
* LG webOS startup audio selection has been improved by keeping track discovery active for a bounded window and preserving supported tracks.
* The modern sidebar blur has been enabled on capable LG webOS televisions running Chromium 120 or newer, while keeping it disabled on unsupported and legacy runtimes.
* Trailer captions have been fixed to prevent reappearing after YouTube player state changes, preserving your preferences.
* Disabled add-ons have been fixed to prevent being re-enabled after profile or device synchronization, ensuring your settings are preserved and synced correctly.
* Subtitle discovery for Anime Kitsu and other non-IMDb sources has been improved by resolving exact unique Cinemeta matches and building addon-compatible episode IDs without replacing the original source identity.
* The Android TV-style “Play manually” action has been added to title and episode menus for a more interactive and convenient experience.
* Skip Intro, Skip Outro, and primary detail actions have been fixed to use correct focus colors with custom themes, making it easier to navigate your content.
* Library focus restoration has been improved to prevent browser focus from unexpectedly scrolling the content, giving you a smoother experience.
* CVE-2026-32141 and CVE-2026-33228 have been resolved by pinning flatted 3.4.2 across the dependency tree and cleaning stale lockfile entries, ensuring your security and stability.
---
## New Releases - 2026-07-26

### Nuvio TV (0.7.20-beta)

- **Watch Your Favorites in Latin American Spanish**: Our Nuvio TV app now supports language normalization for Latin American Spanish trailers on The Movie Database (TMDB). You can enjoy your favorite shows and movies with subtitles and audio in your preferred language.
- **Fewer Glitches, More Fun**: We fixed some pesky issues that were causing problems like duplicate fetch responses, stuck autoloaders, and unexpected behavior. Our app should be more stable and enjoyable for you now.
- **Time for a Change**: If you're a fan of watching movies and shows in languages that read from right to left (RTL), you'll appreciate the changes we made to display time left. No more confusing times, just a clean and easy-to-read interface.
- **New Features to Explore**: We added MyAnimeList (MAL) ratings from MDBList API, live search while typing, and more cloud library features. Now you can easily find and watch your favorite anime shows.
- **More Control, Less Stress**: Our app now prevents unexpected auto resume on transient lifecycle events, keeps your player session consistent, and fixes issues with grid view card consistency and meta cache TTL.

### Localization

- **Say Hello to Czech, Hebrew, and Portuguese Translations**: We've updated translations for Czech, Hebrew, and Portuguese (Brazil), so you can enjoy Nuvio in more languages. Our Slovak translations have also received some exciting improvements.
- **Slovak Language Update**: Big shoutout to the Slovak translators who have worked hard to improve our app's translations. Their efforts will make Nuvio even more accessible to Slovak-speaking users.

### Nuvio Mobile (0.3.1)

- **Nuvio Engine is Here**: We've integrated the Nuvio Engine into our mobile app, bringing you faster navigation, better performance, and an overall improved user experience. Get ready to explore your favorite shows and movies like never before!
- **Navigation, Settings, and More**: Our mobile app has received some fantastic updates, including a new navigation system, improved settings, and more. Enjoy a cleaner and more organized app that's easier to use.
- **Upcoming and Now Playing**: We've added a separate upcoming continue watching row and improved metadata for your Now Playing content. Our mobile app now offers more features and a better way to discover new shows and movies.
- **Grid and Shelf Layouts**: Get ready to explore your library in a whole new way! Our mobile app now supports sortable shelf and grid layouts, making it easier to find and watch your favorite content.
- **Android Split ABI Support**: Our mobile app can now run on Android devices with split ABI (Application Binary Interface) support, providing better compatibility and performance.

### Nuvio Desktop (0.1.14-alpha)

- **Parental Guidance API Update**: We've updated our Parental Guidance API to ensure the app works smoothly and offers the best possible experience for adult and family-friendly content.
- **Subtitle Rail Fix and Improved Performance**: We've fixed the subtitle rail horizontal scrolling issue and improved player exit behavior, making it more stable and enjoyable for users.
- **UI Thread Optimization**: We've optimized our UI thread to prevent the player launch from hanging the app, ensuring a seamless experience for users.
- **Desktop Fullscreen Fix**: We've fixed white border and flash issues when entering desktop fullscreen, providing a cleaner and more immersive experience.
- **Native Player Shutdown Fix**: We've bound the native player shutdown to prevent it from stranding its windows, keeping the app stable and responsive.

### Nuvio Web (0.3.24-beta)

- **Samsung Tizen Installer Fix**: We've fixed issues with Samsung Tizen installer updates, so you can easily install and update Nuvio on your Samsung TV without any problems.
- **Continue Watching Stream Reuse**: Our web app now improves Continue Watching stream reuse, making it easier to continue watching content from where you left off, even if the source provider URLs change.
- **Improved Home Trailer Startup**: We've optimized home trailer startup to reveal playback after the first frame and keep YouTube captions disabled, providing a more enjoyable user experience.
- **Simplified Advanced Settings**: We've simplified Advanced settings by removing the obsolete Remember Last Profile option, making it easier for users to customize their app settings.
---
## New Releases - 2026-07-25

### Nuvio TV (0.7.19-beta)

**New Features and Fixes**

- TV users rejoice! You can now watch Dolby Vision Profile 5 content, including on Zidoo Z9X 8K devices, and the episodes on your favorite shows will have accurate release dates and airtimes.
- Don't worry about your "Continue Watching" row getting lost in space. We've also made sure it's reliable and stays up to date.
- If you switch profiles, you won't see your Continue Watching or watched badges leak into the other profile. That's not very personal, right?
- Auto-next playback after profile changes should now work as expected, and your preference settings will be backed up to keep them safe from file corruption.
- If you want to customize what appears on your screen, you can now save your Collection Editor and Grid View settings with stable IDs.
- Your screen will shine brighter with improved Classic mode vertical fast scrolling and lost shimmer focus in collections.
- No more rejected Trakt refresh tokens for you! We've also fixed subtitle rendering for right-to-left languages, including Hebrew.
- We've polished RTL playback settings sliders, trailer progress, and remaining-time layouts for a more refined experience.

**Localization**

- TV users in Poland, you might have noticed some missing translations; they're now in place.
- We've also updated translation handling for Hebrew and related languages, so your experience is smoother in the right-to-left world.

### Nuvio Mobile (0.3.1)

- **Mobile Navigation**: We made some tweaks to how you navigate through routes on your mobile device.
- **Nuvio Engine Integration**: Get ready to experience Nuvio Engine's advanced features on the go.
- **Recycled Bitmap Crash Fix**: No more crashes when trying to view Now Playing metadata!
- **Settings Simplification**: We've rearranged section headings for clarity and ease-of-use.
- **New Upcoming Continue Watching Row**: You can now track what's up next in your viewing history.
- **Improve Poster Depth**: Visual enhancements for your viewing experience.
- **Library Shelf and Grid Layouts**: Browse your library in style with new shelf and grid layouts.
- **Support for Split ABI**: Behind-the-scenes optimization for better performance.

### Nuvio Desktop (0.1.14-alpha)

- **Parental Guidance Update**: Upstream update for Parental Guidance features, ensuring a safer experience.
- **Subtitle Rail Fix**: No more horizontal scrolling when viewing subtitles!
- **Prevent App Freeze**: We've improved app stability to prevent freezing during player exit.
- **Player Launch Fix**: No more UI thread hang-ups when launching the player.
- **White Border Fix**: Say goodbye to the annoying white border and flash when entering desktop fullscreen.
- **Native Player Shutdown**: We've bound player shutdown to prevent stranding windows.

### Nuvio Web (0.3.24-beta)

**Improvements & Fixes**

- **Installer Update Fix**: Samsung Tizen installer updates should now work smoothly, without the "Author certificate not match" error.
- **Continue Watching Stream Reuse**: Your Continue Watching stream will now be matched even when provider URLs change.
- **Home Trailer Startup**: Experience improved trailer playback with a smoother reveal after the first frame and disabled YouTube captions.
- **Simplified Advanced Settings**: We've removed the obsolete "Remember Last Profile" option to simplify your Advanced settings.