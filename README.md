# Cooperative Wealth & Cohabitation Agreement (Template)

> **Public Domain:** Released under **The Unlicense**. See `LICENSE`.  
> **Not Legal or Tax Advice:** This repository provides an educational template. It is not legal advice, does not create an attorney-client relationship, and may be inappropriate or unenforceable in your jurisdiction. Consult qualified independent legal and tax counsel before using.

## What this is

This repository contains an open-source **cohabitation + wealth vehicle** template for unmarried partners who want:

- A **restricted investment account** governed by a neutral third party (Escrow Agent/Trustee),
- A **time-based vesting schedule** (capped) to allocate an earned share,
- **Periodic Liquidity Events** so Partner B can receive vested value into an account in B’s own name *without ending cohabitation*,
- A **deterministic unwind** (formula-based payout) upon separation,
- A minimal **Joint Asset Protocol** for tangible assets bought with Joint Account funds.

It is designed to reduce common cohabitation failure modes: unclear expectations, opportunistic withdrawals, and high-conflict “who gets what” negotiations at breakup.

## What it does (plain English)

### 1) Creates a governed “Joint Account”
Partner A makes recurring deposits into a jointly governed investment pool. During cohabitation, neither party can withdraw unilaterally. A neutral third party executes distributions only when the contract allows them.

### 2) Grants Partner B a capped earned share
Partner B accrues a **Vested Percentage** monthly (e.g., 1%/month) up to a cap (e.g., 50%).

### 3) Prevents double counting with a distribution ledger
A **B Distribution Ledger** tracks amounts already distributed to/for Partner B, so later Liquidity Events and separation payouts are calculated net of prior distributions.

### 4) Allows scheduled Liquidity Events (default: every 3 years)
At each Liquidity Event, Partner B may elect to receive earned vested value (net of the ledger), preferably **in-kind** into an account in B’s name, with a cash fallback if needed.

### 5) Forces a deterministic unwind at separation
On a valid separation trigger, the neutral freezes the Joint Account (as practicable), values it at a defined **Valuation Time**, and distributes:

- Partner B’s net entitlement (vesting × value − ledger), and
- Partner A’s remainder.

### 6) Handles “Joint Assets” with a minimal protocol
If the Joint Account buys a tangible asset (e.g., vehicle), the template sets ownership percentages, cost sharing, and buyout/sale procedures.

## What this is not

- Not a substitute for jurisdiction-specific legal advice.
- Not a parenting plan.
- Not a reliable mechanism to waive statutory rights (e.g., child support is typically governed by law and courts).

## Repository layout (suggested)

- `agreement.md` — the contract template
- `LICENSE` — The Unlicense
- `README.md` — this file

Optional:
- `DISCLAIMER.md` — expanded disclaimer text
- `CHANGELOG.md` — version notes
- `CONTRIBUTING.md` — contribution guidance

## How to use

1. Copy `agreement.md` into your working doc.
2. Fill in placeholders:
   - Parties, dates, state/county, residence address
   - Contribution amount, start date
   - Vesting rate and cap
   - Default fund/ticker
   - Escrow Agent/Trustee details
3. Choose a custody/control structure that can actually enforce:
   - no unilateral withdrawals during cohabitation
   - neutral execution of Liquidity Events and separation payouts  
   (This is the #1 real-world dependency.)
4. Each party should consult independent counsel (legal + tax).
5. Execute with appropriate formalities (notarization recommended).

## Key concepts

- **Joint Account:** Restricted investment pool governed by this agreement.
- **Vested Percentage:** Partner B’s earned share of the Joint Account (capped).
- **Valuation Time:** Prior trading day close / NAV used for calculations.
- **B Distribution Ledger:** Tracks prior value transferred to Partner B to avoid double counting.
- **Liquidity Event:** Scheduled opportunity for Partner B to receive vested value without separation.
- **Deterministic Unwind:** Formula-based payout on separation to reduce negotiation and conflict.

## Design goals

- Reduce unilateral access to pooled funds (“anti-smash-and-grab”).
- Provide predictable separation outcomes.
- Allow periodic liquidity to reduce “exit to access value” pressure.
- Keep separate property boundaries explicit.
- Keep day-to-day cost sharing separate from wealth mechanics.

## Known limitations / risks

- **Custodian feasibility:** Many institutions won’t implement bespoke withdrawal locks without a compatible legal structure (trust/entity/authorized-control mechanism).
- **Enforceability varies:** Courts/arbitrators may limit waivers based on process, disclosure, fairness, and local law.
- **Tax reporting varies:** Reporting often follows account titling and regulations, not private agreements.

## License

This repository is released into the public domain under **The Unlicense**. See `LICENSE`.
