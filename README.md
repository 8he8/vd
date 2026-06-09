# Videoglancer.top

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/8he8/Videoglancer.top/blob/main/videoglancer-top.ipynb)

**Convert YouTube videos to PDF or PowerPoint presentations — 100% free, no signup required.**

Videoglancer extracts key frames from YouTube videos and organizes them into professional-looking documents. Perfect for creating study notes, video summaries, lecture reviews, or analyzing content visually.

## How to Use

1. **Open the notebook** — Click the "Open in Colab" badge above to launch the notebook in Google Colab.
2. **Run the 3 code blocks in order:**
   - **Block 1** — Downloads the project zip, installs all dependencies (FFmpeg, Python packages, etc.), and sets up everything automatically.
   - **Block 2** *(optional)* — Mounts Google Drive so you can save converted files directly to your Drive.
   - **Block 3** — Starts the Flask dev server and generates 3 public tunnel URLs. Open any of them in your browser — if one doesn't work, try another.
3. **Paste a YouTube URL** — Single video or full playlist.
4. **Configure options** — Choose quality, format (PDF/PPTX), extraction method, and more.
5. **Click "Convert Video"** — Watch real-time progress as your document is built.
6. **Download or save to Google Drive** — Get your PDF or PPTX file instantly. At Google Colab, if Google Drive is mounted, you can save files directly to Drive using the "Save to Drive" buttons or enable "Auto-save" before converting.

## Features

- **Instant preview** — YouTube card shows thumbnail, title, and duration in real-time
- **Two extraction methods** — Choose between Time Interval or Scene Detection
- **Smart deduplication** — Automatically removes similar frames using perceptual hashing
- **Timestamp overlays** — Each frame labeled with its position in the video
- **Playlist support** — Convert entire playlists in one go
- **Google Drive integration** — Auto-save outputs directly to your Drive (Colab only)
- **Real-time progress** — SSE-powered progress tracking with live timer

## Links

- **Website:** [https://videoglancer.top](https://videoglancer.top?utm_source=github&utm_medium=readme)
- **Feedback:** [contact@videoglancer.top](mailto:contact@videoglancer.top)