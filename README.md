# Music for Android

A music player for Android 14+ that plays the songs on your phone and streams from YouTube Music, in one app.
A native Android app with no ads and no account.

This repository holds the signed release APKs and the update manifest. The app's source code lives in a separate repository.

**[Download the latest release](https://github.com/Om-Doiphode/musicplayer-releases/releases/latest)** · [All releases](https://github.com/Om-Doiphode/musicplayer-releases/releases)

## Features

### Listen
- **One library**: the songs on your phone and YouTube Music side by side, in search, playlists and the queue.
- **Home charts**: YouTube Music's top songs today and this week, charts by language, new albums, singles and music videos.
- **Search everything** from one box: songs, albums, artists, videos and playlists, with filters.
- **Artist, album and playlist pages** with Play and Shuffle; tap an artist's name to open their page.
- **What's this song?**: the mic button on Search recognises a song playing nearby and plays it.

### Now Playing
- Big artwork on a blurred background coloured by the cover, with an immersive full-screen view and a visualizer.
- Shuffle, repeat one, 5-second skip, playback speed (0.5x–2x) and a sleep timer.
- Gapless playback, with optional crossfade between songs.
- **Play On**: pick the speaker, Bluetooth or cast device.
- Gestures on the cover: swipe for lyrics or to skip, double-tap to like, long-press for actions.
- Shows each song's format and quality.
- **8D audio** that circles the music around your head on headphones, and **Music Haptics** that tap along with the beat.
- Controls in the notification, on the lock screen and on headset buttons.

### Lyrics
- Time-synced lyrics that scroll with the song; tap a line to jump to it.
- **Karaoke mode** highlights each word as it's sung, with duet sides and backing vocals.
- Translation shown under each line.
- Share a lyric as an image card, or long-press a line to copy it.
- Lyrics on the lock screen, and as captions on music videos.

### Music videos
- Switch between **Song** and **Video** when a song has an official music video.
- Full screen, picture-in-picture, quality choice, swipe controls and a screen lock.
- Save videos to watch offline.

### Queue and playlists
- Play next, add to queue, drag to reorder; swipe right to play next, left to remove (with Undo).
- **Recommended**: when the queue ends, similar songs keep playing (can be turned off).
- Liked Songs and your own playlists.
- **Download for offline**: songs are saved as tagged `.m4a` files with cover and lyrics, so other apps can play them too.

### Your library
- Songs on your phone are found automatically, or only from the folders you choose.
- Covers and lyrics are read from the files, and looked up online when missing.
- **Your listening**: stats on what you play most.

### Look and feel
- Choose between a **Glass** look and **Material 3 Expressive**, in light or dark.
- Smooth motion: covers and album cards move into their pages.

### Sync with the Mac
- Pair with the Mac version of the player to keep playlists, likes and history in sync.
- Hand playback over between the Mac and the phone with **Continue listening**.

### Updates
The app updates itself. It checks for a new version when it opens (at most twice a day) or from **Settings → Updates**,
verifies the download, installs it and then shows what's new.

## Install

1. On your phone (Android 14 or newer), open the [latest release](https://github.com/Om-Doiphode/musicplayer-releases/releases/latest) and download `musicplayer-N.apk`.
2. Open it and allow "Install unknown apps" for your browser or file manager when asked.
3. Later versions arrive through the in-app updater, with no need to come back here.

Play Protect may ask to scan the app the first time, since it isn't from the Play Store.

## Built with

- Kotlin
- Jetpack Compose and Material 3
- Android 14+ (native app, no web view)

## Safe updates

Every update is signed and checked by the app before it's installed. If anything doesn't match, nothing is installed.

## Notes

- YouTube changes its internals from time to time, so streaming can briefly break until an update fixes it.
- Song recognition relies on an outside service and may stop working if that service changes.
- This is a personal project, not affiliated with YouTube, Google or Shazam.
