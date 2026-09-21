# GON Topic Queue — Consolidated
*Canonical file. Last updated: 30 June 2026.*
*Source of truth for the GON production routine. Update this file at the end of every session or routine run — nowhere else.*

---

## HOW THIS FILE WORKS

- The GON production routine reads this file every Monday to select the week's topic
- After drafting, the routine marks the selected item as `[DRAFTED — pending JP review — YYYY-MM-DD]`
- After JP merges the PR and the article goes live, update status to `[PUBLISHED — YYYY-MM-DD]`
- Items marked `[HOLD]` are skipped by the routine automatically
- Items marked `[DEAD]` are ignored and can be cleaned up quarterly

---

## SCORING RUBRIC (embedded — routine uses this directly)

Score each item 1–3 on six criteria. Max: 18. Minimum to develop: 12.

| Criterion | 1 | 2 | 3 |
|---|---|---|---|
| Thesis non-obviousness | Findable in 20min Google search | Requires operator experience to interpret | Contradicts conventional wisdom |
| Timeliness | Evergreen | Relevant now, 3–6 month window | Urgent, 4–8 week window |
| Source quality | Directional only | Mix primary + secondary | Primary institutional sources verified |
| Operator edge | Any analyst could write it | Benefits from JP's experience | Requires 12yrs inside distribution stack |
| Sector range contribution | Same sector as recent articles | Adjacent | New sector |
| VC behavior change potential | Interesting | Useful, VCs reference it | Decision-changing |

**Conflict-of-interest gate:** before selecting any item, check whether it references a current/recent employer, client, or named partner. If yes → mark `[HOLD — COI]` and select next item.

---

## TRACK A — VC/PE ARTICLES

### Tier 1 (score 15–18 — write immediately)

| # | Title | Score | Status | Notes |
|---|---|---|---|---|
| A01 | "BCEAO Just Ended Wave's Moat. Nobody Has Priced This Yet." | 17/18 | [DRAFTED — pending JP review — 2026-09-21] | PI-SPI deadline hook; supersedes earlier Wave/Cameroon version (14/18). Drafted as "BCEAO's Deadline Ends Wave's Moat in Nine Days. Nobody Has Priced It." — Sept 30, 2026 deadline is the new event (not the June/July extension already covered in the live BCEAO article). See PR for full sourcing and the overlap note with the July 13 article. |
| A02 | "Egypt Just Closed the Consumer Finance Door" | 16/18 | Queued | |
| A03 | "The 41% Number That Changes Everything About African VC" | 16/18 | Queued | |
| A04 | "Kenya Didn't Beat Nigeria. The Naira Did." | 15/18 | Queued | |
| A05 | "Rwanda Is the Regulatory Hub Nobody Noticed" | 15/18 | Queued | |
| A06 | "Ivory Coast Has 23 Deals. Senegal Has Wave." | 15/18 | Queued | |
| A07 | Pressure Test #1: The Database Architecture | 15/18 | Queued | Different format — operator stress-test piece |
| A08 | Moniepoint Kenya acquisition (Sumac Microfinance Bank as entry template) | 15/18 | Queued | Memory-only — no source file found; routine must verify primary sources before developing |

### Tier 2 (score 12–14 — develop within 4 weeks)

| # | Title | Score | Status | Notes |
|---|---|---|---|---|
| A09 | "WAEMU Just Ran a Regulatory Selection Exercise on Your Portfolio" | 14/18 | Queued | |
| A10 | "Wave in Cameroon Is Not a Fintech Story" | 14/18 | Queued | May overlap with A01 — routine to check before developing |
| A11 | Copia Global War Games Retrospective | 14/18 | Published | HTML file exists in repo (`copia-global-war-games-retrospective-index.html`) — confirm if already published |
| A12 | "The App You Can't Delete" (iGaming/web vs native) | 13/18 | Queued | |
| A13 | "CEMAC Is Not WAEMU With Oil" | 13/18 | Queued | |

### Unscored — apply rubric before developing

| # | Title | Notes |
|---|---|---|
| A14 | "The CFA Franc's Euro Peg Was a Bug. In 2026 It Became a Feature." | Not yet scored |
| A15 | "Ivory Coast Is Building a Cocoa Data Moat. Nobody Is Valuing It Correctly." | Not yet scored |
| A16 | "Why the Next African Unicorn Will Be Acquired by a Nigerian Bank" | Not yet scored |
| A17 | "AI in Francophone Africa: The Moat Is in the Data Layer, Not the Model" | Not yet scored |
| A18 | Ride-hailing Francophone Africa (Yango/Heetch/Uber) | Verify Yango Cameroun status before developing |
| A19 | Agritech sector deep dive | Next sector gap after Energy |
| A20 | Africa Forward Webinar GON content piece | Format TBD |

