# 🎵 Polo Music Player

A modern, fully-functional web-based music player that streams YouTube music videos with a sleek Spotify-inspired interface.

![Polo Music Player](https://img.shields.io/badge/Polo-Music%20Player-green?style=for-the-badge&logo=spotify)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

---

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Demo](#demo)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Keyboard Shortcuts](#keyboard-shortcuts)
- [Browser Compatibility](#browser-compatibility)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)
- [Credits](#credits)

---

## 🎯 Overview

**Polo** is a single-page web application that provides an immersive music listening experience by streaming YouTube music videos. With a curated collection of 250 popular songs spanning multiple genres and decades, it offers continuous playback, intuitive controls, and a beautiful dark-themed interface inspired by Spotify.

### Why Polo?

- ✅ **No Backend Required** - Runs entirely in the browser
- ✅ **No API Keys** - Uses YouTube's free IFrame Player API
- ✅ **Zero Dependencies** - Single HTML file, no npm packages
- ✅ **Fully Responsive** - Works perfectly on mobile, tablet, and desktop
- ✅ **250 Curated Songs** - Verified, popular music from YouTube
- ✅ **Auto-Error Recovery** - Skips unavailable videos automatically

---

## ✨ Features

### 🎮 Playback Controls
- **Play/Pause** - Central control button with visual feedback
- **Next/Previous** - Navigate through playlist seamlessly
- **Continuous Playback** - Auto-advances to next song
- **Queue Click-to-Play** - Jump to any song instantly

### 📊 Progress & Time
- **Interactive Progress Bar** - Click to seek any position
- **Real-time Updates** - Smooth progress animation (100ms intervals)
- **Time Display** - Current time and total duration

### 🔊 Volume Control
- **Volume Slider** - Adjustable volume (0-100%)
- **Visual Feedback** - Volume fill indicator
- **Desktop Only** - Hidden on mobile devices for clean UI

### 🎬 Video Player
- **YouTube Integration** - Streams actual music videos
- **Responsive Design** - Maintains 16:9 aspect ratio
- **Native Controls** - YouTube's built-in video controls
- **Error Handling** - Auto-skips unavailable videos

### 📱 Queue Management
- **250 Songs** - Curated collection of popular hits
- **Scrollable List** - Smooth scrolling sidebar
- **Album Artwork** - Cover images from Unsplash
- **Active Highlighting** - Visual indicator for current song
- **Artist & Title Info** - Full track information

### 📱 Responsive Design
- **Mobile First** - Optimized for smartphones (320px+)
- **Tablet Support** - Perfect layout for medium screens
- **Desktop Enhanced** - Additional features on large screens
- **Adaptive Layout** - Vertical on mobile, horizontal on desktop

### ⌨️ Keyboard Shortcuts
| Key | Action |
|-----|--------|
| `Space` | Play/Pause |
| `→` (Right Arrow) | Next Song |
| `←` (Left Arrow) | Previous Song |

### 🎨 User Interface
- **Dark Theme** - Easy on the eyes with gradient background
- **Smooth Animations** - Fade effects and transitions
- **Hover Effects** - Interactive feedback on controls
- **Spotify-Inspired** - Modern, minimalist design

---

## 🎬 Demo

### How to Access
1. Download the `index.html` file
2. Open with **Live Server** in VS Code, or
3. Double-click to open in your browser, or
4. Host on any web server (GitHub Pages, Netlify, Vercel)

---

## 🛠️ Technology Stack

### Core Technologies
- **HTML5** - Semantic markup and structure
- **CSS3** - Custom styles and animations
- **JavaScript (ES6+)** - Player logic and interactivity

### Frameworks & Libraries
- **Tailwind CSS** - Utility-first CSS framework (via CDN)
- **Font Awesome 6.4.0** - Icon library (via CDN)

### External APIs
- **YouTube IFrame Player API** - Video playback (Free, no API key)
- **Unsplash** - Album artwork images (via CDN)

---

## 📥 Installation

### Method 1: Direct Download
```bash
# Download the index.html file
# Open in browser or use Live Server
```

### Method 2: Clone Repository
```bash
# Clone the repository
git clone https://github.com/yourusername/nova-cloud-player.git

# Navigate to directory
cd nova-cloud-player

# Open index.html with Live Server or browser
```

### Method 3: Use Live Server (Recommended)
1. Install **Live Server** extension in VS Code
2. Right-click `index.html`
3. Select **"Open with Live Server"**
4. Browser opens automatically at `http://127.0.0.1:5500/`

---

## 🚀 Usage

### Getting Started
1. **Open the application** in your browser
2. **Click Play** button to start music
3. **Browse the queue** on the right sidebar
4. **Click any song** to play it instantly

### Basic Controls
- **Play/Pause**: Click the central white button
- **Next Song**: Click the forward skip button
- **Previous Song**: Click the backward skip button
- **Seek**: Click anywhere on the progress bar
- **Volume**: Drag the volume slider (desktop only)

### Features
- **Continuous Playback**: Music auto-advances through all 500 songs
- **Auto-Skip Errors**: Unavailable videos are skipped automatically
- **Queue Navigation**: Click any song in the sidebar to jump to it
- **Keyboard Control**: Use spacebar and arrow keys

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Function |
|----------|----------|
| `Spacebar` | Toggle Play/Pause |
| `→` | Skip to Next Song |
| `←` | Go to Previous Song / Restart Current |

---

## 🌐 Browser Compatibility

| Browser | Support |
|---------|---------|
| Chrome | ✅ Full Support (Recommended) |
| Edge | ✅ Full Support |
| Firefox | ✅ Full Support |
| Safari | ✅ Full Support |
| Opera | ✅ Full Support |
| Mobile Safari | ✅ Full Support |
| Chrome Mobile | ✅ Full Support |

**Minimum Requirements:**
- Modern browser with JavaScript enabled
- Internet connection for YouTube streaming

---

## 📂 File Structure

```
polo-player/
│
├── index.html          # Main application file (self-contained)
└── README.md           # Documentation
```

### Single File Application
The entire application is contained in **one HTML file** including:
- HTML structure
- Inline CSS styles
- JavaScript logic
- External CDN references

**No build process required!**

---

## 🎵 Music Collection

The player includes **250 curated songs** featuring:

### Genres
- Pop
- Rock
- Hip-Hop/Rap
- Electronic/EDM
- R&B
- Classic Rock
- Alternative
- Country

### Featured Artists
- The Weeknd, Ed Sheeran, Dua Lipa, Harry Styles
- Taylor Swift, Ariana Grande, Justin Bieber
- Drake, Post Malone, Billie Eilish
- Imagine Dragons, OneRepublic, Maroon 5
- Queen, The Beatles, Michael Jackson
- Coldplay, Bruno Mars, Beyoncé
- And many more!

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### Adding Songs
1. Find embeddable YouTube music videos
2. Add to the `songs` array in `index.html`
3. Include: title, artist, album, youtubeId, cover image

### Reporting Issues
- Use GitHub Issues to report bugs
- Include browser and OS information
- Provide steps to reproduce

### Feature Requests
- Open an issue with detailed description
- Explain the use case
- Suggest implementation if possible

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

```
MIT License

Copyright (c) 2025 Polo Music Player

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 🙏 Credits

### Technologies
- [YouTube IFrame Player API](https://developers.google.com/youtube/iframe_api_reference) - Video playback
- [Tailwind CSS](https://tailwindcss.com/) - CSS framework
- [Font Awesome](https://fontawesome.com/) - Icon library
- [Unsplash](https://unsplash.com/) - Album artwork images

### Inspiration
- Design inspired by [Spotify](https://spotify.com)
- User interface patterns from modern music players

### Music
- All music videos are property of their respective artists and labels
- Videos streamed via YouTube's official API
- No music files are hosted or distributed by this application

---

## 📞 Contact & Support

- **Issues**: [GitHub Issues](https://github.com/ravindurb/polo/issues)
- **Discussions**: [GitHub Discussions](https://github.com/ravindurb/polo/discussions)

---

## 🌟 Show Your Support

If you like this project, please give it a ⭐ on GitHub!

---

## 📝 Changelog

### Version 1.0.0 (Current)
- ✅ Initial release
- ✅ 500 curated songs
- ✅ Full playback controls
- ✅ Responsive design
- ✅ Auto-error recovery
- ✅ Keyboard shortcuts
- ✅ YouTube video integration

---

**Made with ❤️ and ☕**

**Enjoy the music!** 🎵
