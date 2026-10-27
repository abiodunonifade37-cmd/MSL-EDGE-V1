# MSL Edge Flow V1.0

A mobile-first, dark, local-first PWA prototype for a liquidity-based trading workflow.

## Included modules
- Overview dashboard with journal-derived stats
- Illustrative candlestick chart
- Liquidity map and model-completeness checklist
- Footprint-inspired ladder, CVD and volume profile display
- Bar-by-bar synthetic replay lab
- Trade journal with screenshot upload, checklist, filtering, edit/delete
- Performance analytics (expectancy, profit factor, average win, drawdown, setup breakdown)
- Liquidity Academy curriculum with completion tracking
- Reversal/continuation playbook
- Generic risk sizing calculator
- JSON backup/import and local data reset
- PWA manifest and offline service worker

## Important limitations
This version does **not** connect to live market data, broker accounts, or order execution. The candles, footprint, CVD and volume profile are synthetic examples. True bid/ask order flow requires a compatible trade/tick data provider and a clearly defined aggressor-side methodology. The risk calculator is generic; instrument-specific pip/tick/contract values must be verified.

Data is stored in this browser's localStorage. Export backups regularly. Large screenshot attachments can hit browser storage limits.

## Run locally
Open `index.html` in a modern browser for basic functionality. For PWA/service-worker installation, serve the folder over HTTPS or localhost.

## Deploy on GitHub Pages
1. Extract the ZIP.
2. Put the contents of this folder at the root of the repository (so `index.html` is at repository root).
3. Commit and push.
4. In GitHub, open **Settings → Pages**, select **Deploy from a branch**, choose your main branch and `/ (root)`.
5. Open the Pages URL and refresh. If an old README or version is cached, hard refresh or clear the site's cached files.

## Data safety
Use **Settings → Export complete backup** before clearing browser data, changing devices, or deploying a replacement. This prototype does not automatically sync data between devices.
