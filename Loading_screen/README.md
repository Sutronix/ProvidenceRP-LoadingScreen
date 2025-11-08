# 🎬 Animated Loading Screen for Garry's Mod

## 📦 Informations générales

- **Nom** : Animated Loading Screen  
- **Auteur** : Benjdiii  
- **Fichiers principaux** : `index.html`, `css/stylesheet.css`, `content/audio.mp3`  
- **Dépendance** : Aucune  
- **Installation** : Place all files on a web server and set the `sv_loadingurl`  
- **Version** : 1.0

---

## 📝 Description

This animated loading screen provides an immersive entry experience for your Garry’s Mod server. It includes:

- A custom loader animation  
- Background images that rotate every 10 seconds  
- Background music with icon and song name displayed  
- A clean, centered footer displaying the currently playing track  
- Responsive layout for all screen sizes

Perfect for RP, sandbox, PvP or any custom server that wants to make a strong first impression.

---

## 📂 Installation

Create a new folder:
```
loading_screen/
├── index.html
├── css/
│   └── stylesheet.css
├── content/
│   ├── audio.mp3
│   ├── icon/
│   │   └── iconsong.png
│   └── img/
│       ├── 1.jpg
│       ├── 2.jpg
│       └── 3.jpg
```

Then in your `server.cfg` (on your Garry’s Mod server), add:

```cfg
sv_loadingurl "http://your-website.com/loading_screen/"
```

---

## 💬 Features

- 🎵 Audio player with visual song icon and title
- 🌌 Smooth background transition between images every 10 seconds
- 🧪 Lightweight: uses pure HTML, CSS, and JavaScript
- 📱 Mobile-friendly & responsive

---

## 🎨 Customization

To change the loading screen:

- Replace the files in `content/img/` for custom backgrounds  
- Update `content/audio.mp3` for your own track  
- Change `iconsong.png` and text inside `index.html` to reflect your music  
- Customize the CSS in `stylesheet.css` for further design tweaks

---

## 🔧 Requirements

- Any basic HTTP server (Apache, NGINX, or static host like GitHub Pages or Neocities)
- A Garry’s Mod server with `sv_loadingurl` set to your hosted page
