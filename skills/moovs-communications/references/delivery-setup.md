# Delivery and number setup

Reviewed 2026-10-16 for SMS registration, GoDaddy correction and call identity;
other sections 2026-10-15. Operator makes every submission, call, send, DNS edit
and save. Do not expose registration documents, identifiers, credentials or
customer message content in chat/screenshots. No purchase or paid enablement by assistant.

## Email missing or spam

1. Confirm correct reservation, recipient and expected message in **Activity Log >
   Email**. Missing log, logged sent and filtered inbox are different conditions.
2. Ask recipient to check Spam/Junk/filtered tabs, search sender/reference and,
   if legitimate, mark Not spam/add sender to contacts. Operator communicates;
   do not repeatedly resend to test placement.
3. Review verified custom email-domain setup where relevant. Authentication can
   help but cannot guarantee inbox placement. Multiple valid recipients missing:
   draft Support context with reference, domain, type and approximate send time.

The [custom-domain guide](https://intercom.help/moovs-05c940f1970e/en/articles/6414592-setting-up-my-custom-domain)
(rechecked 2026-10-16) warns that previously bounced or reported addresses may be
suppressed by the email provider and can require recipient-side handling. Domain
authentication is not proof an address is unsuppressed or mail reached an inbox.
Use current provider/Support guidance; invent no Moovs unblock control or repeated
test sends. A missing email alone does not diagnose suppression.

[Emails Going to Spam](https://intercom.help/moovs-05c940f1970e/en/articles/10503224-troubleshoot-moovs-emails-going-to-spam)

## Custom email domain

January2025 describes branded automated **outbound** email, not syncing/receiving
an external mailbox inside Moovs. Custom-domain authentication is not inbox setup.
Current Help documents permission to send on your behalf, not a mailbox-import
procedure; keep ordinary received email in its provider and obtain current
supported guidance for any different integration request. Do not invent email
sync, request mailbox credentials or change MX records to create an inbox.
[January2025, 27:08-28:19](https://fast.wistia.com/embed/iframe/f18u4cfp3s?wtime=1628s),
[current custom-domain Help, checked 2026-10-16](https://intercom.help/moovs-05c940f1970e/en/articles/6414592-setting-up-my-custom-domain).

A registered business domain and email hosting must already exist; do not start
setup without them. The authorized domain owner handles provider login and DNS
changes privately. Authentication helps but does not guarantee inbox placement.

1. Read current domain status and the relevant provider instructions. Confirm
   intended business domain/FROM address, not gmail.com or an unrelated company.
2. For an intended new setup, public navigation is **General Settings >
   Communication > Custom Domain > Setup Custom Email Domain**. Operator enters
   only the root domain, without www or a URL scheme, matching the FROM address's
   domain, then **Save My Domain**. Do not restart an existing setup speculatively.
3. Operator compares all Moovs-generated CNAMEs with the provider's records.
   GoDaddy Host maps to Name without a duplicated domain suffix; Points To maps
   unchanged to Value. Other auto-suffixing providers can need the same host fix.
   Use current generated values, not copied examples or account details in chat.
4. Cloudflare records must be **DNS-only**, not proxied. Marketing Campaigns use
   their own domain-screen records, distinct from quote/transactional CNAMEs;
   do not reuse one set as proof the other is verified.
5. Operator edits or removes only confirmed incorrect obsolete Moovs CNAMEs; do
   not leave old wrong entries alongside corrected ones. Preserve MX/SPF and all
   unrelated DNS; never bulk-replace a zone or change hosting to repair email.
6. GoDaddy guidance uses **Save All Records**. After the applicable provider save,
   refresh Moovs Communications, then **I've added these records > Verify** where
   offered. Provider/current labels can differ. Allow up to48hours; pending is not
   verified. Reinspect status without a customer test email or delivery guarantee.

[General custom-domain setup](https://intercom.help/moovs-05c940f1970e/en/articles/6414592-setting-up-my-custom-domain),
[GoDaddy verification](https://intercom.help/moovs-05c940f1970e/en/articles/7232138-setting-up-and-troubleshooting-custom-email-domain-in-godaddy)

## SMS registration

1. **Settings > SMS Registration > Register Now/Continue Registration**.
   Confirm authorized business and number. Operator privately supplies official
   business information; the public form supports US EIN or Canadian CBN.
2. Privately prepare business/company type and the primary business contact's
   name, title, job position, email and phone. **Only for a public company**, also
   prepare its stock exchange, ticker and qualifying brand-contact email. Do not
   request these private registration fields in chat.
3. Guide Business Details, Tax Document, Additional Business Details and Point
   of Contact. Do not view, copy or store tax documents/identifiers. Legal name,
   address and registration number must match official records.
4. Operator reviews and submits. Track Brand, Campaign and Phone number stages;
   pending review can take days and is not messaging acceptance. Later stages
   continue automatically after earlier approval.
5. Missing page, unsupported registration type or failure: draft Support request
   with stage/status only. Sensitive documents need a secure Support-provided path.

[Register Local Number](https://intercom.help/moovs-05c940f1970e/en/articles/11373819-register-your-local-number-for-sms)

## Number porting and forwarding

Choose [toll-free porting](#request-and-track-a-toll-free-port) to move a number,
or [call forwarding](#configure-call-forwarding-through-team-profiles) to change
where inbound calls ring. These are different tasks, not a number-edit wizard.

## Request and track a toll-free port

The public guide permits Administrators to initiate a toll-free port. Operator
contacts Support/Porting and supplies account information and a signed LOA through
their approved channel. Review details first: amendments restart processing.
Published 5-10 business days assumes no LOA issues; it is not a guaranteed cutover.
Ask Porting for status; a request submitted is not a completed port. Successful
porting is followed by an email to the Moovs Admin. Do not cancel the existing
carrier service on an assumption. Port status is separate from applicable SMS
registration/readiness; even completion is not proof of SMS delivery.
[Porting](https://intercom.help/moovs-05c940f1970e/en/articles/9927563-porting-in-my-number-into-moovs)

Older general help describes a fixed number. Do not promise self-service number
replacement or deny documented toll-free porting based on that older wording.
[Communication Settings](https://intercom.help/moovs-05c940f1970e/en/articles/6369378-communications-settings)

## Configure call forwarding through team profiles

Open **Settings > Members**. Operator creates or opens the intended Admin/Member,
adds a valid supported mobile number and saves the profile. Reopen that profile
and compare the saved destination; this does not prove successful call delivery.
Moovs can ring up to ten unique numbers on one inbound call, plus a separate voice
forwarding number if configured. The destination need not be US-based, but must
be valid/supported and cannot be the Moovs number itself. Incoming calls can ring
multiple team members simultaneously. Their incoming caller ID is the **Moovs
number**, identifying the business call, not the actual caller. The post-call
summary goes to the general email and identifies the actual caller number, call
duration and basic metrics. Keep that destination current; inspect only a needed
authorized summary, not unrelated call history. This establishes no current
call-history UI or delivery outcome. Do not place a test call without explicit
scope and operator action.
[Moovs Communication](https://intercom.help/moovs-05c940f1970e/en/articles/10441086-understanding-moovs-communication)

## SMS filtering and international use

Choose [filtering investigation](#investigate-sms-filtering) for missing messages,
or [international service](#review-and-request-international-messaging) for
eligibility, coverage and cost. Enabling service does not prove delivery.

## Investigate SMS filtering

Check valid recipient/number, opt-out, registration, enabled trigger/channel and
observed delivery state. Carriers can filter similar-volume patterns or links,
and may not provide a specific reason. Do not evade opt-outs, rotate numbers or
rewrite a prohibited marketing message to bypass filtering. Escalate persistent
patterns with redacted examples instead of generating more traffic.
[SMS filtering](https://intercom.help/moovs-05c940f1970e/en/articles/11055475-why-can-some-moovs-text-messages-be-filtered-a-simple-explanation)

## Review and request international messaging

The dated public guide describes Pro availability on request, prepaid balance and
automatic replenishment. Before operator requests enablement, confirm current
eligibility, countries, rates, usage/allowance and replenishment terms with
account/Support; do not promise included unlimited messaging or quote old rate
tables as current. Recipient carrier charges may also apply.

The guide starts the prepaid balance at $20, replenished when depleted rather
than a monthly subscription charge, and describes a monthly usage/payment/rolling-
balance report. Countries cannot be individually selected: enablement covers all
countries supported by Moovs, not a chosen subset. Operator requests enablement or
cancellation separately through their CSM/Support chat and checks the resulting
service/status and terms; a request is not proof enablement or delivery succeeded.
[International rates](https://intercom.help/moovs-05c940f1970e/en/articles/9455314-international-call-text-rates-for-moovs)
