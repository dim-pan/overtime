<p align="center"><img src="docs/assets/logo.png" alt="Overtime" width="300"></p>

<h1 align="center">Run 100 AI agents in the cloud, 24/7.</h1>

<p align="center">Claude Code, Codex, OpenClaw, Hermes. Each with its own computer. Open source.</p>

<p align="center"><img src="docs/assets/hero.jpg" alt="A punch clock feeding a grid of hundreds of desks, each with an AI worker at its own computer" width="900"></p>

> Private preview. The code moves here once it is ready.

## Problem

- **Chat apps are the wrong cockpit.** Steering an OpenClaw-style agent through real work over Telegram is painful. Steering ten is impossible.
- **The best agent apps are stuck on your laptop.** Claude Code and Codex are great, and computer use is remarkable, but they run locally. Remote control is clunky, and computer use does not scale to many agents working at once.

## Solution

Overtime moves the agents to the cloud and keeps the app.

- **Always on, in the cloud.** Claude Code and Codex agents today, OpenClaw and Hermes next, on your own VMs around the clock. Nothing runs on your laptop.
- **A computer each.** Every agent gets its own desktop and browser, so computer use runs in parallel, not one at a time.
- **An app built for many.** Chat, files, diffs and every agent's live screen in one native Mac app. Take over any screen in a click.
- **You approve what matters.** Sending, posting and buying wait for your OK. The rest just gets done.

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
