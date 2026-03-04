# Mechanism Summary — Cooperative Wealth Governance Agreement (CWA)
*Conceptual template. Not legal or tax advice.*

## 1) One-paragraph overview
The CWA is a **wealth-only, event-driven governance wrapper** for a **ring-fenced investment pool** (a restricted brokerage account held by a Vehicle LLC). It aims to reduce the “dispute surface” of relationship-adjacent wealth outcomes by making (i) allocation rules explicit, (ii) liquidity scheduled and deterministic, and (iii) exit mechanics formulaic and administrator-executed—while avoiding ongoing personal obligations, services, or support-like promises.

## 2) What it is / what it is not

### It *is*
- A governance protocol for a **defined pool** of assets (Vehicle Account + Joint Assets purchased with it).
- A structure with **no unilateral transfers-out** by either party.
- A formula for **allocation accrual**, with **periodic Liquidity Events** and **deterministic termination unwind**.
- A mechanism where a neutral **Independent Administrator** executes “events” and maintains an event-only ledger.
- An optional mechanism for **Discretionary Gift Top-Ups** initiated solely by the Funding Partner and executed to Party B’s designated account, recorded in the ledger to prevent double counting.

### It is *not*
- A relationship mandate, cohabitation agreement, or lifestyle/behavior contract.
- Employment, wages, compensation for services, or any meretricious consideration.
- A promise of funding (funding is voluntary unless a signed amendment says otherwise).
- A tax strategy or promise of tax characterization.
- A waiver of non-waivable rights (including child-related statutory rights/obligations).

## 3) Core components (definitions in plain English)
- **Vehicle LLC:** typically a single-member LLC owned by Party A, used as the account holder for the investment pool.
- **Vehicle Account:** the restricted brokerage account titled to the Vehicle LLC.
- **Independent Administrator:** a neutral third party with authority over **transfers-out/distributions/freeze** for specified events.
- **Trading Authority:** ability to trade within the account, **not** to withdraw/transfer out.
- **Allocation Percentage:** accrues over time (whole months only), capped (e.g., 50%).
- **B Distribution Ledger:** records only actual B Distributions (event-only) to prevent double counting.
- **Discretionary Gift Top-Up:** an optional, Funding-Partner-initiated distribution to Party B’s designated account that is recorded as a B Distribution (and therefore nets against later Liquidity/Termination payouts) without changing Allocation %.

## 4) The formulas (the whole point)
All entitlement calculations are **in-pool, event-driven, and net of the ledger**.

### Liquidity Settlement Amount (at Liquidity Event, if elected)
`max(0, (Vehicle Value × Allocation %) − B Distribution Ledger)`

### Termination payout (at termination)
`max(0, (Vehicle Value × Allocation %) − B Distribution Ledger)`
with the remainder to Party A (net of permitted fees/withholding).

**Key property:** the ledger prevents double counting across multiple Liquidity Events, discretionary distributions recorded as B Distributions, and final unwind.

## 5) The “Operative Date” gating (what makes it real)
The Agreement is **not operative** until the custody/control structure is actually implemented such that, in substance:
1) **No unilateral transfers-out** by either party.
2) Independent Administrator controls **transfers-out/distributions/freeze** for events.
3) Party A has **Trading Authority only** (no payout destination changes).
4) Permission-change controls prevent unilateral recipient/profile edits.
5) Party B has view/statement access only (no transfers-out/trading authority).

If the custodian cannot satisfy a requirement, the Agreement remains non-operative unless the parties + administrator sign a **written exception** describing the constraint and compensating controls.

## 6) Event flow (how it behaves in real life)

### Normal operation (no events)
- Party A may trade inside guardrails.
- No one unilaterally withdraws/transfers out.
- Shared withdrawals require joint instruction.

### Discretionary Gift Top-Up (optional)
- Party A may instruct the Administrator to distribute an additional amount (cash or in-kind) to Party B’s designated account.
- The distribution is recorded in the B Distribution Ledger as a B Distribution to prevent double counting.
- It does not change Allocation % or vesting mechanics.

### Liquidity Event (every N years; default 3) — optional
- Party B may elect a distribution during the Liquidity Window.
- Administrator calculates amount by formula and distributes (in-kind by default; cash fallback).
- Administrator updates the B Distribution Ledger.

### Termination — at will
- Either party can terminate by notice.
- Administrator freezes transfers-out (subject to custodian constraints), values the account, distributes per formula, and closes out.

## 7) Dispute surface: what is minimized vs what remains
### Minimized
- “Fairness narratives” about who contributed what during the relationship (for the defined pool).
- Negotiation over distribution amounts: it’s formula + ledger.
- Opportunistic unilateral withdrawals: blocked by controls.

### Still possible / explicitly preserved
- Fraud, duress, unconscionability challenges.
- Child-related statutory rights/obligations (non-waivable).
- Custodian constraints and operational failures.
- Misconduct (handled via arbitration + narrow restitution carveout if controls fail).

## 8) “Obvious objections” (one-line answers)
- **Is this commodification?** It prices an already-priced wealth dimension, but makes it explicit and less adversarial.
- **Does it incentivize strategy?** Yes—toward cooperative compounding rather than narrative warfare.
- **What about low-income couples?** The mechanism is tierable; the MVP is legibility + deterministic exit.
- **What about abuse/coercion?** At-will + periodic liquidity is anti-entrapment, but no paper solves coercion; process safeguards matter.
- **What if markets are flat?** Wealth growth signal weakens; clarity and deterministic unwind still hold.

## 9) What reviewers should attack
If you are reviewing this as a professional, the highest-value critiques are:
- What legal/operational facts could cause recharacterization (partnership, support optics, etc.)?
- What custody stacks can/can’t implement the control split?
- Where does the Agreement accidentally create enforceable obligations?
- Where is unconscionability/duress risk highest and how should onboarding mitigate it?

## 10) Status
This is a conceptual template. Real-world use requires:
- independent legal counsel for both parties,
- independent tax counsel,
- and a custodian + administrator willing to implement the control structure.
