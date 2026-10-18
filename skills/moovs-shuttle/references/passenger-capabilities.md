# Shuttle passenger capability boundaries

Earlier sources reviewed 2026-10-15; passes/programs additions reviewed 2026-10-16.
These are dated/undated announcements plus bounded
review guidance, not live-tested setup walkthroughs. Check company, route type,
service date/version, purchased experience, role and visible capability. The
Help Center's Enterprise-only Shuttle wording and pricing's cross-tier Shuttle
App add-on remain unresolved product/package scope differences; do not infer
universal availability. See [the skill entrypoint](../SKILL.md).

Use [task authority](task-authority.md) for guided versus authorized execution;
ordinary operator controls may be assistant-owned. Exact consequential approvals
and actual role/source limits remain. Do not invent a live test booking outside
the approved task, take a passenger/driver identity or change location permissions to
test a capability. The checks below are recommended readback, not a demonstrated
end-to-end acceptance test. If no direct view is available, label reports as
operator-reported; no result is verified just because the capability was announced.

## Review Continuous Loop live tracking readiness

Reviewed 2026-10-16. Keep this a readiness review, not a GPS installation or
telemetry-recovery tutorial. Public Help supports the route/map checks below;
August's announcement names fleet integrations and the Driver App as location
sources, not a connection procedure or a guarantee for this account.

1. Confirm intended company, Continuous Loop route and service date. For an
   existing passenger-map review, reuse the provider's current link. For route
   readiness, compare the intended ordered stops, service dates, operating
   days/hours, frequency, assigned vehicles and applicable driver breaks with
   the configured route/current version. In **route > Operations**, select the
   service date and inspect scheduled vehicles/drivers, route progress and map.
   If there are no operational dates, inspect route version, recurrence/hours
   and vehicle configuration before proposing any operator change.
