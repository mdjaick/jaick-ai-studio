# JAICK AI Studio

AI-powered browser-based reel editor for creating short-form social videos.

## Overview
JAICK AI Studio is a lightweight web app for editing short videos directly in the browser. It lets users add clips, trim segments, reorder media, add titles and subtitles, adjust audio, apply visual filters, and export a final reel for social platforms.

## Features
- Add multiple video clips from local files
- Reorder clips in the timeline
- Trim clip in/out points
- Add title overlays and captions
- Choose social presets for Reel, Shorts, TikTok, square, and landscape videos
- Adjust video/audio levels and background music
- Apply visual filters (warm, cool, mono, etc.)
- Export the final edited video locally in the browser
- Works as a local-first project editor without a backend

## Platforms
- Web app (browser-based)
- Works on desktop and laptop browsers
- Mobile-friendly UI for local editing workflows

## Project Type
This repository contains a frontend-only editing prototype built with HTML, CSS, and JavaScript.

## Run Locally
### Option 1: Open directly
1. Download or clone the repository
2. Open `index.html` in a modern browser

### Option 2: Use a local web server
```bash
python -m http.server 8000
```
Then open:
```text
http://localhost:8000
```

## Project Structure
- `index.html` — main app UI and logic
- `README.md` — project documentation

## Development Notes
The app is designed as a local-first editor and uses browser APIs for media handling, timeline editing, and export. It is a good foundation for extending with AI features such as automatic captioning, smart cuts, or richer media generation.

## License
This project is currently under development. Add an appropriate license before public release.
