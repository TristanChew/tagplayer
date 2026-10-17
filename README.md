<div align="center">

<!-- Replace with your app icon / logo -->
<img src="https://placehold.co/160x160/0D1530/5B8CFF?text=TP" alt="Tag Player logo" width="120" />

# 🎵 Tag Player

**A fast music player for Android that lets you tag every song and build playlists with real logic:  
"rock OR jazz, but NOT live, NOT punk."**

[![Platform](https://img.shields.io/badge/platform-Android%208.0%2B-3DDC84?logo=android&logoColor=white)](#)
[![Kotlin](https://img.shields.io/badge/Kotlin-Jetpack%20Compose-7F52FF?logo=kotlin&logoColor=white)](#)
[![Buy Me a Coffee](https://img.shields.io/badge/Support-Buy%20Me%20a%20Coffee-FFDD00?logo=buymeacoffee&logoColor=black)](https://buymeacoffee.com/elytromax)

</div>

---

## ✨ Why Tag Player?

Most music apps sort by artist and album. Real music libraries are messier than that. Tag Player lets you describe your music **your way**, then find or mix exactly what you want, instantly.

- 🏷️ Give every song **as many custom tags as you like**
- 🧠 Search with **AND / OR / NOT** logic, like a tiny database for your music
- ⏱️ Say *"give me 45 minutes of music"* and get a mix that lands almost exactly on the minute
- 🔊 Every song plays at a **consistent volume**, automatically
- 🎚️ Built-in **5-band equaliser**, **speed control** and **section looping**
- 📻 A **radio dial** (FM / AM) with thousands of live stations
- 🎨 **21 colour themes** plus unlockable special interface styles
- 🔒 No ads, no accounts, no tracking. Your music stays on your phone

---

## 📸 Screenshots

<div align="center">

<!-- Swap these placeholders for real screenshots, e.g. docs/screenshots/library.png -->
| Library | Now Playing | Logic Builder |
|:---:|:---:|:---:|
| <img src="https://placehold.co/270x580/0D1530/5B8CFF?text=Library" width="200"/> | <img src="https://placehold.co/270x580/0D1530/4FD1FF?text=Now+Playing" width="200"/> | <img src="https://placehold.co/270x580/0D1530/9B7BFF?text=Logic+Builder" width="200"/> |

| Playlists | Timed Mix | Radio |
|:---:|:---:|:---:|
| <img src="https://placehold.co/270x580/0D1530/5B8CFF?text=Playlists" width="200"/> | <img src="https://placehold.co/270x580/0D1530/FFC857?text=Timed+Mix" width="200"/> | <img src="https://placehold.co/270x580/0D1530/FF6B8A?text=Radio" width="200"/> |

| Equaliser | Achievements | Themes |
|:---:|:---:|:---:|
| <img src="https://placehold.co/270x580/0D1530/9B7BFF?text=Equaliser" width="200"/> | <img src="https://placehold.co/270x580/0D1530/4FD1FF?text=Achievements" width="200"/> | <img src="https://placehold.co/270x580/0D1530/FFC857?text=Themes" width="200"/> |

</div>

---

## 🚀 Features

### 📂 Your library, your way
- **Auto-scan folders:** pick a music folder once and it is re-scanned every time the app opens
- **Manual add:** pick individual songs whenever you like
- Reads title, artist, album, year and embedded album art from your files
- **No storage permission needed.** It uses Android's secure file picker, and your files are only ever *read*, never modified
- Works with MP3, M4A, AAC, FLAC, WAV, OGG, OPUS and WMA

### ▶️ A full-featured player
- Play / pause, next, previous and a smooth seek bar
- **Background playback** with notification and lock-screen controls
- **Shuffle**, **loop playlist** and **loop one song**
- 🐢🐇 **Speed control** from 0.5× to 2× with a slider and presets
- 🎚️ **5-band equaliser** (60 Hz to 14 kHz, ±12 dB) with presets. It runs *before* volume normalisation and adds automatic headroom, so boosting the bass never clips or distorts
- 🔁 **Loop a section:** set point **A** and point **B** and repeat any part of a song
- Large **song card** shown while playing
- **Automatic volume normalisation** that boosts quiet songs and softens loud ones before they play (can be switched off in Settings)

### 🏷️ Tags: the heart of the app
- Add **multiple custom tags** to any song (`rock`, `workout`, `sad`, `90s`…)
- **Multi-select** songs (long-press) and tag, favourite or playlist them in one go
- Tag suggestions as you type, and tag/untag many songs at once

### 🔎 Search with logic
The search bar has two modes:

| Mode | What it does |
|---|---|
| **Search** | Instantly finds songs by title, artist, playlist name or tag |
| **Logic builder** | Slick **AND / OR / NOT / ( )** buttons and tag shortcuts build powerful queries. Save the result as a playlist or play it right away |

**Example queries**

```text
(#rock OR #jazz) AND NOT #punk AND NOT #chinese
#workout AND is:fav
artist:"queen" AND NOT title:"bohemian"
playlist:"road trip" OR #chill
```

| Syntax | Meaning |
|---|---|
| `#rock` / `#"hard rock"` | song has this tag |
| `love` / `"my song"` | title, artist, playlist or tag contains text |
| `artist:` `title:` `playlist:` | search one specific field |
| `is:fav` | starred songs only |
| `AND` `OR` `NOT` `( )` | combine anything (`NOT` > `AND` > `OR`) |

Excluding one specific song is one tap: choose **Exclude from filter** in the song's menu while using the logic builder.

### ↕️ Sorting
Sort by **name, artist, playlist, date added, length or most played**, ascending or descending. ⭐ Favourites always stay on top.

### 📜 Playlists
- Create, **rename** and delete playlists
- ⭐ **Favourite** playlists to keep them at the top
- 🖐️ **Drag to reorder** songs freely inside a playlist, or jump a song to the top, bottom or any position. Your order is yours and is never changed by filters or favourites
- Save any search result or timed mix as a playlist in one tap

### ⏱️ Timed Mix
Pick a length from 5 minutes to 4 hours and Tag Player randomly builds a playlist that lands **as close to that time as possible**. Combine it with the same AND / OR / NOT logic, for example *"60 minutes of `#chill` but NOT `#live`"*. Re-roll as often as you like.

### ⭐ Favourite priority (adjustable chance)
Star the songs you love. In **Settings**, a **0–100% slider** sets the chance that each next song is picked from your favourites. It applies to shuffle and to timed mixes, even for the very first song. Set it to 0% to turn the feature off.

### 🎨 Custom cards
- **Draw your own card** with the built-in mini paint tool (pen, eraser, colours, background, brush size, undo)
- Or **import any image** from your gallery
- Attach cards to **songs and playlists**; they appear on the player and in lists

### 🎮 FUN :) tab
Four tabs in one place:
- 🏆 **Top 10:** your most-listened songs, ranked by real play counts
- 🎧 **Guess:** hear the first **1–5 seconds** of a random song, then press **Reveal**. It goes on endlessly until you quit
- 📻 **Radio:** an **FM / AM dial** powered by the [Radio Browser](https://www.radio-browser.info/) directory. Drag the slider to tune, with a quiet static effect while you turn the dial, or jump between stations with PREV / NEXT. Stations keep playing in the background
- 🏅 **Achievements:** twelve **secret** achievements, a homage to some favourite games. Each one shows only a cryptic riddle until you unlock it. Good luck 🤫

### 🌈 Themes and interface styles
- **21 free colour themes:** the original blue, **10 night** themes and **10 light** themes
- **12 special interface styles**, one for each secret achievement. They change the whole feel (corner shapes, fonts, borders, animated backgrounds and more), not just the colours
- Everything is switchable in **Settings → Appearance**. Locked styles appear once you have earned them

### ⚙️ Settings
- Volume normalisation on / off
- Favourite priority chance slider
- Appearance: colour themes and unlocked styles
- Manage scanned folders, rescan, or re-analyse volume
- ☕ Support link

### 🧱 Built to look the same everywhere
- Locked font size and typeface (Android's small text size and Roboto), so it looks the same on every phone
- Portrait mode only
- Smooth transitions and animations throughout

---

## 📲 Install

1. Download the latest **APK** from the [Releases](../../releases) page *(placeholder: add your link)*
2. Open it on your phone and allow *"Install unknown apps"* if asked
3. Open Tag Player, tap the 📂 folder icon, and choose your music folder

**Requires:** Android 8.0 (API 26) or newer.

---

## 🛠️ Build from source

```bash
git clone https://github.com/<your-username>/<your-repo>.git
```

1. Open the project in **Android Studio** (latest stable)
2. Let Gradle sync
3. **Build → Build APK(s)**, then find it at `app/build/outputs/apk/debug/app-debug.apk`

**Optional media (not included in the repo):** the secret features load their own sounds and pictures from `res/raw/` and `res/drawable/` if you add them. Without them they simply stay silent and use simple drawn placeholders.

**Optional, to lock the font:** download [Roboto](https://fonts.google.com/specimen/Roboto) and place `roboto_regular.ttf`, `roboto_medium.ttf` and `roboto_bold.ttf` in `app/src/main/res/font/` (lowercase names).

### Tech stack
- **Kotlin** + **Jetpack Compose** (Material 3)
- **Media3 / ExoPlayer** for playback, streaming and the background service
- **Room** database for tags, playlists, favourites, cards and play counts
- Custom audio processor for the equaliser and loudness normalisation
- Custom recursive-descent parser for the AND / OR / NOT query language
- [Radio Browser](https://www.radio-browser.info/) API for the radio directory

---

## 🔐 Privacy and permissions

Tag Player has no ads, no analytics and no account. Your music, tags, playlists and cards are stored privately on your device (uninstalling the app removes them). The **only** network use is the optional **Radio** tab, which fetches the public station list from radio-browser.info and streams the station you pick. Everything else works fully offline.

Permissions used: internet (Radio only), foreground service and notifications (background playback and its controls), wake lock (keeps playback running with the screen off), and vibration (haptic effects).

---

## ☕ Support the project

If Tag Player makes your listening nicer, you can support its development:

<a href="https://buymeacoffee.com/elytromax">
  <img src="https://img.shields.io/badge/Buy%20me%20a%20coffee-%E2%98%95-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=black" alt="Buy Me a Coffee" />
</a>

---

## 🗺️ Roadmap ideas
- [ ] Backup & restore tags and playlists
- [ ] Auto-scroll while dragging in long playlists
- [ ] Sleep timer
- [ ] Home-screen widget
- [ ] More interface styles

Suggestions and pull requests are welcome. Open an [issue](../../issues) to start a conversation.

---

## 📄 License

Add your licence here (for example MIT), and replace this line.
