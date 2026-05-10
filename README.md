# ₿ BTC Live Dashboard

A mobile-friendly Bitcoin price dashboard. Single HTML file, no build step, no API key required.

**[Live Demo →](https://your-username.github.io/btc-dashboard)**

![Bitcoin Dashboard](https://img.shields.io/badge/Bitcoin-Live%20Price-f7931a?style=flat&logo=bitcoin)
![No API Key](https://img.shields.io/badge/API%20Key-Not%20Required-00e676?style=flat)
![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-181717?style=flat&logo=github)

---

## Features

- Live BTC/USD price with 24h change
- 24H High / Low / Market Cap / Volume stats
- Interactive price chart — 1D, 7D, 30D, 90D
- Market info (supply, VWAP, % mined)
- Fear & Greed sentiment index
- Auto-refreshes every 30 seconds
- Pauses refresh when tab is hidden (saves API calls)
- Works on mobile and desktop

## Data Sources

| Data | Source | Key Required |
|------|--------|-------------|
| Price, Market Data, Chart | [CoinCap API](https://docs.coincap.io/) | ❌ No |
| Fear & Greed Index | [Alternative.me](https://alternative.me/crypto/fear-and-greed-index/) | ❌ No |

---

## Deploy to GitHub Pages (2 minutes)

1. **Fork or create a repo** named `btc-dashboard` (or anything you like)

2. **Upload `index.html`** to the root of the repo

3. **Enable GitHub Pages:**
   - Go to repo → **Settings** → **Pages**
   - Source: `Deploy from a branch`
   - Branch: `main` → `/ (root)`
   - Click **Save**

4. Your dashboard will be live at:
   ```
   https://your-username.github.io/btc-dashboard
   ```

---

## Run Locally

No server needed — just open the file:

```bash
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

Or use a local server:

```bash
npx serve .
# → http://localhost:3000
```

---

## Road Map

- [ ] iOS app (SwiftUI + Node.js backend)
- [ ] Push price alerts
- [ ] Multi-coin support (ETH, SOL, etc.)
- [ ] Portfolio tracker

---

## License

MIT — free to use, modify, and deploy.