2. If the link is missing, use [link guidance](routes.md#copy-a-shuttle-passenger-or-booking-link):
   **Shuttle Routes > Copy passenger app link** or **Copy booking link**, then
   the intended company/Continuous Loop experience. Operator copies; do not
   send a link, publish a route or make a booking as a test. Passenger links
   open the Loop route experience; booking links open its public route map.
3. Privately open the intended passenger/public map link. Inspect available
   routes and compare the intended stops, operating hours and weekly schedule;
   then inspect the active vehicle information actually shown. Loop requires
   no seat booking. Do not invent map buttons, require a test booking or assume
   another route type's sign-in/checkout flow applies here.
4. Ask which existing location source is intended: fleet integration or Driver
   App. If unknown, record it as unknown and continue the map inspection; do
   not claim live tracking is ready. A configured vehicle, driver assignment,
   static map or displayed schedule does not prove current vehicle position.
   Report update times only if the actual view supplies them; otherwise source
   connection and freshness remain unverified. Invent no refresh/ETA threshold.
5. Separate missing route/map from a visible route whose expected vehicle is
   missing or whose displayed location appears stale. For the former, check
   correct company/link, active route, version and operational dates. For the
   latter, compare intended service hours/vehicle and any actual update evidence;
   without update evidence, record freshness unknown rather than diagnose stale.
   Ask Moovs/provider for supported source troubleshooting. These are triage
   checks, not proven causes. Record route/schedule visibility, displayed vehicle
   information and unresolved source/freshness separately.

**Remaining setup gap:** these sources do not establish integration/device
installation, vehicle/source mapping, Driver App tracking configuration,
permissions, refresh/fallback rules or stale-data recovery. Do not require an
unsupported installation or setup procedure merely to inspect an existing map.
These can still be genuine prerequisites for live tracking; keep their status
unknown until supported evidence establishes it. A map inspection proves none
of them. If setup is needed, request supported guidance; never reconnect an account,
change permissions, start a driver trip or republish service as a test.
The operator makes any separately supported change; reopen the same route/date
and link afterward. Without direct inspection, results are operator-reported.

[Passenger Loop guide](https://intercom.help/moovs-05c940f1970e/en/articles/9302607),
[Route Operations/configuration](https://intercom.help/moovs-05c940f1970e/en/articles/8430098),
[Company/link choices](https://intercom.help/moovs-05c940f1970e/en/articles/8430071),
[August 2026, 00:57-01:43](https://fast.wistia.com/embed/iframe/xkdnq3nqqz?wtime=57s).
The August segment is a presentation with a phone illustration, not current UI.
## Review seat-map and selected-seat scope

August 2026 previews custom seat maps/seat selection; September says the seat
selector is implemented. Do not freeze the August preview as unreleased, or
treat September's broad description as current enablement for every account,
vehicle or route. Loop's no-seat-booking experience remains distinct.

Confirm intended booking experience, route/trip/vehicle and whether the request
is map setup or reviewing an existing selected seat. If authorized state already
shows a map or selected seats, compare only the intended trip, passenger count
and shown seat identifiers with the operator's expectation. A capacity number
or ticket quantity alone does not establish assigned seats or reserved inventory.

**Documentation gap:** reviewed sources do not show map creation/assignment
controls, supported map constraints, inventory locking, accessibility rules,
change/reseat/cancellation behavior or persistence confirmation. Ask Moovs for
current supported setup before operator edits; do not invent a Seat Maps tab,
seat drag/drop, auto-save behavior or availability legend. After any separately
guided operator change, recommend reopening the same map/booking; do not claim
seat inventory was locked, or test by booking/paying as a passenger.

[August preview, 46:16-47:47](https://fast.wistia.com/embed/iframe/xkdnq3nqqz?wtime=2776s),
[September implemented statement, 02:11-02:43](https://fast.wistia.com/embed/iframe/zhhho37xt1?wtime=131s)

## Review Shuttle waitlist scope

September 2026 describes automated waitlists for sold-out Shuttle tickets when
cancellations may free space. It does not demonstrate configuration or promotion.
Confirm the intended route/trip/date, sold-out context and whether the request is
enablement, existing waitlist review or promotion. If an authorized view exists,
inspect only the needed record/status; a waitlist entry is not a confirmed seat,
booking, collected payment or delivered notification.

**Documentation gap:** enablement, eligible route types, ordering/priority,
promotion triggers, expiry, payment collection and notification rules/controls
are unestablished. Do not promise FIFO, automatic charging, guaranteed promotion
or an email/SMS when a seat opens. Ask Moovs for current supported guidance;
operator performs later authorized changes, promotion or messages. Recommend
reading back the specific entry and resulting booking/payment/delivery states
separately if promotion is attempted under that guidance. Do not cancel a booking
or add a real passenger merely to manufacture availability or test automation.

[September 2026, 02:43-03:07](https://fast.wistia.com/embed/iframe/zhhho37xt1?wtime=163s)

## Review Shuttle flight tracking and timing

September 2026 describes FlightAware tracking in Shuttle booking and Operator
experiences. Public booking guides separately document requested flight entry
for airport Shared Shuttle service. Entered flight details alone are not proof
tracking matched a flight, is current or changed a trip's service time.

Identify the intended booking, travel date and flight before inspecting existing
details. Compare requested/stored flight information and any status/timing the
actual authorized view provides. Separate airline/flight timing, requested
service time, route buffers and assigned trip time; do not infer automatic
rescheduling, driver notification or passenger delivery from a displayed delay.

**Documentation gap:** the tracking controls, matching/disruption behavior,
refresh timing and correction/rescheduling workflow are not shown. Request
current supported guidance for missing/incorrect tracking. Operator performs
any approved booking/time changes or messages; recommend reopening the booking
and affected trip afterward, checking stored flight and timing separately from
tracking status and delivery. Do not invent flight fields, invoke a private API,
or create a test flight/booking to prove readiness.

[September 2026, 04:22-04:38](https://fast.wistia.com/embed/iframe/zhhho37xt1?wtime=262s),
[Operator booking guide](https://intercom.help/moovs-05c940f1970e/en/articles/8430112),
[Passenger booking guide](https://intercom.help/moovs-05c940f1970e/en/articles/9302607)

## Ticket passes and remaining uses

The [bus-ticketing product page](https://www.moovsapp.com/bus-ticketing-software)
advertises weekly/monthly commuter, semester and event passes, plus multi-ride
bundles and remaining-use tracking. These are not ordinary single-trip quantities.

[December2025, 09:48-11:00](https://fast.wistia.com/embed/iframe/2cr38q63dr?wtime=588s)
partially narrates creating a named package with ticket count and package price,
including discounted multiple rides. Clarify those business-approved values;
do not copy demo amounts or infer validity dates from a package name. Its Loop/
Fixed Schedule references do not establish every current route's eligibility.
A described creation result is not demonstrated saved-state or remaining-use proof.

**Documentation gap:** exact current creation/save/activation, route eligibility,
valid-date/ride limits, redemption/decrement, expiry, changes and refund workflow
remain incomplete. Ask Moovs for supported setup and the purchased scope before
operator changes. Do not invent a Passes tab, unlimited-use policy or automatic
ride deduction. A ticket purchase or visible pass does not alone verify remaining
uses or a permitted trip; do not make a real booking/payment to test it.

## Client programs and booking access

The [shuttle-software page](https://www.moovsapp.com/shuttle-software) advertises
multiple client programs and SSO-gated executive booking, with program-specific
dispatch, tracking, check-in and reporting. This is not proof that Shared Shuttle
client attribution, app login and enterprise program administration are identical.

**Documentation gap:** no current program-create/assignment, SSO-provisioning,
role/company isolation or booking-eligibility procedure is established. Confirm
actual purchased product and program with Moovs. Do not invent SSO settings,
provision identities, share login tokens or move bookings across companies/programs.
A successful login is not proof the user can book or access every program.

December 2025 intended an employer-sponsored ride without ticket purchase
([14:18-14:34](https://fast.wistia.com/embed/iframe/2cr38q63dr?wtime=858s)), but
[16:49-17:38](https://fast.wistia.com/embed/iframe/2cr38q63dr?wtime=1009s)
then requires purchase; the presenter says the configuration needs modification.
No completed purchase or successful no-charge booking is established. Do not
invent a free-booking toggle or pay to test; ordinary documented booking paths
remain valid, but this program's no-charge setup/result remains unresolved.

## Nearest-shuttle alerts

Reviewed 2026-10-16. The [March 12, 2026 campus post](https://www.moovsapp.com/post/why-your-campus-needs-a-shuttle-app)
advertises nearest-shuttle alerts alongside live route updates and tracking.
That notification function is distinct from opening a Continuous Loop route map;
a visible vehicle or map does not prove alerts are enabled or delivered.

**Documentation gap:** current alert availability, enablement and trigger/channel
instructions are not established here. Ask Moovs for the supported passenger
experience and alert procedure for the intended company/route; do not assume
Loop-only or all-route eligibility, invent a subscribe button, or promise an ETA,
notification channel or background-location requirement. Passenger device and
permission changes stay with the passenger. Do not enroll anyone or trigger a
real ride/message to test. Any later alert result needs its own readback, not a
map screenshot or unsupported claim that every rider is subscribed.
