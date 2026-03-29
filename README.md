<p align="center">
  <img src="assets/meridian-banner.png" width="600" alt="Meridian" />
</p>

<p align="center">
  <strong>🚀 The multi-agent orchestration platform for AI-native developers.</strong>
</p>

<p align="center">
  <em>Replace yourself as the communication bus between parallel coding agents.</em>
</p>

<p align="center">
  <a href="#-download"><img src="https://img.shields.io/badge/Download-v1.0.3-7c3aed?style=for-the-badge&logo=apple&logoColor=white" /></a>
  &nbsp;
  <a href="https://discord.gg/nvkEWVu5Wx"><img src="https://img.shields.io/badge/Discord-Join-5865F2?style=for-the-badge&logo=discord&logoColor=white" /></a>
  &nbsp;
  <a href="#-features"><img src="https://img.shields.io/badge/Features-→-4f46e5?style=for-the-badge" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.3-0a0a0f?style=flat-square&labelColor=1a1a2e&color=7c3aed" />
  <img src="https://img.shields.io/badge/platform-macOS_(Apple_Silicon)-0a0a0f?style=flat-square&labelColor=1a1a2e&color=4f46e5" />
  <img src="https://img.shields.io/badge/commits-550+-0a0a0f?style=flat-square&labelColor=1a1a2e&color=059669" />
  <img src="https://img.shields.io/badge/agents_tested-20-0a0a0f?style=flat-square&labelColor=1a1a2e&color=f59e0b" />
  <img src="https://img.shields.io/badge/IPC_channels-113-0a0a0f?style=flat-square&labelColor=1a1a2e&color=0ea5e9" />
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

## 📦 8 Built-In Templates — 60 Agents from 430k+ Stars

<p align="center">
  <img src="https://img.shields.io/badge/8_Templates-60_Agents-7c3aed?style=for-the-badge" />
  &nbsp;
  <img src="https://img.shields.io/badge/430k+_Stars-Combined-f59e0b?style=for-the-badge&logo=github&logoColor=white" />
  &nbsp;
  <img src="https://img.shields.io/badge/One_Click-Deploy-059669?style=for-the-badge" />
</p>

<br />

**We took the 8 most popular Claude Code workflows on GitHub and turned them into one-click agent teams.**

Every template ships built into Meridian. Pick one, click Apply, and Manager deploys the full team — each role becomes a **real parallel agent** on your topology. No config. No YAML. No setup.

These workflows have **430,000+ combined GitHub stars**. They're incredible prompt systems. But they all share the same limitation: one agent pretending to be 15 different roles. When gstack runs `/review`, it's the same process that just ran `/ship`. No parallelism. No shared memory. No visibility.

**Meridian makes them real.**

<br />

```
CLI workflow (single agent):   Plan → Build → Review → Test → Ship
                               ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
                               One process. One role at a time.

Meridian (real agents):        Planner ━━━━━━┓
                               Builder ━━━━━━┫
                               Reviewer ━━━━━╋━━→ Manager orchestrates
                               Tester ━━━━━━━┫    all in parallel
                               Security ━━━━━┛
```

<br />

### The Templates

