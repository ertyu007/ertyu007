<img src="assets/header.svg" alt="ertyu007" width="100%" />

I build tools I actually use, mostly Windows desktop apps and small web apps in Python. The biggest one is **Clipora**, a media converter that does everything on your own machine.

<br>

## Clipora

**A free, open-source Windows app for converting video, extracting audio and splitting songs into stems. No ads, no account, nothing leaves your PC.**

[Repository](https://github.com/ertyu007/media-toolkit-Open-source) · [Website](https://ertyu007.github.io/media-toolkit-Open-source/) · [Releases](https://github.com/ertyu007/media-toolkit-Open-source/releases)

- Paste a public link (via yt-dlp) or pick a local file, choose a format, press start
- Video to MP4 (H.264/AAC) or MOV (ProRes 422, ready for After Effects), from 360p up to 4K
- Audio out as MP3, M4A, WAV, FLAC or OPUS
- **Stem separation** with Demucs, fully offline: vocals and music split into separate files
- Cancel a job and it only cleans its own temp files; the original output stays until the new one succeeds
- Thai paths, spaces and special characters all work
- The installer bundles FFmpeg, yt-dlp and Deno, and every download is checksum-verified

Shipping is automated. Pushing a tag does the rest:

```text
git tag pc-v*  →  GitHub Actions  →  tests  →  Windows installer  →  SHA-256  →  Release
```

`Python` `Tkinter` `FFmpeg` `yt-dlp` `Demucs` `Inno Setup` `GitHub Actions` · GPL-3.0 · 80+ commits

<br>

## Bingo Creator AI

**Type a topic, get printable Thai bingo cards and a host sheet.**

[Repository](https://github.com/ertyu007/Bingo-webapp)

A Streamlit app where Groq's Llama 3.1 writes 25 Thai words for your topic (or you type your own). It exports player cards as PDF in 3×3, 4×4 or 5×5 with a proper Thai font, plus a separate caller sheet for whoever runs the game. Colours, the free space and the logo are all customisable.

Split into `core/ai_assistant.py` (prompting and cleaning the word list) and `core/bingo_engine.py` (PDF layout), with the UI kept in `app_web.py`.

`Python` `Streamlit` `Groq API` `PDF` · MIT

<br>

## Small stuff

[Batch utilities](https://github.com/ertyu007/tiktok-code_ep_bat): Windows batch scripts, starting with a downloads-folder cleaner.

<br>

## Next up

- Batch queue for Clipora, so many files can run in one go
- Signed installers to cut down SmartScreen warnings (the pipeline already supports it)

<br>

## Toolbox

<img src="https://skillicons.dev/icons?i=python,powershell,windows,git,github,githubactions,vscode&theme=dark" alt="toolbox" />

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ertyu007/ertyu007/output/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ertyu007/ertyu007/output/snake-light.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/ertyu007/ertyu007/output/snake-dark.svg" />
</picture>

<br>

<sub>More in [repositories](https://github.com/ertyu007?tab=repositories).</sub>
