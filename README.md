# 📈 BTC Daily Price Movement & News Dashboard

A responsive, high-reliability web dashboard tracking Bitcoin daily price action over a 1-year rolling window alongside aggregated crypto news and automated sentiment shading.

## ✨ Key Features
- **Dynamic Daily Engine:** Automatically calculates exact 365-day historical daily performance ending yesterday.
- **Robust 4-Tier Failover:** Seamlessly switches between **Binance Vision**, **Kraken**, **Coinbase**, and **Binance Primary** APIs.
- **Interactive Chart Modes:** Switch between **Daily Net Change ($)** and full **Daily Price Range (High–Low)** corridor views.
- **Sentiment News Feed:** Aggregates live headlines from **CoinDesk**, **Bitcoin Magazine**, **Decrypt**, and **The Block**, automatically shading cards across a **Green/Yellow/Red** sentiment spectrum.
- **Stale-While-Revalidate Caching:** Instant loading with zero empty states via local storage persistence.
- **Isolated News Refresh:** Dedicated manual refresh button to update news without reloading the chart.

## 📂 Project Structure
```text
btc-tracker-daily/
├── index.html
└── assets/
    ├── style.css
    └── app.js