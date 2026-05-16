# Yoink NewTab

<p align="center">
  <img src="bongo-cat.gif" alt="Bongo Cat" width="64" />
</p>

<p align="center">
  A sleek, glassmorphism-inspired new tab page with a drumming Bongo Cat companion.
  <br />
  Fully customizable · Catppuccin themed · Zero dependencies
</p>

<p align="center">
  <a href="#features">Features</a> ·
  <a href="#screenshots">Screenshots</a> ·
  <a href="#installation">Installation</a> ·
  <a href="#customization">Customization</a> ·
  <a href="#tech-stack">Tech Stack</a> ·
  <a href="#license">License</a>
</p>

---

## Features

### Design
- **Glassmorphism UI** — Frosted glass tiles with backdrop blur, subtle borders, and layered transparency
- **Catppuccin Dark Theme** — Carefully curated color palette for reduced eye strain
- **Responsive Layout** — Scales to fit any screen size without scrolling or zooming
- **Smooth Animations** — Fade-in-up entrance animations, hover effects, and particle destruction on delete

### Widgets
- **Live Clock** — Flip-style digit display with configurable 12/24h format and seconds toggle
- **Weather** — Real-time weather display with location and conditions
- **Pomodoro Timer** — Built-in focus timer with customizable work/break intervals
- **Stopwatch** — Lap tracking with start, stop, and reset controls
- **Task List** — Quick task management with add, complete, and delete

### Quick Access
- **Shortcut Manager** — Pin your favorite sites with custom icons and colors
- **Pagination** — Supports multiple pages of shortcuts with dot navigation
- **Edit Mode** — Reorder, edit, or remove shortcuts with a visual grid

### Customization
- **Accent Color** — Full-spectrum color picker with swatch presets
- **Background Styles** — Solid, gradient, wave, or custom image/video wallpapers
- **Visual Controls** — Adjust blur intensity, brightness, vignette, tile roundness, and border opacity
- **Settings Pane** — Slide-out panel with live-preview sliders for all options

### Technical
- **Persistent Storage** — All settings saved to `localStorage` for instant reload
- **WebGL Shaders** — Optional animated shader backgrounds with configurable blob/wave modes
- **Video Wallpapers** — IndexedDB-backed video persistence across sessions
- **Image Optimization** — Auto-downscale to 1920px (JPEG 0.92) before storage

---

## Screenshots

<p align="center">
  <em>Add a screenshot of your setup here</em>
</p>

---

## Installation

### Quick Start

1. **Download** the [`yoink-newtab.html`](yoink-newtab.html) file
2. **Open** it in any modern browser (Chrome, Firefox, Edge, Brave)

### Set as New Tab Page

Since browsers don't natively support local files as new tabs, use one of these methods:

| Browser | Extension |
|---------|-----------|
| Chrome / Edge / Brave | [Custom New Tab URL](https://chromewebstore.google.com/detail/custom-new-tab/lfjnnkckddkopjfgmbcpdiolnmfobflj) |
| Firefox | [Custom New Tab URL](https://addons.mozilla.org/en-US/firefox/addon/custom-new-tab-url/) |

Alternatively, set the file as your **homepage** or **startup page** in browser settings.

---

## Customization

Access the settings pane by clicking the **settings** icon in the top-right corner.

| Setting | Description |
|---------|-------------|
| **Accent Color** | Primary theme color for highlights and interactive elements |
| **Blur Intensity** | Backdrop blur strength on glass tiles |
| **Brightness** | Overall background brightness |
| **Vignette** | Radial darkening around edges |
| **Tile Roundness** | Border radius of all UI cards |
| **Border Opacity** | Visibility of tile borders |
| **Background Style** | Solid color, gradient, wave shader, or custom image/video |
| **24-Hour Clock** | Toggle between 12h and 24h time format |
| **Show Seconds** | Toggle seconds display on the clock |
| **Weather Unit** | Celsius or Fahrenheit |

---

## Tech Stack

- **HTML5** — Semantic structure
- **CSS3** — Glassmorphism effects, animations, responsive design
- **Vanilla JavaScript** — Zero framework dependencies
- **WebGL** — Shader-based animated backgrounds
- **IndexedDB** — Persistent video wallpaper storage via [localForage](https://github.com/localForage/localForage)
- **Material Symbols Rounded** — Icon set from Google Fonts

---

## Project Structure

```
Yoink-NewTab/
├── yoink-newtab.html   # Single-file application (all HTML, CSS, JS)
├── bongo-cat.gif       # Animated header companion
├── README.md           # Project documentation
├── LICENSE             # Apache 2.0
└── .gitignore
```

---

## License

Licensed under the [Apache License 2.0](LICENSE).

Feel free to fork, modify, and make it yours.
