# App Store API — iOS App Data, Reviews, Charts & Search

A REST API for the Apple App Store by [AppSigma](https://appsigma.io). Look up iOS apps, pull reviews and ratings, track chart positions and price changes, browse Apple's editorial content and in-app events, and run free-text search — all as clean JSON over HTTPS.

No scraping, no HTML parsing, no headless browsers — a stable, versioned contract on top of frequently updated Apple data.

## Try it — no signup

```bash
curl -H "X-API-Key: demo" "https://api.appsigma.io/v1/applications/544007664"
```

The public `demo` key runs real requests against real App Store data — not mocks (scoped to a curated slice, free and unbilled).

## What you can build

- **Competitive intelligence** — pricing, ratings, version cadence, chart movement across countries
- **ASO tooling** — keyword rankings, review sentiment, metadata changes
- **Review monitoring** — new reviews with score, country, version, and developer responses
- **Price-drop alerts** — historical price changes per app
- **Market dashboards** — Top Free / Paid / Grossing charts with daily history

## Links

- 📖 **API documentation & live playground:** [docs.appsigma.io](https://docs.appsigma.io)
- 🔑 **Get an API key:** [appsigma.io](https://appsigma.io)

---

Made by [AppSigma](https://appsigma.io)
