[Home](../../README.md) | [Quick Start](../../docs/quick-start.md) | [Overview](../../docs/overview.md) | [Features](../../docs/features.md) | [Installation](../../docs/installation/README.md) | [Settings](../../docs/settings/README.md) | [Troubleshooting](../../docs/troubleshooting.md) | [FAQ](../../docs/faq.md)

---
# Settings Overview

Nuvio offers deep customization tailored to your device. Below is a high-level overview of the settings, noting key differences between the **Mobile** and **Android TV** platforms.

> [!IMPORTANT]
> Anything not labeled [TV Only] or [Mobile Only] is available on both versions.

## 1. General & UI
*   **Theme & Colors:** Choose from preset color palettes and toggle pure black backgrounds (AMOLED Black) for OLED screens.
*   **Layout:** Switch between various Home shelf configurations (List, Grid, Modern View)
*   **Poster Style:** Fine-tune the width and corner radius of your media cards.

## 2. Playback
*   **Video Player:** Use the highly recommended Internal Player (ExoPlayer or libmpv), or hand off streams to External Players like VLC.
*   **Binge Watching:** Configure Auto-Play Next Episode, set threshold percentages, and utilize Intro/Outro skipping via AniSkip/IntroDB.
*   **Subtitles & Audio:** Set default languages, skip silent audio, downmix surround sound to stereo, and deeply customize subtitle appearance (including libass support).
*   **Interface Controls:** Utilize touch gestures for volume/brightness **[Mobile Only]**, or enable Pause Overlays and OSD Clocks **[TV Only]**.

## 3. Account Integrations
*   **Services:** Link Trakt for watch history and Torbox/Premiumize for high-speed 4K streaming.
*   **Metadata:** Enable TMDB and MDBList to fetch localized artwork, cast lists, and aggregated ratings.

## 4. Advanced [TV Only]
*   **Hardware Processing:** Prioritize device hardware decoders over software processing.
*   **Dolby Vision:** Manage DV7 fallback and convert DV5 to DV8.1 for unsupported screens.
*   **Audio/Video Sync:** Enable Auto Frame Rate (AFR) to eliminate judder, or use Tunneled Playback for direct hardware-level rendering.
*   **Audio Transcoding:** Force AC-3 transcoding to push 5.1 surround sound over older optical cables.

## 5. Buffer and Network [TV Only]
*   **Custom Buffers:** Override default memory limits to manually set min/max video buffer durations and target RAM allocations.
*   **Disk Cache:** Save active video streams to your physical storage to survive network drops.
*   **P2P & Connections:** Enable torrent streams and force parallel network connections for faster downloads.

## 6. Customization & Management
*   **Profiles & Collections:** Manage multiple user watch histories and group media into custom lists.
