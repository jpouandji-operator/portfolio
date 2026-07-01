# GON Topic Queue — Consolidated
*Canonical file. Last updated: 1 July 2026.*
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
| A01 | "BCEAO Just Ended Wave's Moat. Nobody Has Priced This Yet." | 17/18 | **[DRAFTED — pending JP review — 2026-07-01]** | PI-SPI deadline hook; supersedes earlier Wave/Cameroon version (14/18). Draft covers Instruction 001-01-2024 exclusivity ban + PI-SPI interoperability mandate (Sept 2026 deadline). No COI found (Wave/BCEAO — no current/recent employer or named-partner overlap). See PR for sources and DALL-E prompt. |
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
| A11 | Copia Global War Games Retrospective | 14/18 | Queued | **RECONCILIATION FLAG (2026-07-01): the repo has a committed `copia-global-war-games-retrospective/index.html` (+ header/diagram images), and `sitemap.xml` lists this URL live since lastmod 2026-05-19 — 11 URLs total in sitemap, one more than the 8 articles + 1 draft the session-state file tracks. This contradicts both this queue's "Queued" status and `GON_Master_Session_State.md` (last updated 6 Apr 2026, itself stale per its own 7-day freshness rule), which lists Copia as "NOT STARTED" and the single biggest blocker. The routine could not fetch the live URL directly this run (see PR/email — jpouandji-operator.github.io is blocked by this environment's egress policy), so this is reported, not resolved. JP: please confirm whether Copia is actually live and correct whichever file is stale.** |
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
| A23 | IFC: "The Four Doors Into IFC" | [HOLD — confirm published] | Brief complete as of May 25; checked repo root 2026-07-01 — no matching directory found, so not live. Still needs JP confirmation on brief/publish intent. |
| A24 | Agentforce/Africa gap article | [HOLD — confirm published] | Checked repo root 2026-07-01 — no matching directory found, so not live. Same as A23. |
| A25 | AI agents for Africa - database layer | [HOLD — confirm published] | Checked repo root 2026-07-01 — no matching directory found, so not live. Same as A23. |
| A26 | Lipa Later War Games Retrospective | [HOLD — sources pending] | Blocked on Isaac Hunja + 3 sources |

---

## TRACK B — PMM / TEARDOWNS

*Note: this track is shared with the Applications/job-search project. The Applications project copy of SaaS_Gap_Tracking_Log.md is the source of truth for status. This file is for GON production routing only — do not edit teardown status here without syncing to that file.*

| # | Company | Status | Notes |
|---|---|---|---|
| B01 | Lucca | [PUBLISHED] | Live at /teardowns/lucca-pricing-promises/ as of June 24, 2026. Confirmed 2026-07-01 via teardowns/index.html (only "Teardown 01 · live" card). Flag: this URL is not present in sitemap.xml — routine did not add it (out of scope for this run), but worth an SEO fix. |
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
| 2026-07-01 | (all) | — | — | — | GA4 MCP still not accessible this run (no GA4 connector available in this session). Skipped per protocol — no data guessed. |

---

## CHANGELOG

| Date | Change |
|---|---|
| 30 Jun 2026 | File created. Consolidated from GON_Scan_and_Article_Pipeline_v2.md, GON_Master_Session_State_May18.md, GON_Master_Session_State_May25.md. Previous files retired from active use. |
| 1 Jul 2026 | Routine run: A01 selected and drafted (17/18, no COI). Reconciliation flags added for A11 (Copia — appears live per sitemap, contradicts Queued status and stale Master Session State) and B01 (Lucca teardown live but missing from sitemap.xml). A23/A24/A25 confirmed not live via repo check. GA4 unavailable — skipped, not guessed. Live-site fetch (jpouandji-operator.github.io) blocked by this environment's egress policy this run; reconciliation instead performed against the repository source (sitemap.xml, directory listing, teardowns/index.html) as the best available substitute. |
