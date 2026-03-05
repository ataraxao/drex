# Independent Administrator Role Spec (Event-Only)
*Conceptual template. Not legal or tax advice.*

## 1) Role summary
The Independent Administrator is a neutral party who **controls transfers-out/distributions/freeze actions** for a restricted Vehicle Account and executes only **event-driven instructions under the Agreement**. The Administrator’s duties are limited to:
- **Administrator Events** (Liquidity Events, Termination unwind, and dispute holdback/release of undisputed amounts), and
- **Discretionary Top-Ups** (only if instructed by Party A under the Agreement, and only to Party B’s B Designated Account).

The Administrator is not a portfolio manager, relationship mediator, or fact finder.

## 2) Actions the Administrator performs (and only these)
### A) Administrator Events (as defined in the Agreement)
1) **Liquidity Event distribution** (only if Party B makes a valid Liquidity Election during the Liquidity Window)
2) **Termination unwind** (upon effective termination notice or deemed termination trigger)
3) **Dispute holdback + release of undisputed amounts** (when notified of a dispute affecting distribution amounts)

### B) Discretionary Top-Up processing (not an Administrator Event)
4) **Discretionary Top-Up** (only upon Party A’s written instruction copied to Party B, and only to Party B’s B Designated Account)

## 3) What the Administrator MUST be able to do (capability requirements)
- Execute transfers-out/distributions **only to permitted recipients**:
  - A Designated Account (Party A)
  - B Designated Account (Party B)
  - custodian fees / required withholding recipients
  - any other recipient **only if required** by a final arbitration award, court order, or applicable law
- Freeze transfers-out (subject to custodian constraints)
- Implement in-kind distributions when practicable (cash fallback allowed)
- Maintain an **event-only B Distribution Ledger** (recording B Distributions actually executed)
- Provide an **Implementation Confirmation** when the control split is correctly established (including satisfaction of the Agreement’s implementation control checklist, subject to custodian constraints and any written exceptions)

**Recipient restriction is strict:** the Administrator should refuse any request to transfer to non-designated recipients unless required by a final arbitration award, court order, or applicable law.

## 4) What the Administrator must NOT do (explicit non-duties)
- No investment advice, suitability determinations, or portfolio management
- No monthly accounting or routine monitoring
- No adjudication of misconduct, coercion, or “who’s right”
- No interpretation beyond the document’s plain event instructions absent a final award/order

## 5) Ledger scope (event-only)
The B Distribution Ledger records **only**:
- date of event
- valuation time reference (per custodian record)
- amount distributed (valued at that valuation time)
- distribution form (in-kind / cash)

No requirement for continuous NAV tracking or performance reporting.

## 6) Reliance standard
The Administrator may rely on:
- notices effective per the Agreement’s notice rules
- facially valid signatures/elections
- facially valid arbitration awards/court orders authorizing action

The Administrator has no duty to investigate facts beyond documents received.

## 7) Fee models (illustrative)
Choose one:
- **Per event:** $X per Liquidity distribution; $Y per Termination unwind; plus expenses
- **Hourly:** $X/hour for event processing; plus expenses
- **Retainer + per event:** modest retainer to ensure availability + lower per-event fee

The Agreement should maintain an **Admin Reserve** to pay earned fees from the Vehicle Account.

## 8) Refusal / resignation criteria (recommended)
The Administrator may refuse to serve or may resign if:
- the custodian cannot implement controls that meet the minimum viable requirements
- either party attempts to pressure the Administrator to act outside the Agreement’s permitted actions
- identity/recipient documentation is insufficient under custodian policy
- there are credible safety threats to the Administrator

## 9) Implementation packet (what the Administrator should keep on file)
- authority split documentation (custodian permissions + LPOA/control instruments)
- recipient whitelist / transfer locks confirmation (if supported)
- Designated Account verification for each party
- current ledger
- successor/transition instructions

## 10) Successor transition (minimum expectation)
If replaced, the Administrator should deliver to the successor:
- the current B Distribution Ledger
- event documentation necessary to continue event processing

Transition is ministerial; the Administrator is not responsible for disputes.
