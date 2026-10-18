# Initial setup, authorizations and payment interpretation

Reviewed 2026-10-16 from public guidance. Follow task-authority.md: consequential
controls need exact current approval; sensitive entry stays private with its owner.
No live test charge is implied.

## Initial Moovs Payments setup

First check paid-plan eligibility, owner permissions and the visible Payments
status. Free cannot use Stripe-backed payments. Moovs Payments uses built-in
Stripe-backed processing, not a connection to a personal/standalone Stripe
account. Never request Stripe API keys or create an external account as a fix.
[Moovs Payments](https://intercom.help/moovs-05c940f1970e/en/articles/6634535-what-is-moovs-payments).

The [self-service guide](https://intercom.help/moovs-05c940f1970e/en/articles/6945967-how-do-i-set-up-moovs-payments)
uses **Settings > Payments**, business type, **Complete Account Setup**, then
secure business/owner verification. After the questionnaire returns to Payments,
the operator privately uses **Add Bank Account** for the payout destination.
Explain the required categories without collecting EIN, SSNs, ownership/identity
documents or bank numbers. Pause inspection for the entire questionnaire and bank
entry. Return only to masked/non-sensitive connected or pending status; adding a
bank is not choosing a currency default, a test charge or a payout.

The older [Payments Settings guide](https://intercom.help/moovs-05c940f1970e/en/articles/6383795-payments-settings)
describes assisted connection. Disclose that these public setup routes differ;
follow the actual secure workflow offered or ask Moovs Support rather than
inventing an invitation, emailing identity/bank documents, or promising instant
approval. On return, inspect only non-sensitive connected/pending/restricted
status. Setup submission is not approval, a successful payment or a bank payout.
Existing payout/bank changes are separate Finance tasks, not onboarding cleanup.

The Moovs Payments overview also lists plan-based processing fees and additional
manual-entry, Operator-app and international costs. Refer to its dated published
terms and the operator's current agreement; do not quote them as a universal
account rate, infer duplicate manual-entry/app surcharges, or interpret “no refund
fees” as a promise to return the original processing fee.

## Card authorization

Card-authorization guidance reviewed 2026-10-16 from public sources. The recording
is a historical literal capture, not verification of today's Operator UI.

The [authorization guide](https://intercom.help/moovs-05c940f1970e/en/articles/6763516-authorizing-credit-cards)
documents a $0.50 temporary contact-card hold and risk evaluation, not full-fare
capture or an amount applied to the booking balance. Its dated guidance says the
hold clears in 3-7 business days; do not guarantee an individual bank's timing.

1. Confirm the intended company/contact, masked card and the operator's intent
   to attempt this small hold. Apply the paid-plan, payment-readiness and permission
   checks in the main skill; card presence alone is not permission to authorize.
2. A [literal public product recording from December 29, 2022](https://www.youtube.com/watch?v=QzSivKy5wK8&t=285s)
   shows **Contacts > selected contact > Credit Cards > intended card's More >
   Authorize Card** (04:45-04:49). Guide one step at a time. Explain the documented
   temporary hold before initiation. If current controls or the indicated amount/
   effect differ, stop before initiation and reconcile with current guidance or
   Support rather than guessing.
3. After exact contact/masked-card/hold-amount approval, select **Authorize Card**
   once in execution mode. The recording moves directly into the attempt; no
   separate confirmation is demonstrated. Never silently run a small test. This
   financial action is not part of read-only inspection.
4. For result review, open the intended card's **View Payment Activity** if
   actually offered; then identify the matching attempt, or use the demonstrated
   failed-toast **View Risk Status** path. Review matching card/amount/date/time
   and exact status/risk in the actual resulting activity view, not just a toast. The recording's
   failed example opens that view through **Card authorization failed > View Risk
   Status** (04:50-05:00), showing **Blocked** and **Highest**. Report the actual
   result; those labels are not success. If the matching attempt or outcome is
   unclear, stop and ask Support before another attempt; do not blindly retry or
   bypass a block. Without authorized read-only browser access, readback remains
   operator-reported, not independently verified.

This supports an operator-led attempt and result review, not a promised successful
hold. The dated recording does not establish today's full eligibility/validation
rules or successful-result labels. A passed authorization is not fraud/chargeback
immunity, fare collection or permission to charge a reservation. Do not promise the
future full-amount authorization mentioned as a possibility in older Help prose.

## Incidentals or overages after a booking was paid

1. Confirm the exact reservation, agreed new line item, amount and payer.
2. Public guidance uses **Update Pricing**, then the operator adds the intended
   charge and saves. Verify revised pricing and amount due before any collection.
3. A booking becoming unpaid again can reflect a new amount due; do not recharge
   its original paid total. Review history and the remaining balance.
4. Treat collection as a separate operator-reviewed charge/link task, with the
   correct method, trip scope and potential communications. Reopen/read back
   payments afterward. Do not infer a price edit collected the new balance.
[Incidentals/overages](https://intercom.help/moovs-05c940f1970e/en/articles/6609810-charging-a-customer-for-incidentals-overages-after-they-ve-paid).

## Diagnose generic payment recording

Public [reconciliation guidance](https://intercom.help/moovs-05c940f1970e/en/articles/13289137-why-are-there-discrepancies-in-payment-records-and-financial-tracking-in-moovs)
distinguishes generic **Credit Card/Generic Card** external recording from an
actual saved Moovs payment method. A generic entry can make a trip look paid
without collecting funds through Moovs. External/cash/Zelle recording is not a
transfer. Confirm the original receipt before marking money received.

Do not automatically refund/recharge a suspected wrong-method entry. Compare
actual payment records, method and amount and have Moovs verify unclear accounting
before any corrective operator action. Driver-paid and customer-paid fields can
represent different obligations; report labels alone do not reconcile them.

## Additional external receipt methods

April's public update narrates **QuickBooks ACH**, **donations**, **gift
certificates** and **BizX** as receipt-tracking examples. Its 04:06 roadmap
illustration depicts ACH-External, Donation, Trade, Barter, BizX and Gift Certificate;
this is conceptual orientation, not a literal current selector demonstration.
Do not tell an operator to find a "QuickBooks ACH" option from that narration.
Neither narration nor illustration establishes a method-specific integration,
redemption or transfer contract. Confirm actual receipt, account allowance and
method before operator recording; never claim selecting
such a label collected funds, redeemed a certificate or initiated QuickBooks ACH.
Free's external-paid restriction still applies. If the intended method/semantics
are absent or unclear, use current official guidance/Support rather than a generic
card entry or invented import. Read back exact recorded amount/method separately
from the private outside receipt.
[April 2026, 03:51-04:12](https://fast.wistia.com/embed/iframe/krp2b1wij8?wtime=231s).

## Interpret payment risk

The [risk guide](https://intercom.help/moovs-05c940f1970e/en/articles/6797869-moovs-payments-risk-notifications)
describes transaction risk information under **Edit Trip > Money > payment menu
> View More**. Risk is not a fraud verdict or permission to bypass blocking.
Unknown/error outcomes need readback before retry. Never export customer identity
or investigate personal data publicly to "prove" safety. Use Support/cardholder
issuer processes and appropriate business review.

- **High:** assessed likely fraudulent and blocked by default. Do not override or
  switch channels to evade the block; use cardholder/issuer and Moovs review.
- **Elevated:** higher assessed fraud risk, although the guide says these payments
  are allowed. Allowed is not a guarantee of legitimacy or collection authority.
- **Normal:** fewer fraud indicators, not a guarantee against fraud or dispute.
- **Unknown:** evaluation failed; not an approval or a fraud finding. Check the
  existing attempt/status before considering another operator action; use Support
  when unresolved rather than blindly retrying or bypassing the review.

Read back the exact payment, displayed evaluation/status and any blocking reason.
Keep an assessment, payment outcome and actual settlement separate.

The public [fraud-prevention guide](https://intercom.help/moovs-05c940f1970e/en/articles/6653945-fraud-prevention)
recommends reviewing suspicious/unusual orders. Treat concerns as reasons for
appropriate business verification, not proof of fraud based on a name or email.
Do not call a customer, export their identity or perform public personal-data
searches for the operator. No risk label or authorization guarantees safety.

## Explain processing and payout states

The [pricing](https://www.moovsapp.com/pricing) label **Instant Payments** is not
proof a charge immediately reaches the bank or that instant payouts are enabled.
Clarify customer collection versus merchant payout before choosing guidance.

The processing guide directs operators to **Finance** for card transactions,
including pending payouts. Match the actual transaction: its **In Transit** means
charged and processing, not a posted bank deposit. A payout's similarly named
status is a different record; compare the linked payout separately. The guide's
typical 24–48-hour processing and two-business-day rolling schedule are not SLAs;
unusual/large transactions, weekends/holidays and regional schedules can differ
(it mentions seven-day rolling in some countries). Check the actual schedule and
payout date/amount in the offered Payments/Finance view; unusual delays need
Support, not another charge or payout.
[Processing stages](https://intercom.help/moovs-05c940f1970e/en/articles/9927013-understanding-transaction-processing-in-moovs),
[Payment feature overview](https://intercom.help/moovs-05c940f1970e/en/articles/6314539-intro-moovs-payments-features).
