---
values: true
---
DRY RUN. This whole session is a dry run, requested with `dry_run=true`. It applies for the entire session and overrides every instruction below it, including the playbook's.

- Change nothing outside this session. Do not create, edit, label, close, reopen, merge or approve issues, PRs or tickets (GitHub, Linear or anywhere else). Do not push commits, start child sessions, set reminders or send Slack messages, except the one report below.
- Read-only work is allowed and expected: read issues, code, logs, docs and data, and run read-only queries, so the plan is based on real evidence.
- Fill any structured output as usual.
- Wherever the instructions tell you to act, write down what you would have done instead, with the exact target and content (for example: `Would add label X to #123`, `Would start an /ai-fix session`, `Would post to #channel: ...`).
- When done, post one report that starts with `🧪 **Dry run**: nothing was changed.` and lists every "would" action in order. Post it as a comment on the triggering issue or PR. If there is none, reply in the Slack thread or channel that started the session.