| Template | Source | Stars | Agents | What It Does |
|:---|:---|---:|:---:|:---|
| **gstack** | [Garry Tan](https://github.com/garrytan/gstack) | 54k | 8 | Full engineering org — CEO review, eng review, design, QA, security, shipping |
| **Superpowers** | [Jesse Vincent](https://github.com/obra/superpowers) | 122k | 7 | 7-phase pipeline — brainstorm, plan, execute, TDD, code review, debug, ship |
| **Everything Claude Code** | [Affaan Mustafa](https://github.com/affaan-m/everything-claude-code) | 115k | 8 | Production agent harness — planner, architect, security, TDD, build resolution |
| **GSD** | [TACHES](https://github.com/gsd-build/get-shit-done) | 44k | 7 | Wave-based parallel execution — research, plan, execute, verify, audit |
| **Agents** | [Seth Hobson](https://github.com/wshobson/agents) | 32k | 6 | Team-based orchestration — lead, implement, review, debug, secure, benchmark |
| **Ruflo** | [ruvnet](https://github.com/ruvnet/ruflo) | 28k | 7 | Hierarchical swarm — queen coordinator, domain architects, quality gates |
| **SuperClaude** | [SuperClaude Org](https://github.com/SuperClaude-Org/SuperClaude_Framework) | 22k | 7 | Cognitive architecture — frontend/backend/system architects, quality + security |
| **Oh My Claude Code** | [Yeachan Heo](https://github.com/Yeachan-Heo/oh-my-claudecode) | 15k | 10 | Full 19-agent org — analyst, architect, planner, executor, designer, QA, verifier |

<br />

### How It Works

1. **Pick a template** — browse the 8 built-in options in the Templates panel
2. **Click Apply** — Manager reads the template and deploys every agent
3. **Real agents spawn** — each role becomes a live subprocess on the topology
4. **Start building** — the team is ready. Just describe what you want.

Or **paste any GitHub URL** — Meridian clones the repo, parses the skill files, and builds a custom template on the fly.

<br />

### Why This Matters

| | CLI Workflows | Meridian Templates |
|:---|:---|:---|
| 🤖 Roles | 1 agent switching personas | **Each role = real parallel agent** |
| ⚡ Speed | Sequential — one role at a time | **Parallel — all roles simultaneously** |
| 🧠 Memory | Context lost between role switches | **Scribe tracks all inter-agent communication** |
| 🗺️ Visibility | Terminal output scrolling past | **Live topology map of every agent** |
| 🔄 Recovery | Start over if context resets | **Auto-restart with exponential backoff** |
| 📊 Cost tracking | None | **Per-agent token + cost breakdown** |

<br />

### Import Your Own

Templates aren't locked to our 8 built-ins. The system supports any workflow that uses markdown-based role definitions:

- **GitHub repos** — paste any URL, Meridian clones and parses
- **Local directories** — import from your filesystem
- **Your own workflows** — package your agent team as a shareable template

> **Think Docker Hub, but for AI agent teams.** Pick a template, deploy the team, start building.

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

Meridian's communication layer is built on **113 typed IPC channels** between the Electron main process and the renderer.

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
| 🔌 Bridge | **113 IPC channels** | Typed, validated, bidirectional |
| 🤖 Agents | **Real CLI subprocesses** | Isolated dirs, health monitoring, auto-restart |

> **No in-memory agent simulation.** No JSON file state management pretending to be orchestration. Real processes, real IPC, real results.

<br />

---

<br />

## 🧬 Built on the Best of Open Source

We studied **80+ open-source projects** across the multi-agent ecosystem — orchestration frameworks, memory systems, task engines, terminal emulators, visualization libraries, and production Electron apps. Then we took the best ideas and rebuilt them into Meridian's architecture.

Not forked. Not wrapped. **Studied, understood, and reimplemented** to fit a native desktop orchestrator.

| What We Built | Inspired By | What We Learned |
|:---|:---|:---|
| 🗄️ SQLite persistence + WAL mode | **LangGraph** checkpointing | State machine snapshots survive crashes — flat JSON doesn't |
| 📬 Typed protocol messages | **Overstory** SQLite mail system | ACID message delivery in ~1ms beats parsing free text |
| 📊 DAG task queue | **p-queue** + **toposort** | ~500 lines beats deploying Redis. Local-only, zero infra |
| 🔁 Retry + dead letter queue | **Temporal**, **Inngest** | Exponential backoff + jitter is the universal standard for a reason |
| 🩺 Agent health scoring | **Overstory** tiered monitoring | Mechanical heartbeat → AI-assisted → patrol. Three tiers, not one |
| 🔭 Embedded observability | **OpenLLMetry** (OpenTelemetry) | Traces to local SQLite. Per-agent cost tracking. 2-hour integration |
| 📐 Topology layout | **elkjs** Sugiyama algorithm | Proper hierarchical layout handles any team shape automatically |
| 🔀 Git integration | **simple-git** + **Aider** patterns | Atomic `git apply` for multi-file agent changes. All-or-nothing commits |
| 🖥️ PTY management | **Tabby** three-layer system | Backpressure (`ackData`) prevents memory explosion at 10+ agents |
| 💥 Crash recovery | **VS Code** / **Chrome** patterns | Crash flag on startup, delete on clean exit, safe mode if flag persists |
| 🔄 Plan-Execute-Observe-Replan | **Magentic-One** (Microsoft) | Explicit state machine > ad-hoc dispatch. Agents recover from failures |

### Projects we studied deeply

<details>
<summary><strong>Multi-agent orchestration</strong> — CrewAI, AutoGen/AG2, LangGraph, MetaGPT, Magentic-One, OpenAI Swarm, ChatDev, Overstory, ComposioHQ, AgentScope, Swarms, Pydantic AI, Dify, MassGen, Microsoft Agent Framework</summary>
<br />

We analyzed how each framework handles routing, memory, error recovery, and inter-agent communication. LangGraph's checkpoint pattern and Overstory's SQLite mail were the standout ideas. Most frameworks manage agents as in-memory objects — we went the opposite direction with real subprocesses, which ComposioHQ and Overstory validated as the right call.

</details>

<details>
<summary><strong>Memory systems</strong> — Mem0, Letta (MemGPT), Zep, Hindsight, Zikkaron, Cortex, Memvid, ChromaDB, LanceDB, Qdrant</summary>
<br />

Mem0's multi-tenant scoping and Letta's two-tier memory (RAM-like core + disk-like archival) shaped our Scribe architecture. Zikkaron's hippocampal replay for surviving context compaction is on our v2 roadmap. For v1, we chose human-readable markdown on disk over opaque vector databases — you can grep your project memory.

</details>

<details>
<summary><strong>Task engines</strong> — Temporal, Inngest, BullMQ, Hatchet, embedded-queue, node-persistent-queue, liteque, dagx, toposort</summary>
<br />

Every production queue uses the same retry pattern: exponential backoff with jitter and a dead letter queue. We adopted that universal standard. For DAG resolution, toposort + p-queue gives us dependency ordering and concurrency control in ~500 lines — no Redis, no cloud, no external infra.

</details>

<details>
<summary><strong>Terminal & Electron</strong> — Tabby, Wave Terminal, Hyper, VS Code, Bitwarden, Insomnia, electron-store</summary>
<br />

Tabby's three-layer PTY system (manager → wrapper → data queue with backpressure) prevents memory explosion when running 10+ agents. VS Code's MessagePort IPC and crash recovery patterns informed our stability architecture. We're an Electron app that takes production patterns from apps with millions of users.

</details>

<details>
<summary><strong>Visualization & code gen</strong> — React Flow, Cytoscape.js, G6, elkjs, dagre, Sigma.js, vis-network, Cline, Aider, Continue.dev, bolt.diy, simple-git</summary>
<br />

We stayed with raw Canvas 2D (validated by the research — lighter than WebGL for 20-50 nodes) but adopted elkjs for proper Sugiyama hierarchical layout. Aider's git-first approach (auto-commit with meaningful messages, atomic multi-file apply) shaped our git integration.

</details>

<details>
<summary><strong>Observability</strong> — OpenLLMetry, Langfuse, Phoenix, AgentOps, Helicone</summary>
<br />

OpenLLMetry won: OpenTelemetry-based, vendor-agnostic, exports to local SQLite, zero telemetry collection, 2-hour integration. We get correlation IDs, per-agent cost tracking, and full trace visibility without shipping your data anywhere.

</details>

<br />

> **Every project listed above is MIT, Apache 2.0, BSD, or similarly permissive licensed.** We didn't copy code — we studied architectures, understood the patterns, and rebuilt them from scratch for a native desktop orchestrator. That's how good software gets built. Standing on the shoulders of the open-source community. 🙏

<br />

---

<br />

## 📊 How Meridian Compares

|  | Meridian | Claude Code Teams | Claude Squad | Opcode | Agentrooms |
|:---|:---:|:---:|:---:|:---:|:---:|
| 🤖 Multi-agent orchestration | ✅ | 🧪 Experimental | ❌ | ❌ | ⚠️ Limited |
| 🗺️ Visual topology | ✅ | ❌ | ❌ | ❌ | ❌ |
| 🎯 Dynamic team composition | ✅ | ❌ | ❌ | ❌ | ❌ |
| ⚡ Real parallel agents | ✅ | ✅ | ✅ | ✅ | ⚠️ Partial |
| 🧠 Shared memory (Scribe) | ✅ | ❌ | ❌ | ❌ | ❌ |
| 📦 Workflow templates | ✅ | ❌ | ❌ | ❌ | ❌ |
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
- [x] 🗄️ SQLite persistence — projects, agents, chat, sessions survive restarts
- [x] 📬 SQLite mail system — typed protocol messages between agents (ACID delivery)
- [x] 📊 DAG task queue — p-queue + toposort with dependency resolution
- [x] 🔁 Dead letter queue — exponential backoff retry with jitter
- [x] 🩺 Agent health scoring — success/failure/stale tracking, persisted to DB
- [x] 🔭 Correlation IDs + spans table — per-agent tracing and cost tracking
- [x] 🔄 Plan-Execute-Observe-Replan — dispatch state machine for Manager
- [x] 🔀 Git integration — simple-git, status pill, commit dialog, push/pull from app
- [x] 📚 Obsidian integration — vault picker, Scribe auto-sync, live file browser
- [x] 📐 elkjs Sugiyama layout — automatic hierarchical topology positioning
- [x] 🔍 Zoom + pan — cursor-relative scaling (0.3x–3x), drag to pan
- [x] 🎬 GSAP spawn/exit animations — nodes scale in/out on agent lifecycle
- [x] 💰 Per-agent cost breakdown — model-aware pricing in token popover
- [x] 🔔 Badge indicators — unread counts and error dots on icon rail
- [x] 📦 One-click workflow templates — import any skill pack, each role becomes a real agent
- [x] 🔥 8 built-in templates — 60 agents from 430k+ combined GitHub stars (gstack, Superpowers, Everything Claude Code, GSD, Agents, Ruflo, SuperClaude, Oh My Claude Code)
- [x] 🧠 Elite Manager system prompt — intent classification, task graph decomposition, adaptive replanning, recovery playbook

### 🔜 Coming Soon
- [ ] 🔓 Multi-provider support (Codex, Gemini CLI, any CLI agent alongside Claude)
- [ ] 🌐 Multi-machine orchestration — cluster your Mac Minis, distribute agents across machines (think [exo](https://github.com/exo-explore/exo) but for coding agents)
- [ ] 🪟 Windows + Linux support

### 🔮 Future
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
  <a href="https://github.com/Fresh1289/meridian/releases/latest"><img src="https://img.shields.io/badge/Download-v1.0.3_Alpha-7c3aed?style=for-the-badge&logo=apple&logoColor=white" /></a>
</p>

### Requirements

- **macOS** (Apple Silicon — M1/M2/M3/M4)
- **Claude CLI** installed and authenticated ([install guide](https://docs.anthropic.com/en/docs/claude-code))
- **Claude Max plan** or an Anthropic API key

### Setup

1. **Download** `Meridian-1.0.3-arm64.dmg` from the [latest release](https://github.com/Fresh1289/meridian/releases/latest)
2. **Open** the DMG and drag Meridian to your Applications folder
3. **Bypass Gatekeeper** (app is unsigned — Apple Developer enrollment pending):
   - Right-click Meridian.app → **Open** → Click **"Open"** in the dialog
   - Or run in Terminal: `xattr -cr /Applications/Meridian.app`
4. **Launch** Meridian — sign in with GitHub or email
5. **Connect Claude** — Meridian detects your CLI automatically. Optionally add an API key.
6. **Create a project** — name it, describe what you're building, pick a directory
7. **Start building** — Manager deploys the right team and you're off

### Updates

Meridian checks for new versions automatically. When an update is available, it downloads in the background and installs on next launch. No manual re-downloading.

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

## 💬 Support

- **Bug reports & feature requests** → [GitHub Issues](https://github.com/Fresh1289/meridian/issues)
- **Questions & community** → [Discord](https://discord.gg/nvkEWVu5Wx)

<br />

---

<br />

<p align="center">
  <img src="assets/meridian-icon.svg" width="48" height="48" alt="" />
</p>

<p align="center">
  <code>550+ commits · 142 source files · 113 IPC channels · 85 React components</code>
  <br />
  <code>8 SQLite tables · 14 end-to-end tests · 20-agent stress test cleared</code>
  <br /><br />
  <strong>⚡ Stop being the bottleneck.</strong>
  <br /><br />
  <a href="https://github.com/Fresh1289">
    <img src="https://img.shields.io/badge/Built_by-Matthew_Huang-7c3aed?style=flat-square&labelColor=1a1a2e" />
  </a>
</p>
