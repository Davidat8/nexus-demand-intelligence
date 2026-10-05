# KnightByrd Nexus — Demand Intelligence (open dataset)

> **The things people are begging for that don't exist yet** — a sanitized, anonymized snapshot of real,
> aggregated demand from the [KnightByrd AI Demand Exchange](https://nexus.knightbyrd.com/demand). Updated weekly. No PII:
> clusters only, never raw submissions.

_Last updated: 2026-10-05T18:00:38.271Z · 87 demand clusters · 87 total requests._

## Why this exists
Most people build supply and hope demand shows up. Nexus flips it: people say what outcome they need and
what they'd pay for it, and the AI clusters + scores that demand. This repo publishes the result as an open
dataset so builders and founders have a **validated backlog** to work from. If you ship something from it,
we'd love a link back — and tell the people who asked.

## The most-wanted right now
| # | Demand | Requests | Opportunity | Willingness-to-pay | Audience |
|---|--------|----------|-------------|--------------------|----------|
| 1 | A rating interface that prominently integrates statistical c | 1 | 21 | 0 | Online shoppers and review platforms |
| 2 | A browser extension that automatically detects and flags AI- | 1 | 21 | 0 | LinkedIn users |
| 3 | A platform to log, track, and alert job applicants about emp | 1 | 21 | 0 | Active job seekers |
| 4 | A tool that condenses lengthy AI chat logs and artifacts int | 1 | 21 | 0 | Knowledge workers and software teams using AI tools |
| 5 | A way to learn and understand AI-generated codebases through | 1 | 21 | 0 | Software developers using AI coding tools |
| 6 | A collaborative platform for party guests to aggregate photo | 1 | 21 | 0 | Party hosts and event guests |
| 7 | A web application that generates theoretical etymological ro | 1 | 21 | 0 | Linguistics enthusiasts and writers |
| 8 | A centralized system to manage and track customer orders pla | 1 | 21 | 0 | Social media and chat-based sellers |
| 9 | A browser tool to autofill Indian government exam applicatio | 1 | 21 | 0 | Indian government exam aspirants |
| 10 | A way to programmatically access city and community event ca | 1 | 21 | 0 | Developers building local event discovery tools |
| 11 | An app that calculates and tracks the real daily cost-per-us | 1 | 21 | 0 | Budget-conscious consumers and minimalists |
| 12 | An effortless way to save and organize potential gift ideas  | 1 | 21 | 0 | Gift shoppers |
| 13 | A discreet and hygienic temporary containment solution for u | 1 | 21 | 0 | Sexually active adults |
| 14 | A third-party mobile keyboard that automatically translitera | 1 | 21 | 0 | Arabic speakers typing on mobile devices |
| 15 | A streaming feature that creates custom scheduled linear cha | 1 | 21 | 0 | Streaming service subscribers |

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
