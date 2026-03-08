# Cooperative Wealth Agreement (CWA) — Public Template

![Version](https://img.shields.io/badge/version-v1.4-blue)
![License](https://img.shields.io/badge/license-CC0_1.0-green)
![Status](https://img.shields.io/badge/status-Active_Deployment-orange)

**Canonical Whitepaper & Protocol Updates:** [ataraxao on Substack](https://ataraxao.substack.com/p/the-gravity-model-aligning-price)

**The CWA is a private, deterministic legal and financial protocol designed to make domestic equity legible through a ring-fenced capital pool.** It is a **wealth-only, event-driven governance wrapper** for a restricted brokerage account held through a Vehicle LLC, with operative-date gating, administrator-controlled transfers-out, deterministic unwind logic, and a narrow dispute surface.

---

## ⚠️ SYSTEM NOTICE: READ BEFORE DEPLOYMENT

> **1. NOT LEGAL, TAX, OR FINANCIAL ADVICE**  
> This repository and its contents are conceptual templates provided for educational and informational purposes only. The Author is a systems designer, not a provider of legal, tax, fiduciary, brokerage, custody, or investment-advisory services. No attorney-client, tax-advisor, fiduciary, or investment-advisory relationship is created by your use of these materials.

> **2. JURISDICTIONAL VARIATION**  
> Legal treatment of property rights, LLCs, arbitration, domestic relationships, separate property, equitable claims, asset characterization, and tax reporting varies significantly by jurisdiction. This protocol has not been audited for compliance with the specific laws of any state or country. Users are responsible for local legal compliance.

> **3. FINANCIAL HYGIENE AND EXECUTION RISK**  
> The effectiveness of the CWA depends heavily on disciplined implementation and strict separation between the Vehicle Account and ordinary lifestyle spending. **WARNING:** commingling, support-like side deals, recurring off-pool payments, shared expense blurring, informal promises, or treating the Vehicle LLC/account like a lifestyle wallet can materially increase litigation and tax risk and may undermine the wealth-only posture of the structure.

> **4. INDEPENDENT COUNSEL (STRONGLY ENCOURAGED)**  
> These documents should not be executed without professional review. Each party is strongly encouraged to consult independent legal counsel and independent tax counsel before signing, implementing, funding, or relying on these templates. This is especially important where there is substantial wealth disparity, cross-state or cross-border exposure, marriage risk, or unusual custody/control arrangements.

> **5. PUBLIC DOMAIN (CC0 1.0) / "AS-IS"**  
> This work is published under the CC0 1.0 Universal (Public Domain Dedication). It is provided **AS-IS**, without warranty of any kind. By using this repository, you accept that you are implementing a private contract mechanism at your own risk.

---

## 📂 Repository Structure

Start here (recommended reading order):

1. `introduction.md`  
   The conceptual overview and whitepaper-level framing for the mechanism.

2. `cooperative_wealth_agreement.md`  
   The core **Cooperative Wealth Governance Agreement** template.

3. `docs/`  
   Reviewer-facing support materials, summaries, implementation notes, admin-role notes, and other explanatory documents.

4. `LICENSE.md`  
   CC0 1.0 Universal Public Domain Dedication.

---

## What this repository contains

- `cooperative_wealth_agreement.md`  
  The core **Cooperative Wealth Governance Agreement**: a **wealth-only**, **event-driven**, **ring-fenced** governance wrapper for a restricted brokerage account held through a Vehicle LLC, with:
  - voluntary, non-enforceable funding,
  - no arrears,
  - operative-date gating,
  - an implementation control checklist,
  - an **Independent Administrator** controlling transfers-out/distributions,
  - deterministic termination unwind,
  - periodic Liquidity Events,
  - an event-only **B Distribution Ledger**,
  - administrator event priority rules,
  - record-retention / successor-handoff mechanics,
  - and arbitration + holdback mechanics.

- `introduction.md`  
  The broader mechanism thesis: make domestic equity legible through a verifiable, low-discretion structure.

- `docs/`  
  Reviewer-facing materials and implementation-oriented helpers intended to reduce overhead for legal, tax, custody, and operational review.

- `LICENSE.md`  
  CC0 1.0 Universal Public Domain Dedication.

---

## Design intent (plain English)

This template is designed to reduce the **dispute surface** by keeping the mechanism:

- **wealth-only,**
- **pool-only,**
- **event-driven,**
- **non-support-like,**
- and **operationally legible**.

Core design choices:

- **No relationship obligations.**  
  No duty to cohabit, perform services, maintain a relationship, or continue any personal arrangement.

- **No funding obligation.**  
  Funding is voluntary. There are no arrears, no back-payments, and no expectation damages based solely on stopped or reduced funding.

- **No unilateral withdrawals.**  
  The structure is designed so neither party can unilaterally transfer value out of the Vehicle Account.

- **Event-driven distributions only.**  
  Transfers-out occur only through defined **Administrator Events**:
  - a Liquidity Event election,
  - a Termination unwind,
  - dispute holdback / release of undisputed amounts,
  - or a joint pro rata release.

- **Deterministic math.**  
  Payouts are formulaic and netted against the **B Distribution Ledger** to prevent double counting.

- **No off-pool governance.**  
  This template does **not** govern homes, vehicles, lifestyle expenses, shared purchases, reimbursements, or general household economics.

- **No implied expansion from conduct.**  
  Informal payments, lifestyle help, side promises, or relationship-adjacent conduct are not supposed to reinterpret the pool as support, salary, or a domestic partnership asset stream.

---

## What this template is — and is not

### It is:
- a private contract template,
- a governance wrapper for a restricted capital pool,
- a system for allocation, liquidity, and unwind of a defined pool,
- a way to make transfers-out rule-based rather than discretionary.

### It is not:
- a marriage substitute,
- a family-law waiver kit,
- a child-support workaround,
- an employment agreement,
- a lifestyle support contract,
- a household budgeting agreement,
- an asset-protection plan for off-pool separate property,
- or legal/tax advice.

---

## Who this template is for

This template is for parties who want:

- a **verifiable wealth mechanism**, not a relationship playbook,
- clear rules for **allocation, liquidity, and unwind** of a defined pool,
- an administrator-controlled structure that reduces negotiation at exit,
- and a contract that is intentionally narrower than a general domestic arrangement.

It is most useful for people who are willing to maintain strict financial hygiene and actually implement the custody/control mechanics.

It is a poor fit for people who want:
- informal flexibility,
- merged household finances,
- recurring lifestyle support,
- or broad shared-asset governance inside the same document.

---

## Quickstart: How to use this template

### Step 0 — Do not skip counsel
Each party should retain **independent legal counsel** and **independent tax counsel**.

This is especially important if:
- there is a large wealth disparity,
- either party may relocate,
- the parties may marry,
- there are trust/entity complications,
- or the structure will be implemented with non-standard custody arrangements.

### Step 1 — Decide the key economic parameters
In `cooperative_wealth_agreement.md`, fill in the core placeholders, including:

- **Governing law / venue**
- **Monthly Accrual Rate**
- **Allocation Cap**
- **Admin Reserve**
- **Default portfolio / ticker**
- **Guardrail threshold(s)**
- any other blank operational terms relevant to the chosen implementation path

### Step 2 — Choose a real implementation path
The agreement is **not operative** until it is actually implemented and the Independent Administrator gives an **Implementation Confirmation**.

Review the Appendix implementation paths and choose a feasible custody/control setup, such as:
- LLC brokerage + administrator LPOA + recipient / transfer locks,
- directed trust / escrow-style custody,
- or institutional/RIA custody with controlled disbursements.

**Key requirement:** the relevant provider must actually recognize the authority split in substance.

### Step 3 — Choose the Independent Administrator
The Independent Administrator must be willing to:
- accept the **event-only** role,
- control transfers-out/distributions for Administrator Events,
- follow recipient restrictions,
- maintain the **B Distribution Ledger**,
- keep event records,
- and provide an **Implementation Confirmation** once the control checklist is satisfied.

### Step 4 — Form the Vehicle LLC and open the Vehicle Account
Typical structure in this template:

- Party A forms the Vehicle LLC,
- the Vehicle Account is opened in the LLC’s name,
- permissions are configured so that:
  - **Party A** = trading authority only,
  - **Independent Administrator** = transfers-out / distributions / freeze authority for Administrator Events,
  - **Party B** = view / statement access only.

### Step 5 — Make the agreement operative
The agreement becomes operative only when the Independent Administrator confirms in writing that the implementation control checklist is satisfied (or that an agreed written exception is in place).

No implementation confirmation = no operative economic mechanics.

### Step 6 — Funding
Funding is optional and voluntary.

If Party A reduces, pauses, or stops funding:
- there is no arrears claim,
- no automatic breach,
- and no implied economic right beyond assets actually in the Vehicle Account.

### Step 7 — During the term
During the operative term:
- Party A may trade within guardrails,
- no unilateral withdrawals are permitted,
- the Administrator processes only defined Administrator Events,
- the B Distribution Ledger tracks completed B Distributions,
- and the structure remains wealth-only and pool-only.

### Step 8 — Liquidity Events
At each Liquidity Event window, Party B may elect a Liquidity distribution:
- calculated by formula,
- net of prior completed B Distributions,
- paid in-kind by default where practicable,
- and entered on the ledger.

### Step 9 — Termination unwind
Either party may terminate at will.

Upon termination:
- the Independent Administrator freezes the account as promptly as practicable,
- values the Vehicle Account at the defined Valuation Time,
- pays Party B by formula net of the ledger,
- and distributes the remainder to Party A, net of permitted deductions.

---

## Practical expectations

- **The paper is not the mechanism.**  
  The real mechanism is the implemented custody/control structure.

- **Operability matters more than rhetoric.**  
  If the relevant provider does not actually support the permissions and transfer controls, the paper alone is not enough.

- **Strict hygiene matters.**  
  This structure is strongest when off-pool conduct does not contradict the contract’s wealth-only posture.

- **This is not a tax position.**  
  The template does not promise gift, compensation, partnership, or any other specific tax characterization.

- **This is not child-rights avoidance.**  
  Child-related statutory rights and obligations are not waived by this template.

- **Administrator viability matters.**  
  Fees, responsiveness, replacement, successor transition, and recordkeeping are all operationally significant.

---

## What changed in the current template direction

This public template is intentionally narrower than earlier “hybrid” variants.

Current direction:
- **wealth-only**
- **no shared-asset governance inside the core template**
- **no household/lifestyle side rails**
- **no unilateral discretionary top-up rail**
- **no off-pool interpretive expansion**
- **no implied economic rights by partial implementation or reliance before operability**

That narrowing is deliberate. The goal is to reduce ambiguity and make the dispute surface more legible.

---

## Two-tier use (general users vs. higher-complexity users)

### General users
Most users should think of the CWA as a narrow, ring-fenced account-governance mechanism:
- keep the vehicle investment-focused,
- keep the money trail clean,
- avoid support-like side conduct,
- and avoid importing off-pool issues into the same document.

### Higher-complexity / high-exposure users
Users with substantial wealth, cross-border issues, trust/entity layering, or serious litigation sensitivity will usually need:
- custom legal drafting,
- custom tax review,
- custody/provider diligence,
- and potentially separate planning outside this repository.

This repo is not a substitute for bespoke legal architecture.

---

## How to review / give useful feedback

High-signal critique is welcome.

The most useful feedback is:

- **Fillability:**  
  Can a real custodian / platform / trust company actually implement this control split?

- **Attack surface:**  
  Where would a court or arbitrator try to expand beyond “account + formula + ledger”?

- **Recharacterization risk:**  
  Which phrases, mechanics, or fact patterns create avoidable support / partnership / implied-claim risk?

- **Administrator viability:**  
  Is the event-only role realistic? Are the fee assumptions realistic? Are successor mechanics workable?

- **Operability realism:**  
  Does the implementation checklist match what real providers will actually do?

Best ways to contribute:
- open a GitHub Issue with a narrow, concrete critique,
- or submit a PR with suggested edits and a short rationale.

---

## Contributing / forks

This repo is CC0. You are free to fork, adapt, and republish.

If you build on it, consider preserving the core dispute-surface minimizers:

- operative-date gating,
- actual implementation confirmation,
- administrator-controlled transfers-out,
- recipient restrictions,
- permission-change controls,
- event-only ledgering,
- no unilateral withdrawal rights,
- and deterministic unwind logic.

---

## Attribution (optional)

Attribution is not required under CC0, but if you reference the origin, a simple form is:

`Cooperative Wealth Governance Agreement (CWA) — CC0 public template`

---

## 📡 Protocol Updates

For macroeconomic framing, structural discussion, and protocol-level updates:

**[ataraxao on Substack](https://ataraxao.substack.com)**

---
