# 🌿 [Invite Manager]([url](https://6a43a3cc1763a900098cc62c--grand-bubblegum-93e4a1.netlify.app/))

A beautiful, privacy-first wedding guest management app — built entirely in the browser. No servers, no databases, no data ever leaves your device.

![Green leaf theme](https://img.shields.io/badge/theme-earthy%20green-4a7c59?style=flat-square) ![Static](https://img.shields.io/badge/type-static%20HTML-brightgreen?style=flat-square) ![Privacy](https://img.shields.io/badge/data-stays%20on%20device-blue?style=flat-square)

---

## ✨ Features

- 📂 **Upload CSV** — drag & drop your guest list instantly
- ✏️ **Paste or type** names manually
- 🎯 **4 invite tiers** — Full Invite, Shadi Only, Reception Only, Declined
- 📊 **Live stats dashboard** — see counts at a glance
- 🔍 **Search & filter** by name or status
- 💾 **Export to CSV** — download your finalized list
- 🔒 **100% offline** — all data stays in your browser tab
- 📱 **Mobile friendly** — works on any device

---

## 🚀 Getting Started

### Use it live
Deploy on [Netlify](https://netlify.com) by connecting this repo — free, instant, auto-deploys on every push.

### Run locally
```bash
git clone https://github.com/talewar-darshan/InviteApp.git
cd InviteApp
open index.html   # or double-click the file
```
No install, no build step — just open the HTML file.

---

## 📋 CSV Format

Your CSV needs just one column (`name`). The `source` column is optional:

```csv
name,source
Aisha Khan,Instagram
Rahul Mehta,Family
Priya Sharma,Work
```

---

## 🔒 Security & Privacy

| What | How |
|---|---|
| **No server** | Pure static HTML — nothing to hack server-side |
| **No cookies** | Zero tracking, zero analytics |
| **No external requests** | Only Google Fonts CDN loaded (no data sent) |
| **CSP headers** | Content Security Policy prevents XSS via Netlify headers |
| **No localStorage** | Guest data lives only in memory — clears on tab close |
| **Input sanitization** | All CSV/manual input is sanitized before rendering |
| **No eval()** | Zero use of `eval` or `innerHTML` with unsanitized input |

---

## 📁 Project Structure

```
InviteApp/
├── index.html          ← The entire app
├── netlify.toml        ← Security headers config
└── README.md
```

---

## 🌿 Built with love for your special day
