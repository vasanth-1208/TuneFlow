# 🎵 TuneFlow

> **Modern Web Music Player**

TuneFlow is a lightweight, responsive web-based music player designed to provide a clean and engaging music listening experience directly in the browser.

The project demonstrates how **HTML, CSS, JavaScript, and the Web Audio/Media APIs** can be combined to create an interactive music player interface.

---

## ✨ Features

* 🎵 Music playback
* ▶️ Play / pause controls
* ⏭️ Next and previous track navigation
* 🔊 Volume control
* 📊 Interactive progress bar
* ⏱️ Current time and track duration
* 🎨 Modern dark-themed interface
* 📱 Responsive design
* 🎧 Playlist support
* 🔄 Repeat and shuffle modes
* 🔍 Track search
* 💿 Album artwork display
* 🌙 Modern music-player UI

---

## 🎯 Project Goal

Basic HTML audio players provide only the fundamental playback controls.

TuneFlow aims to create a more complete music experience with:

```text
Music Library
      ↓
   Playlist
      ↓
Track Selection
      ↓
Audio Playback
      ↓
Playback Controls
      ↓
Progress & Volume
      ↓
Listening Experience
```

---

## 🖥️ User Interface

The application provides a dedicated music-player interface containing:

* Current track information
* Artist information
* Album artwork
* Playback controls
* Progress indicator
* Volume controls
* Playlist / music library
* Playback state

The interface is designed to remain usable across desktop and mobile screen sizes.

---

## ⚙️ How It Works

The browser's native audio capabilities are used as the foundation for playback.

```text
User Selects Song
       ↓
Audio File Loaded
       ↓
HTML5 Audio Element
       ↓
Play / Pause
       ↓
Track Progress
       ↓
Volume Control
       ↓
Next / Previous Track
```

JavaScript manages the player state and user interactions while CSS handles the responsive visual design.

---

## 🛠️ Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript

### Browser APIs

* HTML5 Audio API
* DOM API
* Local Storage API

No backend server is required for the basic application.

---

## 📁 Project Structure

```text
TuneFlow/
│
├── index.html
├── style.css
├── script.js
│
├── music/
│   ├── song-1.mp3
│   ├── song-2.mp3
│   └── song-3.mp3
│
├── images/
│   ├── album-1.jpg
│   ├── album-2.jpg
│   └── album-3.jpg
│
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/vasanth-1208/music_player.git
```

### 2. Open the project

```bash
cd music_player
```

### 3. Run the application

Open:

```text
index.html
```

in a modern web browser.

For development, you can also use a local development server such as VS Code Live Server.

---

## 🎧 Example Music Data

A playlist can be represented using JavaScript objects:

```javascript
const songs = [
    {
        title: "Dream Track",
        artist: "Unknown Artist",
        source: "music/song.mp3"
    }
];
```

The player can dynamically load the selected track and update the interface.

---

## 📱 Responsive Design

TuneFlow is designed for:

* 💻 Desktop
* 💻 Laptop
* 📱 Mobile
* 📟 Tablet

The layout adapts to smaller screens while keeping the main playback controls easily accessible.

---

## 🔐 Privacy

TuneFlow can operate entirely within the browser.

No personal information or listening history needs to be sent to a server for local music playback.

---

## 🚀 Future Enhancements

Planned improvements include:

* 🎼 Dynamic playlist management
* ❤️ Favorite tracks
* 🔍 Advanced music search
* 🎚️ Audio equalizer
* 🎵 Multiple playlists
* 💾 Persistent playback state
* 🖼️ Dynamic album artwork
* 📈 Listening statistics
* 🎤 Lyrics display
* 🌐 Online music API integration
* 🔊 Web Audio API visualizer
* 🎧 Media Session API support
* 📲 Installable PWA
* 🌓 Light / dark themes

---

## 🌟 Project Differentiator

Instead of being only a basic HTML audio player, TuneFlow is designed as a **complete browser-based music experience**.

```text
Basic Player
     │
     ├── Play
     ├── Pause
     └── Audio
     
TuneFlow
     │
     ├── Music Library
     ├── Playlist
     ├── Search
     ├── Playback Controls
     ├── Progress Tracking
     ├── Shuffle
     ├── Repeat
     ├── Favorites
     ├── Responsive UI
     └── Listening Experience
```

---

## 📌 Project Status

**Status:** Active Development

The project is being developed from a simple music-player interface into a polished, responsive web music application.

---

## 👨‍💻 Author

**Vasantharaj M**

B.E. Computer Science and Engineering
Bannari Amman Institute of Technology

GitHub: **vasanth-1208**

---

## 📄 License

This project is intended for educational and personal development purposes.
