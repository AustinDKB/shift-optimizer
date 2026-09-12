# Shift Optimizer

Interactive demo of a greedy coverage scheduler for a quick-service restaurant business day (3 AM → 2 AM).

Watch shifts place against an hourly demand forecast: coverage chart, deficit heatmap, and employee schedule animate as the algorithm runs.

**Live demo:** [austinbakanec.com/projects/shift-optimizer/live](https://www.austinbakanec.com/projects/shift-optimizer/live)

**Case study:** [austinbakanec.com/projects/shift-optimizer](https://www.austinbakanec.com/projects/shift-optimizer)

## Run locally

No build step — open `index.html` in a browser, or:

```bash
python3 -m http.server 8080
# → http://127.0.0.1:8080
```

## What’s in here

| Path | Role |
| --- | --- |
| `index.html` | App shell + scheduler (ported from a ~2,000-line notebook into a compact JS core) |
| `assets/styles.css` | Compiled Tailwind |
| `assets/theme-sk.css` | Saskatchewan wheat / evergreen theme |
| `assets/fonts/` | Self-hosted IBM Plex Sans |

## License

MIT
