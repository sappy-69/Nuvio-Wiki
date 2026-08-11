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
---
## New Releases - 2026-08-05

**Nuvio TV (0.8.1-beta)**

Get ready for a smoother TV experience with Nuvio's latest updates!

- **Smoother Browsing**: We've optimized our cache to work in the background, so you can focus on what you want to watch without any hiccups.
- **Intro Trouble Gone**: We fixed the issue with the skip intro button lingering - now you can skip intros easily.
- **Synopsis Scrolling Fixed**: Enjoy long synopsis navigation and scrolling without any issues.

**Localization Updates**

Our TV app now supports Hebrew, making it accessible to a broader audience. Thanks to our community for helping us translate!

**Nuvio Mobile (0.4.1)**

Our mobile app just got a whole lot better!

- **Accurate Watched Markers**: We matched Trakt watched markers across IDs, so your watch history stays accurate.
- **New App Icons**: Customize your app icons with our new selectable options.
- **Improved Plugin Cache**: We split plugin source cache from metadata, making it more efficient.
- **Play Services Improved**: Fixing playback service starts on the main thread ensures a smoother experience.
- **Watched Refresh Reduced**: We reduced redundant Trakt watched refresh to save time.
- **Watched State Serializing**: Serialize watched state snapshots, so you can pick up where you left off.
- **Rate Limiting**: Contain Trakt watched rate limits to prevent any issues.
- **Large Responses Fixed**: We fixed large Trakt watched responses to prevent crashes.
- **Shadow Removed**: We removed the expanded action button shadow for a cleaner look.
- **ID Routing Improved**: We improved Kitsu/MAL ID routing for skip intro and correct AniSkip types query.
- **Localization Updated**: Improve Greek (el) localization coverage and accuracy.
- **Skip-Outro Seek Improved**: Clamp skip-outro seek below the duration boundary and against actual duration for a smoother experience.

**Nuvio Desktop (0.1.16-alpha)**

Our desktop app is now more integrated with SIMKL!

- **Stack Tracking**: We added stack tracking provider cards, making it easier to access your favorite content.
- **Settings Sync Fixed**: Fixing desktop navigation settings sync ensures that your settings stay in sync.

**Nuvio Web (0.3.30-beta)**

We've fixed various issues to make your web experience better!
---
## New Releases - 2026-08-04

**Nuvio TV (0.8.1-beta)**

We've been tweaking Nuvio TV to make it faster and smoother. Here's what's new:

- Now, when Nuvio takes a snapshot of your TV time, it does it in the background so you don't notice any lag.
- The "skip intro" button should now behave as expected, and it won't get stuck on your screen.
- You can now scroll and navigate through episode lists and long summaries without any issues.

We also added new translations for Hebrew, so our app is now more accessible to a wider range of users.

**Nuvio Mobile**

We've been busy fixing bugs and adding some cool new features to Nuvio Mobile. Check out what's new:

- Now, your watched markers on Trakt will match up perfectly, so you can track your favorite shows without any issues.
- You can customize your app icons and make your home screen look however you want.
- We've improved the way we handle plugin sources and metadata, so everything loads a bit faster.
- We fixed a few issues with playback services and dispatching commands, so you should be able to watch your shows without any problems.
- Trakt watched refreshes are now more efficient, so you won't waste time refreshing your watched shows.
- We improved the way we handle Trakt data, so you can see your watched shows accurately.
- Large Trakt responses are now handled properly, so you won't get stuck on a loading screen.
- We removed a pesky shadow that used to appear on the expanded action button, so it's now nice and clean.
- We fixed up some issues with Kitsu and MAL IDs, so you can skip intros and correct AniSkip types without any issues.
- We added some new translations for Greek, so our app is now more accessible to a wider range of users.
- We fixed some issues with skip-outro seek, so you can skip the ending credits without any problems.

**Nuvio Desktop (0.1.16-alpha)**

We're excited to introduce a brand-new feature for Nuvio Desktop: SIMKL Native Integration!

- You can now track your favorite shows in SIMKL directly within our app.
- We fixed up some issues with desktop navigation settings, so you can customize your settings to your heart's content.

**Nuvio Web (0.3.30-beta)**

We've been working hard to squash bugs and fix issues on Nuvio Web. Here's a quick rundown of what we've done:

- Various issues have been fixed, so our app should be more stable and reliable for you to use.