# KnightByrd Nexus — Demand Intelligence (open dataset)

> **The things people are begging for that don't exist yet** — a sanitized, anonymized snapshot of real,
> aggregated demand from the [KnightByrd AI Demand Exchange](https://nexus.knightbyrd.com/demand). Updated weekly. No PII:
> clusters only, never raw submissions.

_Last updated: 2026-08-24T18:00:39.388Z · 32 demand clusters · 32 total requests._

## Why this exists
Most people build supply and hope demand shows up. Nexus flips it: people say what outcome they need and
what they'd pay for it, and the AI clusters + scores that demand. This repo publishes the result as an open
dataset so builders and founders have a **validated backlog** to work from. If you ship something from it,
we'd love a link back — and tell the people who asked.

## The most-wanted right now
| # | Demand | Requests | Opportunity | Willingness-to-pay | Audience |
|---|--------|----------|-------------|--------------------|----------|
| 1 | A platform to connect technical and non-technical founders w | 1 | 21 | 0 | Part-time entrepreneurs and side-project builders |
| 2 | A platform that provides curated, reasonably priced product  | 1 | 21 | 0 | Women consumers |
| 3 | An app that calculates and tracks the real daily cost-per-us | 1 | 21 | 0 | Budget-conscious consumers and minimalists |
| 4 | A tool that sequentially routes project tasks through the fr | 1 | 21 | 0 | Developers and AI power users |
| 5 | A centralized system to manage and track customer orders pla | 1 | 21 | 0 | Social media and chat-based sellers |
| 6 | An automated AI tool that identifies and contacts prospectiv | 1 | 21 | 0 | Domain investors |
| 7 | A platform to log, track, and alert job applicants about emp | 1 | 21 | 0 | Active job seekers |
| 8 | A live on-screen text and image translation tool for PC to e | 1 | 21 | 0 | PC users reading image-based foreign language ebooks |
| 9 | An educational platform delivering structured, bite-sized co | 1 | 21 | 0 | Self-paced learners and newsletter subscribers |
| 10 | A computer recommendation tool that matches laptops to users | 1 | 21 | 0 | Laptop and computer buyers |
| 11 | A third-party mobile keyboard that automatically translitera | 1 | 21 | 0 | Arabic speakers typing on mobile devices |
| 12 | A rating interface that prominently integrates statistical c | 1 | 21 | 0 | Online shoppers and review platforms |
| 13 | A streaming feature that creates custom scheduled linear cha | 1 | 21 | 0 | Streaming service subscribers |
| 14 | A web application that generates theoretical etymological ro | 1 | 21 | 0 | Linguistics enthusiasts and writers |
| 15 | A browser extension that automatically detects and flags AI- | 1 | 21 | 0 | LinkedIn users |

## Files
- [`demand.json`](./demand.json) — full snapshot, structured.
- [`demand.csv`](./demand.csv) — same data, spreadsheet-friendly.

## Field guide
| Field | Meaning |
|-------|---------|
| `demand` | The clustered unmet need. |
| `request_count` | How many distinct people asked for it. |
| `opportunity_score` | 0–100 — demand × willingness-to-pay × feasibility. |
| `wtp_score` | 0–100 — measured willingness to pay. |
| `paying_now_count` | How many already pay for a workaround. |
| `top_audience` | Who is asking, most commonly. |
| `status` | Where it sits in the pipeline. |

## Live API (no download, always current)
- Trending demand: `https://nexus.knightbyrd.com/api/public/demand/trending`
- Build opportunities: `https://nexus.knightbyrd.com/api/public/demand/opportunities`
- Foresight signals: `https://nexus.knightbyrd.com/api/public/foresight`

## Add your own demand
Something you wish existed? **[Tell us what to build →](https://nexus.knightbyrd.com/ideas)** If we build it, you'll hear about it.

---
Free to use with attribution. Data © KnightByrd Tech LLC. Please link back to https://nexus.knightbyrd.com.
