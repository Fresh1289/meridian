<p align="center">
  <img src="assets/meridian-wordmark.svg" width="360" alt="Meridian" />
</p>

<p align="center">
  <strong>🚀 The multi-agent orchestration platform for AI-native developers.</strong>
</p>

<p align="center">
  <em>Replace yourself as the communication bus between parallel coding agents.</em>
</p>

<p align="center">
  <a href="#-download"><img src="https://img.shields.io/badge/Download-v1.0.0-7c3aed?style=for-the-badge&logo=apple&logoColor=white" /></a>
  &nbsp;
  <a href="https://tally.so/r/EkLvbX"><img src="https://img.shields.io/badge/🔔_Join_Waitlist-→-f59e0b?style=for-the-badge" /></a>
  &nbsp;
  <a href="#-features"><img src="https://img.shields.io/badge/Features-→-4f46e5?style=for-the-badge" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-0a0a0f?style=flat-square&labelColor=1a1a2e&color=7c3aed" />
  <img src="https://img.shields.io/badge/platform-macOS_(Apple_Silicon)-0a0a0f?style=flat-square&labelColor=1a1a2e&color=4f46e5" />
  <img src="https://img.shields.io/badge/commits-476+-0a0a0f?style=flat-square&labelColor=1a1a2e&color=059669" />
  <img src="https://img.shields.io/badge/agents_tested-20-0a0a0f?style=flat-square&labelColor=1a1a2e&color=f59e0b" />
  <img src="https://img.shields.io/badge/Electron-React_19-0a0a0f?style=flat-square&labelColor=1a1a2e&color=0ea5e9" />
</p>

<br />

<p align="center">
  <img src="assets/screenshot-chat.png" width="100%" alt="Meridian — 10 agents spawned from a single prompt" />
</p>

<p align="center">
  <sub>☝️ One prompt. 10 agents deployed. Full hierarchical team with leads, builders, QA, designer, and scribe.</sub>
</p>

<br />

---

<br />

## 😤 The Problem

You run Claude Code in 3-10 terminal tabs in parallel. Each session is powerful on its own.

> **But you are the bottleneck.**

You read output from one agent. Copy context to another. Decide who works on what. Resolve conflicts. Relay messages. Manage state. The agents are fast. **You are the slowest link in the chain.**

As agent teams scale, this gets worse. More tabs, more context-switching, more dropped balls. The human communication bus doesn't scale.

Some tools claim to solve this with CLI wrappers, YAML configs, and buzzword architectures. They'll tell you they have "Q-learning routers" and "Byzantine consensus" and "neural self-optimization." But when you actually try to use them, nothing happens — because the agents are just state objects in memory, not real processes doing real work.

**Meridian takes a different approach.** Every agent is a real subprocess. Every message is actually delivered. Every node on the topology is a live process you can watch, talk to, pause, or kill. No theater. No simulated orchestration. Just agents that actually run.

<br />

---

<br />

## 💡 What Meridian Does

Meridian is a **native desktop app** that removes you from the middle.

You talk to **one agent** — the **Manager**. Manager handles everything else: analyzing your request, deploying the right team, routing work between agents, and reporting back when it's done.

You see everything happening in real time on a **visual topology**. One chat. Full visibility. No context-switching. No YAML. No config files. No learning a CLI.

<br />

| | Without Meridian | With Meridian |
|:---|:---|:---|
| 🖥️ | 6 terminal tabs open | 1 app window |
| 📋 | Copy-pasting between agents | Automatic routing |
| 🧠 | You decide who does what | Manager decides |
| 🔀 | You resolve merge conflicts | Manager handles git |
| 💭 | Context lost across sessions | Scribe remembers everything |
| 🔇 | Agents don't know about each other | Full inter-agent communication |
| 📄 | Reading docs to configure YAML | Describe your project in English |

<br />

---

<br />

## ✨ Features

<br />

### 🗺️ Visual Agent Topology

<p align="center">
  <img src="assets/screenshot-topology.png" width="100%" alt="Agent Topology" />
</p>

Real-time org chart of your agent team rendered on **Canvas 2D**. Each node shows the agent's role, status, and model. Connection lines animate when agents communicate — idle dash crawl, active packet animation. Top-down layout with Manager at the center, leads below, sub-agents beneath.

