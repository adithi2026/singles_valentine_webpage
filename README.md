# ❤️‍🩹✨ Singles Valentine Week Web App

A fun, animated multi-page web app designed to celebrate Singles Valentine Week. This project features floating heart animations, a meme carousel, an embedded Spotify playlist, and auto-playing custom audio, all built with pure HTML, CSS, and JavaScript.

---

## 🌟 Features

* **Multi-page interface** with instant navigation (Home, Memes, Playlist)
* **Floating animated hearts** in the background
* **Interactive popup cards** for themed singles days
* **Auto-scrolling meme carousel**
* **static playlist**
* **Custom audio autoplay** with browser-friendly behavior
* **Smooth fade animations** between pages
* **Responsive design** for desktop and mobile

---

## 🛠️ Technologies Used

* HTML5
* CSS3 (animations and transitions)
* Vanilla JavaScript
* Spotify Embed Player

---

## 📂 Project Structure

```
project-folder/
│
├── index.html
├── your-audio-file.mp3
└── README.md
```

> Place your custom audio file in the same folder as the HTML file or update the path in the `<audio>` tag.

---

## ▶️ How to Run the Project

### Option 1: Simple Run

1. Download or copy the project files
2. Double click `index.html`
3. Open in your browser

### Option 2: Local Server (Recommended)

Using VS Code Live Server or Python:

```
python -m http.server
```

Then open:

```
http://localhost:8000
```

---

## 🎵 Custom Audio Setup

Update the audio source in the HTML:

```html
<audio id="previewTrack"
  src="your-audio-file.mp3"
  preload="auto"
  autoplay
  muted>
</audio>
```

Browsers may require one user click before unmuting autoplay audio.

---

## 🎧 Custom Spotify Playlist

To embed your own playlist:

1. Create a playlist in Spotify
2. Click **Share → Embed playlist**
3. Copy the embed link
4. Replace the iframe `src` URL in the HTML

---

## 🎨 Customization Ideas

You can extend the project by adding:

* Swipe gestures for mobile navigation
* More memes in the carousel
* Additional playlist pages
* Audio visualizer effects
* Theme color changes
* Confetti or particle animations

---

## 📜 License

This project is open for personal and educational use. Modify and expand freely.

---

## ❤️ Credits

Created as a fun interactive project celebrating independence, humor, and self-love.

Enjoy building and customizing!
