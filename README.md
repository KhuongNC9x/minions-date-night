# 🎬 Minions Date Night — Interactive Movie Invitation

A cute interactive movie invitation built as a web app, made with love for a special someone. 💛

## ✨ Features

- **3-screen flow**: Cover → Love Letter + Movie Ticket → Confirmation
- **Dodging "No" button**: The decline button runs away every time you try to click it 😝
- **Animations**: Floating hearts, confetti burst, emoji explosions on button tap
- **Background music**: Auto-plays a cheerful melody via Web Audio API
- **Mobile-first**: Optimized for phones

## 🎟️ Movie Details

| | |
|---|---|
| 🎬 Movie | Minions & the Monster (2026) |
| 🕖 Showtime | 19:15 – 20:45, Wednesday 01/07/2026 |
| 📍 Cinema | Beta Xuan Thuy – Floor 4, AEON Xuan Thuy, Cau Giay, Hanoi |
| 🎭 Room | P3 |
| 💺 Seats | D08 · D09 |

## 📁 Project Structure

```
├── index.html          # Main invitation (Design Component)
├── support.js          # DC Runtime (React 18 engine)
├── poster.jpg          # Movie poster
└── videoplayback.mp4   # Background music (add manually)
```

## 🚀 Running Locally

Serve via HTTP (required for audio/video):

```bash
npx serve .
# or
python -m http.server 8080
```

Then open `http://localhost:8080`.

## 🌐 Live Demo

Hosted on GitHub Pages:
**[https://KhuongNC9x.github.io/minions-date-night/](https://KhuongNC9x.github.io/minions-date-night/)**

---

Made with 💛 by a loving husband
