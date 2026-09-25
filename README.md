# NUR 2460 — Exam 2 Study Guide

A single-page, mobile-friendly study guide for NUR 2460 (Family Nursing Care) Exam 2, covering:

- **Week 4** — High Risk Pregnancy
- **Week 5** — High Risk Labor & Delivery + High Risk Newborn
- **Week 6, Part 1** — GYN, STIs, Infertility & Contraception
- **Week 6, Part 2** — Healthy Child Growth & Development (sub-tab inside the Week 6 tab)

Features:

- Tab switcher between Week 4, Week 5, and Week 6 — Week 6 has its own two sub-tabs (GYN/STIs and Growth & Development) so both halves of that week live under one tab
- ★ high-yield flags on topics called out by the course's master study guide outline
- A dedicated, plain-English "Medications (explained)" section for each week/sub-tab, with the exact source document cited per medication (Week 5, and both parts of Week 6)
- Live search across all four content areas' topics, medications, and the medication audit
- Responsive layout — works on both laptop and phone
- Light/dark mode (follows your device/browser setting)
- A custom app icon so the site gets a real icon (not a generic globe) when added to a phone or desktop home screen

## Files

- `index.html` — the study guide itself
- `favicon.ico`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` — the app icon, in the sizes browsers/phones ask for
- `manifest.json` — tells Android/Chrome how to label and icon the site when added to a home screen

## Viewing it

Open `index.html` directly in any browser — it's a single self-contained file (no build step, no dependencies to install).

### Hosting it for free with GitHub Pages

1. Push this repo to GitHub (see the main chat for step-by-step instructions).
2. In the repo on GitHub, go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Pick the `main` branch and the `/ (root)` folder, then **Save**.
5. GitHub will give you a live URL (usually `https://<username>.github.io/<repo-name>/`) within a minute or two.

## Adding it to your home screen

Once the site is live on GitHub Pages:

- **iPhone (Safari):** open the link → tap the Share icon → **Add to Home Screen**. The heart/pulse icon appears automatically.
- **Android (Chrome):** open the link → tap the ⋮ menu → **Add to Home screen** (or you may see an "Install app" banner).
- **Desktop (Chrome/Edge):** open the link → click the install icon (⊕ or a small monitor icon) at the right end of the address bar → **Install**.

## Updating it

This file was generated from course instructor notes/presentations. If you get new material, the simplest path is to come back to the Claude conversation that built this, ask for the update, and re-download/re-copy the refreshed `index.html` here — then commit and push the change.
