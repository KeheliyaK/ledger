# Ledger

A quiet planner for tomorrow, today, and yesterday.

Built for one person — me — because every other productivity app asks for too much upfront. Ledger asks for one thing: *what matters tomorrow?*

**Live app:** https://keheliyak.github.io/ledger/

## What it does

- **Tomorrow** — the nightly 2-minute ritual. Write down 1–3 things that would make tomorrow feel well-spent.
- **Today** — whatever past-you planned, shown plainly. Tap to finish.
- **Diary** — a ledger of what was planned vs. what was kept. Honest, not judgmental.

That’s it. No categories, no tags, no priorities, no streaks to guilt you.

## How it’s built

Plain HTML, CSS, and JavaScript in a single file. No frameworks, no build step, no backend, no dependencies beyond two web fonts. Data lives in the browser’s `localStorage` and never leaves the device.

The whole app is one `index.html` — you can read the entire codebase in one sitting.

### Why plain web tech

- Nothing to install, nothing to deploy, nothing to break
- Every line is something I can understand and change myself
- Works offline once loaded
- Installs to the iPhone home screen via Safari → Share → Add to Home Screen, and behaves like a native app

## Use it yourself

1. Open https://keheliyak.github.io/ledger/ in Safari on your iPhone
1. Tap the **Share** button → **Add to Home Screen**
1. Launch it from your home screen like any other app

Your data stays on your device. Clearing Safari’s storage will wipe the ledger.

## Roadmap

- [x] **Stage 1** — Plan / Today / Diary, cozy dark theme
- [ ] **Stage 2** — Walk through the code and understand every line
- [ ] **Stage 3** — Notifications for specific tasks
- [ ] **Stage 4** — Offline support (service worker), export/backup

## Design

Warm dark palette — candlelight on aged paper, in the dark. Fraunces for display, Literata for body. Subtle paper grain. Gold-ember accents. Built to feel like opening a journal, not launching an app.

-----

Built with Claude as a learning project in plain web development.
