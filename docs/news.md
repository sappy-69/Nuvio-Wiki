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
---
## New Releases - 2026-07-24

### Nuvio TV (0.7.19-beta)

- **Improved Streaming** - Now Nuvio TV can work better with some internet services and DNS providers ( IPv4-first and SNI/TLS 1.3 support). You might have noticed your stream would skip or break up sometimes; this update will hopefully fix those problems.
- **Episode Fix and More** - You can now see exact release dates for episodes and the app will remember where you left off in some of your favorite shows.
- **New Upcoming Features** - Nuvio now shows a special row where you can find upcoming episodes in your favorite shows and the watch history is more reliable.
- **Device Friendliness** - Nuvio TV has officially been approved to work on Zidoo Z9X 8K device, so go ahead and try it out.
- **Profile Protection** - Your watch history will now stay protected across different user profiles.
- **Subtitle Fix for Non-English Users** - Subtitle rendering should work better for languages like Hebrew, and some layout issues should be fixed as well.
- **More Settings Recovery** - You'll now have some protection with your settings in case you accidentally corrupt your app file.
- **Collection Sorting** - You can now sort items in the Collection Editor and Grid View.
- **Fast Scrolling** - Fast scrolling should work smoother in Classic mode.
- **More Stability and Bug Fixes** - Some bugs like rejected Trakt refresh tokens should now be fixed for better performance.

### Localization

- **More Polish Translations** - More Polish translations are now added to the app.
- **International Subtitles** - Subtitles and UI localization handling for Hebrew and related languages have been updated.
---
## New Releases - 2026-07-23

### Nuvio TV (0.7.19-beta)
### Improvements & Fixes

TV just got a lot better. Here's what changed:
- We fixed issues that might have stopped you from watching your favorite shows on some devices, especially those running untrusted SSL streams. Now, your streaming experience is more reliable.
- The way your TV handles certain playback modes on some devices should now work as expected, so you can enjoy seamless viewing.
- You can now watch content on new devices, including the Zidoo Z9X 8K. More choices, more fun!
- If you have a favorite show that just got released, you can now see its air date and the exact time it's on.
- We added a new "Continue Watching" row to help you pick up where you left off.
- For security, we improved profile isolation, so your viewing data stays private.
- If you switch profiles, your watching status should stay up-to-date now.
- Don't worry if your settings get corrupted; we can now recover them.
- Our item IDs are now super-stable, so you can enjoy a seamless experience.
- Scrolling in the Classic mode should be smoother now.
- When you try to log in, your tokens should be valid, and you won't encounter any errors.
- For languages like Hebrew, subtitle rendering should now be perfect, including punctuation and mirrored parentheses.
- The playback settings and trailer progress bar should be working as expected now.
- Finally, we improved playback to be more responsive, so you can enjoy a better viewing experience.

### Localization

TV just got more global! Here's what changed:
- We added some missing Polish translations so your favorite shows and movies are now available in your language.
- For languages like Hebrew and others that read from right to left (RTL), we improved subtitle and UI localization so you can enjoy a better viewing experience.

### Nuvio Mobile (0.3.1)
Nuvio Mobile is getting better and better. Here's what changed:
- Now, when you navigate to a new page, the old one is cleaned up nicely, so it doesn't affect your new session.
- Nuvio Engine is now integrated into the app, making it more powerful and efficient.
- If you encounter a recycled bitmap issue, don't worry; it's now fixed.
- We improved settings so that headings are easier to read.
- We added a separate "Continue Watching" row, just like on TV.
- Poster depth is now applied seamlessly, making it more beautiful.
- On library pages, you can now sort your shelves and grid layouts for easier navigation.
- We also fixed a few more bugs and added support for split ABI.

### Nuvio Desktop (0.1.14-alpha)
Nuvio Desktop is getting more stable and efficient. Here's what changed:
- We updated the Parental Guidance API, making sure your content is suitable for all ages.
- Subtitle rails now scroll horizontally as expected.
- Sometimes, the app would freeze when exiting the player – now it's fixed.
- Player launching no longer freezes the UI thread, so you can enjoy smooth navigation.
- When entering desktop fullscreen, the white border and flash are now gone.
- Player shutdown is now safely bounded, so windows don't get stranded.
- Finally, we fixed a macOS-specific issue where the player runtime used to lag.

### Nuvio Web (0.3.23-beta)
TV just got some behind-the-scenes improvements! Our developers fixed some errors and bugs that were affecting your viewing experience.