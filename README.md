# KnightByrd Nexus — Demand Intelligence (open dataset)

> **The things people are begging for that don't exist yet** — a sanitized, anonymized snapshot of real,
> aggregated demand from the [KnightByrd AI Demand Exchange](https://nexus.knightbyrd.com/demand). Updated weekly. No PII:
> clusters only, never raw submissions.

_Last updated: 2026-09-07T18:00:38.406Z · 81 demand clusters · 81 total requests._

## Why this exists
Most people build supply and hope demand shows up. Nexus flips it: people say what outcome they need and
what they'd pay for it, and the AI clusters + scores that demand. This repo publishes the result as an open
dataset so builders and founders have a **validated backlog** to work from. If you ship something from it,
we'd love a link back — and tell the people who asked.

## The most-wanted right now
| # | Demand | Requests | Opportunity | Willingness-to-pay | Audience |
|---|--------|----------|-------------|--------------------|----------|
| 1 | A way to learn and understand AI-generated codebases through | 1 | 21 | 0 | Software developers using AI coding tools |
| 2 | A platform that provides curated, reasonably priced product  | 1 | 21 | 0 | Women consumers |
| 3 | A web application that generates theoretical etymological ro | 1 | 21 | 0 | Linguistics enthusiasts and writers |
| 4 | A browser extension that automatically detects and flags AI- | 1 | 21 | 0 | LinkedIn users |
| 5 | A platform to log, track, and alert job applicants about emp | 1 | 21 | 0 | Active job seekers |
| 6 | A security sandboxing tool to restrict AI agent access to lo | 1 | 21 | 0 | Users running autonomous AI agents on personal computers |
| 7 | A feature or tool to search and filter customer reviews with | 1 | 21 | 0 | App store shoppers and mobile users |
| 8 | A spoiler-prevention setting for streaming platforms that hi | 1 | 21 | 0 | streaming service subscribers |
| 9 | Instantly preview and stream CD audio by scanning album cove | 1 | 21 | 0 | CD collectors and thrift store shoppers |
| 10 | An app that calculates and tracks the real daily cost-per-us | 1 | 21 | 0 | Budget-conscious consumers and minimalists |
| 11 | A tool that condenses lengthy AI chat logs and artifacts int | 1 | 21 | 0 | Knowledge workers and software teams using AI tools |
| 12 | A web application that generates theoretical etymological ro | 1 | 21 | 0 | Linguistics enthusiasts and writers |
| 13 | A centralized system to manage and track customer orders pla | 1 | 21 | 0 | Social media and chat-based sellers |
| 14 | A way to automatically compile and edit multiple raw video c | 1 | 21 | 0 | Casual smartphone videographers and event attendees |
| 15 | A music streaming interface offering granular algorithmic co | 1 | 21 | 0 | Music streaming power users |

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
