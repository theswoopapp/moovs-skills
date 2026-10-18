# Booking configuration

Reviewed 2026-10-16. Operator makes every editable/save action, including toggles.
Check permissions, plan and affected scope before coaching a setting change.

## Global settings

Open **Settings > Customer Portal > Settings**. Review current values first.

The settings below share this route, not one blanket edit.

## Choose customer Trip Types

**Trip Types** offers One Way, Round Trip and Hourly; at least one must remain
enabled. Operator changes only approved options and reopens the saved list.
These are customer booking choices, not company Order Types/service reasons.

## Restrict booking addresses to the operating country

**Booking Location Restriction** limits pickup/drop-off autocomplete to the
operating country. It is not a custom service-area polygon or proof every local
trip is served. Operator changes the agreed toggle and reopens its saved value.

## Order vehicles in the portal

For radio/direction controls, Manual row handles and a non-submitting filtered
customer-list check, use [vehicle display order](vehicle-display-order.md).
The operator performs every selection/drag; do not assume these are unsaved.
This controls display, not fares, availability or assignment priority.

## Skip vehicle selection and choose a default

Ensure at least one vehicle exists before enabling **Skip Vehicle Selection**.
Operator enables it and chooses the approved default from the alphabetically
sorted list,
then reads back both saved values. Update the default in this same setting;
do not create a vehicle or alter another trip merely to change the default.
To restore customer vehicle choice, operator turns Skip Vehicle Selection off
and reopens the setting. The default's quote/direct/request workflow and price
visibility still apply; skipping selection does not make a vehicle available.
With this enabled, customer **Previous Step** returns to the first booking step,
not a vehicle-choice screen.

