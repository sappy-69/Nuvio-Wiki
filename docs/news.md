## New Releases - 2026-08-03

**Nuvio TV (0.8.1-beta)**

Exciting updates are here for Nuvio TV. Here's what you can expect:

- **Faster Performance**: Our team worked on making the app load faster, thanks to some behind-the-scenes changes to how it handles data.
- **Bug Fixes**: We squashed a few pesky bugs that were causing issues with the 'Skip Intro' button and long show descriptions. Now, everything should run smoothly.
- **New Translations**: We're growing our family, and that means more languages to choose from. Hebrew translations are now available, making Nuvio TV more accessible to everyone.

**Nuvio Mobile (0.4.0)**

Get ready for a mobile experience that's about to get a whole lot better! 

- **New Tracking Provider**: We're joining forces with SIMKL, a top-notch tracking provider that's going to help us bring you more accurate information and better features.
- **Stable Performance**: We fixed a few issues that were causing some trouble on Android devices, like torrent cache pressure. Now, your app should run smoothly.
- **New Language Support**: Say hello to Slovak! We added new language strings so you can enjoy Nuvio Mobile in your native tongue.
- **TmdbEntityBrowser**: We also added some nifty badges to make it easier to navigate through the app.
- **More Fixes**: We made some additional tweaks to ensure that your app is stable and fun to use. We fixed issues like 'Mark as Unwatched' for entire series and corrected authentication errors.

**Nuvio Desktop (0.1.16-alpha)**

**Native Integration with SIMKL**: It's time to take your desktop experience to the next level with our new integration with SIMKL.

- **More Visibility**: We made it easier to manage your tracking provider cards, so you can now view them right on your desktop home screen.
- **Settings Sync**: We also fixed an issue with desktop navigation settings, so they should now sync correctly.

**Nuvio Web (0.3.29-beta)**

The web version of Nuvio gets a much-needed update as well. Here's what's new:

- **All Systems Go**: We fixed a few issues that were causing trouble, and everything should now be running smoothly.
---
## New Releases - 2026-08-02

**Nuvio TV (0.8.0-beta)**

New Features & Fixes
-------------------

- Say hello to SIMKL! We've partnered with them to help track our TV episodes so you can enjoy your favorite shows even more. Our friends at SIMKL will now be working with us to make sure you never miss a beat!
- We've stabilized some fancy technology that helps bring back the focus on selected episodes, so you can pick up right where you left off.
- We've made some updates to Play decoder and privacy link to keep things running smoothly and securely. Don't worry, your data is safe with us!
- Your TV devices are now registered for a seamless viewing experience. That means you can easily pick up where you left off across all your devices!
- We've added the full release date for TMDB collection movies, so you can see when your favorite movies came out. We've also expanded the hero video on collection pages to make them look more amazing!
- When you're browsing through your Continue Watching list, your cards will now look cooler with a new design and lower corners. We've also made sure the next episode is ready for you to watch after you finish the current one!
- When you're watching a video and Skip Intro is visible, you can now tap on the focus line to skip the intro.
- When a problem happens and you see an error message, you can now tap on "Report Issue" to let us know what went wrong.
- We've fixed some issues where seeking forward would take you back to the beginning of the video or the scroll position would reset when switching between source tabs.
- We've kept your subtitles enabled even after you've adjusted the delay.
- We've kept the Fire TV keyboard open and fixed the shimmer depth to make it look cooler.
- When you're watching a video, the Skip Intro button now stays visible for the whole timeout duration, so you won't miss it.
- If a video is too short and doesn't have any saved position, we'll now keep resume position when the saved duration is zero.
- We've applied some cool font size and position settings when a subtitle track becomes active in ExoPlayer. We've also blocked the horizontal scrolling in shimmer rows, so you can enjoy your subtitles without any distractions. Plus, your subtitle preferences will now stick with you, and we'll even persist them even when you close and reopen the app!
- We've reverted some changes that made our video player lifecycle management go awry. Focus handling, pause/resume transitions, and the way we render video are all back to normal now.
- When you resume watching a video, the app will now remember your resume position.
- We've hidden empty source sections in ROWS view mode, so you won't see clutter when you don't have any sources available.
- When you hide unreleased content, we'll no longer show you titles that don't have a release date.
- We've fixed an issue where MKV startup wouldn't work as expected because of some audio analysis delays.
- We've improved the way we handle zero-duration cues and A/V resynchronization after long pauses, so you can watch your videos smoothly.
- If a video can't be decoded by our built-in hardware, we'll now use software audio decoding to play it safely.
- We've fixed the Audio Frequency Rate (AFR) preflight for extensionless streams and large MP4/MKV remuxes, so you can play your videos without any errors.
- We've prevented short error streams from being marked watched or automatically playing the next episode. That means you won't get tricked into watching a short, broken stream instead of your favorite show!
- We've prevented focused posters from expanding when you lose focus on the app. Now when you pick a new show or video, the poster will stay nice and centered on the screen!
- We've made sure expanded cards stay open during the long-press action menu, so you can enjoy your content without distractions.
- We've restored the ability to see all your items using stable item keys, so navigation is now smoother and more natural!
- We've fixed startup loading stalls during cold starts and resume seeks, so you can get into your favorite shows faster.
- We've restored the production company browse card focus after navigating back, so you can easily pick up where you left off!
- We've added an HLS MIME-type fallback when container parsing fails for debrid caching streams. That means you can watch all the available streams without worrying about compatibility issues!
- And finally, we've accelerated scrubbing while remote keys are held, so you can navigate your content even faster!

**Localization**

- We've fixed the hero section so it uses the correct localized month form for release dates. That means our international friends will see the right date formats in their favorite shows!

- We've improved and adjusted Slovak translations to make sure our international friends can access our app seamlessly and in their native language!

**Nuvio Mobile (0.4.0)**

New Features & Fixes
-------------------

- Say hello to SIMKL! We've partnered with them to help track our mobile episodes, which means an even better experience for you!
- We've fixed some issues where the app got too stressed with too many torrent caches.
- We've taken the videoid from meta for track services in progress items, so watching is smoother than ever!
- We've gotten rid of recent history icons for search, so your search results are now cleaner and easier to navigate.
- We've added some cool badges to the TmdbEntityBrowser to help you identify what's trending!
- Our Slovak friends will now have more accurate settings and feature strings, making our app even more accessible to more people!
- We've updated Slovak translations for parental content strings, so all our international friends can watch safely!
- We've fixed the issue where some recent episodes couldn't be marked as unwatched.
- We've sanitized authentication errors so you get clear feedback and you can log in with confidence.
- When you save or change your profile, the selected profile will now be activated immediately!
- We've fixed an issue where Trakt didn't sync the correct seek position.

**Nuvio Desktop (0.1.15-alpha)**

New Features & Fixes
-------------------

- We've fixed an issue with our app not syncing catalogs smoothly, card scroll, and clipping when you launch a new episode.
- We've fixed an issue where the escape key didn't exit fullscreen mode cleanly.
- We've registered Nuvio Desktop devices, so our desktop app can now sync your library and preferences correctly!

**Nuvio Web (0.3.28-beta)**

New Features & Fixes
-------------------

- We've fixed an issue with movie stream discovery, so you'll now see the movie ID preserved across different sources.
- We've fixed an issue where navigation back to the title would go awry and lose the return destination.
- We've fixed an issue where Continue Watching detail routes would stay in browser history even after you went back.
---
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