CRYPTO IDX RESEARCH LAB — 1-MINUTE, STATIC GITHUB PAGES

Upload index.html to the root of your GitHub repository and commit. GitHub Pages should publish from main / (root).

Data input: CSV with columns time,open,high,low,close and optional volume. Time must be ISO 8601 with timezone (e.g. 2026-11-06T10:00:00Z) or Unix milliseconds. Use completed 1-minute Binomo Crypto IDX candles from a permitted export. At least 35 rows for indicators and 60 for backtesting. No API keys or credentials are used.

Binomo's official help center describes Crypto IDX as an internal synthetic asset and disallows bots / specialized trading software for trading. This project deliberately does not connect to Binomo, scrape it, or execute trades. Confirm permissions with Binomo support before using any third-party data extraction.

Backtesting: evaluates each historical signal using only information available at the prior candle close; assumes hypothetical next-close settlement, fixed stake and configurable payout. Ties are neutral for the demo. Real broker results may differ.

The included synthetic example is for UI testing, not market evidence. No live signals or predictive guarantees.
