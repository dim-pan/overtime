<p align="center"><img src="docs/assets/logo.png" alt="Overtime" width="300"></p>

<h1 align="center">Run and manage 100 always-on agents in the cloud, from Mac and iOS.</h1>

<p align="center">The Codex app for AI employees. Open source.</p>

<p align="center"><img src="docs/assets/hero.jpg" alt="A punch clock feeding a grid of hundreds of desks, each with an AI employee at its own computer" width="900"></p>

> Private preview. The code moves here once it is ready.

## Problem

- **Chat apps are the wrong cockpit.** Steering an OpenClaw-style agent through real work over Telegram is painful. Steering ten is impossible.
- **The best agent apps are stuck on your laptop.** Claude Code and Codex are great, and computer use is remarkable, but they run locally. Remote control is clunky, and computer use does not scale to many agents at once.

## What you get

- **Always-on employees.** An OpenClaw-style harness (memory, schedules, heartbeats, Telegram) on top of Claude Code and Codex, with OpenClaw and Hermes next. They keep working when your laptop is closed.
- **Set up in a click.** Each employee gets its own workspace and browser on your VMs. No servers to wire by hand.
- **The Codex interface.** Every step, diff, file and live browser, the way Codex and Claude Code show them. Take over any browser, stop, redirect, approve.
- **Scale.** Run 100 always-on employees from one app.

## Thesis

The businesses that win will be the ones that can run many agents at once, doing valuable work well and without supervision. Get that right and your workforce scales with compute, not headcount.

## Layout

| Folder | |
|---|---|
| [`app/`](app) | Mac app |
| [`gateway/`](gateway) | Server the app talks to, one per workspace |
| [`harness/`](harness) | Runs any agent: Claude Code and Codex today, OpenClaw and Hermes next |
| [`provision/`](provision) | Sets up VMs, workspaces and agents |
| [`docs/`](docs) | [Messaging](docs/messaging.md), [brand](docs/brand.md) |
