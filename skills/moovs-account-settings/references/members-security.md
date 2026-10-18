# Members, permissions and recovery

Reviewed 2026-10-16. Use task-authority.md; sensitive credentials/codes remain private.

## Invite a member

Guide **Settings > Members > Create Member**. Verify the intended person's role,
email and current seat allowance privately with the operator. **Save Member**
sends an invitation, so require exact recipient/role/effect approval before submission. The public guide says the new
member must create a password within ten minutes. If expired, do not automatically
delete/re-add the member even though the older article suggests that workaround:
confirm current recovery options with an Owner/Support to avoid unintended loss.
Reopen Members after the operator acts; do not claim email delivery from presence.

Source: [Adding Members](https://intercom.help/moovs-05c940f1970e/en/articles/6610083-adding-additional-members-to-your-moovs-account)

## Restrict page access

Only an Owner can manage permissions. Open the intended member profile and its
**Permissions** tab. Explain the page-specific toggle and obtain the Owner's exact access-change approval
before executing it in their authorized session; there may be no separate Save. A disabled page disappears from navigation and
cannot be restored by visiting its direct URL. Never route around permissions.
Reopen the member's permission setting; the member's actual access is a separate
operator-performed check, not a reason to impersonate their account.

The [pricing](https://www.moovsapp.com/pricing) label **Roles & permissions** does
not establish a custom-role builder or role deletion/transfer procedure. Use the
documented page toggles for that task; obtain supported instructions for a
different role-lifecycle request instead of inventing permission controls.

Source: [Member Permissions](https://intercom.help/moovs-05c940f1970e/en/articles/9456923-member-permissions)

## Password recovery

If already signed in and specifically seeking a reset, the public procedure
starts with the operator logging out; explain the session effect and let them
approve that exact session effect before executing logout. On the login screen,
they use **Forgot Password**, enter their own email and select **Send Email**.
The link is single-use and expires in five minutes; after an unusable/used/expired
link or error, operator requests a fresh one through this same process. Never
open, read, copy or retain the reset link/new password or inspect their email.

Source: [Reset Password](https://intercom.help/moovs-05c940f1970e/en/articles/6414629-reset-password)

## Two-factor authentication

Owner 2FA is required and cannot be turned off; an Owner can require it for
Admin/member accounts. Coach only the requested phase, with browser inspection
paused for password, number, email-verification and code entry.

For required first enrollment, the user signs in privately and verifies their
email **if prompted**. On **Set up two-factor authentication**, they enter their
own SMS-capable mobile number, select **Send code**, enter the six-digit texted
code privately and select **Verify & turn on 2FA**. After confirmation, they
select **Continue to Moovs**. Moovs emails notice that a phone number was added;
that notice or a requirement flag is not independent proof of later sign-in.

For later sign-in, user privately enters email/password, then the texted code on
**Verify it's you > Verify**. For a missing/expired code, wait for the countdown
before **Resend code** and use the newest code; repeated requests can be limited.

To require another member's 2FA: Owner opens **Settings > Members > member >
Two-Factor Authentication**, turns on **Require two-factor authentication** and
confirms **Require 2FA**.
This emails the member; setup occurs at their next sign-in, not immediately.

When phone access is lost, the user can select **Can't access your phone?** on the
verification screen. For a non-owner, an Owner can use **Reset 2FA** and confirm.
Warn that reset signs the member out and removes the enrolled phone, requiring
new phone enrollment at their next sign-in. Require the Owner's exact reset approval before executing in their authorized session.
An Owner locked out of their own phone,
unsupported region, or inaccessible Owner requires **support@moovsapp.com**, not
a bypass. Help prepare an inquiry if wanted; the operator sends it without codes.

Source: [2FA](https://intercom.help/moovs-05c940f1970e/en/articles/16450734-set-up-and-manage-two-factor-authentication-2fa)
