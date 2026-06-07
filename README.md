# FavFind 🔖

**A beautiful, single-file Progressive Web App (PWA) that lets you save, organize, and instantly search your favorite TikTok, Instagram Reels, and YouTube videos.**

Built as a true mobile-first experience with native Share Target support — just tap **Share → FavFind** from any video app.

---

## ✨ Features

- **Native Share Target** — Works directly from TikTok, Instagram, and YouTube share sheets
- **Advanced Service Worker Caching** — Fully offline capable with intelligent stale-while-revalidate strategy
- **Multi-select Filters** — Combine platforms + any number of hashtags
- **Fuzzy Search** — Across titles, notes, tags, platforms, and dates
- **Voice Notes** — Web Speech API integration for instant tagging
- **Platform Auto-Detection** — TikTok, Instagram Reels, YouTube (shorts & regular)
- **Local-first Persistence** — Everything stored in `localStorage` (100% private, no backend)
- **PWA Ready** — Installable on iOS Safari and Android Chrome with native app feel
- **Minimalist Dark UI** — Clean Tailwind + custom animations

## Tech Stack

- **HTML + Vanilla JavaScript** (single file — no build step)
- **Tailwind CSS** (via CDN)
- **Service Worker** (advanced caching + Share Target)
- **Web Share Target API**
- **Web Speech API** (voice notes)
- **localStorage** for persistence
- **PWA Manifest**

## Quick Start

1. Clone the repo:
   ```bash
   git clone https://github.com/elontheduck/favfind.git
   cd favfind
