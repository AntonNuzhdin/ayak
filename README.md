# AYAK Domain

A 3D anime-cyberpunk portfolio game for graphic designer AYAK (Christine Yasenova).
Walk a neon night city as one of four heroes, step into barriers to open the work,
collect the letters A·Y·A·K, and unlock the CV behind three fenced relics.

Single file, no build step: `index.html` loads Three.js and Google Fonts from CDNs and
generates every texture, model and sound at runtime.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8080
```

then open http://localhost:8080.

## Controls

| Key | Action |
|---|---|
| W A S D / arrows, click or tap | walk |
| Space | domain expansion (each hero has its own world) |
| E | hero ability: bounce · steam stomp · squeeze · roar |
| Q | switch hero |
| T | change weather: auto · sunny day · rain · fog · clear night |
| Esc | close a card |

## Heroes

- **Gummy Bear** — bounces over low fences. Domain: manga.
- **Walking House** — chimney steam and a stomp that opens iron gates. Domain: blueprint.
- **Soot Ball** — squeezes through narrow slits. Domain: zero gravity.
- **Forest Spirit** — roars to reveal hidden letters and open the nearest barrier. Domain: ink wash.

## Deploy

Any static host works. For GitHub Pages: Settings → Pages → Deploy from a branch → `main` / root.
