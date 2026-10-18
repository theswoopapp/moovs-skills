# Customer messages, recipients and content

Reviewed 2026-10-16 for dated email/charge-event orientation, Booking Contact POB
and customer SMS context; other sections 2026-10-15. Operator performs every send and setting/edit, including
controls that save immediately. Protect customer links and recipient information.

## Confirmation email or reservation link

1. During operator creation, inspect **Save reservation** versus **Save reservation
   & send email**. Public confirmation help says save-only does not send that
   booking-contact confirmation; save-and-email does. Explain the actual action.
2. Later, open the correct reservation and current **Send Reservation/Email**
   option. Public email examples show **Email > Reservation Email > Send Email**
   and **Email > Price Summary Email > Send Email**. Verify current labels and
   review every To/Cc recipient, email type and content before operator send.
3. For text instead, operator copies the intended Reservation Link from current
   link controls, opens **Chat**, selects the exact contact and reviews a service
   message before sending. Copying is not sending; do not publish the link.
4. Customer-originated portal reservations receive confirmation after Reserve.
   Do not use this to infer every operator save sends the same email.

Sources: [Confirmation Emails](https://intercom.help/moovs-05c940f1970e/en/articles/6457674-sending-confirmation-emails),
[email types](https://intercom.help/moovs-05c940f1970e/en/articles/6843621-what-emails-are-my-customers-receiving).

### Dated email-event orientation

The older email-types article groups messages around customer quote requests,
added quote trips and priced quotes; customer-created reservations; manually sent
reservation/price-summary emails and invoices; charges, cancellations and paid
invoices; and customer trip-change requests, additional-info updates and
payment-link payments. Its blue call-to-action buttons open the corresponding
quote/reservation/price-summary details. Customer-specific links stay private.
This explains event families, not permission to trigger them or thirteen new tasks.

Its broad automatic/cannot-turn-off and noncustomizable claims are not universal
current rules. Updated [Notification Center](https://intercom.help/moovs-05c940f1970e/en/articles/11101888-notification-center)
documents supported editing and separate delivery settings; it does not prove
every event is editable or switchable. Preserve the operator save-only distinction
above even when generic reservation-created wording suggests automatic email.
[Free exclusions](https://intercom.help/moovs-05c940f1970e/en/articles/9927108-important-updates-for-free-plan-users)
still prohibit booking-confirmation/status notifications and SMS; the digital-
invoice exception enables no payment or notification bypass. Check the intended
event's current setting and activity rather than promising an automatic send,
inbox delivery or a current toggle path from this dated list.

The [deposit guide](https://intercom.help/moovs-05c940f1970e/en/articles/6985845-how-do-i-take-a-deposit-payment)
names **Send automated charge emails to booking contact** under Communication
settings and a payment email linking to Price Summary payment history. If asked
to change this default, confirm account access, intended scope and current offered
control before operator submission/readback. Do not enable it as a diagnostic,
infer it sends a payment link after added charges, or treat email activity as a
processor receipt, customer delivery or successful payment.

### Choose the intended link, not just any trip URL

May's narration distinguishes the passenger reminder/status URL (no payment
information in that example), reservation summary (with **View Price Summary**),
price summary (pricing and payment access) and direct payment URL (payment screen).
For a missing-payment-link question, identify the message's actual event/channel
and supported Smart Key before operator edits; choose the intended destination,
then compare saved content and the private preview without submitting payment.
Demo payments were disabled, so this does not establish collection or every
current link's layout. Free payment/notification exclusions still apply.
[May 2026, 35:01-37:35](https://fast.wistia.com/embed/iframe/uuicxzakrz?wtime=2101s).

July proposes adding a payment URL to the driver-arrival notification as an
alternative to then-roadmap driver tap-to-pay. Use the existing SMS/email editing
procedure only if the actual arrival event offers the supported payment key;
check delivery recipients/triggers separately. Operator saves the agreed content;
arrival or template save does not collect payment. The customer pays privately.
Driver Amount Due visibility and subsequent actual payment readback are separate
checks, not permission to enable a visibility toggle or guarantee driver refresh.
[July 2026, 34:51-35:54](https://fast.wistia.com/embed/iframe/64e8h1tobn?wtime=2091s).

## Email history and evidence

**Reservation > More > View Activity Log > Email**. Expand the matching entry;
compare type, recipient, time and available subject/body or recorded activity.
An open/click can be informative, but absent opens do not prove unread because
providers/privacy settings affect tracking. A sent log is not guaranteed inbox
placement. Check before suggesting resend; operator decides whether another
message is warranted.
[Email history](https://intercom.help/moovs-05c940f1970e/en/articles/10242006-view-email-history-for-a-reservation)

## Contact-wide activity history

February/March public demos show **Contacts > intended contact > three dots >
Activity Log** for emails and SMS across that contact's activity, with available
subject/content and a link into the related reservation. Confirm exact identity
and date/record scope first; this is broader than one reservation's Email tab.
Inspect only needed entries, not the contact's entire communication history.

Use a matching log entry to open the associated reservation and verify its
reference/contact before interpreting it. Logged content or sent state is not
proof of delivery, reading or customer consent; absence of an entry is not proof
no contact occurred through another channel. Do not resend, alter contact data
or change global notifications merely to make history appear.
[February, 10:14-10:54](https://fast.wistia.com/embed/iframe/4xlf6w2fzq?wtime=614s),
[March, 30:45-31:39](https://fast.wistia.com/embed/iframe/12zjubd9ns?wtime=1845s).

## Customer reminder and status delivery settings

1. **Settings > General > Communication**, then **Chat > Contacts** after Chat
   is enabled: inspect current reminder/status recipients and triggers. Automated
   trip SMS comes from the company's Moovs Chat number; do not enable Chat as a
   missing-text diagnostic. Operator chooses Passenger,
   Booking Contact, both or neither as offered. This changes defaults, not one trip.
2. Status updates require Member and/or Driver triggers. No selected trigger
   means no status SMS, even with recipients chosen. Do not turn on triggers
   globally to solve a single-trip recipient request without discussing scope.
   For a Booking Contact **POB** message, operator also enables the POB checkbox
   within **Trip Status Updates**. This optional onboard notification still needs
   the applicable global triggers, recipient choices and account access.
3. For one trip use **More > Notify**, review recipient overrides and let operator
   save. Per-trip recipients cannot override absent global status triggers.
4. If applicable, review Booking Contact customer-portal bell subscription;
   never impersonate them or silently reverse their preference.
5. Public help describes reminders 24 hours and 1 hour before pickup and status
   messages for on-way/on-location/onboard/completed as configured. A completed
   text may contain a review link **if review collection is enabled**; this does
   not establish its setup procedure. Same-phone deduplication may apply. STOP
   blocks all SMS from that number, including reminders/status, until the contact
   opts back in with START; do not bypass an opt-out or tell staff to send it for them.

The older passenger-role article suggests inserting the booker's phone as the
passenger's to redirect updates. Do not overwrite passenger identity as that
workaround; use the supported recipient settings for the intended scope instead.

Sources: [Trip notification controls](https://intercom.help/moovs-05c940f1970e/en/articles/9938857-trip-reminders-and-trip-status-update-notifications),
[Customer trip communications](https://intercom.help/moovs-05c940f1970e/en/articles/6695060-what-communication-do-my-customers-experience-during-a-trip),
[Passenger roles](https://intercom.help/moovs-05c940f1970e/en/articles/6702018-reservation-differences-booking-contact-vs-passenger).

## Notification Center: content is not delivery configuration

Open **Settings > Notifications**. Public help lists paid plans and Notifications
member permission; reusable Message Templates require Pro or above. Check actual
access. Choose automated [SMS](#edit-automated-sms-notification-content),
[email](#edit-automated-email-subject-and-content), or
[manual templates](#create-or-manage-reusable-manual-message-templates).

On **Notification Events**, identify the intended event, trigger and channel.
Disabled events require enablement in their original settings area. Recipient and
channel fields here are informational, not delivery controls. Change delivery
settings separately only when requested. Operator authors/saves the agreed content
and reopens it to compare the saved result; saving a template is not a send or
proof of delivery. Any test must be separately scoped and operator-sent to an
agreed test recipient.
[Notification Center](https://intercom.help/moovs-05c940f1970e/en/articles/11101888-notification-center)

## Edit automated SMS notification content

On **Notification Events**, expand **SMS Notifications** and select the event.
Operator edits **SMS Template**; **+ Smart Keys** lets them copy supported fields
into the text. Review preview, maximum 320 characters and no emojis in automated
SMS, then operator selects **Save**.

Driver contact keys are supported in on-way, on-location and completed SMS, not
booking/quote confirmations. They use the saved driver profile; with multiple
assigned drivers, the first assigned driver's information appears. Do not promise
a specific different driver or unsupported keys. Use synthetic preview values;
real recipient data and customer links stay private.
[Notification Center](https://intercom.help/moovs-05c940f1970e/en/articles/11101888-notification-center)

## Edit automated email subject and content

On **Notification Events**, expand **Email Notifications**, select the event, and
operator edits **Subject** with supported **+ Smart Keys**. If offered, **Edit
Template** opens layout/content editing; type **@** for available merge tags and
operator selects **Save Template**. The full editor is desktop-only; its responsive
preview does not mean mobile editing is supported.

January's dated narration also covers **internal team** notifications, including
invoice-paid, incoming-call and payment-received events. It describes changing
branding/colors, subject Smart Keys and content blocks, then saving. Confirm the
actual event/audience and supported keys before an edit; these are not customer
confirmations or a promise every event has the same keys. Reopen saved subject
and template content; do not trigger a payment or call to test branding/delivery.
[January, 05:52-08:02](https://fast.wistia.com/embed/iframe/jniele7hge?wtime=352s).

For **New Shuttle Booking**, audience is the company's operator email, not a
passenger confirmation. Both subject and email content can be customized. Its
supported keys include operator name, passenger first/last name, shuttle route,
travel date, pickup time and passenger count; review that event's actual fields.
[Notification Center](https://intercom.help/moovs-05c940f1970e/en/articles/11101888-notification-center)

## Create or manage reusable manual Message Templates

On Pro and above, open **Settings > Notifications > Message Templates > Create
Template**. Operator enters the name and message, inserts an available variable
where needed, and selects **Save**. These templates are for manual client texts,
not automatic event enablement or permission to contact anyone. Review actual
message/audience before a separate send.

To edit or delete, return to **Message Templates** and select only the intended
template using the current controls; the article does not name a deletion dialog.
Reopen saved content after editing, or check the list after an agreed deletion.
[Notification Center](https://intercom.help/moovs-05c940f1970e/en/articles/11101888-notification-center)
