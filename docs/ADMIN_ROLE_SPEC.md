# Independent Administrator Role Spec (Event-Only)
*Conceptual template. Not legal or tax advice.*

## 1) Role summary
The Independent Administrator is a neutral administrative control party who **controls transfers-out, distributions, and freeze actions** for the restricted Vehicle Account and executes only **event-driven actions authorized by the Agreement**.

The role is intentionally narrow. The Administrator’s duties are limited to:
- **Administrator Events** under the Agreement:
  - Liquidity Event distributions,
  - Termination unwind,
  - dispute holdback and release of undisputed amounts,
  - joint pro rata releases, and
- related ministerial actions reasonably necessary to implement those events, subject to custodian constraints and applicable law.

The Administrator is **not**:
- a portfolio manager,
- a relationship mediator,
- a fact finder,
- a tax or legal advisor,
- or a general account monitor.

---

## 2) Actions the Administrator performs (and only these)

### A) Administrator Events
1. **Liquidity Event distribution**  
   Only if Party B makes a valid Liquidity Election during the Liquidity Window.

2. **Termination unwind**  
   Upon an effective Termination Notice or a Deemed Termination Event under the Agreement.

3. **Dispute holdback + release of undisputed amounts**  
   When notified of a dispute that would change distribution amounts.

4. **Joint Pro Rata Release**  
   Only upon joint written instruction of both Parties, and only to the Parties’ permitted Designated Accounts in pro rata amounts determined under the Agreement.

### B) Related ministerial actions
5. **Freeze / suspension of transfers-out**  
   As required by the Agreement, custodian constraints, a final arbitration award, court order, or applicable law.

6. **Minimum necessary liquidation**  
   When needed to fund a permitted cash distribution, required withholding, or earned administrator fees/costs, subject to the Agreement and custodian constraints.

7. **Successor transition / record handoff**  
   If replaced or resigning, provide the successor with the current ledger and event-status records reasonably necessary for continuity.

---

## 3) What the Administrator MUST be able to do (capability requirements)
The Administrator should be operationally able to:

- execute transfers-out/distributions **only to permitted recipients**:
  - **A Designated Account** (Party A),
  - **B Designated Account** (Party B),
  - the custodian and/or governmental recipients for fees, withholding, or charges imposed by law or custodian policy,
  - any other recipient **only if required** by a final arbitration award, court order, or applicable law

- freeze or suspend transfers-out, subject to custodian constraints

- process:
  - in-kind distributions when practicable
  - cash fallback distributions where in-kind is impracticable or not permitted

- maintain an **event-only B Distribution Ledger**, recording only B Distributions actually completed

- recognize the difference between:
  - **completed distributions** and
  - **pending / partial distributions**

- provide an **Implementation Confirmation** only when the required authority split and control checklist are actually established in substance, subject to custodian constraints and any agreed written exceptions

- retain and hand off basic event records sufficient for successor continuity

**Recipient restriction is strict:** the Administrator should refuse any request to transfer to non-permitted recipients unless required by a final arbitration award, court order, applicable law, or external legal process that must be honored.

---

## 4) What the Administrator must NOT do (explicit non-duties)
The Administrator has no duty to:

- provide investment advice, tax advice, or legal advice
- make suitability determinations
- manage the portfolio or supervise investment strategy
- perform monthly accounting or continuous NAV/performance reporting
- adjudicate misconduct, coercion, fairness, or “who is right”
- investigate facts beyond facially valid documents received
- monitor the relationship, household, or off-pool conduct of the Parties
- create or infer new rights beyond the Agreement’s event instructions
- process ordinary personal-expense payments for either Party

---

## 5) Event scope and ledger scope (event-only)
The **B Distribution Ledger** should record **only completed B Distributions** under the Agreement.

Recommended ledger fields:
- triggering event type
- event date
- valuation time reference
- amount distributed
- distribution form (cash / in-kind)
- completed vs. partial-completion status
- custodian confirmation/reference sufficient to tie the entry to official records

The Administrator is **not** expected to perform:
- continuous valuation,
- intraday mark tracking,
- performance attribution,
- or household-style accounting.

---

## 6) Reliance standard
The Administrator may rely on:

- notices effective under the Agreement’s notice rules
- facially valid signatures, elections, and joint instructions
- facially valid arbitration awards and court orders
- facially valid documents establishing an **Authorized Representative**
- facially valid documentation regarding recipient accounts and titling
- reasonably available custodian-operational records
- external legal process requiring compliance, subject to applicable law

