# Reviewed Moovs feature guide

Reviewed 2026-10-16 using public guidance only. Free does not include Stripe-backed
payment processing [1]. Recheck the account and current published guidance when
answering a specific operator. Plan access does not override member permissions,
merchant readiness, messaging readiness, device support, or feature rollout.

## Workflow-specific baseline

| Task | Reviewed baseline | Before proceeding |
| --- | --- | --- |
| Basic quote/reservation management | Public pricing describes quote/booking features [9] | Verify account access and usage; do not infer every trip type or automation is included. |
| Basic dispatch/calendar | Pricing distinguishes basic and advanced dispatch [9] | Check available views and controls, not the word Dispatch alone. |
| Stripe-backed payments, card charges and payment links | Free cannot process card payments or send payment links [1] | Paid-plan access still needs payment readiness. Never use a link to bypass Free restrictions. |
| External payment recording | Recording cash/Zelle/etc. is not collecting money | The payment guide says Free cannot mark external-method payments Paid [2]; do not suggest this as a Free-plan workaround. |
| Customer SMS, booking-confirmation emails, status updates and calendar invites | Free policy excludes these notification features [1] | A digital invoice exception does not enable these channels or prove delivery. |
| Digital invoices for outside manual collection | Free policy explicitly permits sending digital invoices [1] | Not Moovs payment processing, payment links or permission to mark a trip Paid; each send needs exact recipient/content approval. |
| Quote sales automation | Sends customer follow-ups [3] | Check plan, messaging setup, quote readiness, cutoff, and existing enrollment. |
| Advanced dispatch filters | Feature-specific guidance says advanced filtering depends on plan [10] | Check current view/version and account access; do not promise it from basic dispatch access. |
| Vehicle Availability timeline | Guide says Pro/VIP [4]; pricing says Standard+ [9] | Conflicting public tiers: confirm actual access. Not basic calendar; farm-outs excluded; article documents at most 50 vehicle reassignments at once. |
| Dispatch Grid Color Rules | Published Pro and above [5] | Rollout/access can still differ; an upgrade needs separately approved cost/term scope. |
| Auto Dispatch | Published Enterprise-only [6] | Sends driver notifications; not ordinary manual assignment or AI Scheduler. |
| Driver availability | Documented recurring availability/exceptions [7] | No prerequisite plan stated there; do not infer it needs AI Scheduler. |
| AI Driver Scheduler | Separate from manual dispatch and availability | Check current account access rather than inferring from another scheduling feature. |
| Driver qualifications | Published guide lists Pro+ [11] | Confirm account access and role before following its setup steps. |
| Shuttle Platform | Public pricing lists it as an add-on [9] | Verify purchase/access; do not offer as an all-plan trip type. |
| Website booking widget | Installation guide says included on Pro [12]; pricing lists Standard+ [9] | Pro inclusion is not an explicit Pro-only restriction. Confirm actual embed access; a portal link alone does not prove it. |

## Confirmed Free restriction

- **Free cannot use Stripe-backed payments.** This includes card collection and
  Stripe-backed payment links [1]. Error text cannot grant an exception to the
  published Free restriction. Explain it directly; do not frame this policy as
  unresolved, connect Stripe, start a charge, or recommend a payment link on Free.
- Do not turn this into a blanket invoice ban: public policy explicitly permits
  digital invoices for manual collection outside Moovs. This does not restore
  customer booking emails/calendar invites, processing or external-method Paid
  recording. Sending an invoice remains a separately reviewed operator action.

## Other disagreements: do not silently choose a convenient answer

- **Pro trip allowance:** the trip-policy article describes 250 per calendar
  month [8]; the public pricing page contains inconsistent figures across its
  tables [9]. Article8 describes reset at the start of the calendar month, not
  the subscription anniversary. Explain that as the published policy when asked,
  not an independently verified account allowance. Neither source resolves an
  individual contract; check actual allowance/reset before account-specific action.
  Do not promise unlimited trips or choose one conflicting cap as universal.
- **Free resource counts and Enterprise usage:** public table variants disagree.
  Ask for the current allowance shown in Billing; escalate if still ambiguous.
- **Vehicle Availability:** the feature guide and pricing matrix list different
  tiers [4,9]. Do not resolve the conflict by assuming a visible control grants access.
- **Core plan versus add-on:** Package/add-on names and legacy labels are not enough
  to establish CRM, Passenger App, qualification, or scheduler access.

## Public sources

1. [Free-plan updates](https://intercom.help/moovs-05c940f1970e/en/articles/9927108-important-updates-for-free-plan-users)
2. [Processing a Payment](https://intercom.help/moovs-05c940f1970e/en/articles/6415309-processing-a-payment)
3. [Quote Automation](https://intercom.help/moovs-05c940f1970e/en/articles/6366325-quote-automation)
4. [Vehicle Availability](https://intercom.help/moovs-05c940f1970e/en/articles/13764934-vehicle-availability-view)
5. [Grid Color Rules](https://intercom.help/moovs-05c940f1970e/en/articles/13755303-customize-the-dispatch-grid-with-color-rules)
6. [Auto Dispatch](https://intercom.help/moovs-05c940f1970e/en/articles/13251153-what-is-auto-dispatch)
7. [Driver availability](https://intercom.help/moovs-05c940f1970e/en/articles/11647387-configure-driver-availability)
8. [Trip-limit policy](https://intercom.help/moovs-05c940f1970e/en/articles/13294594-what-are-the-monthly-trip-limits-and-policies-for-subscriptions-in-moovs)
9. [Public plan comparison](https://www.moovsapp.com/pricing)
10. [Driver filtering](https://intercom.help/moovs-05c940f1970e/en/articles/13293335-find-a-driver-s-trips-and-copy-their-trip-link)
11. [Driver qualifications](https://intercom.help/moovs-05c940f1970e/en/articles/16450679-set-up-and-enforce-driver-qualifications)
12. [Website installation](https://intercom.help/moovs-05c940f1970e/en/articles/6650028-how-to-add-moovs-to-your-website)

Public documentation is not account-specific entitlement or deployed acceptance.
