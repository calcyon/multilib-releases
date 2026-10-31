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

Each release's page lists what changed, and anything you need to do when updating.

## Updating

MultiLib checks this page once a day and tells you when a new version is out, with a Windows notification and a line in the tab bar. It never downloads or installs anything by itself, and you can turn the check off in Settings.

- **Installer:** run the new `MultiLib-Setup-<version>.exe`.
- **Portable:** replace the old `.exe` with the new one, in the same folder as your `MultiLib-data` folder.
- **Browser extension:** MultiLib says "Extension outdated" when the extension really changed. Press Reload on your browser's extensions page, after updating the files if you unzipped it yourself.

## Games

- Add games from an F95zone thread link, by copying a link, with Ctrl+K, or from the browser extension.
- Background update checks with Windows notifications and an updates inbox.
- Your played, installed and latest version for each game, plus the changelogs since the version you played.
- Your own status, rating, notes (which can be tied to a version) and tags.
- Liked and avoided tags, to filter your library.
- Start installed games from MultiLib, with playtime tracking and save backups.
- Compact, detailed and grid views, with columns and sorting you can change, including sorting by how many of your liked tags a game has.
- Import from xLibrary.
- For you: games from F95's latest list ranked by your taste, with filters for engine, status and score.
- Search all of F95's Latest Updates list from For you, so games from years ago can be found.
- Update rhythm: an estimate of how often a game updates and when the next update might come.
- F95 score trend: arrows show how far a game's score has moved since MultiLib first read it.

## Anime

- Two-way sync with MyAnimeList or AniList, or a list kept only on your PC. Separate profiles can each use their own.
- MAL XML import.
- Continue watching, airing this week and sequel alerts.
- Anime folder scanning, with Play buttons for your episodes.
- Automatic episode tracking in MPC-HC and, through the extension, on the streaming sites you switch on (Miruro, AnimeSuge, Animepahe).
- Character lists, notes, dates and rewatch details.

## Statistics and tabs

- A Stats page with separate figures for each tab.
- Settings can hide Games or Anime if you don't use them. Their data and background checks carry on.

## Look and feel

- A dark design where covers supply the colour, with one accent colour per tab.
- Generated artwork for anything without a cover.
- A game or anime's cover moves from the list onto its page. Settings can turn all animations off.
- The search palette (Ctrl+K) shows covers beside games and anime.

## Shortcuts

- Every shortcut can be changed in Settings, using a key combination or a mouse button, and put back to its default.
- The mouse back button returns to the list from a game or anime page, where you left it.
- The mouse forward button opens the last game or anime page again.

## Browser extension

- Adds your library's status to F95zone thread and Latest Updates pages, with a quick add button.
- Tracks episodes on the streaming sites you switch on.
- Talks only to MultiLib on your own PC (`127.0.0.1`).

To install it, open your browser's extensions page, turn on developer mode and choose "Load unpacked". Pick the folder from Settings → Browser extension → "Open extension folder", or unzip the extension file and pick that folder. Then pair it with the code from MultiLib's settings. The portable version keeps this folder in `MultiLib-data\extension`.

## First steps

- **F95zone:** log in from MultiLib's settings for covers, full-size screenshots and download links. Update checks work without logging in.
- **MyAnimeList / AniList:** sign-in uses your own free client ID, which you enter under Settings → Anime.

## Your data

- Everything stays in one database file on your PC, with automatic backups. You can also keep a weekly backup in a folder you choose.
- Settings → Data can export and import the whole database.
