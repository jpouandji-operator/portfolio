# GON Performance Log
*Appended by the GON production routine each run. Canonical performance history — do not edit by hand except to correct errors.*

---

## 2026-07-01

**GA4 status:** Not accessible this run — no GA4 MCP connector available in this session. No pageview, scroll depth, time-on-page, or click-event data pulled. Do not treat the absence of data as zero traffic.

| Article | Pageviews | Scroll depth | Time on page | Notable events |
|---|---|---|---|---|
| — | GA4 unavailable | GA4 unavailable | GA4 unavailable | GA4 unavailable |

**Reconciliation flags (Step 1, this run):**
- Folders present in repo but not referenced in GON_Topic_Queue_Consolidated.md: `africa-ic-checklist`, `ai-africa-platform-economics`, `airtel-infrastructure-pivot`, `canal-multichoice-platform-economics-africa`, `gon-intelligence` (tool page, not an article), `gon-push` (tool page, not an article), `jumia-pudo-ecommerce-africa`, `mtn-ihs-towers-energy-africa`, `stablecoins-africa-fintech-infrastructure`, `teardowns` (index page), `vas-telcos-investment-delegation`, `world-bank-tenders-africa-distribution`. Flagged as "unregistered, live" — expected, since these predate the consolidated queue file (created 30 Jun 2026), but not resolved here per protocol.
- `teardowns/lucca-pricing-promises` — folder exists and matches queue item B01 (marked PUBLISHED), but this URL is **not present in sitemap.xml**. Sitemap may be stale.
- Queue items A23 ("The Four Doors Into IFC"), A24 (Agentforce/Africa gap article), A25 (AI agents for Africa — database layer) are marked `[HOLD — confirm published]` in the queue but no matching repo folder was found for any of them. Flagged as "registered, not confirmed live" — still appear to be unpublished/held, not a discrepancy requiring urgent action, but noted per protocol.
- A11 (Copia Global War Games Retrospective) — confirmed live, folder exists, in sitemap.xml. Matches queue status of "Published."

Not resolved by the routine — JP reviews.
