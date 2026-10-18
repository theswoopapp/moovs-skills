# Compatibility and installation

Reviewed 2026-10-18. These are documented setup paths, not completed acceptance
tests. Host subscriptions, organizational policy, and available tools differ.

## Start without installation

When the host can read the relevant Markdown files and references, use them as
instructions for the current conversation and say so. Do not make persistent
installation or a missing installer a gate for readable coaching. File-context
use is not automatic discovery in a new chat, a plugin install or browser access.
If files cannot be read, disclose that limit and use public Help/manual guidance.
Persistent options below apply only when the user requests installation.

## Claude

- **Claude web/Desktop/Cowork:** where custom skills are enabled, use
  **Customize > Skills > + > Create skill > Upload a skill**. Upload each
  individual skill ZIP, then enable it.
  Claude also requires its code-execution/file-creation capability and relevant
  organization skill policy. The operator/admin manages those permissions; this
  instruction-only pack does not require running repository code.
- **Claude Code:** put each extracted skill folder in
  `~/.claude/skills/<skill-name>/`, preserving `SKILL.md` and `references/`.
  Do not overwrite an existing folder. Confirm discovery in the host's skill UI.
- Local Claude Code folders are not the same installation as account-level
  skills for Cowork/cloud sessions. Supported terminal versions can also sync
  enabled account skills when signed into that same Claude account; API-key or
  cloud-provider sessions do not get that account sync. Check the actual `/skills`
  list rather than copying over synced files or changing sync settings.
- Browser access is a separate connection. Where available, the operator can
  configure Claude in Chrome using the official instructions and site permissions.
  Do not claim that uploading a ZIP connects a browser.

Sources: [Claude skills](https://support.claude.com/en/articles/12512180-use-skills-in-claude),
[Claude Code skills](https://code.claude.com/docs/en/skills),
[Chrome setup](https://support.claude.com/en/articles/12012173-get-started-with-claude-in-chrome).

## Codex local skill hosts

Place each extracted skill folder in `~/.agents/skills/<skill-name>/`, preserving
its references, or use the host's supported skill installer for the corresponding
`skills/<skill-name>` directory in this repository. Confirm the skill appears in
the skill selector; start a new session if the host requires it. Do not overwrite
existing folders or alter the user's global instruction files.

These folders apply to local standalone-skill hosts. The full bundle also has a
portable root `plugin.json`; [published ChatGPT pilot](../CHATGPT-PILOT.md) separates
GitHub marketplace registration, desktop installation, Plugin Creator and admin import. No generic
web ZIP importer or completed ChatGPT plugin installation is established here.
If native installation is unavailable, label the context fallback conversation-only.

Codex skill support does not establish that a particular session has an
authenticated interactive browser. Check the tools actually available in that
session. Do not prescribe an unverified connector or claim that web browsing
can control a signed-in Moovs tab.

Source: [official OpenAI skill documentation](https://learn.chatgpt.com/docs/build-skills).

## Other assistants

Use the host's native [Agent Skills](https://agentskills.io/specification)
installation when supported. Otherwise provide the relevant `SKILL.md` plus its
referenced Markdown files as context. Call that **loaded for this conversation**,
not a persistent installation. Hosts unable to read these files cannot use this
pack directly; offer the published Help Center instead.

## Capability check before product access

1. Can the assistant actually read the complete skill and needed reference files?
2. Does the host report the installed skill as available, or only chat context?
3. Can its authorized tools inspect and navigate the intended Moovs session?
   Ask the operator to sign in directly if needed, then inspect only a
   non-sensitive page to confirm the company. Do not inspect unrelated browser tabs;
   an authorized current-task PDF/output tab is not unrelated.
4. Does the operator consent to the minimum necessary customer data being
   processed by their chosen provider? Follow the organization's AI-use policy.
5. Confirm company and task-relevant role/plan/permission context. Follow requested
   guidance or execution; each domain's `references/task-authority.md` defines
   scope, sensitive-entry boundaries, consequential approvals and saved readback.
   No quote-only/demo-only or blanket human-click restriction.

If any required capability is absent, say what is missing and use manual
guidance. Never claim to have seen, changed, or verified a page without evidence.

## Updates and host acceptance

Install a reviewed version; do not silently update during a task. For an update,
review changes first and ask before replacing the old skill folder.

Before advertising a host as tested, run the scenarios in `evals/` using synthetic
data, verify discovery after restart, browser authorization, correct company/plan
checks, navigation, actual permitted execution, sensitive-entry handoffs and independent readback. A successful
ZIP import alone is not a working Moovs integration.
