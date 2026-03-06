# Cooperative Wealth Agreement (CWA) — Public Template

![Version](https://img.shields.io/badge/version-1.0-blue)
![License](https://img.shields.io/badge/license-CC0_1.0-green)
![Status](https://img.shields.io/badge/status-Active_Deployment-orange)

**Canonical Whitepaper & Protocol Updates:** [ataraxao on Substack](https://ataraxao.substack.com/p/the-gravity-model-aligning-price)

**The CWA is a private, deterministic legal and financial protocol designed to privatize domestic equity.** It functions as a wealth-only, event-driven governance wrapper for a ring-fenced capital pool, replacing subjective family law APIs with strict corporate contract law, algorithmic vesting, and a deterministic unwind.

---

## ⚠️ SYSTEM NOTICE: READ BEFORE DEPLOYMENT

> **1. NOT LEGAL, TAX, OR FINANCIAL ADVICE**
> This repository and its contents (The CWA Protocol v1.0) are conceptual templates provided for educational and informational purposes only. The Author is a systems designer, not a provider of legal, tax, or fiduciary services. No attorney-client or fiduciary relationship is created by your use of these documents.

> **2. JURISDICTIONAL VARIATION**
> Standard legal frameworks regarding property rights, LLC characterization, domestic partnerships, and the equitable distribution of assets vary significantly by jurisdiction. This protocol has not been audited for compliance with the specific laws of any state or country. Users are responsible for ensuring local legal compliance.

> **3. FINANCIAL HYGIENE AND EXECUTION RISK**
> The effectiveness of the CWA depends entirely on the user's ability to maintain strict financial separation. **WARNING:** Routine commingling (treating the Vehicle Account/LLC like a spending account, paying lifestyle expenses, or blurring account ownership and recipient controls) can materially increase legal and tax risk, and may undermine the dispute-surface minimization intended by this structure.

> **4. INDEPENDENT COUNSEL (STRONGLY ENCOURAGED)**
> These documents should not be executed without professional oversight. Each party is strongly encouraged to consult with independent legal and tax counsel to review and adapt these templates to their specific financial situation and jurisdiction. It is ideal to work with professionals familiar with LLC account control structures, arbitration provisions, and relevant gift tax reporting.

> **5. PUBLIC DOMAIN (CC0 1.0) / "AS-IS"**
> This work is published under the CC0 1.0 Universal (Public Domain Dedication). It is provided "AS-IS" without warranty of any kind. By using this repository, you acknowledge that you are managing your assets through private contract and assume all associated risks.

---

## 📂 Repository Structure

Start here (recommended reading order):

```text
├── introduction.md                 # The explanatory whitepaper (“Gravity Model”) motivating the mechanism.
├── cooperative_wealth_agreement.md # The core legal contract template (the instrument).
├── docs/                           # Reviewer pack / supporting documents for evaluation and implementation.
└── LICENSE.md
```

## What this repository contains

- `cooperative_wealth_agreement.md`  
  The **Cooperative Wealth Governance Agreement**: a wealth-only, event-driven governance wrapper for a **ring-fenced pool** (a restricted brokerage account held by a Vehicle LLC), with:
  - voluntary (non-enforceable) funding,
  - an **Independent Administrator** who controls transfers-out/distributions,
  - an **operative-date gating** requirement with an **implementation control checklist**,
  - a deterministic termination unwind,
  - periodic Liquidity Events,
  - a minimal Joint Asset protocol,
  - an event-only B Distribution Ledger (anti-double-counting),
  - optional **Discretionary Top-Ups** (Funding Partner optional; ledgered and netted),
  - and dispute-resolution + holdback mechanics.

- `introduction.md`  
  The “Gravity Model” paper: **make domestic equity legible via an explicit, verifiable mechanism**.

- `docs/`  
  Reviewer-facing materials and implementation-oriented helpers (e.g., mechanism summary, admin role spec, term sheet / review notes, etc.).  
  *Goal:* reduce “intellectual overhead” for professional reviewers and focus critique on fillability + attack surface.

- `LICENSE.md`  
  CC0 1.0 Universal Public Domain Dedication.

## Design intent (plain English)

This template is designed to reduce the “dispute surface” by keeping the agreement **governance-only** and **ring-fenced**:

- **No relationship obligations.** No duties to cohabit, perform services, or maintain a relationship.
- **No funding obligation.** Any funding targets are non-binding; there are **no arrears**.
- **No unilateral withdrawals.** The account is set up so neither party can unilaterally transfer-out.
- **Event-driven distributions only.** Transfers-out occur only on:
  - Liquidity Events (if elected), or
  - Termination unwind, or
  - dispute holdback + release of undisputed amounts,
  - plus optional **Discretionary Top-Ups** initiated solely by the Funding Partner (recorded as B Distributions for anti-double-counting).
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
The agreement is **not operative** until the account is actually implemented with the required control split and the Independent Administrator provides an **Implementation Confirmation**.

Use the contract’s Appendix (“Implementation Paths”) to pick a feasible custody/control setup, such as:
- LLC brokerage + administrator LPOA + transfer/recipient locks, or
- directed trust / escrow-style custody, or
- institutional/RIA custody with controlled disbursements.

**Key requirement:** neither party can unilaterally transfer-out, and the Independent Administrator can execute Administrator Events.

### Step 3 — Choose and engage the Independent Administrator
The Independent Administrator must:
- accept the **event-only** role,
- agree to recipient restrictions (only the designated accounts + fees/withholding),
- maintain the event-only **B Distribution Ledger**,
- and provide an **Implementation Confirmation** once the custody setup satisfies the implementation control checklist.

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
- Optional: Party A may authorize **Discretionary Top-Ups** to Party B (processed by the administrator to Party B’s designated account and recorded in the ledger).

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
- **This is not a tax strategy.** The template explicitly does not promise any tax characterization; certain transfers may be treated as gifts depending on facts and law.
- **This is not child support avoidance.** Child-related statutory rights and obligations are not waivable by private contract.
- **Administrator transition exists.** The contract includes resignation and replacement mechanics (including replacement by joint instruction), plus dispute-resolution tools to preserve the control structure during transitions.
- **Narrow restitution carve-out exists.** The contract contains a narrow outside-the-pool restitution remedy for intentional dissipation not prevented by the controls (as determined by a final award).

## Two-tier use (general users vs. HNW)

This template is designed for broad adoption as a governance-only, ring-fenced account mechanism.

- **General users (most people):** The CWA is typically used as a standalone governance wrapper for a restricted investment pool. The main risk controls are operational: keep the vehicle investment-only, avoid commingling, and keep shared purchases inside the Joint Asset protocol.

- **HNW / high-exposure users:** Many sophisticated users also implement separate structural planning (trusts/entities and jurisdictional planning) to reduce tail risk if the agreement is attacked in litigation. This repository does not provide asset-protection or estate-planning advice. If you have substantial wealth or complex cross-state exposure, consult specialized counsel.

## How to review / provide feedback (high-signal critique welcome)

If you’re reviewing as a lawyer, custodian ops, trust/escrow admin, mediator, or tax professional, the highest-value feedback is:

- **Fillability:** can your custody stack actually implement the authority split, permission-change control, and recipient restrictions?
- **Attack surface:** where would a court/arbitrator expand beyond “account + formula + ledger”?
- **Recharacterization risk:** partnership/support optics and how to reduce them without adding obligations.
- **Administrator viability:** event-only workload, fee realism, refusal/transition conditions.

Best ways to contribute:
- Open a GitHub Issue with your critique (small, specific, actionable).
- Or submit a PR with suggested edits and short rationale.

## Contributing / forks

This repo is CC0. You are free to fork and adapt. If you publish improvements, consider keeping:
- the event-driven architecture,
- recipient restrictions,
- operative-date gating,
- permission-change controls,
- and ledger anti-double-counting,
since those are the core dispute-surface minimizers.

## Attribution (optional)

Attribution is not required under CC0, but if you reference the origin:
- “Cooperative Wealth Governance Agreement (CWA) — CC0 public template.”
