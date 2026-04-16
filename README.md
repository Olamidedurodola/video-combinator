# Video Combinator

Open-source, browser-based tool for merging short videos, adjusting speed, adding text overlays, and reframing for social media.

**All processing happens locally in your browser — your files never leave your device.**

## Features

- 📥 Drag & drop multiple videos (MP4 / WebM / MOV)
- 🔀 Reorder clips, delete, set per-clip playback speed (0.5×–3×)
- 📱 One-click framing: TikTok 9:16, Instagram 1:1, YouTube 16:9, IG Portrait 4:5
- ✍️ Timed text overlays with position, size, and color
- 🎨 Cover/contain fit modes, background color
- ⬇️ Export as WebM with selectable FPS & bitrate

## Usage

Just open `index.html` in any modern browser (Chrome, Edge, Firefox). No build step, no server.

Or host it on GitHub Pages: `Settings → Pages → Deploy from branch → main`.

## Tech

Pure HTML + CSS + vanilla JS. Uses the Canvas API, MediaRecorder, and Web Audio API for in-browser video composition.

## License

MIT
