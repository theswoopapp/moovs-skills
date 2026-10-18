# Moovs Skills catalog

Usable release v0.3.0. Public-documentation-based coaching, not verified host or
live-browser integration. A published repository/release can contain an earlier
version; inspect its actual catalog and manifest rather than assuming this copy
is already on GitHub. Ask how for guidance; ask the assistant to do a task for task-scoped execution.
All domains include `references/task-authority.md`; ordinary operator procedure
steps are executable when authorized, not mandatory human-click handoffs.
Actual role/plan/tool limits, private sensitive entry, exact consequential-action
approval and passenger/driver identity remain distinct. No demo/quote-only ceiling.

Install the complete library if desired; load only the skill relevant to the
current request, then only its required references. Each folder works independently.

| Skill folder | Use for | Keep separate |
| --- | --- | --- |
| `moovs-plans` | Plan limits, allowances, add-on entitlement, upgrades/downgrades/pause questions | Billing/purchase requires its own exact approval |
| `moovs-account-settings` | Company/preferences, operational-time and fee defaults, members, password/2FA and multi-location scope | Private credentials; exact access-change approval |
| `moovs-quotes` | Quote guidance or authorized execution; preparation, Pipeline contracts/options, trip-aware templates and conversion | Quote is not reservation, payment or dispatch |
| `moovs-reservations` | Creation, Plus Code pickups, trip changes, duplication, cancellation/fee review, trip PDFs, manifests and timing | Cancellation is not refund |
| `moovs-contacts` | Contacts, companies, passengers, saved addresses, default notes, merging and export guidance | Profile-wide versus trip-only change |
| `moovs-customer-portal` | Operator booking settings, policies, signed terms PDFs, branding and portal sharing | Portal configuration is not website publication |
| `moovs-communications` | Customer/driver messages, templates, calendar, numbers and delivery | Scheduled/sent log is not delivery |
| `moovs-dispatch` | Dispatch views/search, bulk edits, milestones, assignments, Auto Dispatch and AI Scheduler scope | Assignment, acceptance and notification differ |
| `moovs-drivers` | Driver setup, availability, qualifications, driver-owned trip progress, earnings review, pay defaults and Operator closeout/payables | No driver impersonation; pay review is not payroll submission |
| `moovs-fleet-pricing` | Vehicles/categories, availability blocks, BRA, zones and pricing rules | Suggested price is not an approved rate |
| `moovs-affiliates` | Farm-in/out, partner discovery, GNet and settlement interpretation | Farm request is not acceptance or payment |
| `moovs-shuttle` | Operator companies/routes/bookings, Driver App manifests/stop actions and passenger account/booking handoffs | Check add-on access, route type and intended person's identity |
| `moovs-payments` | Reservation/trip collection, deposits, refunds, cards and merchant setup | Customer charge versus authorization, refund or payout |
| `moovs-invoices` | Customer invoices, eligibility, sending and payment review | Not Moovs subscription invoices |
| `moovs-finance` | Payouts, bank/verification handoffs, subscription billing, disputes, accounting sync and currency scope | No sensitive inspection, tax or lending advice |
| `moovs-reporting-help` | Search, dashboard/exports, Insights, migration preparation and support/feedback drafts | Report fields require their actual definitions |
| `moovs-websites` | Website booking installation, content, templates and domain-launch guidance | Website DNS versus email authentication |
| `moovs-addons` | Passenger App, CRM/Brand Kit, reviews, trip imports, Miles, forms, partners, managed marketing and API/telemetry scope | Advertised capability is not setup documentation or account access |

All folders are under `skills/` and include a `SKILL.md` entrypoint. For a task
spanning domains, finish one phase and pass only the necessary non-sensitive
context to the next. Do not run every skill or inspect every account page.

For an unlisted/undocumented feature, use current public sources and disclose
the gap. No source means no invented private-code-based walkthrough. A public
article or drafted procedure is not proof it works in the operator's account.

For note audiences/direct Dispatch edits and existing-output references, use
[reservation context review](skills/moovs-reservations/references/notes-reference-review.md).
For combined companies versus locations/aliases, use
[account scope review](skills/moovs-account-settings/references/multi-company-scope.md).

For trip PDF output, use [reservation printing](skills/moovs-reservations/references/trip-pdf.md); custom event manifests have [separate scope](skills/moovs-reservations/references/manifest-scope.md).
For proposed-pay note communication, use [Driver Notes](skills/moovs-drivers/references/proposed-pay-note.md), not payroll defaults.
For dated Shuttle stop/vehicle timing preparation, use [builder timing](skills/moovs-shuttle/references/builder-timing.md), not assumed completed publication.
