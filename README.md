[README.md](https://github.com/user-attachments/files/28075514/README.md)
# IDNTT — Marathon Training App

A lightweight, offline-capable web app for tracking the IDNTT run collective's marathon training plan. Built for the **Surfers Point Marathon (Sep 6, 2025)** with a target time of **sub-3:30**.

## What it is

A mobile-first training plan app that lives on your iPhone home screen. No app store, no login, no subscription — just open it and see exactly what you're training today.

---

## Features

- **Today view** — auto-detects your current training week and day, shows the exact session with full workout details
- **Day navigation** — step forward or backward through the plan one day at a time
- **Week jump** — instantly jump to any of the 13 training weeks from a dropdown
- **Full workout popups** — every session has a detailed breakdown: sets, reps, distances, paces, and coaching notes
- **This Week view** — see all 7 sessions for the current week at a glance
- **Plan overview** — all 5 phases with dates, mileage targets, and gym/run day counts
- **Race countdown** — days to race displayed on every screen
- **Accent color picker** — 5 color themes (Solar Gold, Crimson, Inferno, Electric Blue, Plasma), preference saved locally
- **Fully offline** — works with no internet once loaded

---

## The Training Plan

**13 weeks | May 19 – Sep 6, 2025**

| Phase | Weeks | Dates | Mileage |
|---|---|---|---|
| Base Build | 1–3 | May 19 – Jun 6 | 10–15 mi/wk |
| Aerobic Dev | 4–6 | Jun 7 – Jun 27 | 15–20 mi/wk |
| Peak Build | 7–10 | Jun 28 – Jul 25 | 20–25 mi/wk |
| Taper | 11–12 | Jul 26 – Aug 8 | 10–15 mi/wk |
| Race Week | 13 | Aug 31 – Sep 6 | ~8 mi + race |

**Weekly split (4 gym days + runs):**

| Day | Session |
|---|---|
| Monday | Upper 1 — Chest / Back / Biceps |
| Tuesday | Lower 1 — Squat / RDL / Leg press (weights only) |
| Wednesday | Upper 2 + Easy Run (double day) |
| Thursday | Lower 2 — Sprints only (no weights) |
| Friday | Upper 3 — Back / Chest / Triceps |
| Saturday | Long Run |
| Sunday | Tempo Run |

> Friday shifts to an Easy Run and Sunday becomes Tempo + Upper 3 during Peak Build. Thursday becomes Strides only during Taper.

---

## How to use

### Add to iPhone home screen
1. Open the app URL in **Safari** (must be Safari, not Chrome)
2. Tap the share icon at the bottom of the screen
3. Tap **"Add to Home Screen"**
4. Name it `IDNTT` and tap **Add**

The app icon will appear on your home screen and open full-screen like a native app.

### Navigating the plan
- Use **‹ ›** arrows to step through days one at a time
- Use the **week dropdown** to jump directly to any training week
- Tap any session card to see the full workout breakdown
- Switch between **Today**, **This Week**, and **Plan** tabs in the nav bar

---

## Stack

Pure HTML, CSS, and vanilla JavaScript. No frameworks, no dependencies, no build step. One file.

- Fonts: [Barlow Condensed](https://fonts.google.com/specimen/Barlow+Condensed) + [Space Mono](https://fonts.google.com/specimen/Space+Mono) via Google Fonts
- Storage: `localStorage` for accent color preference
- Hosting: GitHub Pages / Netlify

---

## Deploying

### GitHub Pages
1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, root folder
4. Your app will be live at `https://yourusername.github.io/repo-name`

### Netlify Drop
1. Go to [netlify.com/drop](https://netlify.com/drop)
2. Drag `index.html` onto the page
3. Done — instant live URL

---

*Built for the IDNTT run collective. Berkeley → Ventura.*
