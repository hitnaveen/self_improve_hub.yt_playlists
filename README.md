# self_improve_hub.yt_playlists
# YT Playlist Vault

A curated, beautifully designed guide to the best YouTube playlists
across self-improvement, fitness, finance, style, relationships, and more.

Built as a single-page web app with zero dependencies — pure HTML, CSS, and JS.

**Live Site:** [learnstack.dev](https://learnstack.dev)

---

## About

I wanted a single place to bookmark and share the YouTube channels and
playlists that actually move the needle — not generic "top 10" lists,
but honest, opinionated picks with context on *why* each one is worth
your time.

The UI and code were generated with Claude AI based on my ideas,
content choices, and creative direction. Every channel recommendation,
category, tip, and opinion is my own.

---

## Features

- Filter by category (Fitness, Finance, Style, Relationships & more)
- Fully responsive — works on mobile, tablet, desktop
- Zero dependencies — no frameworks, no build step, no npm install
- Dark mode UI with smooth animations
- Direct links to YouTube playlists

---

## Categories Covered

| Category | What You'll Find |
|---|---|
| 💪 Fitness | Workout programming, nutrition, calisthenics |
| 💰 Finance | Investing, budgeting, wealth mindset |
| 👔 Style | Men's fashion, wardrobe building |
| ❤️ Relationships | Communication, emotional intelligence |
| 😂 Humour | Comedy structure, wit, social skills |
| + more | Expanding regularly |

---

## 🛠️ Tech Stack

| Layer | Choice |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, animations) |
| Logic | Vanilla JavaScript |
| Fonts | Google Fonts (Syne, Inter, JetBrains Mono) |
| Hosting | GitHub Pages |
| Domain | Name.com (via GitHub Student Developer Pack) |

---

## Run Locally

No setup needed. Just clone and open:

```bash
git clone https://github.com/yourusername/yt-playlist-vault.git
cd yt-playlist-vault
open index.html   # or just double-click the file
```

---

## How to Edit

All content lives in `index.html`. To add a new channel card, copy
This block and fill in your details:

```html
<div class="channel-card">
  <div class="channel-top">
    <div class="channel-name-wrap">
      <div class="channel-name">Channel Name</div>
      <div class="channel-handle">@handle</div>
    </div>
    <div class="channel-badge">Your Tag</div>
  </div>
  <p class="channel-desc">Why this channel is worth watching.</p>
  <div class="playlist-label">▸ Key Playlists</div>
  <div class="playlists">
    <a class="playlist-item" href="PLAYLIST_URL" target="_blank">
      Playlist Name <span class="pl-arrow">↗</span>
    </a>
  </div>
</div>
```

---

## Roadmap

- [ ] Search bar across all channels
- [ ] Save favourites to localStorage
- [ ] Dark/light mode toggle
- [ ] Submit a channel (Google Form integration)
- [ ] Weekly "Pick of the Week" section

---

## Credits

- **Content & Ideas** — Me
- **UI Code** — Generated with [Claude AI](https://claude.ai) (Anthropic)
- **Fonts** — [Google Fonts](https://fonts.google.com)
- **Hosting** — [GitHub Pages](https://pages.github.com)
- **Domain** — [Name.com](https://name.com) via GitHub Student Developer Pack

---

## 📄 License

MIT — feel free to fork and build your own curated guide.
