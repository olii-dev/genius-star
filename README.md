# Genius Star — Tournament & Solver

A clean, mobile-first web app for [The Genius Star](https://www.smartgames.eu/uk/one-player-games/genius-star) (SmartGames):

- **Tournament tracker** — 2-8 teams, rename inline, per-round scoring, running leaderboard, round history. Scores persist on-device.
- **Puzzle solver** — enter the 7 blocker numbers from your dice roll and browse every solution, drawn on an exact SVG rendering of the star. Supports Standard (11 pieces) and Golden Star (hexagon piece) modes.

The solver uses the real game geometry: the 48-triangle star board, the exact dice faces, and all piece shapes (sourced from [johnrudge/genius_star](https://github.com/johnrudge/genius_star)). Solution counts are verified against an independent reference solver.

## Run locally

```bash
python3 -m http.server 8814
```

Then open http://localhost:8814
