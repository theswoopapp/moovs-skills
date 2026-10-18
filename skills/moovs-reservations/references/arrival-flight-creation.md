# Create an airport-pickup reservation with a matched arrival flight

Reviewed 2026-10-16 using complete public creation Help and its actual embedded
GIF frames. The filmed interface is dated, not current tenant acceptance. This
is a complete new airport-pickup reservation, not existing-trip flight editing,
airport-departure matching, Shuttle booking or an automatic-disruption procedure.

## Before creation

Confirm the authorized company, permission/feature access, intended new booking
and whether a quote/reservation already exists. Do not create a second booking
for a failed/uncertain save or just to test tracking. Use only necessary details.

Confirm booking contact and traveler separately, arrival airport, airline and
flight number, actual flight service date, trip pickup date/time and timezone,
destination, passengers, luggage, vehicle and approved price. A flight number
without its airline, date and route can identify the wrong service. The pickup
airport must be the flight's **arrival**, not its origin. Do not extrapolate this
arrival sequence to an airport drop-off/departure flight.

The operator performs every field selection/edit and final Save. Use authorized
browser inspection only; otherwise coach manually and label results
**operator-reported**. Do not buy tracking, set up a FlightAware account/API key,
change billing or infer entitlement from the button. Pause inspection for any
optional private payment entry; creating a reservation does not require a card
under the public Operator creation guide and adding one is not a charge.

## Build the reservation and match its flight

1. Open **Reservations > Create**. Search/select the intended booking contact;
   deliberately create a contact only if needed, and confirm the separate
   passenger. Select the intended trip type and pickup date/time. This source
   demonstrates a one-way airport pickup; do not assume return-leg flight data
   will copy or that another trip's flight should be overwritten.
2. Under **PICK-UP**, use the airport/airplane mode control rather than the
   ordinary address mode. Confirm **Arrival Airport** appears. Search the actual
   airport and select the matching result by airport name/code. Do not leave
   only typed search text or choose an airport with a similar name.
3. In **Airline**, search and select the intended airline. In **Flight**, enter
   its intended flight number using the field's displayed airline context; do
   not guess a carrier/code or silently substitute another flight if unavailable.
4. Wait for the flight card. Compare its airline/flight identifier, origin and
   destination, flight date and scheduled arrival with the intended service.
   The destination must match the selected arrival airport. Review departure
   and arrival dates separately for overnight services. Compare **status** and
   **Last Updated** if displayed; a Scheduled card or a timestamp is not proof
   of a later live update. No matching card, wrong route/date, missing critical
   identity or incompatible current controls: stop for supported guidance before
   saving. Do not treat notes containing a flight number as a successful match.
5. Compare pickup with arrival in the relevant local timezone and the operator's
   intended passenger-ready interval. Choose the actual service pickup time,
   not the demo's example time; the filmed pickup precedes its displayed arrival
   and is not an operational timing recommendation. Do not alter an otherwise
   correct time merely to compensate for a timezone display. Public wrong-time
   Help explains that mapped location and trip date determine trip timezone.
6. Select the correct mapped **DROP-OFF** address and any intended intermediate
   stops. Review the full ordered itinerary, passenger count, relevant notes and
   luggage. Select the intended vehicle with **Add Vehicle** and check actual
   suitability/availability. Review approved pricing; a BRA suggestion, when
   enabled, is not authorization to change the agreed fare. Complete only the
   intended reservation, not extra legs, payments, assignments or notifications.
7. Review all details and choose **Save reservation** for save-only. The separate
   **Save reservation & send email** sends the Booking Contact a confirmation;
   do not choose it without an explicit send request and recipient review.
   The operator submits the intended choice. Save-only does not prove absence
   of every other configured downstream notification.

## Read back the saved booking

Open the saved reservation and correct trip. Compare confirmation reference,
contact/passenger, pickup airport/date/time, mapped destination, vehicle and
price. Confirm the saved pickup flight card still shows the intended airline
and flight number, its displayed status/time and the correct arrival airport.
A toast alone or a flight card in an unsaved drawer is not saved-state proof.
If the saved card does not expose enough identity/date information to distinguish
the intended service, obtain supported current readback rather than guessing.

Report **saved flight association read back** only for that exact trip, otherwise
**operator-reported**, **prepared** or **blocked**. An uncertain save requires
search/readback before retrying, never creating another reservation automatically.

The flight status is not proof of passenger readiness, driver acceptance,
notification delivery or payment. Refresh cadence, existing-trip edit controls,
airport departures and cancellation/diversion/repricing effects are not established
by this creation sequence. Do not force a flight/time change to test automation.
For an actual tracked arrival update, separately compare flight and pickup time;
the general flight guide explains dated offset narration, not unconditional effects.

## Public sources

- [Creating a Reservation](https://intercom.help/moovs-05c940f1970e/en/articles/6434587-creating-a-reservation):
  explicit creation/save prose and actual embedded GIF1: airport mode and selected
  arrival airport, airline/Flight entry, matched card, final save choices and saved
  trip card. The flight-card route/status observation is from literal frames.
- [Current creation walkthrough](https://intercom.help/moovs-05c940f1970e/en/articles/7827458-how-do-i-create-a-reservation):
  overall builder sequence, mapped-address selection, vehicle and pricing review.
- [Confirmation choices](https://intercom.help/moovs-05c940f1970e/en/articles/6457674-sending-confirmation-emails):
  save-only versus Booking Contact confirmation email.
- [Wrong date/time](https://intercom.help/moovs-05c940f1970e/en/articles/16451211-troubleshoot-a-trip-showing-the-wrong-date-or-time):
  mapped-location/date timezone and exact-trip comparison, not flight matching.
