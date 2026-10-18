# Customer Portal conversion tracking

Reviewed 2026-10-15. Tracking is a separate enabled integration; do not assume
ordinary portal access includes it. Confirm purchased access, intended company,
correct GTM container and operator permission. No API keys or login credentials
belong in chat, notes or this skill package.

## Setup and cost boundary

Public setup guidance directs the operator to Moovs' Conversion Tracking service.
Read current account/service terms before stating a price: older public articles
describe fees and setup credits differently. Subscription, tag publication and consent changes need exact current approval.
Do not connect an unrelated container or include these changes in an explanation task.
The setup article (reviewed 2026-10-16) names a Marketing Team call for interested
operators. Confirm the current intake route with Moovs before the operator books;
an inquiry is not a subscription, configured container or enabled tracking.

[Setup](https://intercom.help/moovs-05c940f1970e/en/articles/8466979-how-do-i-get-started-with-gtm-integration-for-my-customer-portal),
[Service fees](https://intercom.help/moovs-05c940f1970e/en/articles/12050386-why-does-the-google-tag-manager-integration-have-a-99-month-fee),
[GTM overview](https://intercom.help/moovs-05c940f1970e/en/articles/8466968-what-is-google-tag-manager-gtm),
[Use cases](https://intercom.help/moovs-05c940f1970e/en/articles/8466974-why-should-i-integrate-my-customer-portal-with-gtm).

## Use the documented event contract, not generic GTM possibilities

The [event reference](https://intercom.help/moovs-05c940f1970e/en/articles/8466983-what-types-of-events-can-you-track-with-gtm-in-your-customer-portal)
(reviewed 2026-10-16) documents these conversion events:

- `moovs_create_quote`: quote submission, without booking value.
- `moovs_create_reservation`: direct reservation creation, numeric value when
  available at creation.
- `moovs_confirm_reservation`: quote conversion, numeric value when available
  at confirmation.

The same reference maps these page-view events:

- `moovs_page_view_info`: booking information.
- `moovs_page_view_vehicle`: vehicle selection.
- `moovs_page_view_quote_summary`: quote summary.
- `moovs_page_view_reservation_summary`: priced reservation summary.
- `moovs_page_view_reservation_request_summary`: request summary without an
  immediate booking price.
- `moovs_page_view_confirm_quote`: existing quote ready for payment/confirmation.

A page view is not quote submission, reservation confirmation or payment. Reloads
or revisits can emit again; counts are not unique customers. The documented data
layer contains `event` with the event name and `category: Moovs_Tracking`; `value`
is included only for the two reservation conversion events when a numeric total
is available. Do not invent additional fields or configure triggers from a generic
GTM overview.

Booking value is not collected payment or final realized revenue. The documented
event set does not establish payment/cancellation events or currency, customer
email, reservation ID and ad-click-ID parameters. Do not add guessed parameters,
send personal data to analytics, or count quote-plus-reservation as one conversion
without an intentional attribution design.

The Dashboard **Request Source** label is a separate unresolved attribution
scope. March's broad GTM/cookie explanation does not define label assignment,
historical persistence or Google Ads without an active campaign; the event
contract above answers none of those rules. Seek the current exact definition,
not a generic GTM setup or an invented click-ID parameter.
[March 2026, 22:17-24:26](https://fast.wistia.com/embed/iframe/12zjubd9ns?wtime=1337s).

## Verification loop

1. Operator confirms tracking is enabled for the intended portal/container.
2. Use GTM Preview with permission. Compare the data-layer event/category with
   the intended step and corresponding GA4 tag; observe GA4 DebugView separately.
3. Direct booking and quote conversion are different paths; test separately using
   explicitly authorized synthetic data, not real chargeable bookings.
4. Compare the emitted numeric value with the synthetic source reservation.
   Do not claim currency/payment semantics not supplied by the event contract.
5. Separate container configured, preview fired, published tag and verified
   conversion reporting. No purchase, tag publication or real booking is implied
   by a request to explain tracking. Do not promise ads attribution or ROI from
   a single preview event.
