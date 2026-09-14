# KnightByrd Nexus — Demand Intelligence (open dataset)

> **The things people are begging for that don't exist yet** — a sanitized, anonymized snapshot of real,
> aggregated demand from the [KnightByrd AI Demand Exchange](https://nexus.knightbyrd.com/demand). Updated weekly. No PII:
> clusters only, never raw submissions.

_Last updated: 2026-09-14T18:00:38.264Z · 56 demand clusters · 56 total requests._

## Why this exists
Most people build supply and hope demand shows up. Nexus flips it: people say what outcome they need and
what they'd pay for it, and the AI clusters + scores that demand. This repo publishes the result as an open
dataset so builders and founders have a **validated backlog** to work from. If you ship something from it,
we'd love a link back — and tell the people who asked.

## The most-wanted right now
| # | Demand | Requests | Opportunity | Willingness-to-pay | Audience |
|---|--------|----------|-------------|--------------------|----------|
| 1 | A spoiler-prevention setting for streaming platforms that hi | 1 | 21 | 0 | streaming service subscribers |
| 2 | A tool to bulk unfollow or remove LinkedIn connections to cl | 1 | 21 | 0 | LinkedIn sales professionals and power users |
| 3 | A navigation app tailored for scenic drives featuring visibl | 1 | 21 | 0 | Road trippers and leisure drivers |
| 4 | A verification app that provides dependable proof that appli | 1 | 21 | 0 | individuals with departure-related memory anxiety or checking habits |
| 5 | Detachable decorative accessories designed to be worn on the | 1 | 21 | 0 | fashion enthusiasts |
| 6 | A job search platform that allows filtering listings across  | 1 | 21 | 0 | Job seekers open to relocating to multiple target areas |
| 7 | A reliable automated receptionist system to handle inbound c | 1 | 21 | 0 | Small business owners |
| 8 | A way to programmatically access city and community event ca | 1 | 21 | 0 | Developers building local event discovery tools |
| 9 | A tool that condenses lengthy AI chat logs and artifacts int | 1 | 21 | 0 | Knowledge workers and software teams using AI tools |
| 10 | A web application that generates theoretical etymological ro | 1 | 21 | 0 | Linguistics enthusiasts and writers |
| 11 | A discreet and hygienic temporary containment solution for u | 1 | 21 | 0 | Sexually active adults |
| 12 | A music streaming interface offering granular algorithmic co | 1 | 21 | 0 | Music streaming power users |
| 13 | Modular and upgradeable powered wearable assistive devices w | 1 | 21 | 0 | Users of powered wearable and assistive devices |
| 14 | Instantly preview and stream CD audio by scanning album cove | 1 | 21 | 0 | CD collectors and thrift store shoppers |
| 15 | A platform to connect technical and non-technical founders w | 1 | 21 | 0 | Part-time entrepreneurs and side-project builders |

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
