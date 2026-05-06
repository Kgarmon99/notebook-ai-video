# Notebook AI Video

Turn any notes, ideas, or topics into AI-powered explainer videos with voiceover.

**Live Demo:** https://kgarmon99.github.io/notebook-ai-video/

## How It Works

This app uses **real browser APIs** to generate videos:

1. **HTML5 Canvas** - Creates animated visuals based on your content
2. **MediaRecorder API** - Captures the canvas animation as a video file
3. **Web Speech API** - Generates natural voiceover from your text
4. **localStorage** - Saves your videos for later access

## Features

- ✅ **Real video generation** - Creates actual MP4/WebM files
- ✅ **Voice synthesis** - Natural-sounding AI voiceover
- ✅ **3 visual styles** - Professional, Casual, Energetic
- ✅ **3 duration options** - 15s, 30s, 60s
- ✅ **Download videos** - Save as .webm files
- ✅ **Works offline** - PWA with service worker
- ✅ **Preview before download** - Watch video in modal player

## Quick Start

1. Go to https://kgarmon99.github.io/notebook-ai-video/
2. Enter your content (or load a template)
3. Choose style, duration, and voice
4. Click "Create AI Video"
5. Wait for generation (15-60 seconds)
6. Preview or download your video

## Templates

- **Startup Investor Pitch** - Professional pitch deck format
- **Product Demo Video** - Feature showcase style
- **Training & Onboarding** - Educational format

## Browser Support

Works best in:
- Chrome/Edge (recommended)
- Firefox
- Safari (limited voice support)

## Technical Details

- **Canvas Resolution:** 640x360 (16:9)
- **Frame Rate:** 30fps
- **Output Format:** WebM (VP9 codec)
- **Audio:** Web Speech API synthesis
- **Storage:** Browser localStorage

## Privacy

All video generation happens **locally in your browser**. No content is sent to external servers. Videos are stored only on your device.
