# Incoming farm requests, integrations and settlement

Reviewed 2026-10-15. Operator handles integration edits, sends, accept/deny,
booking changes and all financial actions. Never request card numbers or codes.

## GNet / GriddNet

**Outbound scope remains unresolved here.** July2025 advertised GNet farm-out to
other systems with compatibility qualifications and invited operators to contact
Moovs. Current public GNet Help documents **receipt**, not outbound destination
setup/submission. Receiving rides does not prove outbound access or compatibility.
For outbound work, confirm the intended destination system and obtain current
supported instructions/availability from Moovs before any request; do not reuse
the receipt setup or ordinary Moovs-affiliate farm-out as an outbound GNet guide.
[July2025, 32:38-33:13](https://fast.wistia.com/embed/iframe/lx539nwwlt?wtime=1958s).

Use setup only for an intended integration-identity change; a missing-trip request
normally needs delivery diagnosis, not a speculative ID edit.

## Configure GNet receipt

After registration and partnership in GNet, published Moovs setup is **Contacts >
Affiliates > ... > Manage Gnet Id**. Operator verifies their own GriddNet profile
identifier, enters it and **Save**. Do not change an ID as a speculative fix.
Reopen the intended setting and privately compare the saved identifier; setup
alone is not evidence a particular trip was delivered.

## Diagnose a missing GNet trip

For a missing trip: confirm sending partner used intended GNet ID and trip shows
sent in GNet. Ask GNet to verify delivery-to-Moovs configuration and consider a
resend only after checking current Moovs state for duplicates. Delivery is linked
to GNet ID, not a reservation email; no manual sync is described as necessary.
Do not confuse a separate trip-sheet email workflow with GNet. Escalate confirmed
delivery discrepancy to provider/Support rather than inventing an import action.

[GNet setup and delivery](https://intercom.help/moovs-05c940f1970e/en/articles/6602609)

## Trip-sheet Assistant, not a general email importer

Published Assistant Farm-in supports LimoAnywhere and SantaCruz trip-sheet PDFs,
creation only, not automatic trip updates/cancellations. Use the access, sending
or incoming-review scope below; it is separate from GNet.

## Request Assistant access and configure the partner recipient

Operator requests access through Support, obtains the unique Farm-in email and
provides it privately to the intended compatible affiliate. Never guess the
address or publish it in a reusable template. Partner updates its reservation
system with that verified recipient; LimoAnywhere must send a Farmout Trip Sheet.
Confirm granted access and partner-recipient configuration without submitting a
test trip merely to check setup. Configuration is not a received reservation.

## Submit a supported affiliate trip sheet

For a supported farm-out request by email, the operator prepares required pickup/
drop-off locations, date/time, vehicle type and passenger name in the Affiliate
Trip Sheet PDF, verifies destination and sends. Avoid copying the private sheet
into assistant chat. Sending is not acceptance or a guarantee of import.

## Review an Assistant-created farm-in

On received farm-in, inspect the generated reservation against source through an
authorized view, including date/time/timezone, route, vehicle and price. Operator
**accepts or denies** only after review: acceptance notifies the affiliate;
denial removes the trip and notifies them. Do not deny merely to hide a duplicate
without understanding consequences. Check existing record before resending.

Updates need separate partner communication and manual review. Public guidance
routes unsupported cancellation/deletion to Support; do not invent backend/API
steps or assume a revised PDF overwrites a booking.

[Farm-in Assistant limits](https://intercom.help/moovs-05c940f1970e/en/articles/7957083), [Sending a supported request](https://intercom.help/moovs-05c940f1970e/en/articles/7860449)

## Dated farm-in visibility and payer context

July2025's explicitly labeled test-account narration describes a Moovs farm-in
with passenger first name/last initial, limited contact visibility, no trip
editing and the affiliate as booking contact/payer rather than the end customer.
The earlier external-affiliate email/trip-link answer is a different recipient
path. These are dated narrated examples, not a current universal privacy/permission
matrix or permission to retrieve masked information. Check the actual farm-in
scope and current supported guidance; do not edit through another surface, expose
hidden details or charge anyone merely because the demo called them the payer.
The settlement-direction checks below still apply.
[July2025, 44:11-44:44; 47:02-48:00](https://fast.wistia.com/embed/iframe/lx539nwwlt?wtime=2651s).

## Settlement: stop when direction is unclear

Reviewed 2026-10-16 against complete public Help bodies and literal Help forms.
First identify company, exact trip/date, farm direction, partner type, actual
payer/payee, agreed obligation/amount and existing payments or pending attempts.
Farm-in service generally creates this company's receivable from the sending
affiliate; farm-out service creates its payable to the servicing affiliate.
The customer's transportation charge is a separate obligation. The business
agreement and actual record must establish direction, not an article's “Pay”
title, a saved card, Total Amount or a Paid/Not Paid label.

When those facts are known, use the applicable complete path below; do not stop
an established farm-in receivable solely because a source title says “pay.”
When direction, authority or current financial effect is unresolved, stop before
card setup/submission and clarify it with the operator or Support.

### Collect an authorized Moovs-network affiliate farm-in receivable

This path is for this company servicing a **farm-in**, with the sending **Moovs
affiliate as authorized payer**. It charges that affiliate's actual saved card
for the established receivable; it does not pay out a farm-out partner or charge
the end passenger. Do not extend this network-specific card guide to external
partners or GNet merely because they also appear in Affiliates.

1. Match the completed farm-in, sending affiliate, authorized amount/currency
   and payment scope. Inspect current trip payments/refunds and any uncertain or
   pending attempt before considering another collection. Confirm actual account
   processing access and the payer's authorization for this exact charge.
2. Open **Contacts > Affiliates**, find that Moovs affiliate and open its profile.
   Review its existing **Credit Cards** first. If the authorized card is missing,
   the operator uses **Add Card**, privately enters the card/billing information
   in the actual form and **Save**. Pause assistant inspection during sensitive
   entry; do not ask for card data in chat or save it in notes. Saving a card is
   not collection, a payout, or proof of authorization for other charges.
3. Reopen the intended **farmed-in reservation**. For the one intended trip, Help
   gives **Edit Trip > Money > Charge Customer**; Money also shows prior payments
   and refunds. The reservation-wide **Charge Reservation** route can distribute
   a payment across all trips, so do not use it for a single-trip obligation.
4. In the actual charge form the operator reviews the established amount,
   correct affiliate's actual Moovs-linked card/payment method, currency and
   trip scope, with the displayed resulting balance. Do not select generic Card,
   cash or another record-only method to simulate collection. If the affiliate's
   authorized card is not offered or the form would charge a different party,
   stop and resolve that mismatch rather than saving the card elsewhere.
5. After reviewing the exact financial effect and payer authorization, the
   operator performs the supported **Charge Customer** submission for that
   agreed amount. The assistant never submits a financial demonstration.
6. Reopen the same trip's **Money** history and compare the exact attempt's
   amount, method/payer, transaction status and resulting balance with the
   intended collection. A saved card, toast, generic Paid label or pending entry
   is not successful collection. Pending/failed/uncertain results need current
   history and supported follow-up before any retry, not an automatic second
   charge or refund/recharge. Report browser-read versus operator-reported
   evidence honestly. A successful charge is not proof the processor has paid
   funds into this company's bank; settlement/payout timing is separate.

[Affiliate card and farmed-in charge intent](https://intercom.help/moovs-05c940f1970e/en/articles/9113671), [Actual trip/reservation payment forms and Money readback](https://intercom.help/moovs-05c940f1970e/en/articles/6415309), [Generic Card and processor-settlement distinctions](https://intercom.help/moovs-05c940f1970e/en/articles/13289137)

### External farm-out payable: outside payment, not a proven Moovs payable write

For a clear **farm-out**, this company owes the servicing affiliate. The external
article explicitly says that external-affiliate payouts happen **outside Moovs**.
Match the exact partner/trip and agreed payable, review prior/pending outside
payments, and let the authorized operator handle the agreed outside payment in
its actual provider. No bank/card details belong in assistant chat. Read the
provider's actual status/evidence privately; pending is not paid and uncertain
results must be reconciled before any repeat. These Moovs sources do not document
that outside provider's submission flow or prove an outside transfer succeeded.

The same article says close completed work normally, settle outside Moovs, then
**Charge > applicable Payment Method > Charge**. Its pre-submission image instead
labels the form **Charge Customer** and both before/after figures **Reservation
Amount Due**. A separate cropped FARM-OUT pane shows Payable, Amount Paid and
Not Paid; no completed Charge result establishes a payable update. Do not route
an already-paid payable into a customer receivable entry or infer a record-only
payable action from those images. Get the current supported obligation/method/
accounting effect from Support before any such Moovs financial submission.
For a Moovs-network farm-out, the network article's farm-in card-charge procedure
likewise does not establish an outgoing affiliate payout workflow.
[External payout and unresolved recording](https://intercom.help/moovs-05c940f1970e/en/articles/9675649), [Network farm-in charge, not farm-out payout](https://intercom.help/moovs-05c940f1970e/en/articles/9113671).

### Review an external affiliate's settlement evidence

This is the existing **Reconcile existing partner work** task, not a second
settlement task or a payable-recording workaround.

1. Open **Contacts > Affiliates > intended partner > Trips**. Match date,
   confirmation, **Type** (Farm-in/Farm-out) and the intended obligation against
   actual outside-payment evidence held privately by the operator. Distinguish
   money received for this company's service from money paid to another company.
   Help calls Total Amount the designated trip amount; do not assume it means
   the affiliate payable or customer receivable without confirming the record.
2. External trips may show **Not Paid** after outside settlement. State which
   obligation and actual evidence were checked; do not collect/pay again to
   clear that label or claim it proves either an outstanding or settled payable.
3. If separately requested, the operator may add a minimal non-sensitive internal
   reservation comment through the actual available controls, then reopen and
   compare the saved reminder. Stop if the audience/effect is unclear. The guide
   offers a comment but does not name its editor; a comment is not a payment
   entry or independent proof of settlement. Without direct readback, label the
   evidence/operator action operator-reported rather than verified.
[Affiliate trip review and internal reminder](https://intercom.help/moovs-05c940f1970e/en/articles/8268255).

For a separately established **customer receivable** or actual **invoice receipt**,
use its correctly scoped payment guidance, not an affiliate-payable interpretation.
Generic Card can mark a reservation Paid without Moovs collection. Free Help does
not support marking trip payments Paid with external methods; do not bypass it.
These customer/invoice methods do not establish outgoing affiliate settlement.
[Customer payments](https://intercom.help/moovs-05c940f1970e/en/articles/6415309), [Record discrepancies](https://intercom.help/moovs-05c940f1970e/en/articles/13289137), [Invoice receipts](https://intercom.help/moovs-05c940f1970e/en/articles/6703099).
