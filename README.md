# Market Terminal

Live stock market dashboard — [github.com/Jaayy46/market-terminal](https://github.com/Jaayy46/market-terminal)

## Features

- **Watchlist** — real-time price tracking
- **Portfolio P&L** — position tracking with live P&L
- **Alerts** — price threshold notifications
- **News** — market news feed

## Structure

```
index.html    # Dashboard UI
style.css     # Styles
main.js       # Logic: Yahoo Finance API, charts, alerts
```

## Local development

```bash
python3 -m http.server 8080
# → http://localhost:8080
```

## Deploy

GitHub Pages from `main` branch root.

## Workflow

```
feat/* or fix/*  →  dev  →  PR  →  main
```

`main` is protected — always work on `dev` or a feature branch.
