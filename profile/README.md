<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/sinas-platform/sinas/main/console/public/sinas-logo-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/sinas-platform/sinas/main/console/public/sinas-logo-light.svg">
    <img alt="Sinas" src="https://raw.githubusercontent.com/sinas-platform/sinas/main/console/public/sinas-logo-light.svg" height="48">
  </picture>
</p>

<p align="center"><strong>Open-source platform for building AI agents and serverless automation with fine-grained access control.</strong></p>

<p align="center">
  <a href="https://github.com/sinas-platform/sinas">Get Started</a> &middot;
  <a href="https://github.com/sinas-platform/sinas/blob/main/DOCS.md">Documentation</a> &middot;
  <a href="https://sinas.co">Website</a>
</p>

---

Sinas is a self-hosted backend for AI-powered applications. Configure agents with any LLM provider, write Python functions that run in isolated containers, connect everything with webhooks and schedules, and control who can do what with role-based permissions — all managed through a web console or declarative YAML config.

### Repositories

| Repository | Description |
|---|---|
| [**sinas**](https://github.com/sinas-platform/sinas) | Core platform — backend, console, and Docker deployment |
| [**sinas-python**](https://github.com/sinas-platform/sinas-python) | Python SDK for interacting with the Sinas API |
| [**sinas-js**](https://github.com/sinas-platform/sinas-js) | JavaScript/TypeScript SDK for interacting with the Sinas API |
| [**sinas-ui**](https://github.com/sinas-platform/sinas-ui) | Pre-built UI components for embedding Sinas agents and chat in your app |
| [**chat**](https://github.com/sinas-platform/chat) | Private AI chat application built on top of Sinas |

### Highlights

- **Multi-provider AI agents** with tool calling, agent-to-agent orchestration, and SSE streaming
- **Sandboxed Python functions** with automatic execution tracking, triggered via webhooks, schedules, or agents
- **Fine-grained access control** with hierarchical scopes, wildcards, and namespace-level permissions for AI governance
- **Embeddable UI components** compiled by Sinas with built-in proxy to agents, functions, and queries
- **Declarative configuration** for GitOps workflows — idempotent apply, change detection, and dry run
- **SDKs for Python and JavaScript** to integrate Sinas into any application

### Quick Start

```bash
git clone https://github.com/sinas-platform/sinas.git
cd sinas
./install.sh
```

### License

Dual licensed under [AGPL v3.0](https://github.com/sinas-platform/sinas/blob/main/LICENSE) (open source) and a Commercial License (proprietary use). Contact [hello@sinas.co](mailto:hello@sinas.co) for commercial licensing.
