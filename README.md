# CodeReady — Emergency Protocols PWA

Single-page PWA: ACLS / PALS / ATLS / ACR contrast reactions / moderate sedation.
Features: Learn pages, scenario trainer, flashcards, and an offline-capable
Quick Reference "emergency mode" with weight-based pediatric dose calculation.

## Deploy in ~5 minutes (GitHub Pages, free)

1. Create a GitHub account (if needed) and a new **public** repository, e.g. `codeready`.
2. Upload these 3 files to the repo root: `index.html`, `manifest.json`, `sw.js`
   (drag-and-drop in the GitHub web UI works fine).
3. Repo → Settings → Pages → Source: "Deploy from a branch" → Branch: `main` / root → Save.
4. After ~1 minute your app is live at: `https://YOURUSERNAME.github.io/codeready/`

## Install on your iPhone

1. Open the URL in **Safari** (must be Safari, not Chrome).
2. Tap the **Share** button → **Add to Home Screen** → Add.
3. It now launches full-screen like a native app, and works **offline**
   after the first load (service worker caches everything).

## Notes

- Patient weight (for PALS dosing) persists between sessions via localStorage.
- All content is bundled in index.html — no external dependencies, no tracking.
- Educational reference for licensed clinicians; verify against current
  AHA / ACR / ATLS / institutional protocols.
