<p align="center">
  <img src="assets/icon-1024.png" width="128" height="128" alt="Meridian" />
</p>

<h1 align="center">Meridian</h1>

<p align="center">
  <strong>The multi-agent orchestration platform for AI-native developers.</strong>
</p>

<p align="center">
  Replace yourself as the communication bus between parallel coding agents.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-0a0a0f?style=flat-square&labelColor=1a1a2e&color=7c3aed" />
  <img src="https://img.shields.io/badge/platform-macOS-0a0a0f?style=flat-square&labelColor=1a1a2e&color=4f46e5" />
  <img src="https://img.shields.io/badge/commits-476+-0a0a0f?style=flat-square&labelColor=1a1a2e&color=059669" />
  <img src="https://img.shields.io/badge/stack-Electron%20%2B%20React%2019-0a0a0f?style=flat-square&labelColor=1a1a2e&color=0ea5e9" />
</p>

<br />

<p align="center">
  <img src="assets/screenshot-chat.png" width="100%" alt="Meridian — 10 agents spawned from a single prompt" />
</p>

<br />

---

## The Problem

You run Claude Code, Codex, Gemini CLI — maybe 3-10 agents in parallel across terminal tabs. Each one is powerful on its own.

**But you are the bottleneck.**

You read output from one agent. Copy context to another. Decide who works on what. Resolve conflicts. Relay messages. Manage state. The agents are fast. You are the slowest link in the chain.

As agent teams scale, this gets worse. More tabs, more context-switching, more dropped balls. The human communication bus doesn't scale.

---

## What Meridian Does

Meridian is a native desktop app that removes you from the middle.

You talk to **one agent** — the **Manager**. Manager handles everything else: analyzing your request, deploying the right team, routing work between agents, and reporting back when it's done.

You see everything happening in real time on a **visual topology**. One chat. Full visibility. No context-switching.

<br />

| Without Meridian | With Meridian |
|:---|:---|
| 6 terminal tabs open | 1 app window |
| Copy-pasting between agents | Automatic routing |
| You decide who does what | Manager decides |
| You resolve merge conflicts | Manager handles git |
| Context lost across sessions | Scribe remembers everything |
| Agents don't know about each other | Full inter-agent communication |

<br />

---

## Features

### Visual Agent Topology

<p align="center">
  <img src="assets/screenshot-topology.png" width="100%" alt="Agent Topology" />
</p>

Real-time org chart of your agent team rendered on Canvas 2D. Each node shows the agent's role, status, and model. Connection lines animate when agents communicate — idle dash crawl, active packet animation. Top-down layout with Manager at the center, leads below, sub-agents beneath.

**No other tool in the market has this.**

<br />

### One Chat, Full Control

<p align="center">
  <img src="assets/screenshot-dashboard.png" width="100%" alt="Manager Chat" />
</p>

Talk to Manager in natural language. Manager dispatches to the right agents, collects results, and reports back. GitHub Copilot-style input with model selector, file attachments, and markdown rendering.

Every relay between agents is visible. You're never in the dark about what's happening.

<br />

### Dynamic Team Composition

There is no static agent list. **Manager is the only default agent.** When you describe your project, Manager assembles the right team:

| Project Type | Team Deployed |
|:---|:---|
| Backend-heavy | Manager + 3 Builders + QA + Scribe |
| Frontend/design-heavy | Manager + Builder + 2 Designers + QA + Scribe |
| Quick fix | Manager + Builder |
| Full-stack | Manager + 2 Builders + Designer + QA + Scribe |

Agents appear on the topology as they're deployed. Manager can add, remove, or reassign agents mid-project based on what's needed.

<br />

### Shared Structured Memory (Scribe)

Scribe runs silently in the background, reading **all** communication between agents. It logs everything to the project filesystem — decisions, code changes, conversations, corrections.

When Manager forgets context from 50 messages ago, Scribe surfaces it instantly. It's your project's institutional knowledge — the thing that makes agent teams actually work across long sessions.

<br />

### Model-Agnostic

Not locked to one provider. Run **Claude Code**, **OpenAI Codex**, **Gemini CLI**, or any CLI-based coding agent.

Mix models across agents — Opus for Manager, Sonnet for Builders, GPT-4 for review. The right model for each job, not a one-size-fits-all lock-in.

<br />

### Human-in-the-Loop

You see everything. Every relay between agents, every decision Manager makes, every correction loop.

Intervene anytime:
- Redirect work to a different agent
- Adjust an agent's behavior mid-task ("I don't like how the designer writes CSS")
- Pause or kill an agent
- Override Manager's routing

Manager rewrites agent configs on the fly based on your feedback. The agents adapt to you, not the other way around.

<br />

### Built-in Terminal

Run your app without leaving Meridian. Full shell access, embedded in the app. See your agents build it, then run it — same window.

<br />

### Industrial-Luxury Interface

<p align="center">
  <img src="assets/screenshot-settings.png" width="100%" alt="Settings and Configuration" />
</p>

Mission control meets Linear. Near-black base, agent-specific accent colors, glassmorphic panels, precise typography. Information-dense but clean. Every pixel considered.

Built with the same attention to craft as the tools you already use — GitHub, Linear, Vercel, Raycast.

<br />

---

## How It Works

### 1. Sign in

<p align="center">
  <img src="assets/screenshot-login.png" width="720" alt="Sign in" />
</p>

GitHub OAuth or email. One click.

### 2. Connect your AI provider

<p align="center">
  <img src="assets/screenshot-onboarding-cli.png" width="720" alt="Connect Claude" />
</p>

Meridian detects your Claude CLI automatically. Optionally add an API key for pay-per-token billing.

### 3. Describe your project

<p align="center">
  <img src="assets/screenshot-onboarding-project.png" width="720" alt="Create Project" />
