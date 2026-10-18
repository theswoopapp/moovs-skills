# Fleet, categories and operational availability

Reviewed 2026-10-16 (public vehicle/category, downtime and child-seat detail); other sections 2026-10-15. Operator performs every add/edit/toggle/save; connected customer steps stay customer-owned.

## Vehicles and categories

For a vehicle: **Vehicles > Add Vehicle** or open the intended existing vehicle.
Confirm customer-facing name/type, passenger capacity excluding driver, description,
actual plate/color and operating details. Vehicle Type also narrows matching Moovs-network
farming partners; choose the actual type, not a type chosen to force a match.
Help recommends the correct VIN; don't
collect vehicle identifiers unnecessarily in chat. Names/photos and some fields
appear in customer/driver views, so keep private notes out of public descriptions.

On initial vehicle creation, public Help requires **Active** on. Once saved,
Active off hides the vehicle from Booking Tool/website display but does not block
internal trip assignment. Use downtime for maintenance, not an assumed hard block.
Choose previously created cancellation/insurance policies from the offered
selectors and the vehicle's relevant feature checkboxes; this is not creation
of new policies. Cancellation terms reach the customer booking/confirmation-link
views, while the linked insurance policy is not displayed elsewhere in Moovs.
A selected policy is not evidence of insurance validity or legal suitability.
If an actual amenity is missing from the feature list, Help allows describing it
in the public **Description**; do not put private operational information there.
Use the separate vehicle **Internal Notes** write-in field for intended team
context, such as an approved pricing-change note. Operator enters only necessary
private information and checks saved notes using the actual offered controls;
the source does not name a universal save/autosave mechanism for that field.

For photos, operator uploads at most **six JPEG/PNG** images and drags them into
the approved order. The lead photo is used in driver assignment/Driver App and
passenger trip-start messaging. Reopen the vehicle to compare images/order and
intended details using actual offered save controls; don't invent a Photos tab
or universal save label, send an assignment or start a real trip to test it.

For categories: **Vehicles > Categories > Create Category**. Set name, capacity,
photos and account cancellation/insurance policy selections. On **Features**,
choose only applicable amenities/policies. On the category's **Pricing** tab,
review approved transfer base/deadhead/per-mile or flat rates, weekday/weekend
hourly rates/minima, the tiered-pricing toggle and which days count as weekends.
These are the category's rates, not an instruction to edit each member vehicle.
Use [base-rate guidance](base-pricing.md) for meanings; the public text does not
give every tier-band editor control. Enable category BRA only when its automatic
calculation is intended. Review these separate Customer Portal settings before
operator **Save**:
- **Display Category on Customer Portal** controls category visibility.
- **Enable Base Rate Automation on Customer Portal** lets customers see pricing
  without requesting a quote; visibility alone does not enable this pricing.
- Availability options independently block **quote requests** or **reservations**
  when vehicles are unavailable. Establish the intended behavior for each; they
  are not interchangeable with visibility or BRA, and the guide does not define
  a universal category-member availability calculation.
Add vehicles through category **Vehicles > Add Vehicle**, choosing the intended
membership. After save, reopen and compare each requested setting/membership;
a saved category is not proof a real reservation/payment was made. If Categories
is absent, refresh, have the operator sign out and back in, confirm the intended
account, then ask Support to confirm enablement. Login/verification remain private
and none of these recovery steps proves entitlement.

