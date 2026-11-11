# Worked Example

A fictional review of a small-agency master services agreement. Contract value: $48,000 over six months.

## Excerpt (fictional)

```text
4.2 Client shall pay each invoice within ninety (90) days of Client's receipt of
    funds from its end customer.

7.1 All right, title and interest in all materials, including Contractor's
    pre-existing tools, templates and code, shall vest in Client upon creation.

9.1 Contractor shall indemnify, defend and hold harmless Client from any and all
    claims arising from the services, without limitation.

11.2 Client may terminate this Agreement for convenience immediately upon notice.
     Contractor shall be paid only for milestones approved in writing.

12.3 During the term and for twelve (12) months after, Contractor shall not
     provide services to any business in the retail sector.

14.1 This Agreement renews automatically for successive two-year terms unless
     either party gives ninety (90) days' written notice.

15.2 Client may assign this Agreement to any successor without consent.
```

## Output the skill produces

### Verdict

**Do not sign yet** — four clauses expose more than the contract is worth; all are negotiable.

### Risk table

| # | Clause | Risk | Why it matters | Ask |
| --- | --- | --- | --- | --- |
| 1 | §4.2 payment after client's collections | Critical | Your $48k is hostage to a third party's payment behaviour | Net-30 from invoice date, 40% deposit |
| 2 | §7.1 IP includes pre-existing tools | Critical | Signing away your reusable codebase affects every future client | License pre-existing IP; assign bespoke deliverables on full payment |
| 3 | §9.1 unlimited indemnity | Critical | One claim can exceed the entire fee | Mutual indemnity, capped at fees paid |
| 4 | §11.2 immediate termination, approved milestones only | High | Work in progress becomes unpaid work | 30 days' notice; pay for work performed and committed costs |
| 5 | §12.3 12-month retail-sector non-compete | High | Blocks most of your pipeline for a year | Limit to this client's direct competitors and the services provided, 6 months |
| 6 | No liability cap | Critical | Uncapped exposure sits beside uncapped indemnity | Cap at fees paid; exclude consequential damages |
| 7 | §14.1 two-year auto-renew, 90-day notice | Medium | Easy to miss the window and be locked in | 30-day notice or renewal by written agreement |
| 8 | §15.2 assignment without consent | Medium | Your contract could move to a competitor | Consent required; no assignment to a direct competitor |

Missing clauses: late-payment interest, kill fee, portfolio rights, acceptance criteria.

### Top three asks

1. **Payment on invoice, not on their customer's payment.** Net-30, 40% deposit, 1.5% monthly late fee.
2. **Keep your pre-existing tools.** License them to the client; assign only the bespoke deliverables, on full payment.
3. **Cap liability and make indemnity mutual.** Fees paid as the cap; exclude consequential losses.

### Negotiation email

```text
Subject: Northwind MSA — a few small changes before we sign

Hi Dana,

Thanks for sending this over — happy to get started. Before signing, I'd like to adjust three things so the agreement matches how we both work:

1. Payment timing: I'd suggest net-30 from invoice date with a 40% deposit, rather than payment after your end customer pays. A 1.5% monthly late fee would keep it fair on both sides.

2. IP ownership: I'd suggest assigning the bespoke deliverables to you on full payment, while licensing my pre-existing tools and templates back to you for use with this project.

3. Liability: I'd suggest a mutual indemnity capped at fees paid, with consequential losses excluded. That keeps the risk proportional to the engagement for both of us.

Everything else looks good to me, and I'm ready to sign as soon as these are reflected. If any of these are tricky on your side, tell me which and I'll propose an alternative.

Best,
Alex Rivera
```

### Notes

- Informational review, not legal advice. The uncapped indemnity plus unlimited liability is the kind of exposure worth a lawyer's hour.
- Clauses not present: late-payment interest, kill fee, portfolio rights, acceptance criteria.
