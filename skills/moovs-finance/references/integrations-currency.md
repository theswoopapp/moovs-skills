# Accounting integration and payment-currency gaps

Public [pricing](https://www.moovsapp.com/pricing) names **QuickBooks & accounting
sync** and **Currency Payments**. These labels establish advertised capability,
not a connection/payment procedure, supported-currency list or current account
entitlement. Reviewed 2026-10-15. Follow task-authority.md for explicitly
authorized supported UI steps; no credentials or sensitive screenshots in chat
and no private exports in public artifacts.

## QuickBooks and accounting sync

Clarify whether the goal is accounting synchronization, recording an already
received external payment, or downloading a report. A QuickBooks ACH label on an
external receipt is not an enabled accounting integration. A CSV export or a Miles
journal is not proof of QuickBooks sync either.

Identify the intended Moovs company and accounting organization without private
identifiers; confirm purchased/enabled access, role and the operator's intended
scope. The reviewed public sources do not establish a complete connector setup,
authorization scope, mapping, sync direction, cutover/backfill, duplicate handling,
error recovery or disconnect procedure. Read a matching current public Help guide
if available; otherwise obtain supported instructions from Moovs before directing
connection or sync. Do not invent OAuth controls, mappings or historical imports.

Do not connect accounts, request tokens, upload ledgers or trigger a sync as a
test. Before any supported operator action, explain its documented data scope
and duplication risk. Afterward, have the operator privately compare the intended
organization/mapping, sync status, relevant period and sample business records.
Connected status is not proof of historical completeness or reconciliation.

## Currency Payments

Clarify whether the question concerns a customer charge currency, displayed
pricing, payout/settlement currency or a Financial Account's currency-specific
default destination. Those are distinct questions. A bank-routing/default option
does not establish that a customer charge in that currency is supported.

The reviewed pricing label does not establish supported currencies/countries,
merchant eligibility, where to choose currency, FX/fees, settlement or refund
rules. Confirm the intended transaction context and check current public Help;
if unsupported there, ask Moovs for the applicable policy before payment entry.
Do not infer conversion rates, promise settlement currency or link a personal
Stripe account as a workaround. The [Free-plan policy](https://intercom.help/moovs-05c940f1970e/en/articles/9927108-important-updates-for-free-plan-users)
still excludes Stripe-backed processing; currency features do not override it.

No real charge, refund or bank/default change is an access test. For a supported
operator-led workflow, privately review currency and amount before submission,
then compare the actual transaction status/currency and separately the documented
settlement outcome. Do not equate displayed price, successful charge and payout.
