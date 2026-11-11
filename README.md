# Awesome Kimi Plugins

A community catalog of [Kimi Code](https://www.kimi.com/code) plugins — and a **one-line marketplace** for them.

```
/plugins marketplace https://raw.githubusercontent.com/mnshkv/awesome-kimi-plugins/main/kimi-marketplace.json
```

Run this once in Kimi Code (CLI or Desktop) and the plugins below appear in `/plugins` → **Custom**, ready to install. Managed by [@mnshkv](https://github.com/mnshkv). PRs welcome — see [Contributing](#contributing).

Curated list companion: [hashgraph-online/awesome-ai-plugins → Kimi Plugins](https://github.com/hashgraph-online/awesome-ai-plugins#kimi-plugins).

## 🍎 Apple / iOS

| Plugin | What it does | Install |
|---|---|---|
| [**kimi-xcode-plugin**](https://github.com/mnshkv/kimi-xcode-plugin) | Xcode from Kimi Code: builds, tests, SwiftUI previews, simulators & devices, build logs, Apple docs — via Xcode's own MCP server (`xcrun mcpbridge`). The Apple plugin for Claude Code, repackaged. | `/plugins install https://github.com/mnshkv/kimi-xcode-plugin` |
| [**kimi-agent-desktop**](https://github.com/mnshkv/kimi-agent-desktop) | Computer Use on macOS from Kimi Code & Desktop: AX tree with element refs, headless clicks / typing / scroll / keys, screenshots. 21 MCP tools, zero dependencies. Drop-in `kimi-cu` replacement. | `/plugins install https://github.com/mnshkv/kimi-agent-desktop` |

## 🤖 Android

| Plugin | What it does | Install |
|---|---|---|
| [**kimi-android-studio-plugin**](https://github.com/mnshkv/kimi-android-studio-plugin) | Android development from Kimi Code: adb, emulators & devices, screenshots, UI automation, Gradle builds & tests, Android Studio control via the JetBrains MCP server. | `/plugins install https://github.com/mnshkv/kimi-android-studio-plugin` |

## 🧠 Memory

| Plugin | What it does | Install |
|---|---|---|
| [**deja (deja-vu)**](https://github.com/vshulcz/deja-vu) | Shared local memory across 43 coding agents: past transcripts, file blame, error-fix history, cross-agent handoff. MCP + skills + hooks. | `/plugins install https://github.com/vshulcz/deja-vu` |
| [**GoodMemory**](https://github.com/hjqcan/GoodMemory) | Local-first, auditable cross-session project memory with scoped recall, traceable provenance and approval-gated writes. | `/plugins install https://github.com/hjqcan/GoodMemory` |

## 🌐 Web & Media

| Plugin | What it does | Install |
|---|---|---|
| [**HTML/CSS to Image API**](https://github.com/htmlcsstoimage/agent-plugins) | Capture live website screenshots, render HTML/CSS into images or PDFs — no browser management. | `/plugins install https://github.com/htmlcsstoimage/agent-plugins` |

## 🧪 Testing & Browsers

| Plugin | What it does | Install |
|---|---|---|
| [**chrome-devtools-mcp**](https://github.com/ChromeDevTools/chrome-devtools-mcp) | Chrome DevTools from Kimi Code: performance traces, network inspection, console, DOM debugging and screenshots against a live Chrome. Ships a `.kimi-code-plugin` manifest from the Chrome DevTools team. | `/plugins install https://github.com/ChromeDevTools/chrome-devtools-mcp` |

## 🛠️ Workflow & Skills

| Plugin | What it does | Install |
|---|---|---|
| [**superpowers**](https://github.com/obra/superpowers) | A battery of workflow skills — brainstorming, systematic debugging, TDD, planning — with Kimi tool-name remapping built in. | `/plugins install https://github.com/obra/superpowers` |
| [**KimiQB**](https://github.com/alicankiraz1/KimiQB) | Vibecoding-first planning: interrogates the task, keeps specs and checklists honest before code gets written. | `/plugins install https://github.com/alicankiraz1/KimiQB` |
| [**kimi-code-statusbar-plugin**](https://github.com/arsfy/kimi-code-statusbar-plugin) | Extra TUI status-bar metrics: tokens/sec, prompt-cache hit rate, plan usage windows. | `/plugins install https://github.com/arsfy/kimi-code-statusbar-plugin` |
| [**kimi-context-optimizer**](https://github.com/egorfedorov/kimi-context-optimizer) | Cuts redundant reads and weak prompts using wire.jsonl ground truth — 63% measured token savings. | `/plugins install https://github.com/egorfedorov/kimi-context-optimizer` |

## 🔒 Security

| Plugin | What it does | Install |
|---|---|---|
| [**npmscan-mcp-plugin**](https://github.com/salemalem/npmscan-mcp-plugin) | NPMscan security scanning of npm dependencies: vulnerabilities, malicious-code signals, upgrade advice. | `/plugins install https://github.com/salemalem/npmscan-mcp-plugin` |

## ☁️ Cloud & Backend

| Plugin | What it does | Install |
|---|---|---|
| [**CloudBase AI Toolkit**](https://github.com/TencentCloudBase/CloudBase-AI-Toolkit) | Tencent CloudBase backend from Kimi Code: database, auth and cloud functions via plugin, skills & MCP. | `/plugins install https://github.com/TencentCloudBase/CloudBase-AI-Toolkit` |
| [**convex-kimi-plugin**](https://github.com/convex/convex-kimi-plugin) | Official Convex plugin: scaffold and build Convex + Next.js apps with a reactive, type-safe backend. | `/plugins install https://github.com/convex/convex-kimi-plugin` |
| [**Neon agent-skills**](https://github.com/neondatabase/agent-skills) | Neon serverless Postgres: schema design, database branching and SQL from your agent. | `/plugins install https://github.com/neondatabase/agent-skills` |

## 🎬 Media & 3D

| Plugin | What it does | Install |
|---|---|---|
| [**@remotion/kimi-code-plugin**](https://github.com/remotion-dev/kimi-code-plugin) | Official Remotion skills: programmatic video in React — animations, captions, audio, 3D. | `/plugins install https://github.com/remotion-dev/kimi-code-plugin` |
| [**kimi-blender-mcp-plugin**](https://github.com/artmediastudio/kimi-blender-mcp-plugin) | Control Blender from Kimi Code: scene building, modeling and rendering over MCP (wraps blender-mcp). | `/plugins install https://github.com/artmediastudio/kimi-blender-mcp-plugin` |

## 🤝 Multi-agent

| Plugin | What it does | Install |
|---|---|---|
| [**codex-plugin-kimi-code**](https://github.com/winmin/codex-plugin-kimi-code) | Delegate from Kimi to OpenAI Codex: second-opinion reviews, custom prompts, parallel tasks. | `/plugins install https://github.com/winmin/codex-plugin-kimi-code` |

## Contributing

1. Your repo must expose `kimi.plugin.json` (or `.kimi-plugin/plugin.json`) and be installable with `/plugins install <github-url>`.
2. Open a PR adding your plugin to **kimi-marketplace.json** (`id`, `displayName`, `description`, `source`) and to the table above.
3. Descriptions: one sentence, what it does — not what it is. Verified listings only; the maintainer may ask for a demo or docs link.

Also listed in the [HOL plugin registry](https://hol.org/registry/plugins).

## Why this exists

Kimi Code supports custom marketplaces (`/plugins marketplace <url>`), but there was no community catalog doubling as a marketplace feed. This repo is both: browsable README + JSON you can plug straight into the CLI. See [MoonshotAI/kimi-code#1566](https://github.com/MoonshotAI/kimi-code/issues/1566).
