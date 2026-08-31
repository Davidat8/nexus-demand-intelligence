# KnightByrd Nexus — Demand Intelligence (open dataset)

> **The things people are begging for that don't exist yet** — a sanitized, anonymized snapshot of real,
> aggregated demand from the [KnightByrd AI Demand Exchange](https://nexus.knightbyrd.com/demand). Updated weekly. No PII:
> clusters only, never raw submissions.

_Last updated: 2026-08-31T18:00:38.618Z · 38 demand clusters · 38 total requests._

## Why this exists
Most people build supply and hope demand shows up. Nexus flips it: people say what outcome they need and
what they'd pay for it, and the AI clusters + scores that demand. This repo publishes the result as an open
dataset so builders and founders have a **validated backlog** to work from. If you ship something from it,
we'd love a link back — and tell the people who asked.

## The most-wanted right now
| # | Demand | Requests | Opportunity | Willingness-to-pay | Audience |
|---|--------|----------|-------------|--------------------|----------|
| 1 | A third-party mobile keyboard that automatically translitera | 1 | 21 | 0 | Arabic speakers typing on mobile devices |
| 2 | A rating interface that prominently integrates statistical c | 1 | 21 | 0 | Online shoppers and review platforms |
| 3 | A platform to log, track, and alert job applicants about emp | 1 | 21 | 0 | Active job seekers |
| 4 | An AI-powered cognitive training app that generates adaptive | 1 | 21 | 0 | Caregivers and individuals with cognitive decline |
| 5 | A platform to connect technical and non-technical founders w | 1 | 21 | 0 | Part-time entrepreneurs and side-project builders |
| 6 | An effortless way to save and organize potential gift ideas  | 1 | 21 | 0 | Gift shoppers |
| 7 | A way to automatically compile and edit multiple raw video c | 1 | 21 | 0 | Casual smartphone videographers and event attendees |
| 8 | A centralized opt-out registry allowing bereaved individuals | 1 | 21 | 0 | Grieving consumers |
| 9 | A way to programmatically access city and community event ca | 1 | 21 | 0 | Developers building local event discovery tools |
| 10 | A tool that sequentially routes project tasks through the fr | 1 | 21 | 0 | Developers and AI power users |
| 11 | A way to find and legally pay for short-term access to nearb | 1 | 21 | 0 | Homeowners and residents needing temporary junk disposal |
| 12 | Modular and upgradeable powered wearable assistive devices w | 1 | 21 | 0 | Users of powered wearable and assistive devices |
| 13 | A way to learn and understand AI-generated codebases through | 1 | 21 | 0 | Software developers using AI coding tools |
| 14 | A web application that generates theoretical etymological ro | 1 | 21 | 0 | Linguistics enthusiasts and writers |
| 15 | A utility to log non-tipping customers and display real-time | 1 | 21 | 0 | Gig delivery drivers |

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
