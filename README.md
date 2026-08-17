# KnightByrd Nexus — Demand Intelligence (open dataset)

> **The things people are begging for that don't exist yet** — a sanitized, anonymized snapshot of real,
> aggregated demand from the [KnightByrd AI Demand Exchange](https://nexus.knightbyrd.com/demand). Updated weekly. No PII:
> clusters only, never raw submissions.

_Last updated: 2026-08-17T18:00:28.604Z · 16 demand clusters · 16 total requests._

## Why this exists
Most people build supply and hope demand shows up. Nexus flips it: people say what outcome they need and
what they'd pay for it, and the AI clusters + scores that demand. This repo publishes the result as an open
dataset so builders and founders have a **validated backlog** to work from. If you ship something from it,
we'd love a link back — and tell the people who asked.

## The most-wanted right now
| # | Demand | Requests | Opportunity | Willingness-to-pay | Audience |
|---|--------|----------|-------------|--------------------|----------|
| 1 | AI Chat Handoff Summarizer | 1 | 30 | 0 | Knowledge workers and software teams using AI tools |
| 2 | Fictional Word Etymology Generator | 1 | 30 | 0 | Linguistics enthusiasts and writers |
| 3 | Curated Women's Value Shopping | 1 | 29 | 0 | Women consumers |
| 4 | Personal Item Cost-Per-Use Tracker | 1 | 29 | 0 | Budget-conscious consumers and minimalists |
| 5 | Collaborative Event Media Hub | 1 | 28 | 0 | Party hosts and event guests |
| 6 | AI Codebase Educational Explainer | 1 | 28 | 0 | Software developers using AI coding tools |
| 7 | Multi-LLM Free Tier Orchestrator | 1 | 28 | 0 | Developers and AI power users |
| 8 | Confidence-Weighted Review Rating Display | 1 | 28 | 0 | Online shoppers and review platforms |
| 9 | Automated Short-Form Video Extractor | 1 | 27 | 0 | Content creators and video editors |
| 10 | Part-Time Co-Founder Matching | 1 | 27 | 0 | Part-time entrepreneurs and side-project builders |
| 11 | Video Content Quality Nutrition Label | 1 | 26 | 0 | YouTube viewers and digital wellness advocates |
| 12 | Local Event Calendar API | 1 | 26 | 0 | Developers building local event discovery tools |
| 13 | Latin-to-Arabic Transliteration Keyboard | 1 | 25 | 0 | Arabic speakers typing on mobile devices |
| 14 | Personalized Linear Streaming Channels | 1 | 23 | 0 | Streaming service subscribers |
| 15 | 360-Degree Weather Timelapse Stream | 1 | 19 | 0 | Weather watchers, travelers, and outdoor enthusiasts |

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
