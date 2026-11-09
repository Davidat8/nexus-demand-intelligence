# KnightByrd Nexus — Demand Intelligence (open dataset)

> **The things people are begging for that don't exist yet** — a sanitized, anonymized snapshot of real,
> aggregated demand from the [KnightByrd AI Demand Exchange](https://nexus.knightbyrd.com/demand). Updated weekly. No PII:
> clusters only, never raw submissions.

_Last updated: 2026-11-09T18:00:38.505Z · 124 demand clusters · 124 total requests._

## Why this exists
Most people build supply and hope demand shows up. Nexus flips it: people say what outcome they need and
what they'd pay for it, and the AI clusters + scores that demand. This repo publishes the result as an open
dataset so builders and founders have a **validated backlog** to work from. If you ship something from it,
we'd love a link back — and tell the people who asked.

## The most-wanted right now
| # | Demand | Requests | Opportunity | Willingness-to-pay | Audience |
|---|--------|----------|-------------|--------------------|----------|
| 1 | A platform to connect technical and non-technical founders w | 1 | 21 | 0 | Part-time entrepreneurs and side-project builders |
| 2 | An app that calculates and tracks the real daily cost-per-us | 1 | 21 | 0 | Budget-conscious consumers and minimalists |
| 3 | An effortless way to save and organize potential gift ideas  | 1 | 21 | 0 | Gift shoppers |
| 4 | A platform to log, track, and alert job applicants about emp | 1 | 21 | 0 | Active job seekers |
| 5 | A security sandboxing tool to restrict AI agent access to lo | 1 | 21 | 0 | Users running autonomous AI agents on personal computers |
| 6 | A local neighborhood networking platform that allows small b | 1 | 21 | 0 | local small business owners and entrepreneurs |
| 7 | A shared photo app that unlocks a travel group's trip pictur | 1 | 21 | 0 | travelers and friend groups |
| 8 | A computer keyboard integrated with a breathalyzer that unlo | 1 | 21 | 0 | People looking to prevent drunk emailing or texting |
| 9 | A visual recognition app to identify and purchase physical o | 1 | 21 | 0 | Movie viewers and shoppers |
| 10 | A marketplace app connecting individuals with personal styli | 1 | 21 | 0 | Fashion-conscious consumers seeking personal styling |
| 11 | A USB stick with fingerprint security that can store and be  | 1 | 21 | 0 | Consumers seeking secure payment alternatives, unbanked individuals. |
| 12 | A way to easily organize, search, and retrieve saved TikTok  | 1 | 21 | 0 | Active TikTok users who bookmark content |
| 13 | Vending machines configured to dispense ready-to-eat canned  | 1 | 21 | 0 | Commuters and convenience food consumers |
| 14 | A third-party mobile keyboard that automatically translitera | 1 | 21 | 0 | Arabic speakers typing on mobile devices |
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
