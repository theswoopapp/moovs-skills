# Refund a specific payment

Reviewed 2026-10-16 from the [public refund guide](https://intercom.help/moovs-05c940f1970e/en/articles/6620447-how-do-i-process-and-track-a-refund).
Apply task-authority.md: require exact original payment, amount/method and effect
approval before refund submission. External return of money is a separate task.
Confirm company, reservation/trip, original payment, method, requested amount
and reason. A cancellation, price edit or generic paid status does not establish
which payment should be refunded. Never refund an open dispute separately.

## Reservation/trip refund

1. Open the reservation, select the trip tied to the successful payment, then
   **Edit Trip > Money > Payments**. Review that payment's status and prior refunds.
2. Its three-dot menu > **Refund** opens amount/note review. Operator enters the
   intended amount, greater than zero and no more than its remaining refundable
   amount. Check the displayed currency and exact payment, not only trip balance.
3. Explain effect: processor-backed card refunds go to the original card, not a
   different card/bank. External/cash refunds record a return but do not move
   external funds. Confirm which method is involved before the operator submits.
4. After exact current refund approval, select final **Refund** once in execution
   mode. Never issue a second external return while the outcome is unknown.
5. Refresh/reopen payment history and compare refund amount/status/remaining
   refundable amount. Multiple trip/payment allocations can need separate
   deliberate refunds; never automatically loop over all payments.

## Fixed-schedule shuttle booking

Open the fixed-schedule route and intended booking. In its **Payments**, select
the collected payment's menu > **Refund**. Operator reviews amount/note and
submits. The limit is that booking's allocated refundable amount, not the total
reservation or original multi-booking charge. Verify this booking's refund entry.

## Interpret state, not just a success label

For an existing return, compare the original payment's collected amount/status
with its refund amount/status and prior returns before deciding the next step.
A trip balance alone cannot reconcile those separate records.

- Reservation **FULL/PARTIAL** describes the refund relative to that trip's
  payment amount; it does not prove the credit posted at the customer's bank.
- Shuttle **FULL** is a success label for the refund entry, not proof the whole
  booking price was refunded. Read the amount. **PENDING** is still processing;
  **FAILED/CANCELLED** is not a completed return.
- A recent card refund can be a reversal where the original charge disappears.
  The public guide gives approximately **5–10 business days**, depending on the
  bank, not a guaranteed arrival. Check the related reservation's **View Payments**
  if the return is missing from payout history. After 10 business days, the
  cardholder checks whether the original charge disappeared and contacts their
  issuer; operator uses portal **?** Support for Moovs transaction verification.
  Do not promise bank posting from Moovs status; messages require exact send approval.

## Errors, balance limits and unknown outcomes

Refunds deduct from the payout account. The public guide describes an account's
**minimum available-refund-balance threshold**, not a universal rule that every
refund requires a positive balance; it also notes possible negative balances.
That does not override the account's threshold check. A below-minimum block is
documented before creation of refund records; pending incoming funds can affect
availability. Use the displayed explanation and Support, not another channel,
bank changes, a loan or charging another customer to overcome the restriction.

For an unable-to-verify-balance error, the guide suggests waiting briefly before
an operator-considered retry, then Support if it continues. First check the
original attempt/history: pending, ambiguous or unknown outcomes are not proof
no refund exists. Do not automatically retry or send an external reimbursement.

On failure, unexpected pending state, timeout or ambiguous history, stop and
help the operator contact **? > Support** with minimal reference/amount/time/error
and masked details only. Send only after exact recipient/content approval. Verify whether the first return
exists before proposing any retry or external repayment.

Price/balance effects are separate from returning funds. A refund does not itself
authorize new line items, cancellation, recharging, or accounting adjustments.

## Explain a partial refund followed by a new line item

For this specific combined scenario, the public guide says the original
reservation total stays unchanged, the refund appears as an **Amount Due**
adjustment and new charges are added; the customer owes the newly added charge
in its described example. Do not generalize this into a formula for every ledger.
Compare the original successful payment, refund amount/status, approved new
item and actual displayed Amount Due before explaining a discrepancy. If these
do not reconcile, stop for Support review rather than changing price or charging
again. Explaining the existing records authorizes no new item, refund or charge.
