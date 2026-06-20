# Orbit — Personal OS

Orbit is a beautifully designed, monolithic productivity super app built into a single HTML file. It runs entirely in your browser using local storage (IndexedDB) and requires zero servers, accounts, or internet connection.

## 🚀 Features

- **Dashboard:** At-a-glance view of your active tasks, quick notes, and upcoming deadlines.
- **Projects & Tasks:** Full project management suite with progress tracking, task statuses, and due dates.
- **Notes & Documents:** Clean, minimal Markdown-supported note-taking workspace.
- **Resources & Bookmarks:** Organize important links and materials with categories.
- **Media & File Tools:**
  - **Photo Editor:** Native Canvas-based offline image editor with 20+ adjustments (Color Grading, Halftones, Split Toning, Bloom, etc.).
  - **File Converter:** Convert images locally on the fly (PNG, JPEG, WebP, TIFF).
  - **Image Compressor:** Shrink image sizes locally with real-time file size comparison.
- **Utility Tools:** Hash generators, password creators, color pickers, QR code generators, date calculators, word counters, and much more.

## 🛠️ Architecture

Orbit is built entirely inside one single file (`index.html`) using Vanilla HTML, CSS, and JavaScript. 
All data is persistently saved in your browser using a robust local IndexedDB implementation. 
You can export your database anytime from the Settings panel as a local JSON backup.

## 🌐 Hosting on Vercel

Orbit is heavily optimized to be hosted anywhere. 
To deploy on Vercel, simply import the repository. The included `vercel.json` and `index.html` structure ensures Vercel handles it perfectly out-of-the-box as a static HTML application.
