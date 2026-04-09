# Firebrand Intelligence — Daily Brief Archive

**Live Hub:** [firebrandproject.github.io/daily-briefs](https://firebrandproject.github.io/daily-briefs/)
**Parent Repo:** [firebrand-intelligence](https://github.com/firebrandproject/firebrand-intelligence)
**Classification:** OPEN SOURCE | OSINT COMPILATION

---

## What Is This?

Public-facing daily situation reports (SITREPs) deployed as self-contained HTML apps via GitHub Pages. Every claim has a clickable source link. Every assertion carries a confidence badge.

**Confidence System:**
- **CONFIRMED** — Multi-source verified (GeoConfirmed + official statements)
- **LIKELY** — Credible single source with corroboration
- **CLAIM** — Single party claim, unverified
- **ASSESSMENT** — Analyst judgment

---

## Briefs by Campaign Spine

### Operation Epic Fury (Primary)

| Date | Brief | Version | Key Topics |
|---|---|---|---|
| Apr 9, 2026 | [Daily SITREP](https://firebrandproject.github.io/daily-briefs/2026/04/09/sitrep.html) | v1.4 | Ceasefire Day 2, Hezbollah retaliation, Hormuz restrictions, Islamabad talks, Qassem kill claim |

### Lebanon Theater

| Date | Brief | Version | Key Topics |
|---|---|---|---|
| Apr 9, 2026 | [Lebanon Theater Brief](https://firebrandproject.github.io/daily-briefs/2026/04/09/lebanon.html) | v1.0 | Op Eternal Darkness, 254+ KIA, Hezbollah rocket response |

---

## Repository Structure

```
daily-briefs/
|
|-- index.html              # Hub page (card grid, all briefs)
|-- README.md               # This file
|-- 2026/
|   |-- 04/
|       |-- 09/
|           |-- sitrep.html      # Apr 9 Daily SITREP (v1.4)
|           |-- lebanon.html     # Apr 9 Lebanon Theater Brief
```

**Convention:** `YYYY/MM/DD/[brief-name].html`

New briefs are added daily in date folders. The hub page (`index.html`) is updated with card links to each new brief.

---

## How Briefs Are Built

1. **Research cycle** — 3 parallel web searches across Telegram, X, Reddit, aggregators, official sources
2. **Cross-reference** — Every claim tagged with confidence badge
3. **HTML generation** — Self-contained app with BLUF, stats, tables, timeline, watchpoints, clickable sources
4. **Deploy** — Commit to `YYYY/MM/DD/` folder, update hub
5. **Autonomous updates** — v1.1, v1.2, etc. as breaking news develops

---

## Campaign Spine Cross-Reference

Each brief maps to a campaign spine in the [firebrand-intelligence](https://github.com/firebrandproject/firebrand-intelligence) repo:

| Brief Topic | Campaign Spine | Spine File |
|---|---|---|
| Daily SITREP (all-theater) | Operation Epic Fury | `SPINE_Operation-Epic-Fury.md` |
| Lebanon Theater | Epic Fury + Nakba | `SPINE_Operation-Epic-Fury.md` / `SPINE_Nakba.md` |
| Hormuz / Maritime | Gulf Realignment | `SPINE_Gulf-Realignment.md` |
| Houthi / Yemen | Epic Fury (sub-theater) | `SPINE_Operation-Epic-Fury.md` |
| Ceasefire / Diplomacy | Epic Fury Phase 4 | `SPINE_Operation-Epic-Fury.md` |

---

*Firebrand Intelligence Daily Brief System | CAWL D+41 reorganization*
