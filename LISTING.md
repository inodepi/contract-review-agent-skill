# Agensi Listing — Contract Review Agent

Submission copy for https://www.agensi.io/dashboard/submit. Keep in sync with SKILL.md.

## Fields

| Field | Value |
| --- | --- |
| Skill name (internal) | `contract-review-agent` |
| Display title | Contract Review Agent |
| Category | Legal & Compliance |
| Tagline | Find the clauses that will cost you money — before you sign. |
| Price | **$19, paid at launch** (no free period) |
| Version | 1.0.0 |
| License | MIT |
| Skills directory | `contract-review-agent/` |

## Why paid at launch

- The buyer's alternative is a lawyer at $300+/hour; $19 is an impulse purchase against that anchor
- Zero setup — paste a contract and get a verdict, so nothing can fail before the value lands
- Immediate per-use ROI: one fixed clause pays for the skill many times over
- Money-back guarantee covers the risk for the buyer

## Short description

Reviews freelance and agency contracts clause by clause: flags IP grabs, unlimited liability, payment-term traps, auto-renewal, termination lock-in, and broad non-competes, ranks each risk in plain English, and drafts a collaborative three-ask negotiation email. Informational review, not legal advice.

## Long description

You just got the contract. It is nineteen pages, the client wants it signed today, and clause 7 does something with "all right, title and interest" that you do not have time to decode.

This skill reads it the way someone who has been burned would:

- **Inventories everything that matters** — payment, IP, liability, indemnity, termination, restrictive covenants, auto-renewal, governing law, assignment.
- **Flags the missing clauses too.** No liability cap, no kill fee, no late-payment interest, no acceptance criteria. Absence is where the real losses hide.
- **Ranks by money and control**, not by how scary the language sounds: Critical, High, Medium, Low, each with a one-line reason.
- **Tells you what to ask for.** Every Critical and High finding gets concrete replacement language, not "negotiate this".
- **Writes the negotiation email.** Three asks, grouped by theme, under 200 words, collaborative — because the goal is a signed contract, not a fight.
- **Gives a verdict first.** Sign as-is, sign with changes, or do not sign yet.

Ships with a clause-risk library covering the traps that recur across freelance and agency paper, and a full worked example: fictional MSA, eight findings, rendered risk table and negotiation email.

Not legal advice. It does not judge enforceability or cite statutes, and it tells you when the exposure is large enough to warrant a lawyer.

## What's included

- `SKILL.md` — the review method and output format
- `references/clause-risk-library.md` — clause patterns, red-flag phrases, severity, default asks
- `templates/negotiation-email.md` — the three-ask email structure
- `examples/worked-example.md` — a complete fictional review

## Requirements

- A contract to paste or a file to read
- Nothing else — no connectors, no accounts, no API keys

## Keywords

contract review, freelance contract, MSA review, SOW, NDA, red flags, IP assignment, liability cap, non-compete, negotiation email, legal review, small agency, consultant

## Security notes

- No credentials, no network calls, no telemetry
- Contract text is processed by the user's own agent and is not transmitted by the skill
- Outputs a disclaimer: informational review, not legal advice

## Promotion

- Post the "four clauses that cost me $48k" worked example as a thread
- Offer free 3-clause reviews in freelance communities; the risk table is the demo
- Bundle with the AR and proposal skills as a freelancer back office later
