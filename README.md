# JAICK AI Studio

AI-powered browser-based reel editor for short-form video creation.

<p align="center">
  <img src="https://img.shields.io/badge/Type-Web%20App-blue" alt="Type: Web App" />
  <img src="https://img.shields.io/badge/Stack-HTML%2FCSS%2FJS-orange" alt="Stack: HTML/CSS/JS" />
  <img src="https://img.shields.io/badge/Status-Prototype-yellow" alt="Status: Prototype" />
</p>

## Overview
JAICK AI Studio is a browser-based editor for creating short social videos from local media files. It is designed for quick clip organization, trimming, visual styling, and export without needing a backend or heavy desktop editing workflow.

This project focuses on a local-first editing experience, allowing users to:
- add video clips
- reorder the storyline
- trim start/end points
- add titles and captions
- control audio levels
- apply filters
- export the final result

## Why this project
Creating social reels often requires multiple tools and a complex workflow. JAICK AI Studio brings the core editing flow into a simple browser interface so users can work fast and keep everything local to the machine.

## Features
- Multi-clip timeline editing
- Drag-and-drop style clip ordering
- Trim controls for start and end points
- Title overlay support
- Automatic caption workflow support
- Social format presets for reels and vertical videos
- Audio mixing and background music support
- Visual filter presets
- Local export of the finished video
- Frontend-only architecture for easy experimentation

## Supported use cases
- Instagram Reels
- YouTube Shorts
- TikTok-style edits
- Short-form content creation
- Fast social-ready video assembly

## Tech stack
- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Browser Media APIs
- Canvas-based preview/export workflow

## Project structure
```text
jaick-ai-studio/
├── index.html      # Main app interface and logic
├── README.md       # Project overview and setup guide
└── .gitignore      # Git repository configuration (if present)
```

## Run locally
### Option 1: Open directly
1. Clone the repository
2. Open `index.html` in a modern browser

### Option 2: Use a local web server
```bash
python -m http.server 8000
```
Then open:
```text
http://localhost:8000
```

## How it works
The app is designed as a frontend-only editor. It reads local video files through the browser, lets the user adjust timeline and visual settings, and renders the final composition before exporting the video locally.

## Development notes
This project is currently a prototype and is built as a local-first editing app. It is a strong foundation for adding AI-powered features such as:
- automatic subtitle generation
- smart scene detection
- auto-trimming by spoken content
- AI-generated titles and effects
- better transitions and media suggestions

## Current status
Prototype / early development

## License
This project is currently under development. Add a proper license before public release.

## Roadmap
- improve timeline UX
- add better caption timing controls
- add more cinematic filters and transitions
- support drag-to-reorder clips more smoothly
- integrate AI-assisted editing workflows
- add downloadable project presets and templates
