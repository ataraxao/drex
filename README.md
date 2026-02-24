> **Public Domain:** Released under **The Unlicense**. See `LICENSE`.  
> **Not Legal Advice:** This repository provides an educational template. It is not legal advice, does not create an attorney-client relationship, and may be inappropriate or unenforceable in your jurisdiction. Consult qualified independent legal and tax counsel before using.

## What this is

This repository contains an open-source **contract template** intended for unmarried partners who want a **structured, opt-in wealth-building arrangement** while cohabiting—without relying on marriage law or informal “common-law” assumptions.

The core idea is a **restricted joint investment account** governed by an independent neutral (an “Escrow Agent/Trustee”) with:

- **Deterministic unwind** on separation (a mechanical, formula-based payout).
- **Periodic Liquidity Events** that let one partner receive vested value into an account in their own name *without* ending the relationship.
- A **graded vesting schedule** capped at a configurable maximum (e.g., 50%).
- A **distribution ledger** to prevent double counting across liquidity events and final separation.
- A minimal **Joint Asset Protocol** for tangible assets purchased with joint funds (e.g., a vehicle), including buyout/sale procedures.

The template tries to reduce the classic failure modes of informal cohabitation arrangements:
- unclear expectations about equity in one partner’s property,
- disputes about “who gets what” when the relationship ends,
- unilateral access to pooled funds (“smash-and-grab” risk),
- ambiguous mid-relationship withdrawals,
- lack of a planned path for partial liquidity/ownership.

## What it does (high-level mechanics)

### 1) Establishes a restricted “Joint Account”
The Parties attempt to open a brokerage/bank/trust account that is:
- **not unilaterally withdrawable** by either partner during cohabitation, and
- **operable by a neutral third party** to execute:
  - scheduled Liquidity Events, and
  - the deterministic unwind upon separation.

> **Important:** This template assumes the custody/controls are actually implementable with your chosen custodian and legal structure (trust/entity/escrow arrangement). If not implementable, the agreement is designed to be **non-operative**.

### 2) Defines separate property and non-marital intent
It explicitly states:
- property owned individually stays separate,
- the parties do not intend marriage or “holding out” as spouses,
- and includes operational guidance to reduce commingling ambiguity.

### 3) Creates a monthly vesting schedule for Partner B
- Vesting accrues monthly at a configurable rate (e.g., 1% per month).
- Vesting is capped at a configurable maximum (e.g., 50%).
- Vesting entitlements are measured using a defined **Valuation Time** (prior trading day close / NAV).

### 4) Tracks prior distributions to prevent double counting
A **B Distribution Ledger** records value transferred to/for Partner B from the Joint Account.
- Liquidity Event payouts and separation payouts are calculated **net of this ledger**.
- The template includes an explicit **no-clawback** concept (no negative entitlements due to market moves after earlier liquidity).

### 5) Allows optional scheduled Liquidity Events (every 3 years)
On each 3-year anniversary (configurable concept), Partner B can elect within a window to receive:
- the currently earned vested value (net of the ledger),
- ideally as **in-kind securities** into Partner B’s own account (cash fallback if needed).

This provides a way for Partner B to gradually “own” assets outside the Joint Account without ending the relationship.

### 6) Forces a deterministic unwind on separation
Upon Notice of Separation (or other defined triggers):
- the neutral party freezes the account (as practicable),
- computes values using Valuation Time,
- distributes Partner B’s net entitlement,
- and returns the remainder to Partner A.

### 7) Provides a minimal protocol for Joint Assets
If joint funds buy a tangible asset, the template:
- defines titling and percentage ownership,
- allocates carrying costs,
- and provides a buyout-first / sale-second mechanism at separation.

### 8) Includes arbitration and narrow “leaver” adjustments
Disputes are routed to expedited AAA arbitration with court carve-outs for:
- protective orders,
- emergency injunctive relief,
- enforcement of awards.

The template includes narrow Good/Bad Leaver rules with high-evidence thresholds (conviction or arbitration award), intended to minimize messy fault litigation.

## Who this may be for

This template is aimed at people who:
- do **not** want marriage,
- want a **pre-agreed wealth accumulation and unwind mechanism**,
- and are willing to implement real operational controls (neutral, custody structure, compliance, recordkeeping).

It may be relevant for:
- high-trust couples who still want structured financial boundaries,
- arrangements where one partner funds and the other gains a time-based vested interest,
- couples who want periodic liquidity without renegotiating the entire relationship.

## Who this is not for

