# Base Rate Automation and zone pricing

Reviewed 2026-10-16. Operator performs all settings, rate application and saves.

## Configure BRA deliberately

Open **Vehicles > vehicle > Pricing**. The [deadhead guide](https://intercom.help/moovs-05c940f1970e/en/articles/6387682)
instructs turning BRA **Off** before editing its settings. Check the actual
editable/locked state first. Any disable/re-enable is operator-performed and can
change automated booking behavior; review that impact rather than toggling it
just to inspect. If current controls conflict with the guide, pause and reconcile.
Review transfer minimum base rate,
passenger trip rate/mile and deadhead rate/mile; hourly free-deadhead allowance,
weekday/weekend rates and minimum hours; tiering and weekend selection as used.
Ask operator for approved values. **Enable Base Rate Automation** controls
calculation; Customer Portal settings additionally control display and automated
portal pricing. Public setup uses **Display on Customer Portal** and **Enable
Base Rate Automation on Customer Portal**. Review both before enabling.

With BRA/portal automation configured, customer flow can show prices and create
reservations rather than unpriced quote requests. Do not activate it merely to
fix a missing displayed price without confirming desired booking workflow.
The overview describes hovering over the green bolt-with-arrows control in
operator pricing to inspect the suggested calculation; clicking adds it as the
Base Rate. Use only supported non-mutating inspection if offered; the authorized
actor applies or edits the approved value under task authority. Do not click merely to discover a preview.

[BRA overview](https://intercom.help/moovs-05c940f1970e/en/articles/6395469), [Vehicle BRA setup](https://intercom.help/moovs-05c940f1970e/en/articles/9173525)

For a non-tiered weekday/weekend editor walkthrough, see
[vehicle Hourly schedule](hourly-vehicle-pricing.md); do not confuse it with an Hourly trip draft.
For Transfer Fixed bands or weekday Hourly Incremental bands, use the
[tiered vehicle editor](tiered-vehicle-pricing.md); Fixed mode does not imply Flat units.

## Explain the rate, not just the final number

For [pricing](https://www.moovsapp.com/pricing)'s broad **Custom pricing rules**
label, identify the actual goal: vehicle base-rate calculation, a zone route,
targeted category rate or a date/time Trip Rule. Use the corresponding documented
procedure, not an assumed separate "custom pricing" editor.

For transfer trips, check matching zone price first; otherwise review passenger
mileage, garage-based deadhead, minimum base rate, transfer tiers and Trip Rules.
For hourly, review reserved hours, garage travel/free allowance, weekday/weekend
rates/minimums and hourly tiers. Zones do not price hourly trips.

Incremental tiers apply each band's rate to its portion. Fixed tiers apply the
matched band's rule to the entire distance/duration. Do not interchange them.
The pricing Help describes these branches, not a complete tier-band editor:
- Non-tiered transfer: compare the calculated passenger/deadhead fare with the
  minimum base rate. Tiered transfer: calculate its base bands and add deadhead.
  The prose does not settle how every tiered minimum is applied; do not invent it.
- Non-tiered hourly: compare calculated total duration with the weekday/weekend
  hourly minimum, then use the applicable rate. Tiered hourly: calculate the base
  bands and add deadhead duration multiplied by its deadhead hourly rate. This
  does not establish an exact current editor/field label.
Compare the visible calculation with agreed inputs and customer total.

There are concrete public formula conflicts: the pricing article multiplies
transfer deadhead by trip mileage, while the deadhead/vehicle guides describe
garage-to-pickup and dropoff-to-garage legs. The pricing article subtracts a total
free hourly allowance, while an older vehicle example deducts it per garage leg
and conflates zero hours with No deadhead. Do not silently choose a universal
formula from these examples or change live rates to match one. Reconcile current
Help with a permitted visible breakdown or ask Support.

Published deadhead guidance distinguishes zero free hours from a No deadhead
option, and older terminology/examples can differ. Do not substitute one for
the other. Read the actual selector/calculation and current guidance before
quoting a hand-calculated amount. Likewise inspect assigned garage rather than
assuming company address is always used. Escalate unexplained discrepancies.

[Pricing calculation](https://intercom.help/moovs-05c940f1970e/en/articles/9718727), [Deadhead](https://intercom.help/moovs-05c940f1970e/en/articles/6387682),
[Vehicle terminology](https://intercom.help/moovs-05c940f1970e/en/articles/6963946)

## Configure an incremental Transfer first-band flat charge

Reviewed 2026-10-16: literal June 2025 controls add this bounded editor path to
Help's tier formulas. This is vehicle-level pricing, not one quote's manual rate.
Use the configuration/access checks above; operator owns all toggles/entries/save.
Reconcile current editable/locked controls rather than assuming the dated demo
leaves BRA enabled during every present-day rate edit.

1. On the intended **Vehicles > vehicle > Pricing**, review existing Transfer
   bands, deadhead rate and portal impact. For the agreed incremental policy,
   operator selects Transfer **Tiered Pricing** and **Incremental**, not Fixed tier.
2. In **First**, enter the approved band distance and amount, then choose **Flat**
   for a first-band flat charge. **+ Add Tier** adds a **Next** band; its distance
   is the length of that next band, not the cumulative endpoint. Operator sets
   each approved amount and **Per mile** or **Flat**, plus **Remaining miles**.
   Review every band and existing deadhead setting; do not copy demonstration rates.
3. Fill required visible tier inputs. The demo shows missing-field validation;
   do not disable tiering to evade it. Operator reviews the complete vehicle
   policy and chooses **Save** once. Reopen Pricing and compare the saved mode,
   distances, units, amounts and unchanged deadhead/Hourly settings.
4. In an authorized unsent quote/preparation, operator enters the intended sample
   schedule/route and selects that vehicle, then opens **BRA Calculations** where
   offered. Compare band contributions, separately shown deadhead and total.
   Opening the breakdown is not applying it: do not click the base-rate apply
   icon or save/send a booking merely to check calculation. A sample's agreement
   does not establish every boundary/zone/Trip Rule case.

A flat first band supplies an initial component, **not** a maximum-style minimum
fare that absorbs later miles or deadhead. Do not promise a tiered minimum-total
field or that the flat amount already includes deadhead. Current Help supports
incremental portions plus separate deadhead but does not settle every minimum
interaction; preserve the formula conflicts above.
[June 2025, 23:30-24:52](https://fast.wistia.com/embed/iframe/fxg1ydojhc?wtime=1410s)
shows Incremental/Fixed tier, band controls and validation, complete values and
Save, then an unapplied BRA breakdown. [Current pricing Help](https://intercom.help/moovs-05c940f1970e/en/articles/9718727-understanding-pricing-in-the-moovs-app)
provides the formula distinction, not every current editor validation or save effect.

## Announced combined distance-and-time Transfer pricing

[June2026, 31:32-32:52](https://fast.wistia.com/embed/iframe/edhqyl150j?wtime=1892s)
announced combined distance/time Transfer BRA as **coming soon in July**, not
an already demonstrated setup. The reviewed vehicle/pricing Help still describes
Transfer mileage versus Hourly time; it does not supply this combined editor,
formula, save or verified availability. A planned month is not shipment proof.
For this goal, ask Moovs for current public setup instructions and account
availability before changing rates. Do not substitute Hourly, Charter pricing or
a Trip Rule for this Transfer option, invent a per-minute field/formula, or
promise repricing existing bookings. Existing BRA guidance above remains bounded
to its documented calculation branches.

## Zones and fixed routes

For a **zone-only** pricing-policy question, July2025 suggests enabling only zone
pricing and leaving vehicle Transfer pricing disabled. This is dated conceptual
advice, not a current setup/enablement sequence or a promise every unmatched trip
becomes request-only. Current zone Help describes Transfer fallback, BRA and portal
controls separately; service-area request-only behavior was still being explored
in that Q&A. Before any operator mutation, obtain current supported enablement and
fallback guidance for the intended vehicle/portal policy. Do not turn off global
BRA, set rates to zero or invent a service-area control as an equivalent. An
unsubmitted synthetic matched/unmatched-route review can check the intended
behavior after separately supported changes, not establish universal policy.
[July2025, 17:05-17:51](https://fast.wistia.com/embed/iframe/lx539nwwlt?wtime=1025s).

Open **Settings > Zone Pricing > Create**. Operator defines the intended area
using one of the documented methods:
- **Zip Code**: name the zone, search an address/suburb/region, then click the map
  to include intended ZIP areas. Review all included areas before **Create Zone**.
- **Location**: switching from Zip Code to Location resets the map. Place the
  intended pin and increase/decrease its capture area; review the resulting
  area before **Create Zone**. Do not invent units or a radius-field label.
- **Draw**: click map points to define boundaries, then close the polygon by
  clicking the starting point before **Create Zone**. Review the whole boundary.
Draw supports up to 10 polygons/zone and 25 vertices/polygon. Same-type zones cannot
overlap; matching priority is Draw, then Location, then Zip Code.

Once at least **two zones** exist, open **Routes**, select the intended connecting
route block and enter its approved per-vehicle fixed rate. Review origin/destination
zones and vehicle/route before operator submission using actual offered controls.
Help does not name a universal route-rate Save button. Separately, the undated
[official text demo](https://capture.navattic.com/clt5ngw06000m0fl9fs4l1fya)
(steps18–25) names **Save** after route/vehicle price entry. If the current controls
match, the operator reviews and saves; this text is not a current button capture
or evidence of persistence. Read back the intended saved route/vehicle rate.
Both addresses must match defined zones and a vehicle route price must exist for
that fixed rate. Missing match/route rate can fall back to transfer calculation.

April's Q&A says an added intermediate stop removes the fixed zone fare: the
itinerary is no longer just the priced route between two zones. For that case,
review the full stop list and actual calculation before changing an approved fare.
This is not evidence BRA itself turns off or an instruction to toggle BRA/the
extra-stop default. Reconcile a conflicting result with current supported guidance.
[April, 27:43-28:40](https://fast.wistia.com/embed/iframe/krp2b1wij8?wtime=1663s).

For unexpected pricing, inspect both actual addresses and boundaries, matched
zones, vehicle rate, BRA enablement, cutoff and Trip Rules. A portal cutoff can
produce Request For Price. Help gives the dated **Settings > General > Booking
Tool > Reservation Cutoff Period** route; if current navigation differs, reconcile
it rather than inventing a Booking Tool screen. Inspect the existing cutoff and
a permitted unsubmitted scenario outside it; do not change cutoff to force a price.
Do not edit zones to force one test price without
reviewing all affected trips. Validate using an unsubmitted synthetic scenario
or permitted read-only calculation; operator owns any real booking submission.

Public zone Help explicitly says Trip Rules apply on top of ordinary zone rates,
while the pricing overview says a zone match skips the steps below, including
its final adjustment step. The zone body also says only route-priced vehicles can
be selected while separately describing transfer fallback without a route price.
Disclose these inconsistencies; do not infer that zones suppress Trip Rules or
universally exclude vehicles lacking a route price. Use the permitted breakdown
and current supported guidance before changing anything.

[Zone Pricing Deep Dive](https://intercom.help/moovs-05c940f1970e/en/articles/6871879),
[Pricing calculation](https://intercom.help/moovs-05c940f1970e/en/articles/9718727).
