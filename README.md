<div align="center">

<img src="https://jellywatch.app/static/images/JellyWatch_mascot.svg" alt="JellyWatch" width="96">

# JellyWatch for Android TV

**The most complete Jellyfin and Emby client for Android TV and Google TV.**

Native Jetpack Compose app. Built for the big screen and the remote in your hand.

[![Get it on Google Play](https://img.shields.io/badge/Google%20Play-Download-brightgreen?logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.jellywatch.tv)
[![Available on Amazon Appstore](https://img.shields.io/badge/Amazon%20Appstore-Download-orange?logo=amazon&logoColor=white)](https://www.amazon.fr/dp/B0H6F1KLQ4)
[![JellyWatch.app](https://img.shields.io/badge/Website-jellywatch.app-7C3AED)](https://jellywatch.app/android-tv)
[![Discord](https://img.shields.io/badge/Discord-Community-5865F2?logo=discord&logoColor=white)](https://discord.gg/jellywatch)

<br>

> Requires a [Jellyfin](https://jellyfin.org) or [Emby](https://emby.media) server. Not affiliated with the Jellyfin or Emby projects.

</div>

---

## Overview

JellyWatch for Android TV turns your Jellyfin or Emby server into a real home cinema on Android TV, Google TV and Fire TV. A fast, polished interface designed entirely for D-pad navigation, with the features that no other Jellyfin or Emby TV client ships together in one app.

Works on NVIDIA Shield, Chromecast with Google TV, Sony Bravia, Xiaomi Mi Box, Amazon Fire TV, and any device running Android TV 8.0 or above.

---

## Features

### Server Compatibility

| Feature | Details |
|---|---|
| **Jellyfin support** | Full support for Jellyfin 10.8+. All features available including trickplay, theme songs, Skip Intro, SyncPlay, remote subtitle search, and admin dashboard. |
| **Emby support** | Full support for Emby servers. Libraries, Continue Watching, Live TV, recording timers, playback (Direct Play and transcoding), multi-account and linked profiles all work. Jellyfin-exclusive features (trickplay, Skip Intro, SyncPlay, remote subtitles, theme songs) are gracefully hidden when connected to Emby. |
| **Automatic detection** | Enter your server URL and the app detects the server type automatically. No manual selection required in most cases. A manual override is available on the login screen. |

### Playback

| Feature | Details |
|---|---|
| **Direct Play and 4K HDR** | ExoPlayer with hardware decoding. H.264, HEVC, AV1 (libdav1d software fallback), VP9. HDR10, HDR10+, Dolby Vision. |
| **TrueHD Atmos and DTS:X passthrough** | FFmpeg audio extension for local TrueHD and DTS-HD MA decode. Force passthrough mode for stubborn HDMI/eARC setups. |
| **3-level fallback** | Passthrough first, then local FFmpeg decode, then server transcode only as last resort. |
| **Trickplay thumbnails** | Scrub the timeline and see a live preview of the scene above the seek bar. Requires Jellyfin 10.9+. |
| **Display rate switching** | Automatically matches your TV refresh rate to the video frame rate (24p, 25p, 30p, 60p). Eliminates judder on compatible TVs. |
| **Live quality selection** | Switch between Original, 4K, 1080p, 720p, 480p and 360p during playback. Server adapts the stream instantly. |
| **Subtitle rendering** | ASS/SSA rendered pixel-perfect via libass. PGS and DVBSub decoded locally. SRT/ASS/VTT external subtitles loaded as sidecars. |
| **Online subtitle search** | Search and download subtitles from OpenSubtitles (and other providers) directly from the player. Requires the subtitle provider plugin on your Jellyfin server. No account needed in the app. |
| **Playback speed** | 0.5x to 2x from the player overlay. |
| **Zoom / aspect ratio** | Fit, Fill and Crop with one button press. |
| **Skip intro and credits** | Off, Auto-skip or Button, configurable per segment type (intro, credits, recap, preview, commercials). Smart coexistence with Up Next overlay. |
| **Up Next auto-play** | 15-second countdown at episode end. |
| **Stats for Nerds** | Live overlay: codec, resolution, bitrate, HDR type, audio delivery mode, frame rate, dropped frames, buffer health, network bandwidth. |
| **Audio Night Mode** | Dynamic range compression reduces loud peaks and boosts quiet dialog for late-night sessions. |
| **Picture in Picture** | Video continues in a floating window when you leave the app or press Home. Returns to full screen on tap. 16:9 aspect ratio. |

### Smart Home

| Feature | Details |
|---|---|
| **Home Assistant cinema mode** | Connect your Home Assistant (HAOS) instance via a Long-Lived Access Token. Assign a script or service to play, pause and stop events. When you press Play, your lights dim. When you pause or stop, they come back on. Fully local -- no cloud, no polling. Configure in Settings → Home Assistant. |

### Watching Together

| Feature | Details |
|---|---|
| **SyncPlay** | Create or join a group. Play, pause and seek together in real time. Playback pauses automatically when someone is buffering and resumes when everyone is ready. Clock sync and drift correction run in the background. |

### Browsing and Discovery

| Feature | Details |
|---|---|
| **Theme songs** | Ambient background music plays automatically on movie and series detail pages. Configurable volume (Off, Low, Medium, High). |
| **Local trailer autoplay** | Place a `Movie-trailer.mkv` or `Movie-trailer.mp4` next to your film on the server. JellyWatch plays it muted on loop as the detail page backdrop. No YouTube, no API key required. |
| **Book and ebook reader** | Browse your Jellyfin book library and read EPUB files directly on your TV. Full-screen reader with dark, light and sepia themes, adjustable font size, and D-pad page turning. |
| **Music player** | Browse albums, artists, genres and playlists. Play tracks with background playback that continues across all screens. Persistent mini-player, full Now Playing screen with album art, queue management, shuffle and repeat. Playback reports to Jellyfin so your listening history stays in sync. |
| **Music Equalizer** | 10-band equalizer with presets (Bass Boost, Flat, Vocal and more). Adjust in real time from the Now Playing screen. |
| **Multichannel FLAC Surround** | FLAC 5.1 and 7.1 play in full surround on ARC/eARC soundbars and receivers. The app detects multichannel tracks and automatically delivers Dolby Digital Plus (EAC3) over HDMI ARC without touching the server settings. Stereo tracks play lossless as-is. Stats for Nerds overlay shows codec, channel count, sample rate and delivery mode in real time. |
| **Home Screen Channels** | Continue Watching and Recently Added appear directly on your Android TV launcher. Resume in one click. |
| **Seerr integration** | Discover trending titles and request movies or TV shows directly from your remote. Track request status in real time. |
| **Fast search** | Find any movie, series or episode in seconds. Voice search on compatible remotes. |
| **Customizable home screen** | Choose which rows appear and their order: Continue Watching, Next Up, Recently Added. Show, hide and reorder sidebar libraries. Each user configures their own layout. |
| **Feature Board** | Vote on upcoming features and boost the ones you want most. Community-driven development roadmap. |

### Family

| Feature | Details |
|---|---|
| **Kids Profile** | Dedicated Kids mode with parental PIN lock. Custom home screen with poster cards and hero banner. Simplified navigation. Color themes (Blue, Orange, Green) with Fredoka font. Content filtering is handled by your Jellyfin server user policy. |
| **Linked Profiles (Multi-Server)** | Link accounts from different Jellyfin servers together. Their libraries are merged into a single home screen -- one unified Continue Watching, one Next Up, one Recently Added across all servers. Each linked profile stays independent for playback and watch history. Kids profiles cannot be linked. |

### Account and Server Management

| Feature | Details |
|---|---|
| **TV Quick Login** | Enter a short code shown on your phone. No TV keyboard required. |
| **Multi-account** | Switch between Jellyfin accounts instantly. Each user keeps their own watch history and preferences. |
| **Linked Profiles (Multi-Server)** | Connect accounts from multiple Jellyfin servers and link them together. Once linked, the home screen shows a single unified feed: Continue Watching, Next Up and Recently Added are aggregated from every server at once. Manage links from the "Who's watching?" screen. Kids profiles cannot be linked. |
| **Admin dashboard** | Monitor active sessions, library stats, running tasks, connected devices. Trigger library scans from the couch. |

### Comfort Features

| Feature | Details |
|---|---|
| **Still Watching** | After several consecutive episodes without remote interaction, a dialog asks if you are still there. Pauses playback if you do not respond. Configurable threshold (2-5 episodes). |
| **Built-in screensaver** | Artwork slideshow with Ken Burns zoom, horizontal parallax and smooth crossfade. Shifts all elements automatically for OLED burn-in protection. |

### Android Auto (Google Play version only)

| Feature | Details |
|---|---|
| **Music in the car** | When your phone is connected to a car running Android Auto, JellyWatch TV appears in the media apps list. Browse and play your Jellyfin or Emby music library from the car screen. |
| **Full library browsing** | Albums, artists, genres, playlists and audiobooks accessible from the car dashboard. Alphabetical navigation (A-Z) for large libraries. |
| **Voice search** | "Hey Google, play [artist] on JellyWatch TV". Falls back to suggested tracks when no match is found. |
| **Shuffle All and Radio** | Shuffle your entire music library or start an Instant Mix (radio) seeded from any album, artist or track. |
| **Favorites at root level** | Your favourite tracks are one tap away from the Android Auto home screen. No need to drill into a library first. |
| **Recently Played and Recently Added** | Quick access sections on the root screen for discovering new music and resuming what you were listening to. |
| **Playback reporting** | Playback position syncs back to your Jellyfin or Emby server. Your listening history stays consistent across all devices. |
| **HD artwork** | Album art displayed at 600px resolution on the car screen and in the Now Playing view. |
| **Rich metadata** | Album title, track number and duration displayed on the Now Playing screen. Progress bar shows time remaining. |
| **Emby compatible** | Works with both Jellyfin and Emby servers. No configuration needed. |

---

## Why JellyWatch

Compared to the other Jellyfin and Emby Android TV clients (Jellyfin for Android TV, Findroid, Streamyfin, Moonfin, Wholphin), JellyWatch is the only one that ships all of the following in a single app:

- **Both Jellyfin and Emby** from one app, with automatic server type detection

- SyncPlay (watch together in real time)
- TrueHD Atmos and DTS:X force passthrough with FFmpeg local decode fallback
- Local PGS subtitle rendering and libass ASS/SSA
- Online subtitle search and download (OpenSubtitles via Jellyfin server plugin)
- Trickplay thumbnails
- Display rate switching
- Live quality switching during playback
- Stats for Nerds including audio delivery mode
- Audio Night Mode (dynamic range compression)
- Still Watching protection
- TV Quick Login (code-based, no keyboard)
- Screensaver with Ken Burns, parallax and OLED burn-in protection
- Skip intro/credits with 3 configurable modes per segment type
- Local trailer autoplay from server-side files
- Built-in EPUB reader for Jellyfin book libraries (dark, light and sepia themes, D-pad navigation)
- Full music player with background playback (albums, artists, genres, playlists, mini-player, Now Playing, queue, shuffle, repeat)
- Multichannel FLAC Surround: FLAC 5.1/7.1 in full Dolby Digital Plus over HDMI ARC/eARC -- automatic, zero config, with real-time Stats for Nerds overlay
- Customizable home screen rows and sidebar order
- Feature Board (community-driven development roadmap)
- Kids Profile with dedicated home screen, Fredoka font, parental PIN gate and simplified navigation
- Linked Profiles: merge accounts from multiple Jellyfin servers into a single unified home screen
- Picture in Picture (PIP): video in a floating window when you leave the app
- Music Equalizer: 10-band with real-time adjustment and presets
- Home Assistant cinema mode: trigger smart home automations (lights, scripts, scenes) on play, pause and stop
- Android Auto support (Google Play version): browse and play music, audiobooks and playlists from the car screen with voice search, shuffle, radio, favorites at root level, HD artwork, rich metadata and playback reporting to the server. Works with Jellyfin and Emby.

---

## Requirements

- Android TV 8.0 or above
- Jellyfin Server 10.8+ **or** Emby Server (recent version)
- Trickplay thumbnails and theme songs require Jellyfin 10.9+ (Jellyfin only)
- Skip Intro / Credits requires Jellyfin 10.9+ (Jellyfin only)

---

## Installation

**Google Play** (Android TV, Google TV)

Search for *JellyWatch for Android TV* on Google Play or use the direct link:
`https://play.google.com/store/apps/details?id=com.jellywatch.tv`

**Amazon Appstore** (Fire TV)

Available on Amazon Appstore:
`https://www.amazon.fr/dp/B0H6F1KLQ4`

**Setup**

1. Install the app on your TV.
2. Enter your Jellyfin or Emby server URL (the type is detected automatically).
3. Sign in with your credentials or use TV Quick Login with a code from your phone.
4. Start watching.

---

## Companion App

**JellyWatch for Android** is the monitoring and management app for your Jellyfin server. Use it on your phone to track active sessions, manage users, view analytics and control your server. Available on Google Play.

Both apps share the same Watch Pass subscription.

---

## Links

- Website: [jellywatch.app/android-tv](https://jellywatch.app/android-tv)
- Discord: [discord.gg/jellywatch](https://discord.gg/jellywatch)
- Google Play: [JellyWatch for Android TV](https://play.google.com/store/apps/details?id=com.jellywatch.tv)
- Amazon Appstore: [JellyWatch on Amazon](https://www.amazon.fr/dp/B0H6F1KLQ4)

---

<div align="center">

JellyWatch is an independent third-party client. Not affiliated with the Jellyfin or Emby projects.

</div>
