# GON Performance Log

*Appended weekly by the GON production routine. GA4 data (property G-CWB7VQ56XE), pulled for the trailing 7 days, or "unavailable" with reason if the connector could not be reached that run.*

---

## 2026-08-10

**GA4 status:** Unavailable. No GA4 MCP connector is present in this session's tool set (searched via ToolSearch for analytics/GA4/pageview tools — none found). Per routine instructions, skipped rather than guessed at data.

| Article | Pageviews | Scroll depth | Time on page | Notable events |
|---|---|---|---|---|
| — | — | — | — | GA4 not accessible this run |

**Airtable status:** Unavailable. `api.airtable.com` is blocked at the network egress proxy level in this session (`connect_rejected`, gateway 403 on CONNECT) — not an Airtable-side auth error, but the effect is the same: no database read/write this run. Continued without database context per routine instructions.
