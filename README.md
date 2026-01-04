# FFBrowser Automation & Local API

FFBrowser Automation is an **open automation ecosystem** built on top of **FFBrowser** —  
a commercial browser platform designed for **deterministic browser environments**, scalable automation, and long-running workflows.

This repository focuses on **automation, integration, and developer tooling**.  
The browser core itself is distributed separately under a commercial license.

> ⚠️ Important  
> The FFBrowser core (browser executable and environment engine) is a **commercial product**.  
> This repository provides **open-source SDKs, examples, and Local API documentation**.

---

## What is FFBrowser?

FFBrowser is a **browser environment platform** that allows developers to run and control multiple isolated browser environments programmatically.

Key characteristics:

- Isolated browser environments
- Deterministic and reproducible browser sessions
- Controlled runtime variability
- Local HTTP API–driven control
- Designed to run as a long-lived local service

FFBrowser is not a short-lived automation runner.  
It is designed to act as a **persistent browser service** that can be orchestrated externally.

---

## Why FFBrowser Automation?

Modern automation systems require more than launching and closing browsers.

FFBrowser Automation enables:

- Programmatic lifecycle control of browser environments
- Parallel execution of multiple browser sessions
- Stable environments for long-running tasks
- Clear separation between browser core and automation logic
- Easy integration with automation frameworks and AI agents

Typical use cases include:

- Web automation and crawling
- Session-based workflow execution
- Task orchestration systems
- AI-driven browser agents
- Automation platforms and services

---

## Architecture Overview

```text
+--------------------------+
|     Automation Layer     |
|    (SDKs / AI Agents)    |
+------------+-------------+
             |
             | Local HTTP API
             |
+------------v-------------+
|      FFBrowser Core      |
| (Commercial Browser App) |
+--------------------------+
```



- The **FFBrowser core** runs locally as a background service
- Automation tools communicate via a **Local HTTP API**
- SDKs wrap API calls into developer-friendly interfaces
- AI agents can treat FFBrowser as an executable tool

---

## Local API

FFBrowser exposes a **Local HTTP API** for controlling browser environments and runtime behavior.

High-level capabilities include:

- Environment lifecycle management
- Browser instance start / stop
- Window and tab operations
- Batch and group control
- Runtime status and state querying

📘 Documentation:

- Chinese API Documentation: `docs/api_zh.md`
- English API Documentation: `docs/api_en.md`

> API access requires a valid local installation of FFBrowser.

---

## SDKs

Official SDKs simplify interaction with the Local API and are fully open source.

Planned and available SDKs:

- JavaScript / TypeScript
- Python (planned)

SDK repositories:

- `ffbrowser-sdk-js`
- `ffbrowser-sdk-python`

These SDKs are suitable for:

- Automation frameworks
- Workflow engines
- AI tool calling
- Agent-based systems

---

## AI Agent Ready

FFBrowser Automation is **agent-friendly by design**.

The Local API provides:

- Explicit state control
- Deterministic execution behavior
- Clear separation between intent and execution
- Inspectable and reproducible outcomes

This makes FFBrowser suitable for:

- LLM-based agents
- Tool-calling pipelines
- Autonomous task runners
- Hybrid human + agent workflows

Agent examples and integrations will be added progressively.

---

## Getting Started

1. Install FFBrowser (commercial product)
2. Start the FFBrowser local service
3. Use SDKs or direct HTTP calls to control browser environments

Detailed setup instructions are available in the documentation.

---

## Roadmap

- [ ] Stable JavaScript / TypeScript SDK
- [ ] Python SDK
- [ ] Automation examples
- [ ] AI agent demos
- [ ] Workflow templates

---

## Licensing

- SDKs, examples, and documentation: **Open Source**
- FFBrowser core (browser executable): **Commercial License**

---

## Contact & Access

For FFBrowser installation, licensing, or commercial inquiries:

- Website: (coming soon)
- Email: mp7788414#outlook.com
