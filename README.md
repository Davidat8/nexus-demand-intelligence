# KnightByrd Nexus — Demand Intelligence (open dataset)

> **The things people are begging for that don't exist yet** — a sanitized, anonymized snapshot of real,
> aggregated demand from the [KnightByrd AI Demand Exchange](https://nexus.knightbyrd.com/demand). Updated weekly. No PII:
> clusters only, never raw submissions.

_Last updated: 2026-11-02T18:00:38.366Z · 106 demand clusters · 106 total requests._

## Why this exists
Most people build supply and hope demand shows up. Nexus flips it: people say what outcome they need and
what they'd pay for it, and the AI clusters + scores that demand. This repo publishes the result as an open
dataset so builders and founders have a **validated backlog** to work from. If you ship something from it,
we'd love a link back — and tell the people who asked.

## The most-wanted right now
| # | Demand | Requests | Opportunity | Willingness-to-pay | Audience |
|---|--------|----------|-------------|--------------------|----------|
| 1 | A platform that provides curated, reasonably priced product  | 1 | 21 | 0 | Women consumers |
| 2 | An app that calculates and tracks the real daily cost-per-us | 1 | 21 | 0 | Budget-conscious consumers and minimalists |
| 3 | A collaborative platform for party guests to aggregate photo | 1 | 21 | 0 | Party hosts and event guests |
| 4 | A rating interface that prominently integrates statistical c | 1 | 21 | 0 | Online shoppers and review platforms |
| 5 | An automated AI tool that identifies and contacts prospectiv | 1 | 21 | 0 | Domain investors |
| 6 | A browser tool to autofill Indian government exam applicatio | 1 | 21 | 0 | Indian government exam aspirants |
| 7 | A centralized system to manage and track customer orders pla | 1 | 21 | 0 | Social media and chat-based sellers |
| 8 | A browser extension that automatically detects and flags AI- | 1 | 21 | 0 | LinkedIn users |
| 9 | A web application that generates theoretical etymological ro | 1 | 21 | 0 | Linguistics enthusiasts and writers |
| 10 | A utility to log non-tipping customers and display real-time | 1 | 21 | 0 | Gig delivery drivers |
| 11 | A platform to log, track, and alert job applicants about emp | 1 | 21 | 0 | Active job seekers |
| 12 | A music streaming interface offering granular algorithmic co | 1 | 21 | 0 | Music streaming power users |
| 13 | A marketplace platform to commission custom books on specifi | 1 | 21 | 0 | Readers and researchers seeking bespoke non-fiction books |
| 14 | A tool that condenses lengthy AI chat logs and artifacts int | 1 | 21 | 0 | Knowledge workers and software teams using AI tools |
| 15 | A browser extension that assigns nutrition-style health and  | 1 | 21 | 0 | YouTube viewers and digital wellness advocates |

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