This isn't a text log you scroll through. It's a **live, visual map** of your entire agent team — what they're doing, who they're talking to, and whether they're healthy. **No other multi-agent tool has this.** Not as a CLI flag. Not as a dashboard. Not as an afterthought. It's the core of the experience.

<br />

### ⚡ Real Agents, Not State Objects

Every agent in Meridian is a **real CLI subprocess** — a full Claude Code process with its own working directory, config, and lifecycle.

| | Other Tools | Meridian |
|:---|:---|:---|
| 🤖 Agent type | In-memory state object | Real `child_process` subprocess |
| 📝 "Writes code" | Updates a JSON file | Actually writes to disk |
| 🧪 "Runs tests" | Returns simulated result | Tests actually execute |
| 💀 Crash recovery | State reset | Exponential backoff + auto-restart |
| 📊 Proof | Trust the marketing | Check Activity Monitor |

Some orchestrators manage agents as in-memory objects — they track state, update JSON files, and claim "100+ agents" while nothing actually executes. Meridian spawns real processes, monitors them with health checks, and restarts them with exponential backoff if they crash.

<br />

### 💬 One Chat, Full Control

<p align="center">
  <img src="assets/screenshot-dashboard.png" width="100%" alt="Manager Chat" />
</p>

Talk to Manager in natural language. Manager dispatches to the right agents, collects results, and reports back. **GitHub Copilot-style input** with model selector, file attachments, and full markdown rendering.

Every relay between agents is visible. You see exactly what Manager told the Builder, what the Builder responded, and what QA found. No black box. No "trust the swarm." 🔍

<br />

### 🎯 Dynamic Team Composition

There is no static agent list. No YAML files to configure. No "agent definitions" to write. **Manager is the only default agent.** When you describe your project, Manager assembles the right team:

| Project Type | Team Deployed |
|:---|:---|
| 🔧 Backend-heavy | Manager + 3 Builders + QA + Scribe |
| 🎨 Frontend/design-heavy | Manager + Builder + 2 Designers + QA + Scribe |
| 🩹 Quick fix | Manager + Builder |
| 🏗️ Full-stack | Manager + 2 Builders + Designer + QA + Scribe |

Agents appear on the topology as they're deployed. Manager can add, remove, or reassign agents mid-project based on what's needed. **You don't pre-configure your team — you describe your goal and the team materializes.**

<br />

### 🧠 Shared Structured Memory (Scribe)

Scribe runs silently in the background, reading **all** communication between agents. It logs everything to the project filesystem — decisions, code changes, conversations, corrections. **Human-readable markdown**, not opaque vector databases.

When Manager forgets context from 50 messages ago, Scribe surfaces it instantly. It's your project's institutional knowledge — the thing that makes agent teams actually work across long sessions.

> 📂 Plain text on disk. Read it yourself. Search it with grep. Sync it to Obsidian.
> No proprietary binary format. No "memory engine" you can't inspect.

<br />

### 🔀 Mix Models Per Agent

Meridian currently runs on **Claude Code** — the most capable coding agent available. You can assign different Claude models to different agents:

- 🟣 **Opus** for Manager (planning + routing)
- 🔵 **Sonnet** for Builders (fast code generation)
- 🟡 **Haiku** for Scribe (lightweight logging)

The right model for each job. Manager gets the big brain, builders get the fast one, utility agents get the cheap one. You control this per-agent from the settings panel.

> 🔮 **Coming soon:** Multi-provider support — run Codex, Gemini CLI, or any CLI agent alongside Claude. The architecture is designed for it.

<br />

### 🎛️ Human-in-the-Loop

You see everything. Every relay between agents, every decision Manager makes, every correction loop.

Intervene anytime:
- 🔀 Redirect work to a different agent
- ✏️ Adjust an agent's behavior mid-task
- ⏸️ Pause or kill an agent
- 🔄 Override Manager's routing

Manager rewrites agent configs on the fly based on your feedback. **The agents adapt to you**, not the other way around.

> 🛑 Autonomous agent swarms sound cool in demos. In practice, you want a kill switch.
> Meridian gives you one — plus full visibility into what's happening before you need to use it.

<br />

### 📡 Messages That Actually Arrive

Meridian's communication layer is built on **53 typed IPC channels** between the Electron main process and the renderer.