The Administrator has **no duty to investigate facts beyond documents received**, absent actual knowledge of a material defect.

---

## 7) Event priority / sequencing
If multiple events overlap, the Administrator should follow the Agreement’s sequencing rules.

General priority logic:
1. legal restraints, mandatory withholding, final awards, and court orders
2. termination / deemed termination
3. dispute holdback affecting distribution amounts
4. other in-term Administrator Events

The Administrator should avoid **double-processing the same unreleased value** and should preserve already completed distributions unless a final award/order requires otherwise.

---

## 8) Form of distribution
The Administrator should process distributions as follows:

- **Liquidity Events:** in kind by default when practicable; cash fallback where needed
- **Termination unwind:** cash by default unless in-kind is jointly instructed, required by custodian constraints, or otherwise permitted by the Agreement
- **Joint Pro Rata Releases:** cash and/or in-kind as jointly instructed, subject to the Agreement and custodian constraints

All distributions should go only to the relevant permitted recipient account.

If recipient details are invalid or incomplete, the Administrator may hold the affected portion pending cure rather than forfeiting or reallocating it, except as the Agreement expressly provides.

---

## 9) External legal process / compliance-first handling
If the Administrator or custodian receives:
- a levy,
- garnishment,
- restraining notice,
- turnover demand,
- subpoena,
- tax lien,
- bankruptcy notice,
- receivership order,
- or similar external legal process,

the Administrator may:
- comply with applicable law and custodian policy,
- place a protective hold,
- suspend non-mandatory event processing,
- and preserve the Agreement’s mechanics only to the extent consistent with the external process and applicable law.

The Administrator should not be expected to resist external legal process at personal risk.

---

## 10) Fee models (illustrative)
Choose one:

- **Per event:** $X per Liquidity distribution; $Y per Joint Pro Rata Release; $Z per Termination unwind; plus expenses
- **Hourly:** $X/hour for event processing; plus expenses
- **Retainer + per event:** modest retainer for availability plus lower per-event fees
- **Attached schedule:** custom fee exhibit

The Agreement should maintain an **Admin Reserve** so earned fees and reasonable costs can be paid from the Vehicle Account before completing the relevant event.

---

## 11) Refusal / resignation criteria (recommended)
The Administrator may refuse to serve, refuse a specific requested action, or resign if:

- the custodian cannot implement controls meeting the minimum viable requirements
- the Agreement has not become operative
- either Party pressures the Administrator to act outside the Agreement
- recipient or identity documentation is insufficient under custodian policy
- the requested action would violate law, custodian policy, or an external legal restraint
- fees/costs are not reasonably fundable from the Vehicle Account
- there are credible safety, compliance, or reputational threats to the Administrator
- successor transition is necessary and the Parties fail to cooperate

---

## 12) Implementation packet (what the Administrator should keep on file)
The Administrator should retain, at minimum:

- authority-split documentation
  - custodian permissions
  - LPOA/control instruments
  - account control summaries
- Designated Account verification for each Party
- implementation confirmation or implementation-status records
- recipient restrictions / transfer lock confirmation, if supported
- current **B Distribution Ledger**
- material event-status records
- copies of material notices:
  - Liquidity Elections
  - Termination Notices
  - dispute notices affecting distribution amounts
  - joint release instructions
- successor / transition instructions, if any

---

## 13) Record retention
Recommended minimum retention:

- retain ledger and material event records for at least **7 years** after:
  - final distribution and account closure, or
  - handoff to a successor Administrator,
  whichever occurs first,

subject to any longer period required by:
- law,
- court order,
- arbitration order,
- professional obligations,
- litigation hold,
- or custodian policy.

---

## 14) Successor transition (minimum expectation)
If replaced, resigning, or becoming unavailable, the Administrator should provide the successor, to the extent reasonably practicable:

- the current **B Distribution Ledger**
- material event-status records
- pending vs. completed event information
- implementation/control records reasonably necessary for continuity
- copies of material notices and instructions relevant to ongoing events

Transition is ministerial and administrative only. The outgoing Administrator is not responsible for resolving disputes between the Parties.

A successor should not be required to restart an event from the beginning solely because of the transition if reasonably sufficient records exist to continue.

---

## 15) Practical fit check (before anyone hires this role)
Before serving, an Administrator should confirm:

- the chosen custodian can actually support the role in substance
- the recipient restrictions are workable
- the authority split is real, not aspirational
- the fee model matches the expected workload
- the role is truly **event-only**, not disguised case management or relationship supervision

If those conditions are not met, the mechanism is likely not operationally fillable.
