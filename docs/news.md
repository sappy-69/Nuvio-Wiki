## New Releases - 2026-07-30

**Nuvio TV (0.7.20-beta)**

We've made some awesome improvements to Nuvio TV:
- Now you can enjoy your favorite Latin American Spanish shows with improved video descriptions.
- You don't have to worry about duplicates when searching for new content - we've fixed the issue.
- Our team fixed some pesky bugs causing Nuvio to crash or get stuck.
- If you accidentally hit back on an episode, Nuvio will now unblock autoplay and take you back to the start.
- We updated the way Nuvio displays time left in RTL (Right-To-Left) layouts, making it easier to read and understand.
- Our SurfaceFlinger tech got a performance boost and fixed some timing issues, ensuring smoother playback.
- You can now check out MyAnimeList ratings directly from TMDb's API (just another way we're making your life easier).
- Live search is now available on Nuvio TV - simply type in the search bar to get a list of matching results.
- We fixed a few more issues, including preventing unexpected auto-resumes during playback:
  - We fixed the grid view card layout, making it easier on the eyes.
  - You won't have to worry about numbers being displayed incorrectly in some layouts.
  - All tab reshuffling and some cache settings have been updated for a better overall experience.

**Localization**

Big thanks to our translation team for helping us bring Nuvio to more languages:
- Czech-speaking users can now enjoy a more natural experience with updated translations.
- Hebrew and Portuguese (Brazil) translations have also been updated.
- Our Slovak team has been working hard on improving the language, making it more intuitive and natural.

**Nuvio Mobile (0.3.2)**

We're making Nuvio Mobile better with each update:
- Official client devices can now be registered more smoothly.
- Play account settings and background services have been updated for better performance.
- Nuvio's CardDepthEffect has been improved to prevent sheen overlays from getting out of shape.
- Card header accent lines are now removed for a more streamlined design.
- Cloud library search is now a breeze - just type and go!
- MyAnimeList ratings are now directly available from the MDBList API.
- Per-profile isolation for Trakt auth and storage has been fixed for a more secure experience.
- Image-based subtitle rendering has been fixed for better visibility.

**Nuvio Desktop (0.1.15-alpha)**

Nuvio Desktop just got a whole lot better with these fixes:
- The Cold-launch catalog synchronization has been stabilized, ensuring smooth content loading.
- Drag-scrolling continue-watching functionality has been fixed.
- Card sheen clips are now correctly applied for a prettier design.
- Escape key now correctly Exits full-screen mode before navigating away.

**Nuvio Web (0.3.26-beta)**

Don't worry - we didn't forget about Nuvio Web!
- We fixed some issues that might have caused annoyances while using Nuvio Web.
---
## New Releases - 2026-07-28

**Nuvio TV (0.7.20-beta)**

- Get ready to groove to Latin American Spanish trailers in style - they're now properly displayed with language normalization!
- No more duplicates: we've squashed the issue with duplicate fetch response header values.
- Our tech wizards have been hard at work fixing some sneaky Sentry crashes - thanks for the fixes @skoruppa!
- Autoplay and auto-next loader issues are a thing of the past - you can now back out without getting stuck.
- In right-to-left layouts, time is now displayed in a logical order - thanks for pointing that out @haveAnIssue!
- We've improved video performance by tweaking SurfaceFlinger HWC overlays and VSYNC timing - and fixed some preflight probe shenanigans.
- Give MyAnimeList (MAL) ratings a try - we've added them to the mix using the MDBList API with @guuilp's magic.
- Live search is now live - try typing away and see what shows up!
- Media Session tears-down and gets re-constructed without causing a feedback loop - stability win!
- Find what you need faster - search the cloud library right from the library tab!
- We've updated okhttp and OpenSubtitlesHasher with keep-alive magic - and fixed an unexpected auto-resume issue.
- Card consistency is now top-notch, and meta cache TTL is working as expected - thanks for the fixes @skoruppa!
- Numbers now work correctly, including hours in right-to-left views - another @haveAnIssue fix!

**Localization**

- Czech translations are now up-to-date - thanks for the updates @SnaexCZ!
- Hebrew translations have been updated, and Portuguese translations for Brazil and Portugal have also been improved - cheers for the work @haveAnIssue and @danilopagotto82!
- Slovak translations have seen some love - thanks for the translation improvements @mmsw91!

**Nuvio Mobile (0.3.2)**

- You can now register your device with our official client - no more worries about authorization!
- Our Play account integration is compliant with foreground service guidelines - we've got our ducks in a row!
- A minor but lovely tweak: the CardDepthEffect sheen overlay is now clipped to its shape path - more polished visuals!
- Say goodbye to the catalog header accent line - it's been refactored away!
- Cloud library search is now live on mobile - go ahead and search!
- MyAnimeList (MAL) ratings have arrived on mobile - thanks @guuilp!
- Profile isolation has been improved for Trakt auth and storage - safer, more secure!
- And, to wrap it all up, subtitle rendering on images is now working like a charm - no more glitches!

**Nuvio Desktop (0.1.14-alpha)**

- Our parental guidance API has been updated - we're now in line with the upstream version!
- Subtitle rail horizontal scrolling has been removed - a more fluid experience!
- App freezes on exit? Gone - we've disposes of the native player on the EDT!
- No more UI thread hanging - the player launch is now offloaded!
- White borders and flashes? History - we've fixed them when entering desktop fullscreen!
- Native player shutdown is now bounded - no more stranded windows!

**Nuvio Web (0.3.26-beta)**

- We've fixed a bunch of issues to make your experience on Nuvio Web smoother - enjoy!
---
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