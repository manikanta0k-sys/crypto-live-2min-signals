CandlePattern PRO V1.0 — Candlestick Screenshot Dashboard
=======================================================

Source reference: https://www.scribd.com/document/651377054/Candlestick-Chart-Patterns
The page claims 35 patterns; its contents name 32. This app includes those 32 in the reference library.

Start on a Windows/Mac computer:
1. ZIP Extract cheyyandi.
2. index.html ni Chrome lo open cheyyandi.
3. Binomo screenshot Paste (Ctrl+V) or Upload Image click cheyyandi.
4. Chart lo candles unna area matrame drag chesi select cheyyandi (UP/DOWN buttons exclude).
5. Screenshot/chart capture time ni verify cheyyandi. Rightmost candle running aithe "Exclude the rightmost candle" checked undali.
6. Analyze Completed Candles click cheyyandi.
7. Pattern name, direction bias, quality, reconstructed candles and timing chudandi.

On iPhone Chrome:
- If you can open the downloaded HTML locally, use Upload Image, or long-press paste field.
- If Chrome cannot open a local HTML file, publish index.html using your GitHub Pages repository. A public hosted link is not included in this package.

Extra verification:
- OHLC Verification tab supports CSV rows in oldest-to-newest order, each row: time,open,high,low,close
- Never mix Binomo Crypto IDX and Binance prices: market input needs to match source.
- Rightmost candle is excluded by default; if all CSV rows are already completed candles, uncheck it.

Limitations:
- No live chart connection. No candlestick OCR or accurate screenshot timestamp extraction.
- Screenshot scanner reads red and green pixels; it may fail with changed themes, overlays, indicators, zoom settings or cropped candles.
- Visual quality is not win rate, probability or trading confidence.
- 'EST. UP' / 'EST. DOWN' is only pattern-based visual bias; not a trade recommendation or prediction.
- Time is user-entered; a demo pattern assessment needs >=20 completed candles, adequate quality and manually verified recent time.
- Demo journal tracks a 4 minute cooldown; it does not place trades. Browser local storage holds journal.
- Never use screenshot-based estimates as a reliable basis for 1-minute real-money trades.

Created as a self-contained HTML, CSS and JavaScript app; no external APIs.
