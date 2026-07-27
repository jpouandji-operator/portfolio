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
| A01 | "BCEAO Just Ended Wave's Moat. Nobody Has Priced This Yet." | 17/18 | **NEXT** | PI-SPI deadline hook; supersedes earlier Wave/Cameroon version (14/18). Timeliness is urgent — write this week. |
| A02 | "Egypt Just Closed the Consumer Finance Door" | 16/18 | [DRAFTED — pending JP review — 2026-07-27] | Published as "Egypt Closed the Consumer Finance Door in 2024. The Market Didn't Notice Until Now." — PR open. See routine close-out 2026-07-27 for reconciliation flags (A01 appears already covered by live bceao-pi-spi-wave-regulatory-navigation-africa article) and manual sourcing flags (WebFetch blocked this run; all facts sourced via search-snippet synthesis only). |
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
| A23 | IFC: "The Four Doors Into IFC" | [HOLD — confirm published] | Brief complete as of May 25; may already be live — routine to verify in Step 1 before treating as queued |
| A24 | Agentforce/Africa gap article | [HOLD — confirm published] | Same — brief complete May 25, check live status |
| A25 | AI agents for Africa - database layer | [HOLD — confirm published] | Same |
| A26 | Lipa Later War Games Retrospective | [HOLD — sources pending] | Blocked on Isaac Hunja + 3 sources |

---

## TRACK B — PMM / TEARDOWNS

*Note: this track is shared with the Applications/job-search project. The Applications project copy of SaaS_Gap_Tracking_Log.md is the source of truth for status. This file is for GON production routing only — do not edit teardown status here without syncing to that file.*

| # | Company | Status | Notes |
|---|---|---|---|
| B01 | Lucca | [PUBLISHED] | Live at /teardowns/lucca-pricing-promises/ as of June 24, 2026 |
| B02 | Payplug | Queued | Start here for next Teardown run |
| B03 | Pluxee | Queued | |
| B04 | Spendesk or Pennylane | Queued | Choose one — decision pending |
| B05 | Aircall | Queued | |

---

## PERFORMANCE LOG (updated by routine each run)

*GA4 data appended here weekly. Used by the routine to adjust topic scoring.*

| Date | Article | Pageviews | Scroll depth | Time on page | Notes |
|---|---|---|---|---|---|
| — | — | — | — | — | GA4 MCP not yet connected — log starts once connected |
| 2026-07-27 | — | — | — | — | GA4 connector not available in this session — see GON_Performance_Log.md |

---

## RECONCILIATION FLAGS — reported, not resolved (JP reviews)

*Per Step 1 of the routine: repo vs. sitemap vs. this queue, cross-checked 2026-07-27. Flagged, not auto-corrected.*

- **A01** ("BCEAO Just Ended Wave's Moat...", marked NEXT, 17/18) appears to already be covered by the live article at `/bceao-pi-spi-wave-regulatory-navigation-africa/` ("The BCEAO Blinked. Wave Didn't Move.", published 2026-07-13, in sitemap.xml) — same PI-SPI/Wave/BCEAO subject. Queue status was not updated after that article went live. Routine selected A02 instead this run rather than risk a duplicate. JP to confirm whether A01 should be marked PUBLISHED/superseded or whether a genuinely distinct angle remains.
- **A23** (IFC "Four Doors", `[HOLD — confirm published]`) — `ifc-africa-investment-access/` is live in the repo and in sitemap.xml (lastmod 2026-07-22). Confirmed published; HOLD status appears stale.
- **A21** (Energy article, `[HOLD — verification pending]`) — `mtn-ihs-towers-energy-africa/` is already live and in sitemap.xml, covering telecom-energy (MTN/IHS Towers). Unclear if A21 is a duplicate angle or a distinct energy topic — not resolved here.
- **B02** (Payplug, "Queued — start here") and **B03** (Pluxee, "Queued") — both are already live: `teardowns/payplug-acquisition-gap/` and `teardowns/pluxee-world-of-opportunities/` are in the repo and in sitemap.xml. Track B status table is stale.
- **teardowns/lumapps-enterprise-selling/** and **teardowns/sociabble-feature-portfolio/** — live in repo + sitemap, not referenced anywhere in this file's Track B table. Unregistered, live.
- **gon-intelligence/** and **gon-push/** — folders live in repo, not in sitemap.xml, not in this queue. Appear to be tools/database pages rather than articles (titles: "GON Intelligence: Africa Deal Research Database", "GON Push Tool"), but flagged per protocol since they're unregistered.
- **A24/A25** (Agentforce/Africa gap, AI agents database layer, both `[HOLD — confirm published]`) — no matching repo folders found. Registered, not confirmed live. Consistent with existing HOLD status.

---

## CHANGELOG

| Date | Change |
|---|---|
| 30 Jun 2026 | File created. Consolidated from GON_Scan_and_Article_Pipeline_v2.md, GON_Master_Session_State_May18.md, GON_Master_Session_State_May25.md. Previous files retired from active use. |
| 27 Jul 2026 | Routine run: A02 (Egypt consumer finance) drafted, PR opened. Added Reconciliation Flags section (Step 1 output). Airtable unreachable this run (network policy blocked api.airtable.com, HTTP 403 at the proxy) — Step 4/Step 10 skipped, see close-out report. GA4 connector not available this session. |

Airtable token rotated — date unknown, confirmed by JP 1 Jul 2026. New token stored in Routine environment.
