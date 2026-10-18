<p align="center"><img src="docs/assets/logo.png" alt="Overtime" width="300"></p>

<h1 align="center">The command center for always-on AI agents doing real work</h1>

<h3 align="center">An open-source OpenAI dots and Grok Bot alternative. See every agent and every action, Codex-style. Scale from one agent to 100 with ready-made templates.</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Codex--style_app-0D0D0D?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHJlY3QgeD0iMiIgeT0iNCIgd2lkdGg9IjIwIiBoZWlnaHQ9IjE2IiByeD0iMyIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIi8%2BPHBhdGggZD0iTTYgMTBsMyAyLTMgMk0xMSAxNWg1IiBmaWxsPSJub25lIiBzdHJva2U9IndoaXRlIiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIvPjwvc3ZnPg%3D%3D" alt="Codex-style app">
  <img src="https://img.shields.io/badge/Ready--made_VM_templates-E3242B?style=for-the-badge&logo=linuxserver&logoColor=white" alt="Ready-made VM templates">
  <img src="https://img.shields.io/badge/Mac_%2B_iOS-2741D6?style=for-the-badge&logo=apple&logoColor=white" alt="Mac and iOS">
  <img src="https://img.shields.io/badge/Open_source-0D0D0D?style=for-the-badge&logo=github&logoColor=white" alt="Open source">
</p>

<p align="center"><img src="docs/assets/hero.jpg" alt="A punch clock feeding a grid of hundreds of desks, each with an AI employee at its own computer" width="900"></p>

Overtime is an open-source command center for always-on AI agents: Claude Code and Codex agents that each get their own computer and browser, on servers you own, set up from ready-made VM templates, with your own Claude and Codex logins. You manage them from a native app on Mac and iPhone that shows their work the way Codex does, and you can step in at any time. Your logins, files and data never leave your machines.

Also an alternative to Paperclip, OpenClaw and Hermes Agent.

<p align="center">
  <a href="docs/deploy.md#hetzner"><img src="https://img.shields.io/badge/Deploy_on-Hetzner-D50C2D?style=flat-square&logo=hetzner&logoColor=white" alt="Deploy on Hetzner"></a>
  <a href="docs/deploy.md#digitalocean"><img src="https://img.shields.io/badge/Deploy_on-DigitalOcean-0080FF?style=flat-square&logo=digitalocean&logoColor=white" alt="Deploy on DigitalOcean"></a>
  <a href="docs/deploy.md#google-cloud"><img src="https://img.shields.io/badge/Deploy_on-Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="Deploy on Google Cloud"></a>
</p>

## Problem

- **Chat is the wrong interface.** Every new agent app is a chat with bots you talk to like contacts. You get messages, not the steps, diffs and screens behind the work.
- **They're built for one assistant, not a team.** OpenAI's dots gives you one agent. The open-source clones give you a handful of bots.
- **Agents get lost.** Run many and they talk over each other, with no way to see who is doing what.
- **Hosting is hard.** Running dozens of agents in the cloud, with their own computers, logins and browsers, is all on you.

## Thesis

The solopreneurs and businesses that win will be the ones that figure out how to run tens to hundreds of always-on AI agents: doing productive work, coordinating with each other, and knowing when to hand off to a human.

## See it work

<p align="center"><img src="docs/assets/app.jpg" alt="Overtime: the Growth agent has set up an ads campaign in its own browser, shown live in the app, and waits for approval" width="900"></p>

Growth set up a $40/day campaign in Ads Manager on its own browser. You watch it live, then approve or take over.

<p align="center"><img src="docs/assets/app-engineering.jpg" alt="Overtime: the Engineer agent fixed a checkout bug, ran the tests, and is clicking Pay on localhost:3000 in its own browser" width="900"></p>

Engineer fixed the checkout button, ran the tests, and checked it on `localhost:3000` in its own browser, all on the server.

## What you get

- **A work view, not a chat.** Every agent's steps, diffs, files and live screen side by side, like Codex. Take over any screen, stop, redirect, approve.
- **Built for fleets.** Run 100 always-on agents, grouped into workspaces. Each workspace is isolated on your own servers, with its own files, logins and browsers. Ready-made VM templates get a new workspace running in minutes.
- **They work together.** Agents hand work to each other, share a workspace's files, and only ping you when they're stuck or need a decision.
- **Native and fast.** A Swift app for Mac and iOS. Not a web dashboard, not Electron.
- **Everything else you'd expect.** A computer and browser for every agent, memory, schedules, approvals, integrations and Telegram. Runs on Claude Code and Codex, with OpenClaw and Hermes coming.

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

| | Overtime | OpenAI dots | Grok Bot | Rakazo | OpenMausBot | OpenDots |
|---|---|---|---|---|---|---|
| Main interface | Work view: steps, diffs, live screens | Chat | Chat | Chat | Chat | Chat and docs |
| Agents | Fleets of 100 | One per plan | A few bots | A team of bots | A team of bots | A few dots |
| Runs on | Your servers | OpenAI's cloud | xAI's cloud | Your machine or a sandbox provider | Your machine, plus a cloud computer | Your servers, plus CopilotKit's backend |
| Isolated workspaces | Yes, one per team | No | Not documented | Shared or private computers | Not documented | Spaces |
| Apps | Native Swift, Mac and iOS | ChatGPT apps | Mac and iOS | Electron, iOS, Android | Desktop | Web and mobile |
| Agent | Claude Code, Codex | GPT-6 Astra | Grok | Any model | Claude, Codex | Any model |
| Open source | Yes | No | No | Apache-2.0 | Apache-2.0 | MIT |

Checked October 2026. Links: [dots](https://openai.com/index/introducing-dots/), [Grok Bot](https://docs.x.ai/grok-bot/faq), [Rakazo](https://github.com/elie222/rakazo), [OpenMausBot](https://github.com/milind-soni/OpenMausBot), [OpenDots](https://github.com/CopilotKit/OpenDots).

## Layout

| Folder | |
|---|---|
| [`app/`](app) | Mac app |
| [`gateway/`](gateway) | Server the app talks to, one per workspace |
| [`harness/`](harness) | Runs agents on Claude Code and Codex |
| [`provision/`](provision) | Sets up VMs, workspaces and agents |
| [`docs/`](docs) | [Messaging](docs/messaging.md), [brand](docs/brand.md) |

## License

[Apache-2.0](LICENSE). Copyright 2026 Dim Pan.