```
Sub-agent → Lead → Manager → Lead → Sub-agent
     ✅        ✅       ✅       ✅       ✅
```

**14 end-to-end tests.** Including a **20-agent stress test** with full hierarchical routing. Messages don't get lost. Agents don't talk past each other. The communication bus works because it was **tested relentlessly**, not theorized about.

<br />

### 🖥️ Built-in Terminal

Run your app without leaving Meridian. Full shell access, embedded in the app. See your agents build it, then run it — same window. 🏃‍♂️

<br />

### 🎨 Industrial-Luxury Interface

<p align="center">
  <img src="assets/screenshot-settings.png" width="100%" alt="Settings and Configuration" />
</p>

**Mission control meets Linear.** Near-black base, agent-specific accent colors, glassmorphic panels, precise typography. Information-dense but clean. Every pixel considered.

Built with the same attention to craft as the tools you already use — GitHub, Linear, Vercel, Raycast. Not a CLI with a `--pretty` flag. Not a web dashboard bolted on after the fact. **A native desktop app designed from day one to be the interface.**

<br />

---

<br />

## 🚀 How It Works

<br />

### Step 1 — Sign in

<p align="center">
  <img src="assets/screenshot-login.png" width="720" alt="Sign in" />
</p>

GitHub OAuth or email. One click. No config files. No environment variables. No `npx init`. ✨

<br />

### Step 2 — Connect your AI provider

<p align="center">
  <img src="assets/screenshot-onboarding-cli.png" width="720" alt="Connect Claude" />
</p>

Meridian detects your Claude CLI automatically. Optionally add an API key for pay-per-token billing. Two options, one screen, done. ✅

<br />

### Step 3 — Describe your project

<p align="center">
  <img src="assets/screenshot-onboarding-project.png" width="720" alt="Create Project" />
</p>

Name it, describe what you're building, pick a directory. Meridian scaffolds the workspace with `.meridian/`, `.agents/`, and a `CLAUDE.md`. No YAML agent definitions to write. No topology configs to learn. **Just tell it what you're building.** 💬

<br />

### Step 4 — Manager assembles the team

<p align="center">
  <img src="assets/screenshot-chat.png" width="100%" alt="10 agents spawned" />
</p>

Manager reads your description and deploys the right agents — Frontend Lead, Backend Lead, QA, Designer, Scribe, and sub-agents under each lead. **Each one is a real CLI process** with its own working directory. You watch the org chart populate in real time. 🎬

<br />

### Step 5 — Watch, iterate, ship

<p align="center">
  <img src="assets/screenshot-topology.png" width="100%" alt="Full topology" />
</p>

Agents code, review, and test. Manager orchestrates. Connection lines animate as messages flow. Ask for changes — Manager dispatches, agents fix, Manager reports. **Everything is committed to GitHub automatically.** 🚢

<br />

---

<br />

## 🏗️ Architecture

```
┌──────────────────────────────────────────────────────────┐
│                      Meridian App                         │
│                                                          │
│  ┌──────────────┐         ┌────────────────────────────┐ │
│  │  🔧 Electron  │         │  🎨 React 19 + Canvas 2D   │ │
│  │  Main Process │   IPC   │                            │ │
│  │               │◄───────►│  Topology · Chat ·         │ │
│  │  Agent        │   53    │  Terminal · Settings ·     │ │
│  │  Spawner      │  chan   │  Vault · Status Bar        │ │
│  └──────┬───────┘         └────────────────────────────┘ │
│         │                                                │
│  ┌──────┴──────────────────────────────────────────────┐ │
│  │              🤖 Agent Processes                      │ │
│  │                                                      │ │
│  │  Manager · Builder · Designer · QA · Scribe          │ │
│  │  (Claude Code — more providers coming soon)          │ │
│  └──────────────────────────────────────────────────────┘ │
└──────────────────────────────────────────────────────────┘
```

| Component | Technology | Why |
|:---|:---|:---|
| 🖥️ Runtime | **Electron** | Native performance, direct `child_process` spawning |
| ⚛️ UI | **React 19 + TypeScript + Tailwind 4** | Modern stack, domain-specific Zustand stores |
| 🗺️ Topology | **Canvas 2D** | Lightweight rendering — not WebGL, small bundle |
| 🔌 Bridge | **53 IPC channels** | Typed, validated, bidirectional |
| 🤖 Agents | **Real CLI subprocesses** | Isolated dirs, health monitoring, auto-restart |

