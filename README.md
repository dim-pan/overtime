<p align="center"><img src="docs/assets/logo.png" alt="Overtime" width="300"></p>

<h3 align="center">An open-source Codex and Claude Code app for running hundreds of always-on agents in the cloud.</h3>

<p align="center"><img src="docs/assets/hero.jpg" alt="Overtime: a wall of AI workers, each at its own computer, next to a punch clock" width="900"></p>

> Private preview. The code moves here once it is ready.

## Thesis

The businesses that win will be the ones that can run many agents at once, doing valuable work well and without supervision. Get that right and your workforce scales with compute, not headcount.

## What it does

- Runs Claude Code and Codex agents on your own cloud VMs, always on.
- Gives each agent a role, its own files and memory, and a real browser.
- Lets you watch any agent live and take over its screen.
- Holds anything consequential (sending, posting, buying) for your approval.
- One app to manage them all: a native Mac app, plus Telegram.

Agents run in the cloud only, never on your laptop.

## Layout

| Folder | |
|---|---|
| [`app/`](app) | Mac app |
| [`gateway/`](gateway) | Server the app talks to, one per workspace |
| [`harness/`](harness) | Runs an agent on Claude Code or Codex |
| [`provision/`](provision) | Sets up VMs, workspaces and agents |
| [`docs/`](docs) | [Messaging](docs/messaging.md), [brand](docs/brand.md) |
