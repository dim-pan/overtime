<p align="center"><img src="docs/assets/logo.png" alt="Overtime" width="300"></p>

<h1 align="center">Run and manage 100 always-on agents in the cloud</h1>

<h3 align="center">Each with its own computer and browser</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Codex_app_clone-0D0D0D?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHJlY3QgeD0iMiIgeT0iNCIgd2lkdGg9IjIwIiBoZWlnaHQ9IjE2IiByeD0iMyIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIi8%2BPHBhdGggZD0iTTYgMTBsMyAyLTMgMk0xMSAxNWg1IiBmaWxsPSJub25lIiBzdHJva2U9IndoaXRlIiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIvPjwvc3ZnPg%3D%3D" alt="Codex app clone">
  <img src="https://img.shields.io/badge/Computer_%2B_browser_use-E3242B?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Computer and browser use">
  <img src="https://img.shields.io/badge/Mac_%2B_iOS-2741D6?style=for-the-badge&logo=apple&logoColor=white" alt="Mac and iOS">
  <img src="https://img.shields.io/badge/Open_source-0D0D0D?style=for-the-badge&logo=github&logoColor=white" alt="Open source">
</p>

<p align="center"><img src="docs/assets/hero.jpg" alt="A punch clock feeding a grid of hundreds of desks, each with an AI employee at its own computer" width="900"></p>

<p align="center">The Codex app with computer and browser use is so powerful. You can do so much productive work while you're at your computer.</p>

<p align="center"><b>How can we make this SCALE, and manage always-on assistants that do REAL work for us?</b></p>

## Problem

- **Interfaces suck.** Telegram and chat threads give you a summary, not the steps, diffs and screens behind the work.
- **Computer use doesn't scale.** It only runs on your laptop, one agent at a time.
- **Agents get lost.** Run several from one thread and they talk over each other, with no way to see who is doing what.
- **Hosting is hard.** Running agents at scale in the cloud means wiring up servers, logins and browsers, and keeping them alive yourself.

## See it work

<p align="center"><img src="docs/assets/app.jpg" alt="Overtime: the Growth agent has set up an ads campaign in its own browser, shown live in the app, and waits for approval" width="900"></p>

Growth set up a $40/day campaign in Ads Manager on its own browser. You watch it live, then approve or take over.

<p align="center"><img src="docs/assets/app-engineering.jpg" alt="Overtime: the Engineer agent fixed a checkout bug, ran the tests, and is clicking Pay on localhost:3000 in its own browser" width="900"></p>

Engineer fixed the checkout button, ran the tests, and checked it on `localhost:3000` in its own browser, all on the server.

## What you get

- **Always-on employees.** An OpenClaw-style harness (memory, schedules, heartbeats, Telegram) on top of Claude Code and Codex, with OpenClaw and Hermes support coming. They keep working when your laptop is closed.
- **Set up in a click.** Each employee gets its own workspace and browser on your VMs. No servers to wire by hand.
- **The Codex interface.** Every step, diff, file and live browser, the way Codex and Claude Code show them. Take over any browser, stop, redirect, approve.
- **Real work.** Browser use plus integrations for the tools a business runs on: ads, payments, email, CRM, socials, analytics.
- **Scale.** Run 100 always-on employees from one app.

## From assistant to employee

Personal assistants answer you. Employees do a job: they own an outcome, work on a schedule, show their work and answer to you. Overtime makes that leap: agents you can manage, watch and measure, doing jobs that make money.

| Job | What they do | What you see |
|---|---|---|
| Growth | Run ads, post content, track what works | Spend, campaigns, posts |
| Sales | Find leads, follow up, book demos, update the CRM | Meetings booked |
| Engineering | Ship fixes and features, test them in a real browser | Diffs, tests, live checks |
| Support | Answer tickets, draft refunds for your approval | Tickets closed |
| Finance | Send invoices, chase payments, reconcile the books | Cash collected |
| Store ops | Update listings, prices and orders | Orders shipped |

## Compared

| | Overtime | Codex | Claude Code | OpenClaw | Hermes | Paperclip |
|---|---|---|---|---|---|---|
| Keeps working when your laptop closes | Yes | Cloud tasks | Cloud sessions | Yes | Yes | Yes |
| Browser use in the cloud | Every agent | Local only | Local only | Yes | Yes | Via Browser Use Cloud |
| Watch the browser live, take over | Yes | Local only | Local only | Yes | Not documented | Yes |
| Claude Code-style app: steps, diffs, live screens | Yes | Yes | Yes | Chat | Chat, terminal | Web task pages |
| Many agents in parallel | 100 | Parallel tasks | Parallel sessions | Yes | Subagents | Yes |
| Runs other agents | Claude Code, Codex (OpenClaw, Hermes coming) | No | No | Coding agents via ACP | No | Yes |
| Native Mac and iOS apps | Yes | Mac, iOS controls the Mac | Mac, iOS via Claude app | Companion apps | Desktop, third-party iOS | Web only |
| Open source, your own servers | Yes | CLI only | No | Yes | Yes | Yes |

Checked October 2026.

## Thesis

The solopreneurs and businesses that win will be the ones that figure out how to run tens to hundreds of always-on AI agents: doing productive work, coordinating with each other, and knowing when to hand off to a human.

## Layout

| Folder | |
|---|---|
| [`app/`](app) | Mac app |
| [`gateway/`](gateway) | Server the app talks to, one per workspace |
| [`harness/`](harness) | Runs agents on Claude Code and Codex |
| [`provision/`](provision) | Sets up VMs, workspaces and agents |
| [`docs/`](docs) | [Messaging](docs/messaging.md), [brand](docs/brand.md) |
