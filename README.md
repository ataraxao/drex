# Cooperative Wealth Governance Agreement 

## License / Public Domain
This repository is intended to be released into the public domain under **The Unlicense**. Include a `LICENSE` file containing the Unlicense text.

## Not Legal or Tax Advice
This repository contains conceptual templates for educational and informational purposes only. It is **not** legal advice or tax advice and does not create an attorney-client relationship. Laws and tax rules vary widely by jurisdiction and by facts. Use independent legal counsel and independent tax counsel before using or adapting any template here.

## What This Is
This repo contains a “wealth-governance” contract template designed to coordinate a private cooperative wealth arrangement using:

- a restricted brokerage account held by a single-member **Vehicle LLC** (owned by Party A), and
- a neutral, third-party **Independent Administrator** with limited (**event-only**) authority to execute distributions and freezes.

The template aims to be **wealth-only** (not a relationship contract) while still providing deterministic mechanics for:

- periodic **Liquidity Events**, and
- a deterministic **unwind on termination**.

## Core Design Goals

### 1) Anti-smash-and-grab controls
Neither party can unilaterally transfer assets out of the Vehicle Account. Party A has **trading authority only**, while transfers-out and distributions are controlled by the Independent Administrator.

### 2) Event-only third-party administration
To make the Administrator role realistically fillable, the Administrator’s duties are limited to events:
- Liquidity Event processing when Party B elects,
- termination unwind processing, and
- dispute holdbacks / distribution of undisputed amounts.

No monthly bookkeeping, no investment advice, no continuous monitoring.

### 3) Deterministic math + ledger netting
The template uses:
- an **Allocation Percentage** (default example: 1% per month up to a cap, typically 50%), and
- a **B Distribution Ledger** to avoid double-counting across Liquidity Events and final termination.

### 4) Non-recourse
Party B’s entitlement is limited to assets actually in the Vehicle Account (and proceeds of Joint Assets purchased with Vehicle Account funds). There is **no recourse** against Party A’s separate property.

### 5) Implementation integrity
The Vehicle LLC includes anti-bypass covenants and “minimum terms” that should be mirrored in LLC documents and custodian permissions so Party A cannot easily override the intended control structure.

### 6) Tax-neutral posture (recommended)
The template avoids promising that distributions will be treated as “gifts” or any other specific tax classification. Reporting depends on account titling, entity classification, facts, and law. Each party should consult tax counsel.

## What This Is Not
- Not a marriage contract or prenup.
- Not a parenting plan.
- Not a household chores or “relationship performance” contract.
- Not a promise of investment returns.
- Not a guarantee of tax treatment.

## Repo Contents (Suggested Files)
1) `Cooperative_Wealth_Governance_Agreement.txt` (or `.md`)  
   The main agreement: Vehicle LLC + Vehicle Account governance, allocations, Liquidity Events, termination unwind, dispute resolution, exhibits.

2) `Household_Budget_Shared_Expense_Memo.txt` (optional)  
   A separate private side letter for routine household budgeting via a separate checking account. Not incorporated into the wealth agreement.

3) `LICENSE`  
   The Unlicense text.

4) `README.md`  
   This file.

## How It Works (Plain English)

### 1) Set up the structure
- Party A forms a single-member Vehicle LLC.
- The Vehicle LLC opens a brokerage account (“Vehicle Account”).
- The custodian permissions and LLC documents are configured so:
  - Party A has **trading authority only**, and
  - the Independent Administrator has **exclusive authority** over transfers-out, freezes, and distributions.

### 2) Fund and invest
- Party A may contribute voluntarily (non-binding by default).
- Investments default to broad-market index funds/ETFs unless changed by agreement.

### 3) Allocation accrues
- Party B’s Allocation Percentage accrues (example: 1% per month) up to a cap (often 50%).
- This Allocation Percentage is used only to divide the Vehicle Account under Liquidity Events and termination unwind.

### 4) Liquidity Events
- On each scheduled Liquidity Event, Party B may elect a Liquidity distribution during a defined window.
- The Administrator calculates the “net owed” amount:

  `max(0, Account Value × Allocation % − B Distribution Ledger)`

- The Administrator distributes (preferably in-kind if practicable) to Party B’s designated brokerage account.

### 5) Termination unwind
- Either party may terminate at any time by notice.
- The Administrator freezes the account (as feasible), values it at the defined Valuation Time, and distributes:
  - Party B’s net share, then
  - Party A receives the remainder.

### 6) Joint Assets (optional)
If Vehicle Account funds buy tangible assets:
- default titling is tenants-in-common with percent ownership matching the Allocation Percentage at purchase, and
- the Joint Asset Protocol covers buyout/sale procedures.  
Alternatively, the parties may elect to title an asset to the Vehicle LLC with special rules.

## Key Implementation Dependency (Most Important)
This template only works if the custodian/account setup can actually enforce the authority split:

- Party A: trading only
- Independent Administrator: exclusive transfers-out/distributions/freeze authority

Not all retail brokerages support this cleanly. Confirm the exact account type and permissions in writing before relying on the template. The agreement is not “operative” until the control structure is implemented.

## Why There Is a Separate Household Memo
Household budgeting is intentionally separated:
- The wealth agreement is designed to be “wealth-only” and does not govern cohabitation, support, or household operations.
- If needed, use the separate Household Budget & Shared Expense Account Memo for daily-life expenses. It does not affect vesting, allocations, or unwind mechanics.

## Dispute Resolution
Disputes are handled via binding arbitration (AAA) with:
- holdback of only the disputed incremental amount, and
- court carve-outs for emergency injunctive relief and award enforcement.

## Contributions / Forks
If you fork or adapt this template, keep these principles intact:
- clear separation between “wealth governance” and “household/relationship” topics,
- custodian feasibility gating (not operative until permissions are proven), and
- avoid making hard tax promises in the contract itself.
