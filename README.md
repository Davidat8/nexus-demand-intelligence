# KnightByrd Nexus — Demand Intelligence (open dataset)

> **The things people are begging for that don't exist yet** — a sanitized, anonymized snapshot of real,
> aggregated demand from the [KnightByrd AI Demand Exchange](https://nexus.knightbyrd.com/demand). Updated weekly. No PII:
> clusters only, never raw submissions.

_Last updated: 2026-09-21T18:00:38.257Z · 63 demand clusters · 63 total requests._

## Why this exists
Most people build supply and hope demand shows up. Nexus flips it: people say what outcome they need and
what they'd pay for it, and the AI clusters + scores that demand. This repo publishes the result as an open
dataset so builders and founders have a **validated backlog** to work from. If you ship something from it,
we'd love a link back — and tell the people who asked.

## The most-wanted right now
| # | Demand | Requests | Opportunity | Willingness-to-pay | Audience |
|---|--------|----------|-------------|--------------------|----------|
| 1 | A way to programmatically access city and community event ca | 1 | 21 | 0 | Developers building local event discovery tools |
| 2 | A tool that automatically extracts high-interest segments fr | 1 | 21 | 0 | Content creators and video editors |
| 3 | A centralized system to manage and track customer orders pla | 1 | 21 | 0 | Social media and chat-based sellers |
| 4 | Bite-sized micro-courses delivered entirely via daily or wee | 1 | 21 | 0 | Self-directed learners and professionals |
| 5 | An automated digital decluttering tool that organizes and cl | 1 | 21 | 0 | people overwhelmed by digital clutter |
| 6 | A tool to bulk unfollow or remove LinkedIn connections to cl | 1 | 21 | 0 | LinkedIn sales professionals and power users |
| 7 | A scenic drive navigation app that displays tappable saved l | 1 | 21 | 0 | Road trippers and recreational drivers |
| 8 | A platform to connect technical and non-technical founders w | 1 | 21 | 0 | Part-time entrepreneurs and side-project builders |
| 9 | A continuous 24/7 360-degree timelapse weather monitoring se | 1 | 21 | 0 | Weather enthusiasts and sightseers |
| 10 | A security sandboxing tool to restrict AI agent access to lo | 1 | 21 | 0 | Users running autonomous AI agents on personal computers |
| 11 | A spoiler-prevention setting for streaming platforms that hi | 1 | 21 | 0 | streaming service subscribers |
| 12 | A third-party mobile keyboard that automatically translitera | 1 | 21 | 0 | Arabic speakers typing on mobile devices |
| 13 | A browser extension that assigns nutrition-style health and  | 1 | 21 | 0 | YouTube viewers and digital wellness advocates |
| 14 | A platform to log, track, and alert job applicants about emp | 1 | 21 | 0 | Active job seekers |
| 15 | Phone grip accessories engineered with diverse tactile and s | 1 | 21 | 0 | Sensory seekers and fidgeters |

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
