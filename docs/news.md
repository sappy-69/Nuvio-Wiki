## New Releases - 2026-07-16

### Nuvio TV (0.7.16-beta)

Catch up with your favorite shows and movies without any fuss! This update brings you:

- A more reliable experience with Trakt, where episodes marked as watched will now show up on your Home page as expected.
- A fix for missing series markers on the Home page.
- Better loading times for watched movies.
- The ability to sync your Trakt credentials across devices.
- Automatic refreshes to keep your movies and shows in sync.
- New loading indicators that behave as they should.
- A fix for tiny movie posters that wouldn't load properly.
- Better video quality control, ensuring Dolby Vision works as it should.
- A visual refresh for stream loading badges.
- And, behind the scenes, improved diagnostics to help us understand any issues you might encounter.

### Localization

Time to go international! Your Nuvio TV update also includes:

- Fresh French translations that make you feel like you're in Paris.
- A boost of new Hebrew translations to help users who speak the language.
- Improved Latin American Spanish localization to make your experience more personalized.
- Greek strings are now complete, with placeholders in case something's missing.
- And, last but not least, Italian translations to help our Italian friends enjoy their movies.

### Nuvio Mobile (0.2.25)

Mobile users, rejoice! This update brings a few crucial fixes:

- Your predictive back feature is now working as it should on Android devices.
- Plus, a refactoring of the contribution summary to make things more tidy.

### Nuvio Desktop (0.1.13-alpha)

Don't worry, desktop users! We've got you covered with this tiny but vital update.

- Your Windows desktop browser's web view should be calculating its layout size correctly now.

### Nuvio Web (0.3.16-beta)

Our web update brings a few behind-the-scenes fixes to keep you going:

- Various tweaks to make your experience with Nuvio Web better and smoother.
---
## New Releases - 2026-07-15

### Nuvio TV (0.7.16-beta)

- **Trakt Time**: We've improved our relationship with Trakt, making sure you don't miss out on episodes and seasons you've watched. Our TV app now accurately keeps track of watched shows, so you can easily pick up where you left off. 
- **Longer Trakt Lists**: You can now browse all your watched movies on Trakt without having to scroll endlessly. Our pagination feature allows you to see your entire collection at a glance.
- **Synced Trakt Credentials**: Your Trakt login credentials are now shared across all Nuvio devices, so you'll never have to log in again.
- **Auto-Renew**: Nuvio will now periodically refresh your watchlist and recommendations, making sure you stay up to date with the latest shows and movies.
- **Loading Improvements**: We've tweaked the way our loading indicators work, so they're now more responsive and reliable.
- **Poster Perfection**: Our TV app now accurately downloads poster images, even for movies with no known poster.
- **Audio Upgrade**: We've restricted Dolby Vision playback to only Dolby Vision tracks, ensuring you get the best possible audio experience.
- **Visual Refinements**: Our stream chip loading badge now has a more consistent design, making it easier to use.
- **Diagnostics**: Our new Sentry tombstone reporting feature will help us better diagnose and fix technical issues.

### Localization

- **Language Love**: We've added French translations to Nuvio, making it more accessible to our French-speaking users.
- **Hebrew Support**: We've added and updated Hebrew translations, making sure Hebrew speakers can enjoy Nuvio with ease.
- **Latin American Spanish**: Our Latin American Spanish localization strings are now up to date, ensuring a smoother experience for Spanish speakers.
- **Greek Translations**: We've added and updated Greek translations, making Nuvio more enjoyable for Greek speakers.
- **Italian Translations**: We've added Italian translations, extending our reach to Italian-speaking users.

### Nuvio Mobile (0.2.24)

