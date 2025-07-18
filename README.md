# TubeMediaPlayer

A **privacy-first, single-page** YouTube client that lives entirely in your browser.  
Search, watch, build playlists and browse channels **without ever sending your API key to a server**.

---

## ✨ Features

- 🔐 **Encrypted local storage** – your YouTube Data-API key is kept safe inside IndexedDB (AES-GCM).  
- 🎬 **Inline mini-previews** – hover thumbnails for muted 3-second clips.  
- 📂 **Playlist manager** – load any public playlist, reorder or jump to any track.  
- 📺 **Channel explorer** – browse uploads, Shorts, lives, playlists in tabbed sections.  
- 🎛️ **Dark YouTube-style UI** – responsive, keyboard shortcuts, no external deps.  
- 🚫 **Zero telemetry** – 100 % front-end, TOS-compliant.

---

## 🚀 Getting Started

1. **Fork or clone** this repo.  
2. **Serve the folder** (IndexedDB needs `http://`, not `file:///`):  
   ```bash
   python -m http.server 8000
   # or use VS Code Live-Server

3. Open http://localhost:8000/index.html.
4. Paste your YouTube Data-API key once – it will be remembered encrypted.

## 📦 Tech Stack
Vanilla HTML5 / CSS3 / ES6
YouTube IFrame API
Web Crypto + IndexedDB for local storage

## ⚖️ License
MIT © 2025 – Juan Berta
You are free to use, modify and redistribute under the MIT terms.

## 🤝 Contributing
Pull requests welcome.
If you add a cool feature, open an issue first so we keep the project tiny.

## 📝 Changelog
```Table
Version	Notes
1.0.0	Initial release – search, playlists, encrypted key storage
```
```
###  Repository skeleton
TubeMediaPlayer/
├── index.html
├── README.md
├── LICENSE          (copy-paste MIT text below)
└── .gitignore       (optional – ignore logs, .DS_Store, etc.)
```
