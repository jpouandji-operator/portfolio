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
| A01 | "BCEAO Just Ended Wave's Moat. Nobody Has Priced This Yet." | 17/18 | **NEXT — PREMISE FLAGGED, DO NOT DRAFT AS-IS** | PI-SPI deadline hook; supersedes earlier Wave/Cameroon version (14/18). Timeliness is urgent — write this week. **13 Jul 2026 routine run:** search-snippet research (WebFetch was down all-domains this session, could not independently verify) suggests the headline premise conflates two separate BCEAO instruments — "PI-SPI" appears to mean "Plateforme Interopérable du Système de Paiement Instantané" (an interoperability rail with its own connection deadline, currently ~Sept 30 2026), not a PSP-licensing instruction. The actual licensing change (ending mandatory bank-sponsorship for fintechs, ~30 new fintechs licensed) is under Instruction N°001-01-2024, a separate track. Multiple sources (Jeune Afrique, SenePlus, unverified this session) suggest Wave may currently be *absent* from PI-SPI rather than newly subjected to it — the opposite mechanism from "BCEAO ended Wave's moat." Needs a primary-source pass directly on bceao.int (and resolution of the pre-existing Article 18 vs Article 14 discrepancy already flagged in GON_Benchmark_Repository_v3.md line ~1017) before this is drafted. Do not treat prior 17/18 score as validated until re-scored against corrected facts. |
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
| 13 Jul 2026 | — | — | — | — | GA4 still not connected (no Analytics connector in workspace — only Gmail connected). Airtable unreachable this run (proxy returned 403 policy denial on api.airtable.com). WebFetch returned 403 on every URL tested this session, including control domains (example.com) — systemic tool outage, not a site block. No article drafted this run; see A01 note above and CHANGELOG. |

---

## RECONCILIATION FLAGS (13 Jul 2026 routine run)

**Unregistered in sitemap.xml but live in repo (folders exist, pages render):**
- `airtel-infrastructure-pivot/` — published per GON_Master_Session_State.md (23 Feb 2026), not in sitemap.xml
- `vas-telcos-investment-delegation/` — published per GON_Master_Session_State.md (13 Jan 2026), not in sitemap.xml
- `gon-intelligence/` — internal tool page ("GON Intelligence"), not an article, not in sitemap
- `gon-push/` — internal tool page ("GON Push Tool"), not an article, not in sitemap

**Registered in sitemap.xml but NOT found as a repo folder (broken/missing):**
- `lipa-later-war-games-retrospective/` — listed in sitemap.xml, no matching folder in repo root (queue lists A26 as `[HOLD — sources pending]`, consistent with not-yet-published, but the sitemap entry implies it's live — discrepancy)
- `africa-market-entry/` — listed in sitemap.xml, no matching folder in repo root (Master Session State lists this as "Draft only — Not published")

**Queue items marked HOLD — confirm published (A23 IFC, A24 Agentforce, A25 AI agents/database layer):** no matching folders found in repo for any of the three — still unconfirmed, remain on HOLD.

**A11 Copia Global War Games Retrospective:** folder exists (`copia-global-war-games-retrospective/`), matches sitemap entry — confirmed live, queue status "Published" is consistent.

JP to review and resolve — routine does not auto-resolve per protocol.

---

## CHANGELOG

| Date | Change |
|---|---|
| 30 Jun 2026 | File created. Consolidated from GON_Scan_and_Article_Pipeline_v2.md, GON_Master_Session_State_May18.md, GON_Master_Session_State_May25.md. Previous files retired from active use. |
| 13 Jul 2026 | Routine run: no article drafted. Blocked on (1) Airtable unreachable — proxy 403 policy denial, (2) WebFetch returning 403 on all tested URLs this session including control domains — systemic outage, no live primary-source research possible, (3) GA4 still not connected. Independent research (search-snippets only, not fetched/verified) raised a material accuracy concern on A01's premise — see note under A01 above. Reconciliation flags from Step 1 logged above. No files pushed to main; PR opened against claude/ branch with these notes only, no article. |

Airtable token rotated — date unknown, confirmed by JP 1 Jul 2026. New token stored in Routine environment.
