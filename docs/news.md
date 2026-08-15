## New Releases - 2026-08-15

### Nuvio TV (0.8.4-beta)

**New Features and Fixes**

- Now you can fetch movie and TV show information more efficiently - Nuvio TV does things a bit faster.
- The service now supports Hebrew subtitles, which should make watching movies in different languages much easier.
- When setting up automatic timing for episodes, the 'Sync Line' feature won't progress to the next part as soon as you press a key.
- Performance enhancements and tweaks to the subtitle rendering, streaming latency, and skipping intro features have been made for a smoother viewing experience.
- Various design improvements, including more stable video playback, accurate resume positions, and better handling of movie collections.
- A temporary glitch that affected the video playback experience after a pause has been fixed.
- If a movie doesn't have any information, the system can now better handle and repair the data.
- If you leave the video playback, your last playback position will be remembered, so you can easily continue where you left off.

### Nuvio Mobile (0.4.5)

**Important Fixes**

- A small spacing issue that affected the episode progress bar has been fixed to give you a better mobile viewing experience.
- The system now respects your choices for caching movie data on your mobile device.
- The subtitle font size on iOS devices can now be adjusted to fit your preferences.
- The 'disintegrate' animation effect that caused a minor issue has been fixed.

### Nuvio Desktop (0.1.19-alpha)

**Fixes**

- The problem that caused an issue with the player focus on macOS devices has been resolved.

### Nuvio Web (0.3.35-beta)

**Enhanced Features**

- The system now supports full MKV `S_HDMV/PGS` subtitle tracks.
- If a movie is in a format that uses the `S_HDMV/PGS` subtitle track, the system can now detect and handle it properly.
- Key metadata, such as language, name, default settings, and forced subtitles, are now preserved throughout the playback process.
- When playing movies, the system can now extract and play the `S_HDMV/PGS` subtitle track.
- SUP windows are now displayed with the correct `S_HDMV/PGS` subtitle timestamps.
- When seeking or changing videos mid-playback, the system can now recover the correct playback position you previously had.
- The system now includes improved support for `S_HDMV/PGS` subtitle decoding and rendering through `PgsParser` and `libbitsub`.
- The system can now play multiple `S_HDMV/PGS` subtitle compositions with custom coordinates, alpha transparency, and scaling.
- The system is better equipped to handle various `S_HDMV/PGS` related issues during playback, including seeking, track switching, and cleanup.
- The system can now cancel obsolete extraction requests triggered due to rapid seeking, avoiding errors.
- The system is now more efficient at handling HTTP `429` errors when retrieving PGS windows.
- Luna service error handling has been improved for a smoother experience.
- Fallback options are available for files without `CueRelativePosition`, providing a seamless playback experience even without that specific metadata.
- The system still supports VobSub compatibility for continued playback in case `CueRelativePosition` is unavailable.
---
## New Releases - 2026-08-13

**Nuvio TV (0.8.4-beta)**

This update is packed with exciting improvements for your Nuvio TV experience:

- **Faster Streaming**: We've made some magic happen under the hood to get your favorite shows and movies to load way faster!
- **More Languages to Choose From**: You can now enjoy subtitles in Hebrew, adding more diversity to your TV time.
- **A Smoother Visual Ride**: Expect silky-smooth animations, fewer glitches, and a more enjoyable overall viewing experience.
- **Play, Pause, and Resume**: No more annoying playback issues - the cache is now optimized to remember where you left off.
- **Cleaning Up Errors**: We've also improved how Nuvio TV handles messy catalog entries, so you can focus on enjoying your content without any headaches.

**Nuvio Mobile (0.4.5)**

Our mobile update is all about fine-tuning your on-the-go experience:

- **Better Progress Tracking**: Episode progress spacing has been tweaked to look neater, making it easier to keep track of where you're at.
- **Cache Control**: Add-ons now behave more consistently, ensuring you don't accidentally trigger unnecessary animations.
- **Subtitles Get a Size Boost**: You can now adjust subtitle sizes to fit your mobile screen perfectly.
- **A Fresh Animation**: The disintegrate animation has been adjusted to look even more stylish.

**Nuvio Desktop (0.1.19-alpha)**

This update is a minor but important fix for our desktop users:

- **macOS Focus Bridge**: We've fixed an issue that was affecting macOS player focus, making for a more seamless experience.

**Nuvio Web (0.3.33-beta)**

In this update, we've focused on:

- **General Stability and Fixes**: We've squashed a range of pesky issues, ensuring your web experience with Nuvio is more reliable and enjoyable.
---
## New Releases - 2026-08-11

**Nuvio TV (0.8.3-beta)**

### Bug Fixes and Enhancements

- We've fixed crashes that happened when trying to watch shows, now you can keep enjoying your favorite series without interruptions. We've also made some tweaks to the layout so everything looks more organized.
- You can now customize the look of your Continue Watching list, and we've also improved how video titles and posters are displayed. Plus, we've sorted out some issues with scrolling and playback to make it smoother.
- We've added a new feature to save your provider credentials, so you won't have to enter them every time you want to watch something. And, for the environmentally conscious, we've increased the token lifetime to seven days, reducing unnecessary requests to our servers.
- Now, when you're watching a short-form video, it will automatically load the correct information, and we've also fixed an issue where subtitles from previous episodes would carry over to the next one.
- You can now search for videos without any lag, and we've also updated our library poster images.
- We've fine-tuned the new sidecar fast startup mode, and it's now better at handling different types of videos.
- We've fixed an issue where the 3:2 pulldown refresh weight was being overridden, and we've also improved our track frame rate to make sure it's accurate.
- Performance issues have been addressed, and we've also fixed a crash that happened on our 3D TV.
- You can now watch videos on WebDAV servers even after they've been redirected.
- We've standardized the time left copy, so it's now displayed correctly.
- We've added a reset button to the subtitle delay overlay, making it easier to customize your subtitles.
- You can now choose whether to play videos in their original frame rate or in a different one.
- We've introduced a new setting to "fall back" to a different group of videos if your main group fails to play.
- We've improved video playback by reducing stuttering when you mark episodes as watched.

**Localization**

- We've updated our translation strings for Latin American Spanish to make sure they're accurate and helpful.
- We've added missing translations for Hungarian to make sure our app is accessible to everyone.
- We've added translations for 23 new languages, including Arabic, Czech, German, Greek, Spanish, French, Italian, Hebrew, Japanese, Polish, Portuguese (Brazil), Portuguese, Russian, Turkish, Ukrainian, Simplified Chinese, and Traditional Chinese.
- We've removed some orphaned layout strings from the Hungarian and Latin American Spanish translations.

### Nuvio Mobile (0.4.4)

- We've fixed a memory leak that was causing the app to use too much memory when you marked videos as watched.
- We've added a new feature to customize your TMDB Discover exclusion filters.
- We've prevented Simkl from providing FullyWatchedSeriesKeys.
- We've added a new toggle to manually set binge group fallback mode.

### Nuvio Desktop (0.1.19-alpha)

- We've fixed an issue with the macOS player focus bridge.

### Nuvio Web (0.3.33-beta)

- Various issues have been fixed and stability has been improved.