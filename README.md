# Cooperative Wealth & Cohabitation Agreement (Template)

> **Public Domain:** Released under **The Unlicense**. See `LICENSE`.  
> **Not Legal or Tax Advice:** This repository provides an educational template. It is not legal advice, does not create an attorney-client relationship, and may be inappropriate or unenforceable in your jurisdiction. Consult qualified independent legal and tax counsel before using.

## What this is

This repository contains an open-source **cohabitation + wealth governance** contract template for unmarried partners who want:

- A **restricted investment “Joint Account”** with withdrawal controls
- A neutral **Escrow Agent/Trustee** to execute scheduled events
- A **time-based vesting schedule (capped)** to allocate an earned share to Partner B
- **Scheduled Liquidity Events** (default: every 3 years) that can transfer vested value to Partner B’s own account without ending cohabitation
- A **deterministic unwind** (formula payout) upon separation
- A minimal **Joint Asset Protocol** for tangible assets bought with Joint Account funds
- A **light-touch privacy/confidentiality** covenant suitable for high-net-worth use
- A vesting condition explicitly tied to **ongoing lawful consideration** (waivers + privacy covenants), reducing arguments that vesting is “payment for romance”

## What it does (plain English)

### 1) Builds a governed wealth pool
Partner A makes recurring deposits into a Joint Account invested in broad market index funds (configurable). During cohabitation, neither party can unilaterally withdraw. A neutral party administers permitted distributions.

### 2) Allocates Partner B an earned share via vesting
Partner B accrues a **Vested Percentage** monthly up to a cap (e.g., 50%). Vesting is conditioned on:
- Continuous Cohabitation, and
- Material compliance with key covenants (privacy + waiver), determined by notice/cure and (if disputed) arbitration.

### 3) Prevents double counting with a distribution ledger
A **B Distribution Ledger** records value already transferred to or for Partner B. Liquidity and separation payouts are calculated net of this ledger.

### 4) Allows Liquidity Events without breakup
On a schedule (default: every 3 years), Partner B can elect a one-time distribution of earned vested value (net of ledger), ideally **in-kind** into Partner B’s own brokerage account (cash fallback if needed).

### 5) Provides deterministic unwind on separation
On separation, the Escrow Agent/Trustee values the account at a defined **Valuation Time** and distributes:
- Partner B’s net entitlement, and
- Partner A’s remainder.

### 6) Covers Joint Assets with a minimal protocol
If Joint Account funds buy a tangible asset (e.g., vehicle), the template sets ownership percentages, cost sharing, and buyout/sale procedures.

## What this is not

- Not legal advice.
- Not a substitute for jurisdiction-specific family law counsel.
- Not a parenting plan.
- Not a mechanism to waive non-waivable rights (e.g., child support is generally governed by statute/courts).

## Repository layout (suggested)

- `agreement.md` — the contract template (main file)
- `LICENSE` — The Unlicense
- `README.md` — this file

Optional:
- `DISCLAIMER.md` — longer disclaimer
- `CHANGELOG.md` — revisions and version notes
- `CONTRIBUTING.md` — contribution guidelines

## How to use

1) Copy `agreement.md` into your working document.  
2) Fill placeholders:
- Parties, dates, state/county, residence address
- Contribution amount and start date
- Vesting rate and cap
- Liquidity cadence/window (if you change defaults)
- Default fund/ticker
- Escrow Agent/Trustee identity and contact details

3) Choose a custody/control structure that can actually enforce:
- no unilateral withdrawals during cohabitation
- neutral execution of Liquidity Events and separation unwind  
(**This is the #1 real-world dependency.**)

4) Each party should consult independent counsel (legal + tax).  
5) Execute with appropriate formalities (notarization recommended).

## Key concepts

- **Joint Account:** Restricted investment pool governed by this agreement.
- **Vested Percentage:** Partner B’s earned share (capped) accruing monthly.
- **Valuation Time:** Prior trading day close / NAV used for calculations.
- **B Distribution Ledger:** Tracks prior transfers to Partner B to avoid double counting.
- **Liquidity Event:** Scheduled option to transfer earned value to Partner B without separation.
- **Deterministic Unwind:** Formula-based payout at separation.
- **Material Compliance:** A non-abusive notice/cure/arbitration mechanism tied to privacy and waiver covenants; the Escrow Agent/Trustee is not a fact finder.

## Design goals

- Reduce unilateral access to pooled funds (“anti-smash-and-grab”).
- Reduce ambiguity and leverage at separation.
- Provide periodic liquidity to reduce “exit to access value” pressure.
- Keep separate property boundaries explicit.
- Provide privacy hygiene suitable for high-net-worth users.
- Keep day-to-day household cost sharing separate from the wealth mechanics.

## Known limitations / risks

- **Custodian feasibility:** Many institutions won’t implement bespoke withdrawal locks without a compatible legal structure (trust/entity/authorized-control setup).
- **Enforceability varies:** Courts/arbitrators may limit waivers based on disclosure, fairness, duress, and local law.
- **Tax outcomes vary:** Reporting often follows account titling and regulations, not private agreements.

## License

This repository is released into the public domain under **The Unlicense**. See `LICENSE`.
