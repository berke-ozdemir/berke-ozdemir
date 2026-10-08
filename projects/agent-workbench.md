# Agent Workbench

A local Python toolkit for keeping agent context, messages, decisions, and handoffs explicit.

**Status:** Offline core implemented; live integration unfinished · **Stack:** Python, SQLite, Git · **Source:** Local, not yet published

## The project

Agent Workbench records which project and session a piece of work belongs to, which files were provided as context, and which decisions were accepted. Context packages are immutable snapshots tied to a Git revision; later source changes do not silently change a captured package.

Messages can be queued into another session's local inbox under explicit authorization or a bounded grant. Decisions are proposed and accepted separately, and handoffs collect selected records into a checkpoint.

## Areas of work

- Project and session registration.
- Context snapshots with content hashes and revision information.
- Local message forwarding, quotas, expiry, and idempotency.
- Decision records with explicit acceptance and replacement.
- Handoff manifests and audit events.

The accepted offline core has a recorded 349-test verification checkpoint. This is historical evidence, not a claim that the current working tree has been retested. The newer protocol component remains pending verification.

The tool does not yet run agents, deliver messages to providers, or enforce a sandbox. Permission labels are metadata; local grants are not an operating-system security boundary.

[Back to my profile](https://github.com/berke-ozdemir)
