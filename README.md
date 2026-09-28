# 🎮 Pac Man Contribution Graph

Generates an animated **Pac-Man arcade** version of my GitHub contribution graph — Pac-Man eats the squares while the ghosts chase him.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Aastik780/pac-man-contribution-graph/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Aastik780/pac-man-contribution-graph/output/pacman-contribution-graph.svg">
  <img alt="Pac-Man contribution graph" src="https://raw.githubusercontent.com/Aastik780/pac-man-contribution-graph/output/pacman-contribution-graph.svg">
</picture>

## 🧰 Things I build

- 🎵 **[Pulsee](https://github.com/Aastik780/Discord-music-bot)** — a `~` prefix music bot powered by the most powerful and premium Lavalink: themed now-playing cards, radio & 24/7 mode, audio filters, playlists, and a one-click Windows launcher.

## ⚙️ How it works

- A **GitHub Action** runs on every push, daily at `00:00 UTC`, or manually from the Actions tab
- It fetches my contribution data and renders SVG games into the [`output`](https://github.com/Aastik780/pac-man-contribution-graph/tree/output) branch
- The profile README at [Aastik780/Aastik780](https://github.com/Aastik780/Aastik780) embeds those SVGs

## 🕹️ Embed in your README

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/YOUR_USER/YOUR_REPO/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/YOUR_USER/YOUR_REPO/output/pacman-contribution-graph.svg">
  <img alt="Pac-Man contribution graph" src="https://raw.githubusercontent.com/YOUR_USER/YOUR_REPO/output/pacman-contribution-graph.svg">
</picture>
```

---

<p align="center"><i>built with <a href="https://github.com/abozanona/pacman-contribution-graph">abozanona/pacman-contribution-graph</a> · <a href="https://github.com/Aastik780/pac-man-contribution-graph">Aastik/pacman-contribution-graph</a></i></p>