Sources: [Portal Settings](https://intercom.help/moovs-05c940f1970e/en/articles/6365893-customer-portal-settings),
[Skip Vehicle Selection](https://intercom.help/moovs-05c940f1970e/en/articles/9746193-skip-vehicle-selection-on-customer-portal).

## Per-vehicle customer journey

**Vehicles > select vehicle > Customer Portal Settings**:

Read back only agreed settings after operator changes. Any customer preview is
separately scoped and must not submit a booking. Hidden is not conflict-blocked.

## Show or hide one vehicle

**Display on Customer Portal** controls customer visibility. Operator changes
only the intended vehicle and reopens its saved value. Off hides the vehicle;
it does not delete it or prevent internal trip assignment.

## Show vehicle pricing and direct booking

**Enable Base Rate Automation on Customer Portal** shows price/direct booking
when configured; off offers request for pricing. Check the vehicle's **Pricing**
configuration first, then operator changes the agreed value and reads it back.
For the ordinary quote/direct-booking journey, BRA off means quote inquiries
regardless of the cutoff. Separately enabled unpriced reservation requests are a
different workflow; check that setting/audience rather than calling every inquiry
a quote. Do not invent rates or promise this bypasses other protections.

## Block conflicting quote requests

**Block Quote Requests on Trip Conflict** prevents conflicting inquiries for
this vehicle. Public Help requires an upgrade without naming a universal tier;
confirm actual access. Operator changes this toggle and reads it back, leaving
the reservation-conflict control unchanged unless also requested.
A blocked customer can choose another vehicle, change the requested pickup time
or contact the operator; do not disable blocking merely to bypass a conflict.

## Block conflicting reservations

**Block Reservations on Trip Conflict** prevents conflicting reservations for
this vehicle. Confirm access rather than guessing the required plan. Operator
changes this toggle and reads it back, leaving the quote-conflict control
unchanged unless requested. Blocked customers can choose another vehicle, adjust
the requested pickup time or contact the operator. Do not disable blocking or
create a conflicting real booking as a test.

[Vehicle Portal Settings](https://intercom.help/moovs-05c940f1970e/en/articles/6610096-vehicle-customer-portal-settings)

## Unpriced reservation requests

Public help lists this feature in Pro; confirm the actual account entitlement.

Configuration and processing an individual request are separate tasks below.

## Configure reservation-request audience

**Vehicles > select vehicle > Customer Portal Settings > Enable Reservation
Requests on Customer Portal**. Operator chooses all customers or intended specific
contacts/companies, then reopens the saved enablement and exact audience. Other
customers retain the vehicle's standard workflow. Portal gratuity is not shown
for requests; do not disable this workflow merely to make gratuity appear.

## Review and accept or decline a reservation request

On **Reservations > Unconfirmed**, locate the exact request and review trips,
contact, vehicle, availability and price intent. Operator chooses **Accept** or
**Decline** only after reviewing customer impact; both send email. Reopen the
request and compare its status, not assumed email delivery. Only confirmed
requests appear in Dispatch/can have drivers assigned; acceptance is not assignment.
An accidental decline can be accepted. Adding a price makes it visible in the
portal before or after acceptance or decline; status does not hide that price.
Customer submission emails relevant parties; this is separate from the decision
email. Do not submit a real request merely to test notifications or assume delivery.
Submission/acceptance does not charge. Payment-information requirements,
Curbside/Meet & Greet and Child Seat configuration still apply. Collection is separate.

[Reservation requests](https://intercom.help/moovs-05c940f1970e/en/articles/9746099-priceless-reservations-reservation-requests)

## Cutoff and customer changes

These share the global Portal settings route but have different effects.

## Set the reservation cutoff

**Reservation Cutoff** is a company-wide rolling window (0-23, Hours or Days).
For the ordinary quote/direct-booking journey, within it customers see **Request
for Pricing** rather than a price to reserve: contact/trip details are captured
without payment and the operator later converts the quote manually. Operator
sets the approved value/unit and reopens both. Default **0 Hours** does not prove
all inquiries will be direct bookings: BRA off still yields quotes, and separately
enabled unpriced reservation requests follow their own workflow. Do not extend
the cutoff example's no-payment-info claim to those requests. This cutoff also
limits customer cancellation requests.

## Automate customer-requested trip updates

**Automate trip updates requested by customer** has its own Hours/Days cutoff.
Before that cutoff, submitted changes can apply without operator review.
Explain this before operator enablement; reopen the saved toggle and cutoff
values. Do not enable it as incidental cleanup for a cancellation request.

## Allow customer cancellation requests

**Allow customers to request a cancellation** permits requests before the
reservation cutoff. Operator enables only the agreed setting and reads it back.
This is not automatic cancellation or refund. Review notification settings and
the exact request before the operator separately processes any cancellation.
The older cancellation article describes email on customer request submission;
that notification is neither verified delivery nor a processed cancellation.

Sources: [Portal Settings](https://intercom.help/moovs-05c940f1970e/en/articles/6365893-customer-portal-settings),
[Reservation Cutoff](https://intercom.help/moovs-05c940f1970e/en/articles/6888652-what-is-the-booking-tool-reservation-cutoff-period).
The older [cancellation article](https://intercom.help/moovs-05c940f1970e/en/articles/10552607-enabling-cancellation-on-the-customer-portal)
lacks complete controls; use current settings guidance, not its subscription wording.

## Configure reservation deposit collection preference

For future-reservation Deposit using an already configured, operator-approved
percentage, use [percentage deposit preference](future-deposit-percentage-selection.md).
Establish the existing configured percentage before any immediate-write selection;
No Charge hides it in the dated capture, so never toggle to discover an unknown value.
Public Help supplies the selection instruction; July2026 literal capture supplies
Deposit, %/Charge Percent and the mode Saving/Saved transition. Reopen the same
company's setting for readback. This is not proof of customer collection.

The original amount-configuration scope remains a **documentation gap**: changing
Charge Percent, fixed-dollar setup and their completion behavior are not established.
Do not infer percent-field autosave from mode saving or use a booking/charge test.

## Gratuity

In Customer Portal settings, operator enables selection, chooses three presets,
cash/custom options, a custom minimum matching the lowest preset (or no minimum),
and whether selection is optional. Confirm business amounts, not example percentages;
Help calculates percentages from base rate. Check reservation-request compatibility
and payment entitlement. Reopen settings; any checkout preview must not submit/charge.

July 2025 narration explains that Operator-added gratuity suppresses the customer's
checkout gratuity prompt; without it, enabled portal gratuity options can appear.
Review the intended trip's existing price items/settings first. Do not remove an
agreed gratuity, reprice/send a quote or create a booking merely to expose a tip box.
This is dated checkout behavior, not an additional post-service tipping procedure;
custom fixed-dollar tipping was future in that recording, not proven released.
[July 2025, 20:16-27:20](https://fast.wistia.com/embed/iframe/lx539nwwlt?wtime=1216s).

**Free excludes Moovs payment collection, including tips**. Cash/external-app
collection is outside Moovs, not a Free checkout/link workaround or permission to
mark paid. Help mentions tipping after service but gives no actor, controls or
charging workflow; use current public guidance/Support, not invented screens.
Sources: [Portal Settings](https://intercom.help/moovs-05c940f1970e/en/articles/6365893-customer-portal-settings),
[Gratuity options](https://intercom.help/moovs-05c940f1970e/en/articles/6985857-how-to-set-up-and-offer-gratuity-options-for-your-customers).
