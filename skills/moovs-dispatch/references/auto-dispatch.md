# Auto Dispatch

Reviewed 2026-10-15. Published as **Enterprise-only**, with account enablement
required. Check role and actual availability as well. Do not infer entitlement
from ordinary Dispatch access.

## Before starting a trip search

Confirm exact company/trip, pickup time and desired search start time/timezone.
Trip must exist and be unassigned. Auto Dispatch must be enabled in **Settings >
Auto Dispatch**. Drivers need Driver App push notifications and availability.

Explain the effect: nearby drivers receive push requests; the first acceptance
assigns the trip. Batches and radius expansion can notify multiple drivers.
This is not a harmless live test or a promise that a driver will accept.

## Start or schedule

1. Open Reservations, select the trip, then **More > Auto Dispatch**.
2. Review the intended action. The operator chooses **Start Now** to begin search,
   or the **Schedule Later** toggle, a date/time, and **Schedule** for a future search.
   The scheduled search time is not the customer's pickup time.
3. Review progress; an immediate search opens a modal listing pinged drivers and
   their response statuses. Read back the resulting assignment rather than
   declaring success when the request was merely submitted.
4. To stop an active search, use **Cancel Dispatch** in the progress modal. The
   operator performs it after reviewing current state in case acceptance occurred.
   Public guidance says the trip returns to unassigned. Do not substitute an
   assumed close/dismiss action or confuse this with cancelling the booking.
5. For failed searches, check drivers are online in the Driver App; review
   availability, notifications and settings
   before a considered retry or manual assignment. No repeated automatic retries.

## Configure search only when requested

Use **Settings > Auto Dispatch** for the settings below. Confirm the exact
requested field(s), current values and approved operational values; do not replace
company policy with generic recommendations. Explain the relevant effect before
the operator changes/submits anything. Reopen settings afterward and compare each
requested value. The public guide does not establish a final save-button label or
how edits affect already active/scheduled searches; stop if that scope is unclear.

## Enable Auto Dispatch

Operator uses **Enable Auto Dispatch** for the intended account only after access
and notification readiness are checked. Read back the switch state; enabling is
not a test dispatch or proof a driver will accept.

## Change initial search radius

Set the starting search radius in miles from pickup. A smaller radius may miss
nearby available drivers outside it; a larger radius can notify farther drivers.

## Change expansion increment

Set the miles added on each expansion when drivers do not accept. Review this
with the starting radius and outer limit so the intended search area is clear.

## Change maximum search radius

Set the outer search limit in miles. Expansion stops at this radius; increasing
it can notify drivers farther from pickup.

## Change ping timeout

Set the response wait in seconds before the next batch or expansion. Shorter
waits speed cycling but leave drivers less time to respond.

## Change maximum expansion attempts

Set the expansion limit before dispatch is marked failed. Failure requires a
reviewed retry or manual assignment, not unlimited searching.

## Change drivers per batch

Set how many drivers receive requests simultaneously. More may improve quick
acceptance but notify more drivers for the same trip.

If an option is missing, check entitlement and enablement. If a scheduled search
has not run, check intended time and whether the trip was modified or manually
assigned. The docs do not prove what any particular live request did.

[Overview](https://intercom.help/moovs-05c940f1970e/en/articles/13251153), [Trigger or schedule](https://intercom.help/moovs-05c940f1970e/en/articles/13251239), [Settings](https://intercom.help/moovs-05c940f1970e/en/articles/13251189).