- **Greek Translations Complete**: Our Greek translations are now complete and up to date, making Nuvio Mobile more accessible to Greek speakers.
- **Italian Translations Update**: Our Italian translations have been updated to provide an even better experience for Italian speakers.
- **Vietnamese Translations Update**: Our Vietnamese translations have been updated, making Nuvio Mobile more enjoyable for Vietnamese speakers.
- **Parental Guidance**: Our Parental Guidance API integration has been updated, ensuring a safer and more enjoyable experience for users.
- **Media Controls**: Nuvio Mobile now supports Android Now Playing media controls, making it easier to control playback directly from your phone.
- **Continue Watching**: We've fixed issues with Continue Watching functionality, ensuring you can easily pick up where you left off.
- **Matching Trakt Behavior**: Our Continue Watching behavior now matches Nuvio TV, providing a consistent experience across devices.
- **Picture-in-Picture**: We've fixed Picture-in-Picture behavior on Android, ensuring a seamless playback experience.
- **Library Syncing**: Our library syncing feature will now work correctly, even during active pulls.
- **Scroll Position**: The Continue Watching scroll position should now be stable while items load.

### Nuvio Desktop (0.1.13-alpha)

* We've fixed a bug that prevented the Windows WebView from calculating its layout size after a recent migration.

### Nuvio Web (0.3.15-beta)

- **LG Audio**: Our new audio detection feature for LG webOS devices now supports automatic DTS and TrueHD compatibility detection, ensuring a richer audio experience.
- **LG Audio Settings**: We've added advanced audio settings for LG webOS devices, allowing you to manually select DTS or TrueHD tracks.
- **MKV Playback**: Our MKV playback feature on LG webOS devices now waits for embedded audio-track discovery before applying the preferred language, preventing silent playback or incorrect track selection.
- **Audio Language**: If your preferred audio language is unavailable, the player will now automatically fall back to the first supported audio track, ensuring seamless playback.
- **Audio Detection**: Our audio detection feature now accurately identifies and labels audio tracks, even when unsupported codecs are filtered on LG webOS devices.
- **Subtitle Selection**: Forced subtitles are now used when the selected audio matches the preferred language, while regular subtitles are used for foreign-language audio, matching Android TV behavior.
- **Samsung Subtitle**: We've improved Samsung Tizen subtitle handling, using AVPlay's native renderer for embedded and external subtitles when available, preventing conflicts between native and HTML rendering.
- **Subtitle Delay**: You can now enable subtitle delay support for external subtitles rendered natively by Samsung AVPlay.
- **Subtitle Settings**: We've updated Samsung Tizen subtitle settings, disabling styling controls that cannot affect native subtitles and clearly marking them as unavailable.
- **Subtitle Addons**: Our subtitle addons now correctly prioritize the exact episode ID passed to the player, ensuring accurate subtitle display.
- **Thumbnail Blur**: We've added an option to blur thumbnails for unwatched episodes, making it easier to distinguish between watched and unwatched content.
- **Episode Thumbnail**: We've fixed issues with episode thumbnail blur and watched-state updates not refreshing correctly after marking an episode as watched.
- **Home Collection**: Our Home collection previews now preserve animated Hero media while moving between collection folders and prevent unnecessary preview restarts.
- **Poster Transitions**: We've fixed overlapping poster expansion and collapse transitions on LG webOS and Samsung Tizen devices that could leave stale or duplicated poster layers visible.
- **Home Content**: We've fixed preserved Home content appearing over newly opened screens on Samsung Tizen devices by moving the retained Home layer completely offscreen while another route is active.
- **Collection Updates**: We've improved collection and folder Hero updates by preventing delayed metadata requests from replacing the currently focused item with stale content.
- **Trailer Playback**: Our automatic trailer playback feature will now start behind the Continue Watching stream-selection flow.
- **Profile Settings**: Secondary profiles can now access profile preferences, while primary profiles retain profile management restrictions.
- **TMDB Metadata**: We've fixed issues with TMDB metadata, artwork, collections, and recommendations failing with incorrectly formatted regional language codes.
- **Playback Persistence**: The selected stream ID and its source context are now retained for future playback and Continue Watching sessions.
---
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