This template is likely a poor fit if:
- you cannot implement a restricted account structure with a neutral,
- you want a simple “split everything 50/50” approach,
- either party expects the agreement to replace personalized legal advice,
- there is coercion, dependency, or unsafe relationship dynamics,
- one or both parties would not realistically obtain independent counsel.

## Repository contents

- `agreement.md`  
  The main template: **Cooperative Wealth & Cohabitation Agreement (v2 — Hardened Template)**, including exhibits and addendum.

- `LICENSE`  
  The Unlicense (public domain dedication).

- (optional) `CHANGELOG.md`, `CONTRIBUTING.md`  
  If you add these later, they can document revisions and contribution norms.

## How to use

### Step 1 — Copy the template
Copy `agreement.md` into your own working document.

### Step 2 — Fill in placeholders
Search for bracketed placeholders like:
- `[Date]`
- `[State]`, `[County, State]`
- `[Insert Property Address]`
- `[Start Date]`
- `$[Monthly Deposit Amount]`
- `[Default Fund/Ticker]`
- vesting rate `[1.00]%`
- vesting cap `[50.00]%`
- Escrow/Trustee identity and contact info
- custodian/account structure details

### Step 3 — Decide on the custody/control structure
This is the most important real-world step.

The agreement is designed to become **operative only if** the Joint Account can be opened with:
- withdrawal restrictions (no unilateral access), and
- neutral execution of Liquidity Events and Separation distributions.

Common implementation patterns (jurisdiction/custodian dependent) include:
- a trust account with a professional trustee,
- an entity account (e.g., LLC) with multi-party authorization rules,
- other custodian-supported dual-control setups.

> If the structure cannot be implemented, the agreement is designed to remain **non-operative**.

### Step 4 — Engage independent counsel and tax counsel
For both parties, separately.
- Cohabitation/property rights vary widely.
- Tax characterization can vary based on account title and facts.
- Arbitration enforceability and consumer-style defenses differ by state/country.

### Step 5 — Execute with proper formalities
The template recommends:
- notarization,
- optional Certificates of Independent Legal Counsel,
- consistent operational behaviors (see Addendum A).

## Key concepts explained (plain English)

### “Vested Percentage”
A time-based percentage that represents Partner B’s earned share of the Joint Account value, capped at a maximum.

### “Valuation Time”
A standardized way to avoid disputes about intraday pricing: typically the prior trading day’s official close/NAV.

### “B Distribution Ledger”
A record of value already transferred to Partner B from the Joint Account so that later payouts are netted and not double-counted.

### “Liquidity Event”
A scheduled opportunity (every three years in the template) for Partner B to receive their earned vested value (net of ledger) without separation.

### “Deterministic Unwind”
A mechanical payout procedure upon separation that attempts to reduce negotiation, leverage, and ambiguity.

## Assumptions and limitations (read this)

1. **Custodian constraints dominate reality.**  
   Brokerages/trust companies may not support what the contract imagines. The agreement tries to handle this by making itself non-operative until implemented, and by allowing “closest practicable alternative” execution consistent with custodian rules.

2. **This template can’t guarantee enforceability.**  
   Courts/arbitrators may limit waivers, especially with inadequate disclosure, lack of counsel, coercion, or unfairness.

3. **Tax outcomes are not determined by the contract.**  
   Reporting often follows account title and IRS rules, not private agreements. The template includes cooperation language, not tax advice.

4. **Safety and consent matter.**  
   This template is not appropriate for relationships involving coercion, violence, or unsafe power dynamics. Seek help and legal protection where needed.

## Design goals

- Reduce unilateral access to pooled funds during cohabitation.
- Provide a predictable unwind rule on separation.
- Allow periodic “own-the-asset” liquidity to Partner B.
- Minimize fault-based litigation incentives via narrow leaver standards.
- Keep separate property boundaries explicit.
- Keep day-to-day household cost sharing separate from wealth mechanics.

## Contributing

Contributions are welcome, but please keep in mind:
- This is not legal advice and shouldn’t be represented as such.
- Changes should prioritize clarity, operational realism, and jurisdiction-agnostic drafting.
- Avoid adding “relationship behavior” clauses that resemble employment terms.

Suggested contribution types:
- tighter definitions,
- clearer notice mechanics,
- better custody implementation notes,
- improved exhibit structure,
- edge-case handling (death/incapacity, successor escrow agent, custodian limitations).

## License

This repository is released into the public domain under **The Unlicense**.  
See `LICENSE`.

---
