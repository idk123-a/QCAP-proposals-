# Proposal: Temporary Burn Replenishment for QVAULT and QBOND

## Summary

This proposal requests a modification of the existing burn replenishment mechanism to restore the burn reserves of QVAULT (Contract 10) and QBOND (Contract 17), which were depleted during a spam event.

No funds are requested from the CCF, and no additional QUBIC will be created or distributed. The proposal only modifies how a portion of the existing replenishment burns are allocated.

---

## Background

QVAULT and QBOND accumulated burn reserves during their IPO phases. These reserves were designed to support the long-term sustainability and operation of their respective smart contracts.

During a period of abnormal transaction activity, both contracts experienced rapid reserve depletion. The event coincided with an unexpectedly high smart contract fee multiplier, which significantly accelerated reserve consumption rates.

As a result, reserves that had been accumulated over an extended period were depleted within a relatively short timeframe.

The activity primarily originated from a single address repeatedly interacting with the affected contracts.

### Evidence

The following screenshots illustrate examples of the transaction activity associated with the reserve depletion event:

![Spam Activity 1](PLACEHOLDER_IMAGE_1)

![Spam Activity 2](PLACEHOLDER_IMAGE_2)

![Spam Activity 3](PLACEHOLDER_IMAGE_3)

---

## Mitigation Measures

Following the incident, Qubic Capital immediately implemented and funded mitigation measures.

- QVAULT has already been updated to introduce usage fees that significantly increase the cost of abusive transaction activity.
- A corresponding update for QBOND is currently being implemented and has already been proposed separately.

All development, testing, deployment, and maintenance costs associated with these improvements have been fully covered by Qubic Capital.

No reimbursement for these expenses is requested through this proposal.

---

## Proposal

Modify the existing burn replenishment contract to allocate a portion of the current replenishment burns to the following smart contracts:

| Contract | Smart Contract | Replenishment Amount |
|----------|---------------|----------------------|
| 10 | QVAULT | 38.3 Billion QUBIC |
| 17 | QBOND | 6.25 Billion QUBIC |

The total amount burned per epoch remains unchanged.

No additional funding from the CCF is required.

---

## Rationale

This proposal seeks to restore reserves that were originally generated through the IPO process and later depleted under exceptional circumstances.

The requested change does not increase network expenditure and does not require new funding. Instead, it reallocates a portion of the existing burn replenishment mechanism to support the recovery of two affected smart contracts.

This approach preserves the original economic framework of QVAULT and QBOND while minimizing impact on the broader ecosystem.

---

## Voting Options

### Option 0

Reject the proposal.

### Option 1

Approve the modification of the burn replenishment contract to allocate:

- **38.3 Billion QUBIC to Contract 10 (QVAULT)**
- **6.25 Billion QUBIC to Contract 17 (QBOND)**

through the existing burn replenishment mechanism.

---

## Acknowledgements

We would like to thank the Computors for temporarily suspending the fee multiplier changes following the incident. This provided affected projects with valuable time to assess the situation, implement mitigation measures, and respond appropriately.

We also thank the Computors for considering this proposal and for their continued support of the Qubic ecosystem.

**Qubic Capital Team**
