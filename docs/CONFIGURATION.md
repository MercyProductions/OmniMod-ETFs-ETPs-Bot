# Configuration reference

Generated from `new-bots/etfs-etps/.env.example`. Copy the template, never another person's `.env`. Template defaults are starting settings, not account/risk recommendations. Read its comments and source before changing a safety control.

| Variable | Template default | Role |
| --- | --- | --- |
| `DISCORD_TOKEN` | your own value; optional when its source is disabled | Private credential from your own account/application. |
| `DISCORD_CLIENT_ID` | your own value; optional when its source is disabled | Your own server/application/account identifier. |
| `DISCORD_GUILD_ID` | your own value; optional when its source is disabled | Your own server/application/account identifier. |
| `DISCORD_CHANNEL_ID` | your own value; optional when its source is disabled | Your own server/application/account identifier. |
| `DISCORD_DELIVERY_MODE` | bot | Runtime, data-source, cost, review or safety setting; see template comments. |
| `SCAN_TIMEOUT_MINUTES` | 20 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `ETF_SOURCE` | fixture | Runtime, data-source, cost, review or safety setting; see template comments. |
| `ETF_SESSION_FILE` | examples/paper-session.json | Runtime, data-source, cost, review or safety setting; see template comments. |
| `ALPACA_API_KEY_ID` | your own value; optional when its source is disabled | Private credential from your own account/application. |
| `ALPACA_API_SECRET_KEY` | your own value; optional when its source is disabled | Private credential from your own account/application. |
| `ETF_ALPACA_FEED` | iex | Runtime, data-source, cost, review or safety setting; see template comments. |
| `ETF_DISCOVERY_MODE` | full-market | Runtime, data-source, cost, review or safety setting; see template comments. |
| `ETF_SYMBOLS` | (empty; review before enabling) | Runtime, data-source, cost, review or safety setting; see template comments. |
| `ETF_UNIVERSE_CACHE_PATH` | .cache/etf-universe.json | Runtime, data-source, cost, review or safety setting; see template comments. |
| `ETF_UNIVERSE_REFRESH_MS` | 21600000 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `ETF_UNIVERSE_MAX_STALE_MS` | 172800000 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `ETF_DISCOVERY_MAX_CANDIDATES` | 200 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `ETF_DISCOVERY_HISTORY_PATH` | .cache/etf-discovery-history | Runtime, data-source, cost, review or safety setting; see template comments. |
| `ETF_ETP_CLASSIFICATION_PATH` | examples/etp-classifications.json | Runtime, data-source, cost, review or safety setting; see template comments. |
| `ETF_ETP_CLASSIFICATION_MAX_AGE_DAYS` | 180 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `ETF_CATALYST_REVIEW_FILE` | examples/catalyst-reviews.json | Runtime, data-source, cost, review or safety setting; see template comments. |
| `ETF_MAX_CATALYST_REVIEW_AGE_MS` | 1800000 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `ETF_CATALYST_SOURCE` | manual | Runtime, data-source, cost, review or safety setting; see template comments. |
| `FINNHUB_API_KEY` | your own value; optional when its source is disabled | Private credential from your own account/application. |
| `PAPER_ACCOUNT_EQUITY_USD` | (empty; review before enabling) | Runtime, data-source, cost, review or safety setting; see template comments. |
| `TRADING_RISK_STATE_PATH` | (empty; review before enabling) | Runtime, data-source, cost, review or safety setting; see template comments. |
| `OMNIMOD_EMERGENCY_STOP` | true | Runtime, data-source, cost, review or safety setting; see template comments. |
| `OMNIMOD_LIVE_TRADING_ENABLED` | false | Runtime, data-source, cost, review or safety setting; see template comments. |
| `ETF_MAX_QUOTE_AGE_MS` | 15000 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `ETF_MAX_OPEN_MARK_AGE_MS` | 300000 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `ETF_TIME_OF_DAY_VOLUME_PROFILE_ENABLED` | false | Runtime, data-source, cost, review or safety setting; see template comments. |
| `ETF_TOD_VOLUME_PROFILE_SYMBOLS_PER_SCAN` | 10 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `ETF_TOD_VOLUME_PROFILE_SYMBOLS_PER_DAY` | 10 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `ETF_TOD_VOLUME_CACHE_DIR` | .cache/etf-tod-volume | Runtime, data-source, cost, review or safety setting; see template comments. |
| `ETF_MAX_SPREAD_PCT` | 0.5 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `ETF_MAX_TRADE_RISK_PCT` | 0.25 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `ETF_MAX_TOTAL_OPEN_RISK_PCT` | 1 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `ETF_MAX_GROSS_EXPOSURE_PCT` | 200 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `ETF_MAX_DAILY_LOSS_PCT` | 1 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `ETF_MIN_REWARD_RISK` | 1.5 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `ETF_ROUND_TRIP_FEES_PER_UNIT` | (empty; review before enabling) | Runtime, data-source, cost, review or safety setting; see template comments. |
| `ETF_SLIPPAGE_RESERVE_PER_UNIT` | (empty; review before enabling) | Runtime, data-source, cost, review or safety setting; see template comments. |
| `SCAN_INTERVAL_MINUTES` | 5 | Runtime, data-source, cost, review or safety setting; see template comments. |
| `DISCORD_WEBHOOK_URL` | (empty; review before enabling) | Runtime, data-source, cost, review or safety setting; see template comments. |
| `PAPER_MONITOR_INTERVAL_SECONDS` | 0 | Runtime, data-source, cost, review or safety setting; see template comments. |