> **No in-memory agent simulation.** No JSON file state management pretending to be orchestration. Real processes, real IPC, real results.

<br />

---

<br />

## 📊 How Meridian Compares

|  | Meridian | Claude Code Teams | Claude Squad | Opcode | Agentrooms |
|:---|:---:|:---:|:---:|:---:|:---:|
| 🤖 Multi-agent orchestration | ✅ | 🧪 Experimental | ❌ | ❌ | ⚠️ Limited |
| 🗺️ Visual topology | ✅ | ❌ | ❌ | ❌ | ❌ |
| 🎯 Dynamic team composition | ✅ | ❌ | ❌ | ❌ | ❌ |
| ⚡ Real agent subprocesses | ✅ | ✅ | ✅ | ✅ | ⚠️ Partial |
| 🧠 Shared memory (Scribe) | ✅ | ❌ | ❌ | ❌ | ❌ |
| 🔀 Per-agent model selection | ✅ | ❌ | ❌ | ❌ | ❌ |
| 🖥️ Native desktop app | ✅ | CLI | TUI | Tauri | Web |
| 🎛️ Human-in-the-loop | ✅ | ⚠️ Limited | ✅ | ✅ | ⚠️ Limited |
| 🧪 Tested at 20 agents | ✅ | ❌ | ❌ | ❌ | ❌ |

<br />

---

<br />

## 🗺️ Roadmap

### ✅ Shipped (v1.0.0)
- [x] 🗺️ Visual agent topology with real-time status
- [x] 🎯 Dynamic team composition via Manager
- [x] 🧠 Scribe agent for shared structured memory
- [x] 🔀 Per-agent model selection (Opus, Sonnet, Haiku per agent)
- [x] ✨ 7-phase animated onboarding flow
- [x] 🔐 Supabase auth (GitHub OAuth + email)
- [x] 💬 Chat persistence and auto-scroll
- [x] 🖥️ Embedded terminal
- [x] ⚙️ Agent config editor and customization
- [x] 📦 Auto-updater
- [x] 🔀 Hierarchical team routing (sub-agents → leads → Manager)
- [x] 🩺 Self-healing agents (retry, backoff, model fallback)
- [x] 🔄 Context rotation (auto session dump at 85% usage)
- [x] 🧪 14 end-to-end tests passed, including 20-agent stress test