</p>

Name it, describe what you're building, pick a directory. Meridian scaffolds the workspace with `.meridian/`, `.agents/`, and a `CLAUDE.md`.

### 4. Manager assembles the team

<p align="center">
  <img src="assets/screenshot-chat.png" width="100%" alt="10 agents spawned" />
</p>

Manager reads your description and deploys the right agents — Frontend Lead, Backend Lead, QA, Designer, Scribe, and sub-agents under each lead. You watch the org chart populate in real time.

### 5. Watch, iterate, ship

<p align="center">
  <img src="assets/screenshot-topology.png" width="100%" alt="Full topology" />
</p>

Agents code, review, and test. Manager orchestrates. Connection lines animate as messages flow. Ask for changes — Manager dispatches, agents fix, Manager reports. Everything is committed to GitHub automatically.

<br />

---

## Architecture

```
┌──────────────────────────────────────────────────────┐
│                    Meridian App                       │
│                                                      │
│  ┌─────────────┐      ┌───────────────────────────┐  │
│  │  Electron    │      │   React 19 + Canvas 2D    │  │
│  │  Main        │      │                           │  │
│  │  Process     │ IPC  │  Topology · Chat ·        │  │
│  │             ◄──────►│  Terminal · Settings ·     │  │
│  │  Agent       │  53  │  Vault · Status Bar       │  │
│  │  Spawner     │ chan  │                           │  │
│  └──────┬──────┘      └───────────────────────────┘  │
│         │                                            │
│  ┌──────┴────────────────────────────────────────┐   │
│  │              Agent Processes                   │   │
│  │                                                │   │
│  │  Manager · Builder · Designer · QA · Scribe    │   │
│  │  (Claude Code / Codex / Gemini / Any CLI)      │   │
│  └────────────────────────────────────────────────┘   │
└──────────────────────────────────────────────────────┘
```

- **Electron** — native desktop performance, direct CLI process spawning
- **React 19 + TypeScript + Tailwind CSS 4** — modern UI with domain-specific Zustand stores
- **Canvas 2D** — lightweight topology rendering (not WebGL — small bundle, fast paint)
- **53 IPC channels** — typed bridge between renderer and main process
- **Each agent is a separate CLI process** — isolated, killable, restartable, with its own config

<br />

---

## How Meridian Compares

|  | Meridian | Claude Code Teams | Claude Squad | Opcode | Agentrooms | Ruflo |
|:---|:---:|:---:|:---:|:---:|:---:|:---:|
| Multi-agent orchestration | **Yes** | Experimental | No | No | Limited | Yes |
| Visual topology | **Yes** | No | No | No | No | No |
| Dynamic team composition | **Yes** | No | No | No | No | Manual YAML |
| Shared memory (Scribe) | **Yes** | No | No | No | No | Vector-based |
| Model-agnostic | **Yes** | No | No | Claude only | Limited | Claude only |
| Native desktop app | **Yes** | CLI | TUI | Tauri | Web | CLI |
| Human-in-the-loop | **Yes** | Limited | Yes | Yes | Limited | Minimal |

<br />

---

## Roadmap

### Shipped (v1.0.0)
- [x] Visual agent topology with real-time status
- [x] Dynamic team composition via Manager
- [x] Scribe agent for shared structured memory
- [x] Multi-model support (Claude, Codex, any CLI agent)
- [x] 7-phase animated onboarding flow
- [x] Supabase auth (GitHub OAuth + email)
- [x] Chat persistence and auto-scroll
- [x] Embedded terminal
- [x] Agent config editor and customization
- [x] Auto-updater
- [x] Hierarchical team routing (sub-agents report to leads)
- [x] Self-healing agents (retry, backoff, model fallback)
- [x] Context rotation (auto session dump at 85% usage)

### Coming Soon
- [ ] Multi-computer orchestration (run agents across multiple machines)
- [ ] Obsidian vault integration for project memory
- [ ] Git integration UI (commit, push, pull from within app)
- [ ] Windows + Linux support

### Future
- [ ] Community workflow templates (shareable agent team configs)
- [ ] Agent marketplace
- [ ] Voice control
- [ ] Team collaboration (multiple humans, shared project)

<br />

---

## Pricing

### Free — forever
Everything on a single machine. No limits. No trials. No feature gates.
Full orchestration, all agents, all models, all features.

### Pro — coming later
Multi-computer orchestration. Run agents across your laptop and build server simultaneously.
Cloud sync. Team features.

*We believe the single-machine experience should be completely free. You only pay when you need to scale beyond one computer.*

<br />

---

## Built With

<p>
  <img src="https://img.shields.io/badge/Electron-35-47848F?style=flat-square&logo=electron&logoColor=white" />
  <img src="https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-5-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind%20CSS-4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/Canvas%202D-native-F7DF1E?style=flat-square" />
  <img src="https://img.shields.io/badge/Supabase-auth-3FCF8E?style=flat-square&logo=supabase&logoColor=white" />
</p>

<br />

---

## Download

### macOS (Apple Silicon)

<!-- Link to GitHub Release once DMG is uploaded -->
**Coming soon** — v1.0.0 release in progress.

> Meridian is currently unsigned (Apple Developer Program enrollment pending).
> On first launch: **Right-click the app > Open > Click "Open"** in the dialog.
> Or run: `xattr -cr /Applications/Meridian.app`

<br />

---

<p align="center">
  <code>476+ commits · 119 source files · 53 IPC channels · 56 React components</code>
  <br />
  <code>5 domain stores · 14 live tests passed · 20-agent stress test cleared</code>
  <br /><br />
  <strong>Stop being the bottleneck.</strong>
  <br /><br />
  <sub>Created by <a href="https://github.com/Fresh1289">Matthew Huang</a></sub>
</p>
