# JellyWatch for Android TV

JellyWatch is a fast, native Jellyfin client for Android TV and Google TV. Sign in to your Jellyfin server and stream your movies and TV shows on the big screen with Direct Play, 4K, HDR and full subtitle support, all built around the remote control.

**[Get it on Google Play](https://play.google.com/store/apps/details?id=com.jellywatch.tv)**

JellyWatch is an independent third party client for Jellyfin. A Jellyfin server is required. JellyWatch is not affiliated with the Jellyfin project.

## Overview

JellyWatch turns your Jellyfin server into a home cinema experience on the television. It is built natively for the big screen with a modern Material Design 3 interface, smooth D-pad navigation, high resolution artwork and instant playback. The goal is simple: a fast, elegant Jellyfin TV player without sluggish menus.

## Features

### Playback

- Real Direct Play so your files are streamed as is, with no quality loss
- Hardware accelerated playback powered by ExoPlayer (Media3)
- Smart transcoding fallback when a codec is not supported by the device
- 4K, HDR and HLS support
- Multiple audio tracks and surround sound, with optional stereo downmix
- Full subtitle support: SRT, styled ASS and SSA, with optional server burn-in
- Chapters, resume playback and automatic next episode

### Home screen

- Resume watching right where you left off
- Next Up to keep track of your TV shows
- Recently added content organized by library
- Direct access to every Jellyfin library

### Movies and TV shows

- Detailed pages with overview, cast, crew and studio
- Browse by seasons and episodes
- Technical info: resolution, video and audio codecs, container
- More like this and similar content suggestions
- Mark as watched or unwatched and restart from the beginning

### Search

- Find movies, TV shows and episodes in seconds
- Filter by content type

### Requests with Seerr

- Jellyseerr and Overseerr integration
- Request new movies and TV shows straight from your TV
- Track requests: pending, approved and available
- Request full sagas and collections in one action
- Browse trending and popular titles and upcoming releases

### Admin Dashboard

- Real time server monitoring on your TV
- View active playback sessions with backdrop artwork, progress and transcode status
- Library statistics: movie, series, episode and song counts
- Connected devices summary grouped by user
- Trigger a full library scan from the remote
- Running task progress with live updates every 3 seconds
- Server info: version, OS, local address, update and restart alerts
- Admin only: visible in the sidebar when logged in as a Jellyfin administrator

### Multi Account

- Switch between multiple Jellyfin accounts on the same device
- Account picker with avatar, server info and quick switch
- Auto focus on the active account
- Remove accounts with confirmation dialog

### Sign in

- Username and password login with show and hide toggle
- Credentials encrypted and stored securely on the device

### Built for your setup

- Automatic detection of device capabilities and codecs
- Force stereo output for older receivers and televisions
- Image cache management
- Optional animated background
- GPU optimized animations for smooth performance on low end TV hardware

## Requirements

- A running Jellyfin server
- Android TV or Google TV device
- Android 8.0 (API 26) or newer

## Tech stack

- Kotlin and Jetpack Compose for TV
- Material Design 3
- ExoPlayer / Media3 for playback
- Hilt for dependency injection
- Retrofit and Gson for networking
- Coil for image loading
- Compose compiler stability configuration for minimal recompositions
- Baseline Profile for fast cold start
- GPU accelerated animations via graphicsLayer

## Keywords

Jellyfin Android TV client, Jellyfin TV player, Jellyfin Google TV, stream movies and TV shows, Direct Play, 4K HDR streaming, Jellyseerr requests, media server client, home cinema, admin dashboard, server monitoring.
