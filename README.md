# K·F BEATZ

> A self-contained, offline-capable beat-making studio that lives in a **single HTML file**.

K·F BEATZ is the **BeatForge** engine: a browser-based groove box for sketching beats — synth voices, drums, sample chopping, layered patterns, MIDI import, and WAV bounce — with **no React, no Tailwind, and no build step**. Open the file and play.

## ✨ Features

- **Step sequencer** — program drums and synth voices across a grid of steps.
- **Built-in synth & drums** — generate sounds entirely in the browser via the Web Audio API; no samples required to get started.
- **Sample import** — drop a `.wav` or `.mp3` onto the page to add it as a playable sample.
- **MIDI import** — drop a `.mid` file to add it as a new layer.
- **Layers** — stack multiple patterns/instruments into a single arrangement.
- **WAV bounce** — render your arrangement to a `.wav` file you can download.
- **Filters & effects** — shape each voice with filtering and delay.
- **Tempo control** — set the BPM for your groove.
- **YouTube play-along** — drop in a video to jam over (audio-only reference; not part of the bounce).
- **Themes** — `cyan`, `amber`, and `magenta` looks.
- **Works offline** — everything runs locally. Google Fonts load when online and fall back to system fonts when not.

## 🚀 Getting started

No install, no dependencies, no build.

### Option A — open locally
```bash
# clone, then just open the file in any modern browser
open KF_BEATZ.html        # macOS
# xdg-open KF_BEATZ.html  # Linux
# start KF_BEATZ.html     # Windows
```

### Option B — live demo (GitHub Pages)
Once this repo is pushed and Pages is enabled, the app is served at:

> `https://<your-username>.github.io/kfbeatz/`

(The included `index.html` redirects to `KF_BEATZ.html` so the Pages root works.)

## 🎛️ Usage

1. Set your tempo (BPM).
2. Toggle steps on the sequencer to program a pattern.
3. Drop a `.wav`/`.mp3` to add a sample, or a `.mid` to add a layer.
4. Tweak filters/effects per voice.
5. Hit **bounce** to render your arrangement to a downloadable `.wav`.

## 🧱 Project structure

```
kfbeatz/
├── KF_BEATZ.html     # the entire application (HTML + CSS + JS, self-contained)
├── index.html        # redirect to KF_BEATZ.html (for GitHub Pages root)
├── README.md
├── LICENSE-MIT
└── LICENSE-APACHE
```

## 🌐 Browser support

Requires a modern browser with **Web Audio API** support (Chrome, Edge, Firefox, Safari). Audio export uses in-browser rendering — no server involved.

## 📄 License

Licensed under either of

- Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or <http://www.apache.org/licenses/LICENSE-2.0>)
- MIT license ([LICENSE-MIT](LICENSE-MIT) or <http://opensource.org/licenses/MIT>)

at your option.

Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in this project by you, as defined in the Apache-2.0 license, shall be dual licensed as above, without any additional terms or conditions.
