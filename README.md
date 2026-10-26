# KnightByrd Nexus — Demand Intelligence (open dataset)

> **The things people are begging for that don't exist yet** — a sanitized, anonymized snapshot of real,
> aggregated demand from the [KnightByrd AI Demand Exchange](https://nexus.knightbyrd.com/demand). Updated weekly. No PII:
> clusters only, never raw submissions.

_Last updated: 2026-10-26T18:00:38.528Z · 183 demand clusters · 183 total requests._

## Why this exists
Most people build supply and hope demand shows up. Nexus flips it: people say what outcome they need and
what they'd pay for it, and the AI clusters + scores that demand. This repo publishes the result as an open
dataset so builders and founders have a **validated backlog** to work from. If you ship something from it,
we'd love a link back — and tell the people who asked.

## The most-wanted right now
| # | Demand | Requests | Opportunity | Willingness-to-pay | Audience |
|---|--------|----------|-------------|--------------------|----------|
| 1 | A third-party mobile keyboard that automatically translitera | 1 | 21 | 0 | Arabic speakers typing on mobile devices |
| 2 | A discreet and hygienic temporary containment solution for u | 1 | 21 | 0 | Sexually active adults |
| 3 | A matchmaking platform that suggests romantic partners based | 1 | 21 | 0 | Singles interested in biological matchmaking |
| 4 | A series of ambient, slow gameplay videos set to Sonic Mania | 1 | 21 | 0 | Sonic fans and ambient video watchers |
| 5 | A game mod porting Don't Starve Together skin styles to Hazb | 1 | 21 | 0 | Don't Starve Together and Hazbin Hotel gamers |
| 6 | An app that allows users to view historical information abou | 1 | 21 | 0 | Local historians, curious residents, urban explorers. |
| 7 | A 5-liter vacuum-sealing container designed to store bulk pa | 1 | 21 | 0 | Home cooks and bakers |
| 8 | A platform that provides curated, reasonably priced product  | 1 | 21 | 0 | Women consumers |
| 9 | A browser tool to autofill Indian government exam applicatio | 1 | 21 | 0 | Indian government exam aspirants |
| 10 | A recipe application that displays only ingredients and inst | 1 | 21 | 0 | home cooks and bakers |
| 11 | A system that provides doctors with visibility into patient  | 1 | 21 | 0 | Medical professionals, healthcare providers. |
| 12 | A centralized dashboard to monitor and manage notifications  | 1 | 21 | 0 | Software engineers running multiple AI coding agents |
| 13 | An automated AI tool that identifies and contacts prospectiv | 1 | 21 | 0 | Domain investors |
| 14 | A tool that automatically extracts high-interest segments fr | 1 | 21 | 0 | Content creators and video editors |
| 15 | A tool that sequentially routes project tasks through the fr | 1 | 21 | 0 | Developers and AI power users |

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
