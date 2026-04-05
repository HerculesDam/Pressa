# Pressa — Leitura Dinâmica

A speed reading web app that uses the RSVP (Rapid Serial Visual Presentation) technique to help you read faster by flashing one word (or a chunk of words) at a time on screen.

## Features

- **Adjustable reading speed** — set your WPM (words per minute) from 100 to 1,200
- **Chunk mode** — display multiple words at once to increase throughput
- **Focus letter highlighting** — each word highlights its optimal recognition point to reduce eye movement
- **Playback controls** — start, pause/resume, stop, rewind 10 words, and skip forward 10 words
- **Progress tracking** — live progress bar, word count, elapsed time, and estimated time remaining
- **Completion summary** — shows total words read, time taken, and average WPM at the end
- **Keyboard shortcuts** for hands-free control (see below)
- **Responsive design** with a dark, animated UI

## Usage

1. Open `index.html` in any modern web browser — no build step or server required.
2. Paste or type your text into the input area.
3. Adjust speed and chunk size to your preference.
4. Click **Iniciar** (or press `Space`) to start reading.

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Space` | Start / Pause / Resume |
| `Escape` | Stop and reset |
| `←` | Rewind 10 words |
| `→` | Skip forward 10 words |
| `↑` | Increase speed (+50 WPM) |
| `↓` | Decrease speed (−50 WPM) |

## Tech Stack

Pure HTML, CSS, and vanilla JavaScript — no dependencies or frameworks. Fonts are loaded from Google Fonts (Space Grotesk, JetBrains Mono, Fraunces).

## License

No license specified.
