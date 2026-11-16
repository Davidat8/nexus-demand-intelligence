# KnightByrd Nexus — Demand Intelligence (open dataset)

> **The things people are begging for that don't exist yet** — a sanitized, anonymized snapshot of real,
> aggregated demand from the [KnightByrd AI Demand Exchange](https://nexus.knightbyrd.com/demand). Updated weekly. No PII:
> clusters only, never raw submissions.

_Last updated: 2026-11-16T18:00:38.625Z · 138 demand clusters · 138 total requests._

## Why this exists
Most people build supply and hope demand shows up. Nexus flips it: people say what outcome they need and
what they'd pay for it, and the AI clusters + scores that demand. This repo publishes the result as an open
dataset so builders and founders have a **validated backlog** to work from. If you ship something from it,
we'd love a link back — and tell the people who asked.

## The most-wanted right now
| # | Demand | Requests | Opportunity | Willingness-to-pay | Audience |
|---|--------|----------|-------------|--------------------|----------|
| 1 | A platform to connect technical and non-technical founders w | 1 | 21 | 0 | Part-time entrepreneurs and side-project builders |
| 2 | A collaborative platform for party guests to aggregate photo | 1 | 21 | 0 | Party hosts and event guests |
| 3 | A utility to log non-tipping customers and display real-time | 1 | 21 | 0 | Gig delivery drivers |
| 4 | A centralized opt-out registry allowing bereaved individuals | 1 | 21 | 0 | Grieving consumers |
| 5 | A verification app that provides dependable proof that appli | 1 | 21 | 0 | individuals with departure-related memory anxiety or checking habits |
| 6 | A computer keyboard integrated with a breathalyzer that unlo | 1 | 21 | 0 | People looking to prevent drunk emailing or texting |
| 7 | A matchmaking platform that suggests romantic partners based | 1 | 21 | 0 | Singles interested in biological matchmaking |
| 8 | An autonomous self-driving camper that travels independently | 1 | 21 | 0 | campers and outdoor travelers |
| 9 | A way to easily organize, search, and retrieve saved TikTok  | 1 | 21 | 0 | Active TikTok users who bookmark content |
| 10 | A printer that applies a selective glossy resin finish speci | 1 | 21 | 0 | Makers, crafters, and office workers |
| 11 | A search engine feature allowing users to specify preferred  | 1 | 21 | 0 | Multilingual internet users |
| 12 | Users want an app that links to platforms like GitHub, Game  | 1 | 21 | 0 | Developers, gamers, content creators |
| 13 | A third-party mobile keyboard that automatically translitera | 1 | 21 | 0 | Arabic speakers typing on mobile devices |
| 14 | A slow-paced visual inspiration tool that presents a new cur | 1 | 21 | 0 | Creative professionals and artists |
| 15 | A way to find and legally pay for short-term access to nearb | 1 | 21 | 0 | Homeowners and residents needing temporary junk disposal |

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