June explains category availability using the combined availability of its
member vehicles: in its one-member example that vehicle being booked makes the
category unavailable; in the two-member example both being booked does so.
Use this dated example to review intended membership and the same requested
service window, not a universal capacity calculation or guaranteed hard block.
Independently inspect quote-request and reservation conflict blocking in the
category/customer-portal settings; do not substitute visibility or BRA. Operator
changes only agreed settings using supported controls, then reads back each and
membership. An authorized unsubmitted preview may compare choices; do not create
conflicting real bookings or assume this prevents internal assignment conflicts.
[June 2026, 26:44-28:06](https://fast.wistia.com/embed/iframe/edhqyl150j?wtime=1604s).

Category **Optional Info > Target Specific Companies or Contacts** controls
special pricing audience. Without targets the category/pricing is general to
all portal customers; targeted customers must log in to see exclusive rates.
Published guidance says matching contact/company targeted pricing overrides
vehicle base pricing for operator bookings too, even if category name is not
shown. Verify the intended contact/company and result, not just the name.

[Vehicle fields and visibility](https://intercom.help/moovs-05c940f1970e/en/articles/6963946), [Category setup](https://intercom.help/moovs-05c940f1970e/en/articles/12407973), [General and targeted category pricing](https://intercom.help/moovs-05c940f1970e/en/articles/12408012)

## Maintenance or downtime

**Vehicles > vehicle > Unavailability > Add Block**. Operator chooses One-time,
Daily or Weekly recurrence. For One-time, select its date; Daily repeats every
day with optional start/end dates; Weekly requires the intended one or more
weekdays, also with optional start/end dates. Enter start/end times and an
optional reason, then operator **Save**. Confirm selected weekdays/date bounds
and affected service window before save and in the reopened block.
Operator shows conflict/unavailability during review; Customer Portal prevents
selecting affected vehicle regardless of trip-conflict settings. Timeline shows
gray hatched downtime. It is separate from a trip overlap; both can be shown.
Review existing affected assignments rather than assume a block reschedules them.
Edit/delete the intended block only and read back dates/recurrence afterward.

[Vehicle unavailability](https://intercom.help/moovs-05c940f1970e/en/articles/13862796)

March's separate announcement of integration-driven automatic vehicle blocks is
not this manual workflow. Provider identity, setup/mapping, sync, conflict and
recovery behavior remain unsupported by the reviewed public guides; do not
promise that creating a manual block enables or validates the integration.
Ask Moovs for the exact supported provider-driven procedure when that is the goal.
[March 2026, 02:16-02:26 versus 10:00-11:39](https://fast.wistia.com/embed/iframe/12zjubd9ns?wtime=136s).

## Assign a vehicle garage

The garage guide lists **Pro/Enterprise**, while public pricing labels the broader
**Multi-garage management** Enterprise-only. These labels may have different scope;
do not assume they establish identical entitlement. Confirm the actual account's
garage access with Moovs. Open vehicle > **Optional
Info > Garage Location**, choose existing or **Create New Garage**, operator
saves. BRA uses assigned garage for deadhead; no garage falls back to company
address. Do not infer live driver location determines the calculated rate.
Reopen the intended vehicle's Optional Info and compare the saved garage; use only
an authorized synthetic pricing preview if calculation validation is needed, not
a real booking or charge. A saved garage is not proof existing trip prices changed.

[Vehicle garages](https://intercom.help/moovs-05c940f1970e/en/articles/15505547),
[public pricing comparison](https://www.moovsapp.com/pricing).

## Configure inspection buffers

Inspection buffers are published **Pro/VIP**. **Settings > General > Preferences
> Pre-trip and post-trip time adjustments**. Operator enables intended buffer
and sets 0-120 minutes per side. Buffers expand operational occupation/conflict
windows, can affect time-based pricing and Driver App start time, but do not
change customer pickup/drop-off times. Defaults apply to routes created/saved
after the change, not retroactively to all existing trips; saved route values
remain relevant. Confirm future versus existing scope before changing defaults.
Reopen Preferences and compare both enablement/minute values. Existing routes
retain saved values; do not infer new defaults rewrote their customer times.

[Inspection buffers](https://intercom.help/moovs-05c940f1970e/en/articles/15649013)

## Child seats

Vehicle > **Features > Child Seats**. Operator selects **Forward-facing seat**,
**Rear-facing seat** and/or **Booster seat** as actually offered. Set the maximum
quantity of **each type** this vehicle can accommodate, per-seat price (zero
allowed), optional short description (up to 35 characters) and required photo.
The default photo may be used or replaced; a new upload is not always necessary.
Review actual suitability/capacity, not just configured quantity.

For the connected booking walkthrough, the customer stays in their own session;
neither operator nor assistant impersonates them. After choosing a vehicle with
child seats, the **Review & Reserve** page displays its Child Seats section. Have
the customer review types/descriptions/photos/per-seat prices and choose intended
quantities. Compare the adjusted total **before** any separately authorized booking
submission. After submission, review the intended trip notes and total: seat
details reach Driver App/links and Dispatch/Reservations through trip notes.
Do not submit a test booking or advance driver statuses to prove this effect.
Configuration does not certify a seat or its legal suitability.

The Help body also names **Child Seat Quantity** and **Child Seat Amount** in
reservation/quote reports. This is supporting report context, not a documented
new report-creation/export procedure or proof of a completed booking.

[Child seats](https://intercom.help/moovs-05c940f1970e/en/articles/9396906).
