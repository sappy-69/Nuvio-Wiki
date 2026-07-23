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
---
## New Releases - 2026-07-22

**Nuvio TV (0.7.19-beta)**

Improvements & Fixes
-----------------------

Get ready for a smoother TV-watching experience! We've restored important features like SNI and TLS support, which will make our app work better on your network. This update also fixes a few pesky bugs that were making AFR (Auto-Refresh Feature) act wonky and Display Mode restoration stop working.

To make your favorite shows even better, we've improved how we handle Dolby Vision Profile 5. Now, when you enable "Always Strip DV," it will work perfectly in the background. And, if you own a Zidoo Z9X 8K device, you might be happy to know that we've added recognition for this awesome device!

We've also made some tweaks to episode release dates and airtimes, so they should now be showing up correctly. You'll find a new "Continue Watching" row when you navigate to upcoming episodes, and it will give you reliable recommendations to keep you entertained.

**Nuvio Mobile (0.3.1)**

Nuvio Mobile 0.3.1 is here with some exciting updates!

This new version focuses on making navigation smoother, fixing some pesky bugs, and adding some awesome new features. For example, you can now browse through "Upcoming Continue Watching" episodes, and we've also introduced separate shelf and grid layouts to make your library experience more fun.

Additionally, we've improved the app's design, fixing issues like poster depth and recycled bitmap crashes. And the cherry on top? We've integrated Nuvio Engine to give you an even better experience!

**Nuvio Desktop (0.1.14-alpha)**

Time to level up your desktop experience!

We've made some key improvements to ensure a smooth player experience. Now, when you exit the app, it will no longer freeze, and subtitles will scroll smoothly without any issues. Plus, we've fixed some tricky bugs related to desktop fullscreen entry and native player shutdown.

To give you a faster and more seamless experience, we've also ensured that our app no longer hangs on player launch, and we've bundled the player runtime with the app to make everything run more smoothly.

**Nuvio Web (0.3.22-beta)**

**Coming Soon...!**

This version of Nuvio Web is a big behind-the-scenes update, but we can't wait to share some amazing improvements that are coming your way! Stay tuned for more information and a future update.
---
## New Releases - 2026-07-21

### Nuvio TV (0.7.19-beta)

**Your TV Just Got a Whole Lot Better!**

Here are the latest updates:
- Fixed a few pesky issues with how your Nuvio TV connects to the internet and works with some devices.
- Improved how we play Dolby Vision content, so it looks super sharp and bright.
- You can now watch stuff on your Zidoo Z9X 8K device, yay!
- We fixed some problems with episode release dates and air times, so you don't get confused.
- You can expect a smooth Continue Watching experience with our new and improved reliability features.
- Your profile will be safer and more secure, thanks to added protection against sneaky data leaks.
- We fixed an annoying glitch where playback wouldn't pick up where you left off.
- And, we added some neat new features like Upcoming Continue Watching rows and stable IDs for your favorite collections.

### Localization

**More Languages, More Love!**

We added some missing Polish translations and improved support for Right-To-Left languages, so you can enjoy Nuvio in even more languages.

### Nuvio Mobile (0.3.1)

**Nuvio Goes Mobile!**

Here's what's new:
- Improved navigation by cleaning up the routes after you pop back to the home screen.
- We integrated our Nuvio engine, making it faster and smoother.
- Fixed a crash that happened when you recycled a bitmap in the Now Playing metadata.
- We fixed some wonky setting headings, so it's easier to navigate.
- Introducing a new shelf and grid layout for your library, plus an upcoming Continue Watching row.
- You can now apply poster depth to remaining surfaces, and... split ABI support!

### Nuvio Desktop (0.1.13-alpha)

**Your Desktop Just Got Better!**

We fixed a problem with the Windows webview layout calculation, so it should work seamlessly now.

### Nuvio Web (0.3.20-beta)

**Your Web Experience Just Got a Lot Sweeter!**

Here are the updates:
- We improved navigation on Samsung Tizen and other TV runtimes by avoiding that frustrating lag.
- You'll now see a pre-start compatibility screen when your TV isn't supported, showing you the minimum requirements.
- We improved adaptive-streaming reliability by packing assets locally and keeping lazy loading.
- You can now pick your favorite audio tracks per title or profile.
- The Next Episode overlay looks better now, showing the localized air date while preserving autoplay and playback guards.
- We fixed some stuck hero information on Samsung Tizen, so now backdrop and logo preloading works.
- Addon subtitles look more polished now on Samsung Tizen.
- We made some icons more readable on white themes, and improved Continue Watching artwork metadata resolution. Last but not least, the Trakt window selector got an Android TV-style revamp!