### 🔜 Coming Soon
- [ ] 🔓 Multi-provider support (Codex, Gemini CLI, any CLI agent alongside Claude)
- [ ] 🌐 Multi-machine orchestration — cluster your Mac Minis, distribute agents across machines (think [exo](https://github.com/exo-explore/exo) but for coding agents)
- [ ] 📚 Obsidian vault integration for project memory
- [ ] 🔀 Git integration UI (commit, push, pull from within app)
- [ ] 🪟 Windows + Linux support

### 🔮 Future
- [ ] 📦 Community workflow templates (shareable agent team configs)
- [ ] 🏪 Agent marketplace
- [ ] 🎙️ Voice control
- [ ] 👥 Team collaboration (multiple humans, shared project)

<br />

---

<br />

## 💰 Pricing

### 🆓 Free — forever
Everything on a single machine. **No limits. No trials. No feature gates.**
Full orchestration, all agents, all models, all features.

### 💎 Pro — coming later
Multi-machine orchestration. Cluster your MacBook, Mac Mini, and build server into one fleet — distribute agents across hardware like exo does for inference, but for coding. Cloud sync. Team features.

> *We believe the single-machine experience should be completely free. You only pay when you need to scale beyond one computer.*

<br />

---

<br />

## 🛠️ Built With

<p align="center">
  <img src="https://img.shields.io/badge/Electron-35-47848F?style=for-the-badge&logo=electron&logoColor=white" />
  <img src="https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/Canvas_2D-native-F7DF1E?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Supabase-auth-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" />
</p>

<br />

---

<br />

## 📥 Download

<p align="center">
  <strong>macOS (Apple Silicon)</strong>
</p>

<p align="center">
  <strong>🚧 Coming soon</strong> — v1.0.0 release in progress.
</p>

<p align="center">
  <a href="https://tally.so/r/EkLvbX"><img src="https://img.shields.io/badge/🔔_Join_the_Waitlist-Get_notified_on_launch-f59e0b?style=for-the-badge" /></a>
</p>

<p align="center">
  ⭐ <strong>Star this repo</strong> to follow development and get release notifications.
</p>

> **Note:** Meridian is currently unsigned (Apple Developer Program enrollment pending).
> On first launch: **Right-click the app → Open → Click "Open"** in the dialog.
> Or run: `xattr -cr /Applications/Meridian.app`

<br />

---

<br />

## ❓ FAQ

<details>
<summary><strong>What AI providers does Meridian support?</strong></summary>
<br />

Currently, Meridian runs on **Claude Code** (Anthropic). You can assign different Claude models (Opus, Sonnet, Haiku) to different agents. Multi-provider support (Codex, Gemini CLI, etc.) is on the roadmap — the architecture is built to support any CLI-based agent.

</details>

<details>
<summary><strong>Do I need a Claude API key?</strong></summary>
<br />

No. Meridian works with the **Claude CLI** using your Max plan credits — no API key required. If you prefer pay-per-token billing, you can optionally add an API key during onboarding.

</details>

<details>
<summary><strong>How many agents can I run at once?</strong></summary>
<br />

Meridian has been stress-tested with **20 concurrent agents** in a full hierarchical setup (leads, sub-agents, scribe). In practice, most projects use 5-12 agents. Each agent is a real CLI process, so your limit is your machine's resources and API rate limits.

</details>

<details>
<summary><strong>Is this open source?</strong></summary>
<br />

The source code is currently private. This repo is a showcase of what Meridian is and does. We're evaluating open-source options for post-1.0.

</details>

<details>
<summary><strong>What operating systems are supported?</strong></summary>
<br />

**macOS (Apple Silicon)** today. Windows and Linux support is on the roadmap.

</details>

<details>
<summary><strong>How is this different from just running multiple Claude Code sessions?</strong></summary>
<br />

When you run multiple Claude Code sessions yourself, **you** are the communication bus — reading output from one, pasting context into another, deciding who does what. Meridian replaces you in that role. Manager handles all inter-agent routing, Scribe maintains shared memory, and the topology gives you real-time visibility into what every agent is doing. You go from being the bottleneck to being the overseer.

</details>

<details>
<summary><strong>How much does it cost to run?</strong></summary>
<br />

Meridian itself is **free**. Your cost is the AI usage — same as running Claude Code directly. A typical 10-agent session building a medium-sized feature costs roughly what 10 individual Claude Code sessions would cost. The difference is Meridian makes those 10 sessions work together instead of in isolation.

</details>

<details>
<summary><strong>Can I customize how agents behave?</strong></summary>
<br />

Yes. Each agent has its own config that Manager can rewrite on the fly. Tell Manager "I don't like how the designer writes CSS" and it will update the designer's system prompt immediately. You can also edit agent configs directly from the settings panel.

</details>

<details>
<summary><strong>What happens when an agent crashes?</strong></summary>
<br />

Meridian has **self-healing built in**. If an agent crashes, it automatically restarts with exponential backoff. If it keeps failing, Manager is notified and can reassign the work. Health monitoring runs continuously — you'll see the agent's status change on the topology in real time.

</details>

<details>
<summary><strong>Why Electron and not a web app?</strong></summary>
<br />

Meridian needs to spawn and manage CLI subprocesses (Claude Code, etc.) directly on your machine. A web app can't do that — it would need a local server or daemon, adding complexity. Electron gives us native process spawning, direct filesystem access, and a polished desktop experience in one package.

</details>

<br />

---

<br />

<p align="center">
  <img src="assets/meridian-icon.svg" width="48" height="48" alt="" />
</p>

<p align="center">
  <code>476+ commits · 119 source files · 53 IPC channels · 56 React components</code>
  <br />
  <code>5 domain stores · 14 end-to-end tests · 20-agent stress test cleared</code>
  <br /><br />
  <strong>⚡ Stop being the bottleneck.</strong>
  <br /><br />
  <a href="https://github.com/Fresh1289">
    <img src="https://img.shields.io/badge/Built_by-Matthew_Huang-7c3aed?style=flat-square&labelColor=1a1a2e" />
  </a>
</p>
