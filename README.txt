Crypto / Asset Signal Lab - Live 2-minute research dashboard

Deploy: upload index.html to the root of your GitHub Pages repository.
No build, backend, API key or screenshot required.

Uses Binance Spot public market data WebSocket and public 1m candle history.
Two-minute candles are aggregated from pairs of UTC-aligned 1m candles.
The next window bias is calculated using COMPLETED candles at each 2m boundary.

IMPORTANT:
- Binance exchange prices are NOT Binomo IDX/OTC prices.
- UP/DOWN is a heuristic technical-analysis bias, NOT a trade recommendation.
- Scores are indicator evidence points, NOT predicted accuracy or win probabilities.
- Browser must stay open; connection requires network access to Binance.
- Binance endpoints may be unavailable or blocked in some regions.
- No orders are placed and no trading account is connected.

Official API docs: https://github.com/binance/binance-spot-api-docs
