![Contract Review Agent](assets/logo-512.png)

# Contract Review Agent

A SKILL.md skill that reads a freelance or small-agency contract like someone who has been burned by one: finds the clauses that cost real money, ranks them, explains them without jargon, and drafts the negotiation email.

A lawyer costs $300+/hour. This gives you the first pass before you decide whether you need one.

## What it does

1. Inventories every clause — payment, IP, liability, indemnity, termination, non-compete, auto-renewal, boilerplate
2. Also flags clauses that are **missing** — the absent liability cap is often the real risk
3. Scores each finding Critical / High / Medium / Low with a money-or-control reason
4. Explains the concrete scenario, then gives replacement language to ask for
5. Drafts a collaborative three-ask negotiation email under 200 words
6. Ends with a clear verdict: sign as-is, sign with changes, or do not sign yet

## The verdict is the product

```text
## Verdict
Do not sign yet — four clauses expose more than the contract is worth.

## Risk table
| # | Clause | Risk | Why it matters | Ask |
| 1 | §4.2 payment after client's collections | Critical | Your $48k is hostage to a third party | Net-30 from invoice, 40% deposit |
| 2 | §7.1 IP includes pre-existing tools | Critical | Signing away your codebase affects every future client | License pre-existing IP |
...
```

No generic "review your contract" advice. Specific clauses, specific asks.

## What's inside

```text
contract-review-agent/
├── SKILL.md
├── references/
│   └── clause-risk-library.md   # red-flag phrases, severity, default asks by clause type
├── templates/
│   └── negotiation-email.md     # three-ask, under 200 words, collaborative
└── examples/
    └── worked-example.md        # fictional MSA → risk table → rendered email
```

## Who it's for

- Freelancers and consultants signing client paper
- Small agencies reviewing MSAs, SOWs, retainers, and NDAs
- Anyone who has ever signed something and regretted clause 7

## What it is not

An informational review, **not legal advice**. It does not judge enforceability, cite statutes, or replace a lawyer when exposure is material. The skill says so in every output and tells you when the exposure warrants professional advice.

## Get it

- **Agensi:** _listing link after publication_
- **Local:** copy `contract-review-agent/` into your agent's skills directory (Claude Code: `~/.claude/skills/contract-review-agent/`). Folder name must match the frontmatter `name`.

No connectors, no API keys, no accounts — paste the contract and go.

## License

MIT
