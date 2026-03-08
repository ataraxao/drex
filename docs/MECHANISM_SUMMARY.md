# Mechanism Summary — Cooperative Wealth Governance Agreement (CWA)
*Conceptual template. Not legal or tax advice.*

## 1) One-paragraph overview
The CWA is a **wealth-only, event-driven governance wrapper** for a **ring-fenced investment pool**: a restricted brokerage account held by a Vehicle LLC and administered under a defined control split. Its purpose is to reduce the “dispute surface” of relationship-adjacent wealth outcomes by making (i) allocation rules explicit, (ii) liquidity optional but scheduled, (iii) exit mechanics deterministic, and (iv) transfers-out administrator-controlled—while avoiding ongoing personal obligations, support-like promises, off-pool asset governance, and implied economic drift.

## 2) What it is / what it is not

### It *is*
- A governance protocol for a **defined pool** of assets held in the **Vehicle Account**.
- A **wealth-only** structure with **no unilateral transfers-out** by either party.
- A formula for **Allocation Percentage** accrual, with **periodic Liquidity Events** and **deterministic termination unwind**.
- A mechanism where a neutral **Independent Administrator** executes defined **Administrator Events** and maintains an **event-only B Distribution Ledger**.
- A structure that becomes operative **only after actual implementation** and written **Implementation Confirmation**.

### It is *not*
- A relationship mandate, cohabitation agreement, lifestyle contract, or household governance framework.
- Employment, wages, compensation for services, domestic labor compensation, or personal-relationship consideration.
- A promise of funding or a promise that the Vehicle Account will reach any particular size.
- A tax strategy or a promise of tax characterization.
- A shared-asset governance protocol for homes, cars, lifestyle purchases, reimbursements, or off-pool co-ownership.
- A waiver of non-waivable rights (including child-related statutory rights/obligations).

## 3) Core components (definitions in plain English)
- **Vehicle LLC:** typically a single-member LLC owned by Party A, used as the account holder for the investment pool.
- **Vehicle Account:** the restricted brokerage account titled to the Vehicle LLC.
- **Independent Administrator:** a neutral third party with authority over **transfers-out, distributions, and freeze actions** for specified events.
- **Trading Authority:** ability to trade within the account, **not** to withdraw or transfer out.
- **Allocation Percentage:** a time-based allocation key that accrues in whole months only, subject to a cap.
- **B Distribution Ledger:** an event-only ledger that records only actual completed **B Distributions** to prevent double counting.
- **Administrator Event:** only:
  1. a Liquidity distribution,
  2. a Termination unwind,
  3. dispute holdback / release of undisputed amounts, or
  4. a joint pro rata release.

## 4) The formulas (the whole point)
All entitlement calculations are **pool-only, event-driven, and net of the ledger**.

### Liquidity Settlement Amount (if elected at a Liquidity Event)
`max(0, (Vehicle Account value × Allocation %) − B Distribution Ledger)`

### Termination payout
`max(0, (Vehicle Account value × Allocation %) − B Distribution Ledger)`

The remainder goes to Party A, net of permitted fees, withholding, and other deductions reflected on custodian records or required by law/custodian constraints.

**Key property:** the ledger prevents double counting across completed Liquidity distributions, completed joint pro rata releases allocable to Party B, and final unwind.

## 5) The “Operative Date” gating (what makes it real)
The Agreement is **not operative** until the custody/control structure is actually implemented such that, in substance:

1. **No unilateral transfers-out** by either party.  
2. The Independent Administrator controls **transfers-out, distributions, and freeze actions** for Administrator Events.  
3. Party A has **Trading Authority only**.  
4. Permission-change controls prevent unilateral recipient/profile edits.  
5. Party B has view/statement access only, if any.  
6. The Administrator gives a written **Implementation Confirmation** based on actual implemented permissions/control arrangements.

If the relevant provider cannot satisfy a requirement, the Agreement remains non-operative unless the parties and the Administrator sign a **written exception** describing the constraint, the substitute controls, and any compensating restrictions.

**No implied operability by conduct:** draft onboarding, account activity, funding activity, or partial setup does not make the Agreement operative by itself.

