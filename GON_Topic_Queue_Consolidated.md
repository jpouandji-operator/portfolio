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
| A01 | "BCEAO Just Ended Wave's Moat. Nobody Has Priced This Yet." | 17/18 | **NEXT — FLAGGED, see Reconciliation 2026-09-07** | PI-SPI deadline hook; supersedes earlier Wave/Cameroon version (14/18). Routine's 2026-09-07 run found this topic appears already live under a different headline — see Reconciliation Flags section below. JP to confirm before this is selected again. |
| A02 | "Egypt Just Closed the Consumer Finance Door" | 16/18 | **[DRAFTED — pending JP review — 2026-09-07]** | Drafted as "Egypt Closed the Consumer Finance Door. The Central Bank Opened a Different One." — see PR opened 2026-09-07. |
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
| B02 | Payplug | **FLAGGED, see Reconciliation 2026-09-07** | Routine's 2026-09-07 run found /teardowns/payplug-acquisition-gap/ already live per sitemap.xml (lastmod 2026-07-09). Queue still shows "Queued" — JP to confirm and update. |
| B03 | Pluxee | **FLAGGED, see Reconciliation 2026-09-07** | Routine's 2026-09-07 run found /teardowns/pluxee-world-of-opportunities/ already live per sitemap.xml (lastmod 2026-07-14). Queue still shows "Queued" — JP to confirm and update. |
| B04 | Spendesk or Pennylane | Queued | Choose one — decision pending |
| B05 | Aircall | Queued | |

---

## PERFORMANCE LOG (updated by routine each run)

*GA4 data appended here weekly. Used by the routine to adjust topic scoring.*

| Date | Article | Pageviews | Scroll depth | Time on page | Notes |
|---|---|---|---|---|---|
| — | — | — | — | — | GA4 MCP not yet connected — log starts once connected |
| 2026-09-07 | (all) | — | — | — | GA4 unavailable this run — no GA4 MCP connector present in session (only Google Calendar and Google Drive connectors available). See GON_Performance_Log.md. |

---

## RECONCILIATION FLAGS — 2026-09-07 routine run

*Step 1 of the routine cross-checked repo folders, sitemap.xml, and this queue. Per protocol, discrepancies are reported, not resolved — JP reviews and updates statuses.*

**Queue entries whose topic appears to already be live in the repo, but whose status here was not updated:**
- **A01** ("BCEAO Just Ended Wave's Moat...", marked NEXT, 17/18) — repo folder `bceao-pi-spi-wave-regulatory-navigation-africa/` is live (sitemap lastmod 2026-07-13) with headline "The BCEAO Blinked. Wave Didn't Move." — same subject (BCEAO PI-SPI / Wave), different published headline. This routine did NOT select A01 as this week's topic because of this. Recommend JP confirm and mark A01 `[PUBLISHED]` if it is the same article, or clarify how it differs if a genuinely separate angle is still intended.
- **B02** (Payplug) and **B03** (Pluxee) — both appear live per sitemap.xml (`/teardowns/payplug-acquisition-gap/`, lastmod 2026-07-09; `/teardowns/pluxee-world-of-opportunities/`, lastmod 2026-07-14) despite queue showing "Queued." Recommend JP confirm and update Track B status, and sync with the Applications project's SaaS_Gap_Tracking_Log.md per this file's own note.

**Repo folders/teardowns live but not tracked anywhere in this queue ("unregistered, live"):**
- `teardowns/lumapps-enterprise-selling/` — live per sitemap (lastmod 2026-07-07), no queue entry.
- `teardowns/sociabble-feature-portfolio/` — live per sitemap (lastmod 2026-07-16), no queue entry.
- `door2-partner-checklist/` — present in repo, but sitemap.xml carries an explicit comment that it is intentionally NOT live yet (private preview). Folder content reads "MOCKUP v2." No corresponding queue entry under this name. Flagging only — not treated as live given the sitemap's own comment overrides folder presence.

**Held items possibly already resolved (repo evidence, not confirmative):**
- **A23** (IFC "Four Doors", HOLD — confirm published) — repo folder `ifc-africa-investment-access/` is live (sitemap lastmod 2026-07-22), title "IFC Africa Investment: The Four Doors Most Founders Never Find." This matches A23's description closely. Recommend JP confirm and mark `[PUBLISHED]`.
- **A24/A25** (Agentforce/Africa gap; AI agents database layer, both HOLD — confirm published) — no folder matching "Agentforce" was found. `ai-africa-platform-economics/` is live (title: "AI in Africa: Beyond the Hype, Who is Actually Figuring It Out?") but this reads as a distinct, broader AI-in-Africa piece, not clearly either A24 or A25. Left as HOLD — could not confirm either way.

No action was taken on any of the above beyond this flag. Queue entries for A01, B02, B03 were left with their existing Status text (only annotated) rather than changed, since resolving requires JP's confirmation that the repo article is in fact the same piece.

---

## CHANGELOG

| Date | Change |
|---|---|
| 2026-09-07 | Routine run: selected A02 (Egypt consumer finance / FRA-CBE regulatory piece), drafted, PR opened. GA4 unavailable (no MCP connector). Airtable unreachable (network egress policy blocks api.airtable.com — see PR for detail). Added Reconciliation Flags section above per Step 1 findings. |
| 30 Jun 2026 | File created. Consolidated from GON_Scan_and_Article_Pipeline_v2.md, GON_Master_Session_State_May18.md, GON_Master_Session_State_May25.md. Previous files retired from active use. |

Airtable token rotated — date unknown, confirmed by JP 1 Jul 2026. New token stored in Routine environment.
