# Cards, bank authentication and payment requests

Reviewed 2026-10-16. Confirm company, exact contact/booking and relevant plan.
Free does not include Stripe-backed card collection or payment links; do not
offer a link as a workaround. Sensitive card/bank entry and its private submission remain with their owner
while inspection is paused. Ordinary profile actions and approved sends follow
task-authority.md; exact recipient/content approval is required before sending.

## Request payment through the customer-facing link

1. Open the correct reservation and review outstanding balance, all trips and
   intended booking contact. **Links** provides its payment link; some older
   public guidance calls the preview **Preview Payment Link**.
2. Operator checks destination and intended recipient. Copying is not sending;
   a booking-specific link is private and must not enter public notes or chat.
3. Establish exact recipient/content approval before sending via an authorized
   channel. Do not click the customer's final payment, add unapproved recipients
   or imply copying requested a payment.
4. Cardholder enters their payment details privately and completes required bank
   prompts. Read back payment status/amount on the intended reservation afterward;
   link delivery, page opening or card addition alone is not payment completion.

For a **card-update** request, the older guide also offers **Preview Payment Link**
from the correct reservation, with the customer updating their own method. Keep
that intent separate from asking them to pay; return only to the intended masked
method/status afterward. Do not treat an updated card as a completed charge.
Links cover the **whole reservation**, not one selected trip. They must be shared
manually. The [deposit guide](https://intercom.help/moovs-05c940f1970e/en/articles/6985845-how-do-i-take-a-deposit-payment)
says added charges do not automatically generate or send a payment link. Review
the whole reservation before requesting a deposit.

[Payment requests](https://intercom.help/moovs-05c940f1970e/en/articles/6609965-requesting-payment-from-a-customer),
[Updating card information](https://intercom.help/moovs-05c940f1970e/en/articles/6609788-updating-a-customer-s-credit-card-information).

For a customer who cannot find payment, May distinguishes a passenger status URL
from the reservation summary, price summary and direct payment URL. Privately
check which destination the existing message uses before proposing another send;
use the intended payment link above, not the Passenger tracking link. The test
environment's payments were disabled, so the narrated payment path is not a
successful collection. July's arrival-message alternative likewise requires an
actually supported arrival-event payment key and separate recipient configuration;
it is not driver tap-to-pay or automatic collection. Read actual payment state
and, only with the driver's own permitted view, Amount Due separately; that display
alone is not a processor receipt or proof of a persisted visibility preference.
[May 2026, 35:01-37:35](https://fast.wistia.com/embed/iframe/uuicxzakrz?wtime=2101s),
[July 2026, 34:51-35:54](https://fast.wistia.com/embed/iframe/64e8h1tobn?wtime=2091s).

## Set a reservation's customer-link deposit

This differs from entering a partial amount in the Operator Charge dialog or
changing the quote's deposit policy. Confirm the exact reservation and agreed
deposit before the operator uses its **Set deposit** control. Follow actual unit
and save controls; the public May demonstration shows a fixed amount, not every
possible percentage option or validation limit.

After operator submission, review the reservation and refresh its payment-link
preview privately. The demonstrated customer choice is deposit or full amount.
Setting a deposit does not collect it or authorize sending/charging; each needs
its own exact current approval and appropriate operator identity.
The demonstration shows the deposit option disappearing after payment and the
deposit clearing when the trip amount changes or it is explicitly cleared.
Recheck after pricing changes; never assume the old requested deposit persists.
Read back both configured amount and customer choices without exposing the link.

[Official webinar library](https://www.moovsapp.com/post/moovs-webinars),
[May 2026, 30:39-32:04](https://fast.wistia.com/embed/iframe/uuicxzakrz?wtime=30m39s),
[public captions](https://fast.wistia.com/embed/captions/uuicxzakrz.vtt?language=eng).

## Secure card updates

The published operator route is **Contacts > find contact > Add Card**. The
customer can instead use their booking portal **name > Profile > Add Card**.
Explain the choice without asking anyone to paste or dictate card data into chat.
For the published customer route, the customer privately completes entry and
selects **Add**. Keep inspection paused until they finish and confirm a
non-sensitive masked/status view. Adding a card is not charging it.

Review which existing card is being replaced. Deleting an expired/rejected card
is a separate operator decision; do not remove every stored method or apply a
contact-wide change to solve a trip-only question. Verify only intended masked
method and readiness afterward, not full values or payment credentials.
[Customer card instructions](https://intercom.help/moovs-05c940f1970e/en/articles/9490098-how-can-my-customers-add-a-payment-method),
[Operator card updates](https://intercom.help/moovs-05c940f1970e/en/articles/6609788-updating-a-customer-s-credit-card-information).

## PENDING card is not a pending charge

A **PENDING saved card** has not finished Stripe setup/authentication and must
not be relied on for future charges. Ask the cardholder to add it directly in
the Customer Portal and complete their bank prompts. After they finish, refresh
the contact/company profile and verify active rather than pending. If it cannot
be authenticated, issuer assistance or another method is needed, not a bypass.
[Pending cards](https://intercom.help/moovs-05c940f1970e/en/articles/14077157-what-does-a-pending-card-status-mean).

For ZIP/CVC mismatches, the cardholder privately confirms details with their
issuer. The published flow replaces the rejected card with corrected information;
deletion requires exact scope approval; reentry and verification remain private
with the operator/cardholder, not the model.
Moovs cannot override issuer checks. A successful charge alone does not prove
every verification check passed. Never request CVC/postal/card values in chat.
[Verification checks](https://intercom.help/moovs-05c940f1970e/en/articles/14323155-resolve-zip-code-or-cvc-verification-issues).

## Interpret an already-shown decline code

Reviewed 2026-10-16 from the [public code table](https://www.moovsapp.com/decline-codes)
and the existing failed-payment/verification guidance. The table is undated, has
an old footer and inconsistent rows; it is not a current processor contract or
permission to retry, bypass a block or infer card-reader/PIN support.

- `duplicate_transaction`: inspect the intended payment's existing activity first.
  Match the relevant record, amount/time and masked method; resolve any successful,
  pending or unclear attempt before another operator-reviewed collection decision.
- `authentication_required`: the cardholder handles the secure bank prompt or
  issuer assistance privately. Authentication is not itself a successful charge.
- Expired-card, CVC/ZIP/number or insufficient-funds results need the cardholder's
  private correction, issuer help or an eligible alternative—not values in chat,
  a risk bypass or an unapproved/unknown-outcome retry.
- The table calls for generic customer-facing decline wording for `fraudulent`,
  `lost_card`, `stolen_card` and `merchant_blacklist`. Do not expose internal risk
  reasons or accuse the customer of fraud/theft. A shown code is not a proven
  personal diagnosis; customer communication remains an operator-reviewed task.

Use only the actual shown code, not a guessed diagnosis. For ambiguous/inconsistent
codes, conflicting guidance or unknown payment state, stop for Support rather than
silently fixing the table or following its generic retry advice. Current Help and
actual account restrictions still govern; Free payment exclusions remain unchanged.