## 6) Event flow (how it behaves in real life)

### Normal operation (no events)
- Party A may trade within the investment guardrails.
- No one unilaterally withdraws or transfers out.
- The Administrator does not perform routine monitoring, monthly accounting, or relationship supervision.

### Joint Pro Rata Release (optional; requires both parties)
- The parties may jointly instruct a release from the Vehicle Account.
- The release is allocated pro rata using Party B’s Allocation Percentage at the applicable Valuation Time.
- Party B’s portion goes to Party B’s B Designated Account and is entered on the B Distribution Ledger.
- Party A’s portion goes to Party A’s A Designated Account.

### Liquidity Event (default cadence: every 3 years) — optional
- Party B may elect a Liquidity distribution during the Liquidity Window.
- The Administrator calculates the amount by formula.
- Distribution is in kind by default where practicable, with cash fallback if needed.
- The Administrator updates the B Distribution Ledger for completed amounts only.

### Termination — at will
- Either party may terminate by notice.
- The Administrator freezes transfers-out as promptly as practicable, subject to custodian constraints.
- The account is valued at the defined Valuation Time.
- Party B is paid by formula net of the ledger.
- The remainder goes to Party A, net of permitted deductions.

### Disputes affecting distribution amounts
- The Administrator releases only undisputed amounts.
- Only the disputed incremental amount is held back pending resolution.

## 7) What is intentionally excluded
The current CWA template is intentionally **narrower** than broader hybrid variants.

It does **not** include:
- home purchase governance,
- vehicle purchase governance,
- shared tangible-asset protocols,
- reimbursement rails,
- household budgeting,
- lifestyle spending governance,
- unilateral discretionary top-up rails,
- or off-pool interpretive side channels.

If parties want to govern any of those matters, they must do so in a **separate lawyer-managed agreement**.

## 8) Dispute surface: what is minimized vs. what remains

### Minimized
- Opportunistic unilateral withdrawals from the pool.
- Negotiation over distribution amounts once an event occurs.
- Implied support-like drift within the defined pool.
- Double counting across multiple event payouts.
- Informal reinterpretation of the Vehicle Account as a general domestic payment stream.

### Still possible / explicitly preserved
- Fraud, duress, coercion, unconscionability, and public-policy challenges.
- Child-related statutory rights/obligations and other non-waivable rights.
- Custodian constraints, onboarding failures, and implementation breakdowns.
- External legal process (levies, garnishments, tax liens, bankruptcy-related process, etc.).
- Misconduct affecting the pool, handled through arbitration and the narrow restitution carveout if controls fail.

## 9) Obvious reviewer questions (short answers)
- **Is this a relationship contract?**  
  No. It is drafted as a wealth-only governance mechanism for a defined pool.

- **Is this support or compensation?**  
  The drafting is intended to avoid that characterization, but facts and jurisdiction still matter.

- **Does this require funding?**  
  No. Funding is voluntary unless a signed amendment says otherwise.

- **Does Party B get anything if the account stays small or unfunded?**  
  Possibly little or nothing. That risk is explicit in the structure.

- **Is the paper alone enough?**  
  No. The mechanism depends on actual implementation and custodian-recognized controls.

- **Can it govern houses, cars, or lifestyle assets?**  
  Not in the current wealth-only template.

## 10) What reviewers should attack
If you are reviewing this as a lawyer, tax professional, administrator, custodian ops professional, or allocator of implementation risk, the highest-value critiques are:

- What facts could cause recharacterization (support optics, partnership optics, implied economic drift)?
- Which custody stacks can or cannot actually implement the control split?
- Where does the Agreement accidentally create reliance risk or implied obligations?
- Where is unconscionability / coercion / procedural unfairness risk highest?
- What implementation gaps would let a tribunal escape the four corners of the contract?
- Are the Administrator duties truly event-only and operationally fillable?

## 11) Status
This is a conceptual template. Real-world use requires:

- independent legal counsel for both parties,
- independent tax counsel,
- a willing custodian / platform / trust company,
- and an Independent Administrator willing to implement the control structure in substance.