### Held

| # | Title | Status | Reason |
|---|---|---|---|
| A21 | Energy article | [HOLD — verification pending] | Backend verification still needed — held across multiple sessions |
| A22 | Ayoba / Feature-First Fallacy | [HOLD — COI] | Employer conflict of interest |
| A23 | IFC: "The Four Doors Into IFC" | **[DISCREPANCY — confirm]** CONFIRMED LIVE at /ifc-africa-investment-access/ (in sitemap, lastmod 2026-07-22) | Routine confirmed this is published. JP to update status to [PUBLISHED] if correct. |
| A24 | Agentforce/Africa gap article | [HOLD — confirm published] | No matching repo folder found this run — still unconfirmed either way |
| A25 | AI agents for Africa - database layer | [HOLD — confirm published] | No matching repo folder found this run — still unconfirmed either way |
| A26 | Lipa Later War Games Retrospective | **[DISCREPANCY — confirm]** CONFIRMED LIVE at /gon-wargames-lipalater/ (in sitemap, lastmod 2026-07-22) despite HOLD status | Folder exists and is indexed live, but queue still shows this blocked on Isaac Hunja + 3 sources. Either it published without the routine's queue being updated, or this is a different/older version of the piece. JP to confirm and reconcile. |

---

## TRACK B — PMM / TEARDOWNS

*Note: this track is shared with the Applications/job-search project. The Applications project copy of SaaS_Gap_Tracking_Log.md is the source of truth for status. This file is for GON production routing only — do not edit teardown status here without syncing to that file.*

| # | Company | Status | Notes |
|---|---|---|---|
| B01 | Lucca | [PUBLISHED] | Live at /teardowns/lucca-pricing-promises/ as of June 24, 2026 |
| B02 | Payplug | **[DISCREPANCY — confirm]** Repo/sitemap show this LIVE at /teardowns/payplug-acquisition-gap/ already | Queue said "Start here for next Teardown run" but the folder and sitemap entry already exist — routine did not draft this. JP to confirm status and correct this row. |
| B03 | Pluxee | **[DISCREPANCY — confirm]** Repo/sitemap show this LIVE at /teardowns/pluxee-world-of-opportunities/ already | Same issue as B02 — marked Queued but already published. JP to confirm and correct. |
| B04 | Spendesk or Pennylane | Queued | Choose one — decision pending. Next real candidate for a Teardown run given B02/B03 are already live. |
| B05 | Aircall | Queued | |

---

## PERFORMANCE LOG (updated by routine each run)

*GA4 data appended here weekly. Used by the routine to adjust topic scoring.*

| Date | Article | Pageviews | Scroll depth | Time on page | Notes |
|---|---|---|---|---|---|
| — | — | — | — | — | GA4 MCP not yet connected — log starts once connected |

---

## CHANGELOG

| Date | Change |
|---|---|
| 30 Jun 2026 | File created. Consolidated from GON_Scan_and_Article_Pipeline_v2.md, GON_Master_Session_State_May18.md, GON_Master_Session_State_May25.md. Previous files retired from active use. |
| 21 Sep 2026 | Routine run. Selected A01, drafted as "BCEAO's Deadline Ends Wave's Moat in Nine Days." Marked A01 DRAFTED. Flagged discrepancies: A23 and A26 confirmed live despite HOLD status; B02 (Payplug) and B03 (Pluxee) confirmed live despite Queued status. Also found several repo folders live and indexed (ai-africa-platform-economics, airtel-infrastructure-pivot, canal-multichoice-platform-economics-africa, gon-wargames-sendy, gon-wargames-wave, jumia-pudo-ecommerce-africa, mtn-ihs-towers-energy-africa, stablecoins-africa-fintech-infrastructure, vas-telcos-investment-delegation, world-bank-tenders-africa-distribution, teardowns/lumapps-enterprise-selling, teardowns/sociabble-feature-portfolio) that have no corresponding row in this queue at all — not necessarily a problem, just unregistered. Full detail in PR #TBD. GA4 MCP connector not available this run. Airtable blocked by network egress policy this run (not an auth failure) — see PR for detail. |

Airtable token rotated — date unknown, confirmed by JP 1 Jul 2026. New token stored in Routine environment.
Note 21 Sep 2026: Airtable calls this run were blocked at the network layer (egress proxy policy denial on api.airtable.com, HTTP 403 at the proxy gateway) before any request reached Airtable's API, so this is not a token/auth issue — token status could not be tested.
