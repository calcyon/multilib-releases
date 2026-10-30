# MultiLib

A Windows desktop library for your F95zone games and your anime, which runs quietly in the tray. Your library is stored on your own PC.

This repository holds the releases and documentation. The source code isn't public.

## Download

Open [the latest release](../../releases/latest) and pick what you need:

| File | What it is |
|---|---|
| `MultiLib-Setup-<version>.exe` | The installer. Your library is kept in `%APPDATA%\MultiLib`, and uninstalling leaves it there. |
| `MultiLib-Portable-<version>.exe` | Runs without installing. Your library is kept in a `MultiLib-data` folder next to the file. |
| `MultiLib-extension-<version>.zip` | The optional browser extension for Chromium browsers (Brave, Opera, Vivaldi and others). |

Each release's page lists what changed.

## Games

- Add games from an F95zone thread link, by copying a link, with Ctrl+K, or from the browser extension.
- Background update checks with Windows notifications and an updates inbox.
- Your played, installed and latest version for each game, plus the changelogs since the version you played.
- Your own status, rating, notes (which can be tied to a version) and tags.
- Liked and avoided tags, to filter your library.
- Start installed games from MultiLib, with playtime tracking and save backups.
- Compact, detailed and grid views, with columns and sorting you can change.
- Import from xLibrary.

## Anime

- Two-way sync with MyAnimeList or AniList, or a list kept only on your PC. Separate profiles can each use their own.
- MAL XML import.
- Continue watching, airing this week and sequel alerts.
- Anime folder scanning, with Play buttons for your episodes.
- Automatic episode tracking in MPC-HC and, through the extension, on the streaming sites you switch on (Miruro, AnimeSuge, Animepahe).
- Character lists, notes, dates and rewatch details.

## Browser extension

- Adds your library's status to F95zone thread and Latest Updates pages, with a quick add button.
- Tracks episodes on the streaming sites you switch on.
- Talks only to MultiLib on your own PC (`127.0.0.1`).

To install it, unzip it, open your browser's extensions page, turn on developer mode and choose "Load unpacked". Then pair it with the code from MultiLib's settings.

## First steps

- **F95zone:** log in from MultiLib's settings for covers, full-size screenshots and download links. Update checks work without logging in.
- **MyAnimeList / AniList:** sign-in uses your own free client ID, which you enter under Settings → Anime.

## Your data

- Everything stays in one database file on your PC, with automatic backups. You can also keep a weekly backup in a folder you choose.
- Settings → Data can export and import the whole database.
