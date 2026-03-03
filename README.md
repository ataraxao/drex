# README.md

# Cooperative Wealth Agreement (CWA) — Public Template (CC0 1.0)

**Status:** Public domain template (CC0 1.0).  
**Disclaimer:** **NOT LEGAL OR TAX ADVICE.** This repository contains conceptual templates for educational and informational purposes only. Laws regarding property rights, LLCs, arbitration, securities custody, partnership characterization, and taxation vary heavily by jurisdiction. **Each party must consult independent legal counsel and independent tax counsel** before using or executing any document here.

## What this repository contains

- `cooperative_wealth_agreement.md`  
  The **Cooperative Wealth Governance Agreement**: a wealth-only, event-driven governance wrapper for a **ring-fenced pool** (a restricted brokerage account held by a Vehicle LLC), with:
  - voluntary (non-enforceable) funding,
  - an **Independent Administrator** who controls transfers-out/distributions,
  - a deterministic termination unwind,
  - periodic Liquidity Events,
  - a minimal Joint Asset protocol,
  - an event-only B Distribution Ledger (anti-double-counting),
  - and tight dispute-resolution / holdback mechanics.

- `introduction.md`  
  The explanatory whitepaper (“Gravity Model”) that motivates the design: **make domestic equity legible via an explicit, verifiable mechanism**.

- `LICENSE.md`  
  CC0 1.0 Universal Public Domain Dedication.

## Design intent (plain English)

This template is designed to reduce the “dispute surface” by keeping the agreement **governance-only** and **ring-fenced**:

- **No relationship obligations.** No duties to cohabit, perform services, or maintain a relationship.
- **No funding obligation.** Any funding targets are non-binding; there are **no arrears**.
- **No unilateral withdrawals.** The account is set up so neither party can “smash-and-grab.”
- **Event-driven distributions only.** Transfers-out occur only on:
  - Liquidity Events (if elected), or
  - Termination unwind, or
  - dispute holdback + release of undisputed amounts.
- **Deterministic math.** Payouts are formulaic and netted against the B Distribution Ledger to prevent double counting.

## Who this template is for

This template is for parties who want:

- a **verifiable wealth mechanism** (not a relationship contract),
- clear rules for **allocation, liquidity, and unwind** of a defined pool,
- an administrator-controlled structure that reduces negotiation at exit.

It is **not** intended to replace family law, waive child-related statutory rights, or create employment/compensation arrangements.

## Quickstart: How to use this template (recommended workflow)

### Step 0 — Don’t skip counsel
Each party should retain **independent counsel** (separate attorneys) and **independent tax counsel**. This is especially important if:
- there is a large wealth disparity,
- either party may relocate across states/countries,
- the parties are considering marriage,
- or the structure will be publicly referenced.

### Step 1 — Decide the key economic parameters
In `cooperative_wealth_agreement.md`, fill in:
- **Governing law / venue**: `[State]`, `[County, State]`
- **Monthly Accrual Rate**: e.g., `1.00% per full calendar month`
- **Allocation Cap**: e.g., `50.00%`
- **Liquidity cadence**: default is every 3 years (already set)
- **Admin Reserve**: recommended range is included
- **Default portfolio / ticker**: pick an index ETF/fund
- **Guardrail threshold**: max single-stock exposure (if any)

### Step 2 — Select an implementation path (make it real)
The agreement is **not operative** until the account is actually implemented with the required control split.

Use the Appendix (“Implementation Paths”) to pick a feasible custody/control setup, such as:
- LLC brokerage + administrator LPOA + transfer/recipient locks, or
- directed trust / escrow-style custody, or
- institutional/RIA custody with controlled disbursements.

**Key requirement:** neither party can unilaterally transfer-out, and the Independent Administrator can execute Administrator Events.

### Step 3 — Choose and engage the Independent Administrator
The Independent Administrator must:
- accept the **event-only** role,
- agree to recipient restrictions (only the designated accounts + fees/withholding),
- maintain the event-only **B Distribution Ledger**,
- and provide an **Implementation Confirmation** once the custody setup is correct.

### Step 4 — Form the Vehicle LLC and open the restricted Vehicle Account
- Party A forms the Vehicle LLC (single-member by default in this template).
- The Vehicle Account is opened in the LLC’s name with the chosen custodian.
- Account permissions must reflect:
  - Party A: trading authority only (no transfers-out)
  - Independent Administrator: transfers-out/distributions/freeze authority for Administrator Events
  - Party B: view/statement access only (no trades, no transfers-out)

### Step 5 — Make the agreement operative (Implementation Confirmation)
The agreement becomes operative only after the Independent Administrator confirms, in writing, that the control checklist is satisfied (or that an agreed written exception is in place).

### Step 6 — Funding (optional, voluntary)
- Funding is voluntary.
- If Party A pauses or stops funding, there are **no arrears** and no breach (absent a signed amendment stating otherwise).

### Step 7 — During the term
- The vehicle remains invested within guardrails.
- Joint withdrawals require joint instruction.
- Joint assets purchased from the vehicle follow the Joint Asset protocol.

### Step 8 — Liquidity Events (optional, every 3 years)
During each Liquidity Window, Party B may elect a Liquidity Distribution:
- calculated by formula (net of ledger),
- paid in-kind by default (cash fallback),
- and recorded in the ledger to prevent double counting later.

### Step 9 — Termination unwind
Either party can terminate at will.
Upon termination:
- the Independent Administrator freezes transfers-out (subject to custodian constraints),
- calculates value at the defined Valuation Time,
- pays Party B by formula net of the ledger,
- and returns the remainder to Party A (net of permitted fees/withholding).

## Practical notes / expectations

- **Fillability matters.** The “paper” agreement is not the mechanism; the custody/control implementation is.
- **Expect custodian constraints.** Many custodians have strict rules about permissions and disbursement controls. Work with counsel and the administrator to pick a feasible path.
- **This is not a tax strategy.** The template explicitly does not promise any tax characterization.
- **This is not child support avoidance.** Child-related statutory rights and obligations are not waivable by private contract.

## Contributing / forks

This repo is CC0. You are free to fork and adapt. If you publish improvements, consider keeping:
- the event-driven architecture,
- recipient restrictions,
- operative-date gating,
- and ledger anti-double-counting,
since those are the core dispute-surface minimizers.

## Attribution (optional)

Attribution is not required under CC0, but if you reference the origin:
- “Cooperative Wealth Governance Agreement (CWA) — CC0 public template.”

---
