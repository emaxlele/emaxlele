<div align="center">

# Hi, I'm Emanuele Gallo 👋

**AI Engineer & Full-Stack Developer**

_Building enterprise GenAI platforms and self-hosted tooling from the ground up_

[![Website](https://img.shields.io/badge/Website-emaxlele.com-0066cc?style=flat&logo=googlechrome&logoColor=white)](https://emaxlele.com)
[![GitHub](https://img.shields.io/badge/GitHub-emaxlele-181717?style=flat&logo=github)](https://github.com/emaxlele)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0002--4310--8014-A6CE39?style=flat&logo=orcid&logoColor=white)](https://orcid.org/0009-0002-4310-8014)

</div>

---

## About Me

Packaged App Development Analyst at Accenture (ATC SAP Italy), specialized in designing and shipping enterprise-grade GenAI platforms end-to-end — from SDK architecture to cloud deployment.

Built an **enterprise multi-agent AI platform** serving 36+ active users in production, spanning a custom React SDK (`web-chat-core`), a full PWA frontend, and a multi-agent orchestration layer on Microsoft Copilot Studio — all architected and delivered from scratch.

> From intern to de-facto Technical Lead in **16 months**.

More on my background and projects: **[emaxlele.com](https://emaxlele.com)**

---

## Tech Stack

**Frontend**

```
React 19 · TypeScript 5.9 · Vite 7 · Tailwind CSS 4 · PWA · MSAL (Entra ID) · react-aria
```

**AI / GenAI**

```
Microsoft Copilot Studio · Multi-Agent Orchestration
Azure OpenAI (GPT-4.1) · AWS Bedrock (Claude Opus 4, Claude Sonnet 4)
Prompt Engineering · MCP (Model Context Protocol)
```

**Media Processing (Client-Side)**

```
FFmpeg WASM (multi-thread) · Azure Speech SDK · In-browser video transcription & frame extraction
```

**Backend & Cloud**

```
Python (FastAPI · aiohttp · Bot Framework SDK v4) · Node.js · Docker
Azure Functions · APIM · Static Web Apps · Key Vault · VNET · AI Search · Azure ML · Entra ID
```

**DevOps**

```
GitHub Actions · Azure DevOps · func CLI · Docker · ZIP deploy · CI/CD
```

**Other**

```
Go · Chrome Extensions (MV3) · Native Messaging · SAP (ABAP) · AWS IAM / SigV4
```

---

## Projects

### [M365-Copilot-Extension](https://github.com/emaxlele/M365-Copilot-Extension)

> Chrome extension (MV3) that supercharges Microsoft 365 Copilot

-   **Model forcing** — override the active model at the protocol level
-   **System prompt override** — inject custom instructions into every request
-   **MCP Tools** — read/write local filesystem, run PowerShell commands from chat
-   **Conversation history** — persistent IndexedDB-backed history
-   **Traffic inspector** — intercepts WebSocket/fetch/XHR payloads
-   6-tab floating panel, keyboard shortcuts, export to Markdown/JSON

**Stack**: `JavaScript` `CSS` `Chrome MV3` `Vite` `MIT`

---

### [Edge-Bridge](https://github.com/emaxlele/Edge-Bridge)

> Portable Microsoft Edge launcher with embedded extensions and local MCP/native messaging bridge

-   Isolated Edge profile with auto-loaded extensions
-   Go-based native messaging bridge (`bridge.exe`)
-   Portable build: single `scripts\build.bat` produces full artifact tree
-   App mode + browser mode, MCP integration

**Stack**: `Go` `Batchfile` `MIT`

---

### [react-dropdown-multilevel](https://github.com/emaxlele/react-dropdown-multilevel)

> Accessible multi-level dropdown menu component for React

-   Arbitrary nesting depth, keyboard navigation, full focus management
-   Zero external dependencies

**Stack**: `React` `TypeScript` `MIT`

---

### [Stampa3DUtility](https://github.com/emaxlele/Stampa3DUtility)

> Web utility for 3D printing calculations

**Stack**: `HTML`

---

### PocketBase VPS Desktop

> Desktop app (Go, Wails, React 19) to visually manage a Linux VPS running PocketBase — no terminal needed

-   GUI for atomic frontend deployments, site management, backup and rollback
-   SSH/SFTP-native: file manager, PTY terminal, system monitor, systemd services, process manager, cron editor, firewall
-   Config persisted in `%APPDATA%/PocketBase-VPS-Desktop/config.json`

**Stack**: `Go` `Wails` `React 19` `TypeScript` `Tailwind CSS v4`

![PocketBase VPS Desktop — Home](https://emaxlele.com/screenshots/vps-desktop/home.png)

---

### PocketBase VPS Toolkit

> CLI multi-call (Go) for Caddy + PocketBase + SPA stack on Linux VPS — idempotent, systemd-native

-   Atomic frontend deploys with symlink switching and versioned releases
-   `sitectl`, `deploy-frontend`, `backupctl` as composable CLI commands
-   HTTPS via Caddy with automatic TLS and optional Cloudflare mTLS

**Stack**: `Go` `Caddy` `PocketBase` `systemd`

---

### PocketBase Toolkit

> Desktop app (Go, Wails, React 19) for importing and managing data in PocketBase instances

-   Field mapping, self/cross/manual relations, media pipeline
-   Guided step-by-step flow; supports creating collections from scratch without JSON

**Stack**: `Go` `Wails` `React 19` `TypeScript` `PocketBase`

![PocketBase Toolkit — Home](https://emaxlele.com/screenshots/pocketbase-toolkit/home.png)

---

## Enterprise Work _(private repos / Azure DevOps)_

| Project                        | Stack                                 | Impact                                   |
| ------------------------------ | ------------------------------------- | ---------------------------------------- |
| **GenAI Platform PWA** v0.0.80 | React 19, Vite 7, TS 5.9, MSAL, PWA   | 36+ users in production                  |
| **web-chat-core SDK** v1.6.0   | React 19, FFmpeg WASM, Azure Speech   | 40+ deps, in-browser video transcription |
| **AI Code Analyzer**           | Python, FastAPI, Docker, LLM, Mermaid | 230 files / 50K LOC auto-analyzed        |
| **Multi-Agent AI Platform**    | Copilot Studio, Azure OpenAI, Bedrock | +16% productivity, 20+ AI use cases      |
| **Azure Functions Middleware** | Azure Functions, APIM, CI/CD, SigV4   | AWS Bedrock bridge, full playbook        |
| **ZKait Azure SDK Bot**        | Python, Bot Framework SDK v4          | Team's first AI bot                      |

---

## Impact Numbers

| Metric                           | Value                             |
| -------------------------------- | --------------------------------- |
| Productivity improvement (trial) | **+16%** across 1,239 effort-days |
| Coding task time savings         | Up to **79%** (12h → 2.5h)        |
| Active users in production       | **36+**                           |
| Enterprise projects shipped      | **5+**                            |
| AI use cases shipped             | **20+** across 4 categories       |
| SDK dependencies managed         | **40+**                           |

---

## Education

-   🎓 **Laurea in Informatica (L-8)** — Unimercatorum (Università Telematica Mercatorum)
-   📚 GenAI in TDLC — Accenture Training Labs (2026)
-   🔬 ORCID: [0009-0002-4310-8014](https://orcid.org/0009-0002-4310-8014)

---

<div align="center">

_Pace del Mela (ME), Sicily · Accenture ATC SAP Italy · June 2026_

</div>
