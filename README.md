# OncAccess Demo Reel

A HyperFrames video composition. Plain HTML + GSAP; rendered to MP4 by the `hyperframes` CLI.

12 scenes / 60 seconds / 1920×1080.

## Requirements

- **Node.js 22+** — [nodejs.org](https://nodejs.org/)
- **FFmpeg** — `brew install ffmpeg` (macOS) or `sudo apt install ffmpeg` (Debian/Ubuntu)

Verify: `npx hyperframes doctor`

## Preview

```bash
npx hyperframes preview
```

Opens HyperFrames Studio at `http://localhost:3002` with frame-accurate scrubbing.

## Render

```bash
npx hyperframes render index.html -o oncaccess-reel.mp4
```

## Refine with Claude Code

```bash
npx skills add heygen-com/hyperframes
npx hyperframes lint
npx hyperframes preview
```
