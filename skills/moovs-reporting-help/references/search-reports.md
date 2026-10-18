# Search, dashboard and exports

Reviewed 2026-10-16. Follow task-authority.md for scoped downloads/financial actions.

## Find the correct record

Public Global Search guidance supports an order-trip reference and shows stage
(quote, reservation or unconfirmed). Search an exact synthetic reference such as
**1234-1**, then confirm stage, date and intended contact before opening. The
article describes up to15trip results, not an exhaustive history; absence from
that limited list is not proof a record does not exist. This is a dated source
limit, not a guarantee every current search/view uses that limit.

The July 2025 webinar also narrates finding a quote/reservation through either
its **Booking Contact** or **Passenger** contact. If the reference is unknown,
try the intended contact in Global Search, then compare stage, trip date and both
contact roles; a contact match alone does not identify the right trip. The
captions do not establish exact query syntax or current controls; reconcile with
current Help or the offered search before giving a click sequence.
[July 2025, 00:40-01:05](https://fast.wistia.com/embed/iframe/lx539nwwlt?wtime=40s).

Source: [Global Search](https://intercom.help/moovs-05c940f1970e/en/articles/11657554-turbocharge-your-searches-moovs-unveils-supercharged-global-search)

## Choose a dashboard view

Published route: **Dashboard** in the sidebar or under **More**. Choose the tab
based on the question: Reservations/Quotes for activity, Customers for repeat
business, Drivers and Vehicles for utilization, Affiliates for payouts,
Accounting for outstanding amounts, Audit Log for changes, QR Code for campaigns.
Use the date quick options or custom date picker for the intended period. Other
filters depend on the tab: confirmation number, user email, UTM parameters, invoice
number and closed status. Operator changes only relevant filters, not every one.
Inspect Data Sync Status when available; a label alone is not independent freshness
proof. Keep raw financial identifiers hidden and exports in the approved private destination.

February locates last/next-sync information at the bottom of Overview and
narrates a three-hour cadence. Check the actual displayed sync times/status for
the selected view; that dated cadence is not a current SLA or proof every
record/accounting period is complete.
[February 2026, 39:52-40:26](https://fast.wistia.com/embed/iframe/4xlf6w2fzq?wtime=2392s).

Task-oriented report map from the public Dashboard body:

| Question | Tab and supported report scope |
| --- | --- |
| Activity overview | **Overview**: month/quarter/year reservation comparisons, Total Reservations chart, Total Quotes and sync status. |
| Reservation trends/details | **Reservations**: count/amount by date, amount YoY, order-type breakdowns, initial stage, promo count/value, weekday counts and **All Reservations Table**. |
| Quote activity | **Quotes**: price YoY, weekday counts, monthly total price and **All Quotes Table**; quote value is not collected revenue. |
| Repeat business | **Customers**: top15by trip count, top by revenue and new/returning mix, not all-customer completeness. |
| Fleet/driver performance | **Drivers and Vehicles**: vehicle trip counts/amounts, driver trips/mileage, vehicle distance utilization, **Drivers Table** and **Driver Payout Summary**. |
| Driver balances | **Driver Payout Summary** shows trip count, earnings, gratuity, amount paid and balance due; it does not send payroll. |
| Farm-out amounts | **Affiliates > Affiliate Payouts**: farmee, trip count and payable amount for the selected period, not a customer-charge or bank-deposit report. |
| Outstanding amounts | **Accounting**: **Total Reservation Amount Due**, **Total Reservation Amount Due - Not Invoiced**, **Moovs Invoices**, **All Reservations Table - Amount Due**; these are distinct views, not proof money was collected. |
| Change investigation | **Audit Log > Moovs Operator Request Activity**; scoped details below. |
| Campaign attribution | **QR Code > All Reservations Table - QR Code** groups by order number with total amount and UTM Source/Medium/Campaign/Term/Content/ID, not causal ROI or proof of payment. |

Do not assume all charts count cancellations identically: the guide distinguishes
an Overview chart excluding them from a Reservations amount chart including them.
A chart's value is not automatically cash received. Table **...** menus provide
CSV export; operator verifies scope and starts it. Custom report builders,
scheduled delivery and their accounting definitions are not established here.

Source: [Dashboard](https://intercom.help/moovs-05c940f1970e/en/articles/6809586-in-moovs-what-is-the-dashboard)

For paid-total discrepancies, distinguish driver earnings/payables from customer
collections and from merchant payouts. Compare exact field definitions, date
basis, period/timezone and payment methods before deciding a total is wrong.
A successful customer charge can precede settlement and bank payout; payout
timing is not necessarily trip date or charge date. Generic/external payment
recording is also not Moovs-collected money. Do not edit records to force a match.
[Payment/report distinctions](https://intercom.help/moovs-05c940f1970e/en/articles/13289137-why-are-there-discrepancies-in-payment-records-and-financial-tracking-in-moovs)

For office-staff commissions, August describes **Assigned Member** on a quote/
reservation and reporting by that assignee so the business can calculate amounts.
Use the [ownership guide](https://intercom.help/moovs-05c940f1970e/en/articles/15505676-assigned-member-track-who-owns-each-quote-and-reservation)
for an intended owner change; do not reassign records just to improve a report.
Review the intended period and actual assignee data with the operator, separately
from the business's approved commission calculation. The narration does not give
an exact reporting filter or establish automatic commission calculation, a ledger
or payment. Assigned Member is not driver assignment, driver payroll or the
partner Agents Portal; obtain current supported report instructions if needed.
[August 2026, 40:10-41:44](https://fast.wistia.com/embed/iframe/xkdnq3nqqz?wtime=2410s).

## Custom one-entry Excel tooling is not a Dashboard export

September2026 describes a custom implementation that retained an Excel document
while entering reservations only once in Moovs. This testimonial is not a public
setup, sync or export contract. For that goal, clarify the intended document,
fields and update needs, then request current supported implementation guidance.
Do not present the manual Dashboard CSV download above as automatic Excel sync,
invent an integration/install path or promise freshness or plan availability.
[September, 20:14-21:55](https://fast.wistia.com/embed/iframe/zhhho37xt1?wtime=1214s).

## Request Source attribution is not the conversion-event contract

March's Q&A names **Request Source** in the Reservations tab and explains GTM/
Analytics parameters and cookies broadly. It does not define how labels such as
Google Ads, Direct or Passenger App are assigned, how attribution persists on
older records, or why Google Ads can appear without an active campaign. Current
Dashboard and GTM event Help do not resolve those exact rules.

For an existing discrepancy, confirm the intended reservation, date/filter and
literal displayed label; compare only relevant available UTM/source details.
Keep the label and observed fields separate from an inferred marketing cause.
Ask Moovs for the current Request Source definition/history rules; do not relabel
records, enable GTM or create bookings to manufacture an explanation. A fired
conversion event does not prove that label or ad-campaign attribution is correct.
[March 2026, 22:17-24:26](https://fast.wistia.com/embed/iframe/12zjubd9ns?wtime=1337s),
[GTM event reference](https://intercom.help/moovs-05c940f1970e/en/articles/8466983).

## Investigate dates, utilization and changes

July 2025 first answered a Dashboard question using Dispatch's week view, then
corrected the surface: Dashboard preset hover/selected-date display reveals the
actual included dates. Do not transfer Dispatch's Monday-Sunday answer to
Dashboard or assume a preset is a rolling seven days. Inspect the offered date
range before comparing metrics; operator changes any persistent filters. If hover
is unavailable, use the visible range/current Help rather than inventing dates.
[July 2025, 42:53-44:10 and corrected 50:19-51:43](https://fast.wistia.com/embed/iframe/lx539nwwlt?wtime=3019s).


The February public Dashboard walkthrough shows relative presets and fixed
before/on/after/range filters; its demonstrated default is previous twelve months,
not a universal current account setting. Inspect active filters before comparing
metrics, and let the operator change any persistent filters deliberately.

For Drivers/Vehicles, compare the intended period and metric: mileage, trip count,
amount and utilization are not interchangeable. An empty date window is not zero
historical work. Displayed mileage is not tax certification or a verified GPS log.
For Accounting, distinguish open reservations/amount due from collected revenue.
Inspect only authorized relevant metrics/status; keep sensitive identifiers hidden.

In **Audit Log**, the demo searches member email, confirmation reference and date
to investigate price/vehicle changes. Use the minimum intended record and compare
visible actor/time/changed fields and before/after values. Current public Help
describes **Moovs Operator Request Activity** as the most recent100changes: this
is displayed-result scope, not a100-change retention limit, complete history or
a duration guarantee. Do not promise complete indefinite retention,
every field's history or proof a person physically performed a trip. Do not change
records to demonstrate an audit entry. Report unavailable/ambiguous evidence.
[February 2026, 36:12-39:33](https://fast.wistia.com/embed/iframe/4xlf6w2fzq?wtime=2172s),
[Dashboard Help](https://intercom.help/moovs-05c940f1970e/en/articles/6809586-in-moovs-what-is-the-dashboard).

## Ride Report arrival and departure review

The public Reporting page gives the route **Dispatch Log > Ride Report** for
driver arrival/departure times. Confirm company, intended trip/service date and
driver before interpreting timestamps; inspect the offered scope rather than
inventing filters, an export schema or a scheduled-report builder.

Compare the displayed trip and arrival/departure entries with the question being
investigated. Missing timestamps are not proof the driver did not perform the
trip. Do not change trip status, simulate Driver App events or alter pay to fill
a reporting gap. Keep passenger/location details private. If the tab or expected
entries are unavailable, state what is missing and ask Support; opening a report
does not establish location accuracy, data completeness or payroll approval.

Source: [Official Reporting page](https://www.moovsapp.com/solutions/solutions-reporting)
(reviewed anonymously 2026-10-15; route and purpose, not a full report-builder demo).

## Processing statements, charges and payouts

Guide privately: **Finances > Payments/Payouts > Export**, choosing the intended
period first if a selector exists. Published guidance describes monthly exports,
with broader range selection only when actually available. For a year, operator
checks consecutive periods without gaps/duplicates rather than assuming one
monthly download contains the full year. Inspect only authorized task-relevant
columns/results; keep raw financial identifiers hidden and exports private.

Keep merchant transaction exports separate from the invoices Moovs sends for
software/services. Those are under Billing/Invoices; **Load More** reveals older
invoices. The article says Google Ads spend is separate. If mobile Load More
fails, try desktop/another browser before considering cache clearing, which can
remove sessions. Export success is not proof totals reconcile or deposits arrived.

Sources: [Charges/payout exports](https://intercom.help/moovs-05c940f1970e/en/articles/16961094-how-can-i-export-charges-and-payouts-from-moovs),
[One-month statement](https://intercom.help/moovs-05c940f1970e/en/articles/13293402-how-can-i-export-a-one-month-processing-statement-in-moovs)
