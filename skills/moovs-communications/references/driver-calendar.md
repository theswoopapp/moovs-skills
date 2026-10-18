# Driver notifications and Calendar

Reviewed 2026-10-15. Confirm company and task; check the trip/driver for a
record-specific request. Changes, invites and sends follow
[task authority](task-authority.md), with exact audience/effect approval. Company-wide settings do not require a test trip or driver assignment.

## Configure driver automations

Shared setup for the five settings below: open **Settings > General >
Communication > Drivers**. A change affects qualifying future trips, not just one
driver. Operator changes only the agreed option using the current control, then
reopens settings to compare its saved value. This verifies configuration, not
message delivery or driver acceptance. App push also needs device permission.
[Communication settings](https://intercom.help/moovs-05c940f1970e/en/articles/6369378-communications-settings)

## Configure driver trip reminders

Use **Send trip reminder texts to driver** for the documented SMS reminders
24 hours and 1 hour before pickup. Reminders ask the driver to update status;
receiving one does not establish that the driver has started the trip.
[Reminder texts](https://intercom.help/moovs-05c940f1970e/en/articles/8006883-driver-notification-send-trip-reminder-texts-to-driver)

## Configure pending-job response reminders

Use **Remind driver to accept or deny pending jobs**. Moovs checks pending
assignments every two hours and sends reminders 8 AM-10 PM in the trip's local
time. They continue until acceptance, denial, unassignment, cancellation or trip
start. Current delivery requires an active Driver App push token; do not promise
SMS fallback from other automations. A reminder is not an accepted assignment.
[Pending jobs](https://intercom.help/moovs-05c940f1970e/en/articles/8007469-driver-notification-remind-driver-to-accept-or-deny-pending-jobs)

## Configure overdue trip-status reminders

Use **Remind driver to update trip statuses**. The public guide describes:

| Missing status | First prompt | Repeat interval until updated |
| --- | --- | --- |
| On the Way | 45 minutes before pickup | 10 minutes |
| On Location | 5 minutes before pickup | 5 minutes |
| Passengers on Board | 10 minutes after pickup | 5 minutes |
| Done | 30 minutes after scheduled drop-off | 15 minutes |

Its channel rule is push when the app is installed and the driver is logged in,
otherwise text. For missing delivery, inspect expected status and trip timing;
do not mark a status just to silence a reminder.
[Status reminders](https://intercom.help/moovs-05c940f1970e/en/articles/8007480-driver-notification-remind-driver-to-update-trip-statuses)

## Configure tracked-flight change notifications

Use **Send driver a text if flight time is updated** for an airport pickup's
tracked-flight change. The dedicated guide says 15 minutes or more, while the
[general guide](https://intercom.help/moovs-05c940f1970e/en/articles/6369378-communications-settings)
says more than 15. Disclose the conflict rather than promising exact-boundary
behavior; inspect the observed change and current UI for an actual delivery issue.
[Flight update](https://intercom.help/moovs-05c940f1970e/en/articles/8002457-driver-notifications-send-driver-a-text-if-flight-time-is-updated)

## Configure accepted-trip update notifications

Use **Send driver trip update notifications**, documented off by default. It
covers customer/operator changes to accepted upcoming trips, with a 10-minute
delay and related unacknowledged changes grouped per trip. The guide describes
push for drivers with the Driver App and SMS otherwise. Drivers must acknowledge
changes before starting. A settings-only task ends at saved configuration; for an
actual trip update, inspect its acknowledgement separately rather than equating
an update save or notification with driver acknowledgement.
[Trip updates](https://intercom.help/moovs-05c940f1970e/en/articles/9875130-driver-notification-updates-in-a-trip)

## Driver declines or notification errors

Choose [decline notifications](#investigate-driver-decline-notifications) for an
actual rejection, or [notification errors](#investigate-driver-notification-errors)
for failed notification delivery. Neither diagnosis authorizes reassignment.

## Investigate driver-decline notifications

A driver rejecting an assigned trip can notify **all members** through separately
configured email and SMS settings in the operator app. These are channel settings,
not an individual-member recipient picker. Inspect the relevant current controls,
chosen channels and trip response; public prose does not provide a precise
settings path. Operator changes only the requested channel if needed and checks
its saved value. Do not reassign or generate another decline as a delivery test.
[Declines](https://intercom.help/moovs-05c940f1970e/en/articles/9740727-operator-notification-driver-declines-a-trip-assignment)

## Investigate driver notification errors

For **Error sending notification to driver**, inspect saved assignment first.
Then open **Settings > Drivers > Select Driver** to check saved profile details,
especially the phone number; public guidance also calls for the latest Driver App.
Operator checks/edits privately, with saved profile readback for an agreed change.
The error does not prove assignment failed; do not repeat assignment just to
create another notification.
[Driver notification error](https://intercom.help/moovs-05c940f1970e/en/articles/9850596-why-do-i-get-the-error-sending-notification-to-driver)

## Connect Google Calendar

1. Check paid-plan Calendar access and authorization to connect the intended
   company/Google organizer. Open **Settings > General > Moovs Market > Google
   Calendar**. Operator completes Google's offered authorization privately;
   never request tokens/codes or connect the assistant's account.
2. Return to Moovs and inspect the displayed connection/authorization state.
   An authorized trip's **Invite** menu is a corroborating sign, not proof any
   guest received an event. Do not create a trip or send an invite just to test.
3. If authorization is missing or uncertain, report that state and use Support;
   the guide does not establish every Google consent-screen or recovery step.

The [public integration guide](https://intercom.help/moovs-05c940f1970e/en/articles/7199695-about-google-calendar-integration)
adds one-account authorization and up to24hours for initial creation. Operator
privately checks **My calendars** in the authorized Google account, then reviews
only the intended permitted trip/event for sync; calendar appearance or an Invite
menu is not delivery/acceptance proof. That guide says driver unassignment, trip
cancellation or deletion sends cancellation email. Do not mutate trips to test it.
Reviewed 2026-10-16 for this setup/readback enrichment, not current sync acceptance.

[Google Calendar Invites](https://intercom.help/moovs-05c940f1970e/en/articles/10058047-google-calendar-invites)

## Set default Calendar guests

1. With the intended Calendar connected, open **Settings > General >
   Communications > Contacts**. Inspect **Add Booking Contacts to Trip Calendar
   Invites** and **Add Passengers to Trip Calendar Invites**. Both are documented
   off by default; actual saved values take precedence.
2. Explain these are company-wide defaults, not a one-trip guest edit. Operator
   changes only the agreed choices using current controls, including auto-save.
3. Reopen the settings and compare both saved values. Configuration readback is
   not proof existing events changed or that recipients saw/accepted an invite.

[Google Calendar Invites](https://intercom.help/moovs-05c940f1970e/en/articles/10058047-google-calendar-invites)

## Change per-trip Calendar guests

1. Confirm the exact trip and authorized Calendar. Open its top-right **Invite**
   menu; the public guide says it appears when Calendar is enabled/authorized.
2. Review organizer, assigned driver with email, and Booking Contact/Passenger
   guest choices. The organizer is the linked Google user. Operator adjusts the
   intended guest toggles and selects **Save**. This changes external guests,
   not just a local preview; do not change the assignment to troubleshoot it.
3. Reopen the guest list and, if authorized, the matching Calendar event. Compare
   the intended trip and guests. Saved guests do not prove delivery or acceptance;
   unknown outcome means inspect existing state before another save/invite.

[Google Calendar Invites](https://intercom.help/moovs-05c940f1970e/en/articles/10058047-google-calendar-invites)

## Calendar time troubleshooting

Reviewed 2026-10-16 from the Calendar Invites prose. Compare mapped pickup/drop-off
addresses, dates and times in Moovs first. The event starts at the pickup time in
the **pickup stop's time zone**. When a drop-off time is available, its end uses
the **drop-off stop's time zone**. Viewers can see conversion to their own
Calendar/device zone; do not apply one stop's zone to both endpoints by default.
Check the recipient's primary Calendar zone and the device's date, time and
time-zone settings, including automatic zone adjustment. If trip data was
corrected, allow the live event to sync, not a duplicate manual event. Escalate
persistent mismatch with reference, expected/displayed times and surfaces, using
redacted evidence. Operator sends Support request.

[Google Calendar Invites](https://intercom.help/moovs-05c940f1970e/en/articles/10058047-google-calendar-invites)

## Advertised Driver Wake-up Calls

Reviewed 2026-10-16. The undated [taxi](https://www.moovsapp.com/taxi-ride-hailing-operator),
[medical](https://www.moovsapp.com/medical-transportation-provider) and
[party-bus](https://www.moovsapp.com/party-bus-limo-operator) product pages advertise
Driver Wake-up Calls. Their punctuality claims are not a delivery guarantee.
This is distinct from the documented SMS trip reminders, pending-job push
reminders and overdue-status notifications above; do not reuse their schedules
or channels for calls. General third-party AI wake-up advice is not Moovs setup.

**Documentation gap:** current activation and call scheduling/delivery instructions
are not established by these pages. Ask Moovs whether this advertised function
is available for the intended company and for its supported instructions before
operator changes. Do not invent a Wake-up Calls toggle, place a test call, change
an assignment or infer a driver is awake from a reminder or accepted job.
