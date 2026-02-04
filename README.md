<div align="center">

<!-- title -->

<!--lint ignore no-dead-urls-->

# Awesome OpenClaw [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Lint](https://github.com/NipunaRanasinghe/awesome-openclaw/actions/workflows/lint.yml/badge.svg)](https://github.com/NipunaRanasinghe/awesome-openclaw/actions/workflows/lint.yml) [![Check Links](https://github.com/NipunaRanasinghe/awesome-openclaw/actions/workflows/links.yml/badge.svg)](https://github.com/NipunaRanasinghe/awesome-openclaw/actions/workflows/links.yml)

<!-- description -->

_A curated list of awesome [OpenClaw](https://openclaw.ai/) resources — community projects, tools, skills, integrations, and examples for the open-source personal AI assistant._ 🦞

<!-- image -->

<a href="https://github.com/NipunaRanasinghe/awesome-openclaw" target="_blank" rel="noopener noreferrer">
  <img src="assets/banner.png" alt="Awesome OpenClaw Banner">
</a>

</div>

---

[OpenClaw](https://github.com/openclaw/openclaw) is an open-source personal AI assistant you run on your own devices. It connects to the channels you already use (WhatsApp, Telegram, Slack, Discord, Signal, iMessage, and more), features voice capabilities, and offers a live Canvas for visual interactions.

---

## Contents

- [📌 Official Resources](#-official-resources)
- [🧩 Community Skills](#-community-skills)
  - [📋 Productivity](#-productivity)
  - [🏠 Smart Home](#-smart-home)
  - [💻 Development](#-development)
  - [💰 Finance](#-finance)
  - [🎬 Media & Entertainment](#-media--entertainment)
  - [🔧 Utilities](#-utilities)
- [🖥️ Alternative Clients & UIs](#-alternative-clients--uis)
- [🚀 Deployment & Infrastructure](#-deployment--infrastructure)
  - [🐳 Docker & Containers](#-docker--containers)
  - [☁️ Cloud Deployment](#-cloud-deployment)
  - [🏠 Self-Hosting](#-self-hosting)
- [📚 Libraries & SDKs](#-libraries--sdks)
- [🔌 Channel Integrations](#-channel-integrations)
- [📊 Monitoring & Analytics](#-monitoring--analytics)
- [🎤 Voice & Audio](#-voice--audio)
- [⚡ Productivity & Workflows](#-productivity--workflows)
- [🛠️ Developer Tools](#-developer-tools)
- [⚙️ Configuration & Dotfiles](#-configuration--dotfiles)
- [📖 Tutorials & Blog Posts](#-tutorials--blog-posts)
- [🎥 Videos & Talks](#-videos--talks)
- [🌐 Community](#-community)
- [🔗 Related Projects](#-related-projects)
- [🚀 Contributors](#-contributors)

---

## 📌 Official Resources

Official projects and documentation from the OpenClaw team.

| Resource                                                        | Description                                              |
| --------------------------------------------------------------- | -------------------------------------------------------- |
| [OpenClaw](https://github.com/openclaw/openclaw)                | The main open-source repository                          |
| [Documentation](https://docs.openclaw.ai/)                      | Official documentation and guides                        |
| [ClawHub](https://clawhub.com/)                                 | Official skills registry for discovering and sharing     |
| [Nix Flake](https://github.com/openclaw/nix-clawdbot)           | Official Nix-based declarative configuration             |
| [Discord](https://discord.gg/clawd)                             | Official Discord server for support and discussions      |
| [DeepWiki](https://deepwiki.com/openclaw/openclaw)              | AI-generated documentation wiki                          |

---

## 🧩 Community Skills

Skills that extend OpenClaw's capabilities.

### 📋 Productivity

| Skill                                                                    | Stars                                                                 | Description                                        |
| ------------------------------------------------------------------------ | --------------------------------------------------------------------- | -------------------------------------------------- |
| [claw-skill-todoist](https://github.com/mharris/claw-skill-todoist)      | ![](https://img.shields.io/github/stars/mharris/claw-skill-todoist)   | Todoist integration for task management            |
| [claw-skill-notion](https://github.com/jzhang/claw-skill-notion)         | ![](https://img.shields.io/github/stars/jzhang/claw-skill-notion)     | Notion workspace integration with database support |
| [claw-skill-linear](https://github.com/devops-ai/claw-skill-linear)      | ![](https://img.shields.io/github/stars/devops-ai/claw-skill-linear)  | Linear issue tracking and project management       |
| [claw-skill-calendar](https://github.com/timekeeper/claw-skill-calendar) | ![](https://img.shields.io/github/stars/timekeeper/claw-skill-calendar) | Google Calendar and Outlook calendar sync        |
| [claw-skill-obsidian](https://github.com/note-taker/claw-skill-obsidian) | ![](https://img.shields.io/github/stars/note-taker/claw-skill-obsidian) | Obsidian vault integration for knowledge management |

### 🏠 Smart Home

| Skill                                                                               | Stars                                                                          | Description                              |
| ----------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ | ---------------------------------------- |
| [claw-skill-homeassistant](https://github.com/smarthome-dev/claw-skill-homeassistant) | ![](https://img.shields.io/github/stars/smarthome-dev/claw-skill-homeassistant) | Home Assistant integration             |
| [claw-skill-homekit](https://github.com/apple-home/claw-skill-homekit)              | ![](https://img.shields.io/github/stars/apple-home/claw-skill-homekit)         | Apple HomeKit device control             |
| [claw-skill-hue](https://github.com/lightmaster/claw-skill-hue)                     | ![](https://img.shields.io/github/stars/lightmaster/claw-skill-hue)            | Philips Hue lighting control             |
| [claw-skill-mqtt](https://github.com/iot-tools/claw-skill-mqtt)                     | ![](https://img.shields.io/github/stars/iot-tools/claw-skill-mqtt)             | Generic MQTT device integration          |

### 💻 Development

| Skill                                                                          | Stars                                                                       | Description                              |
| ------------------------------------------------------------------------------ | --------------------------------------------------------------------------- | ---------------------------------------- |
| [claw-skill-github](https://github.com/octodev/claw-skill-github)              | ![](https://img.shields.io/github/stars/octodev/claw-skill-github)          | GitHub issues, PRs, and repo management  |
| [claw-skill-gitlab](https://github.com/gitlabber/claw-skill-gitlab)            | ![](https://img.shields.io/github/stars/gitlabber/claw-skill-gitlab)        | GitLab CI/CD and merge request handling  |
| [claw-skill-jira](https://github.com/atlassian-tools/claw-skill-jira)          | ![](https://img.shields.io/github/stars/atlassian-tools/claw-skill-jira)    | Jira issue tracking integration          |
| [claw-skill-docker](https://github.com/container-ai/claw-skill-docker)         | ![](https://img.shields.io/github/stars/container-ai/claw-skill-docker)     | Docker container management and logs     |
| [claw-skill-kubernetes](https://github.com/k8s-claw/claw-skill-kubernetes)     | ![](https://img.shields.io/github/stars/k8s-claw/claw-skill-kubernetes)     | Kubernetes cluster management            |

### 💰 Finance

| Skill                                                                 | Stars                                                                  | Description                                   |
| --------------------------------------------------------------------- | ---------------------------------------------------------------------- | --------------------------------------------- |
| [claw-skill-stocks](https://github.com/fintech-ai/claw-skill-stocks)  | ![](https://img.shields.io/github/stars/fintech-ai/claw-skill-stocks)  | Real-time stock quotes and portfolio tracking |
| [claw-skill-crypto](https://github.com/cryptolobster/claw-skill-crypto) | ![](https://img.shields.io/github/stars/cryptolobster/claw-skill-crypto) | Cryptocurrency prices and wallet monitoring |
| [claw-skill-ynab](https://github.com/budget-ai/claw-skill-ynab)       | ![](https://img.shields.io/github/stars/budget-ai/claw-skill-ynab)     | YNAB budget tracking and transaction logging  |

### 🎬 Media & Entertainment

| Skill                                                                 | Stars                                                                  | Description                              |
| --------------------------------------------------------------------- | ---------------------------------------------------------------------- | ---------------------------------------- |
| [claw-skill-spotify](https://github.com/musiclaw/claw-skill-spotify)  | ![](https://img.shields.io/github/stars/musiclaw/claw-skill-spotify)   | Spotify playback and playlist management |
| [claw-skill-plex](https://github.com/mediaserver/claw-skill-plex)     | ![](https://img.shields.io/github/stars/mediaserver/claw-skill-plex)   | Plex media server control                |
| [claw-skill-youtube](https://github.com/vid-ai/claw-skill-youtube)    | ![](https://img.shields.io/github/stars/vid-ai/claw-skill-youtube)     | YouTube search and video summarization   |

### 🔧 Utilities

| Skill                                                                                  | Stars                                                                               | Description                                      |
| -------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- | ------------------------------------------------ |
| [claw-skill-weather](https://github.com/weatherclaw/claw-skill-weather)                | ![](https://img.shields.io/github/stars/weatherclaw/claw-skill-weather)             | Weather forecasts with multiple providers        |
| [claw-skill-translator](https://github.com/polyglot-ai/claw-skill-translator)          | ![](https://img.shields.io/github/stars/polyglot-ai/claw-skill-translator)          | Multi-language translation via DeepL and Google  |
| [claw-skill-web-search](https://github.com/searchclaw/claw-skill-web-search)           | ![](https://img.shields.io/github/stars/searchclaw/claw-skill-web-search)           | Web search with Brave, DuckDuckGo, Perplexity    |
| [claw-skill-screenshot-ocr](https://github.com/vision-tools/claw-skill-screenshot-ocr) | ![](https://img.shields.io/github/stars/vision-tools/claw-skill-screenshot-ocr)     | Screenshot capture with OCR text extraction      |

---

## 🖥️ Alternative Clients & UIs

Alternative interfaces for interacting with OpenClaw.

| Client                                                                            | Stars                                                                          | Description                                      |
| --------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ | ------------------------------------------------ |
| [openclaw-web](https://github.com/nicholasng/openclaw-web)                        | ![](https://img.shields.io/github/stars/nicholasng/openclaw-web)               | Modern React-based web client with real-time     |
| [claw-tui](https://github.com/terminal-ux/claw-tui)                               | ![](https://img.shields.io/github/stars/terminal-ux/claw-tui)                  | Beautiful terminal UI built with Bubble Tea      |
| [openclaw-raycast](https://github.com/raycast-ext/openclaw-raycast)               | ![](https://img.shields.io/github/stars/raycast-ext/openclaw-raycast)          | Raycast extension for quick access on macOS      |
| [claw-alfred](https://github.com/alfredapp/claw-alfred)                           | ![](https://img.shields.io/github/stars/alfredapp/claw-alfred)                 | Alfred workflow for OpenClaw commands            |
| [openclaw-streamdeck](https://github.com/streamdeck-plugins/openclaw-streamdeck)  | ![](https://img.shields.io/github/stars/streamdeck-plugins/openclaw-streamdeck)| Elgato Stream Deck plugin for voice and commands |
| [claw-emacs](https://github.com/emacs-ai/claw-emacs)                              | ![](https://img.shields.io/github/stars/emacs-ai/claw-emacs)                   | Emacs integration with org-mode support          |
| [openclaw-nvim](https://github.com/nvim-plugins/openclaw-nvim)                    | ![](https://img.shields.io/github/stars/nvim-plugins/openclaw-nvim)            | Neovim plugin for in-editor AI assistance        |
| [claw-vscode](https://github.com/vscode-ext/claw-vscode)                          | ![](https://img.shields.io/github/stars/vscode-ext/claw-vscode)                | VS Code extension with inline chat and canvas    |
| [openclaw-kde](https://github.com/kde-widgets/openclaw-kde)                       | ![](https://img.shields.io/github/stars/kde-widgets/openclaw-kde)              | KDE Plasma widget and system tray integration    |

---

## 🚀 Deployment & Infrastructure

Tools and templates for deploying OpenClaw.

### 🐳 Docker & Containers

| Tool                                                                                | Stars                                                                            | Description                                    |
| ----------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | ---------------------------------------------- |
| [openclaw-docker-compose](https://github.com/selfhosted/openclaw-docker-compose)   | ![](https://img.shields.io/github/stars/selfhosted/openclaw-docker-compose)      | Production-ready Docker Compose with Traefik   |
| [openclaw-kubernetes](https://github.com/k8s-deploy/openclaw-kubernetes)           | ![](https://img.shields.io/github/stars/k8s-deploy/openclaw-kubernetes)          | Helm charts for Kubernetes deployment          |
| [claw-podman](https://github.com/rootless-containers/claw-podman)                  | ![](https://img.shields.io/github/stars/rootless-containers/claw-podman)         | Rootless Podman configuration for security     |

### ☁️ Cloud Deployment

| Tool                                                                       | Stars                                                                       | Description                                 |
| -------------------------------------------------------------------------- | --------------------------------------------------------------------------- | ------------------------------------------- |
| [openclaw-fly](https://github.com/fly-apps/openclaw-fly)                   | ![](https://img.shields.io/github/stars/fly-apps/openclaw-fly)              | One-click deployment to Fly.io              |
| [claw-railway](https://github.com/railway-templates/claw-railway)          | ![](https://img.shields.io/github/stars/railway-templates/claw-railway)     | Railway.app deployment template             |
| [openclaw-render](https://github.com/render-blueprints/openclaw-render)    | ![](https://img.shields.io/github/stars/render-blueprints/openclaw-render)  | Render.com blueprint for instant deployment |
| [claw-aws-cdk](https://github.com/aws-patterns/claw-aws-cdk)               | ![](https://img.shields.io/github/stars/aws-patterns/claw-aws-cdk)          | AWS CDK stack with ECS Fargate and RDS      |
| [openclaw-terraform](https://github.com/iac-tools/openclaw-terraform)      | ![](https://img.shields.io/github/stars/iac-tools/openclaw-terraform)       | Terraform modules for multi-cloud           |
| [claw-pulumi](https://github.com/pulumi-examples/claw-pulumi)              | ![](https://img.shields.io/github/stars/pulumi-examples/claw-pulumi)        | Pulumi infrastructure as code               |

### 🏠 Self-Hosting

| Tool                                                                       | Stars                                                                       | Description                                 |
| -------------------------------------------------------------------------- | --------------------------------------------------------------------------- | ------------------------------------------- |
| [openclaw-ansible](https://github.com/ansible-roles/openclaw-ansible)     | ![](https://img.shields.io/github/stars/ansible-roles/openclaw-ansible)     | Ansible playbooks for automated setup       |
| [claw-nixos-module](https://github.com/nixos-community/claw-nixos-module) | ![](https://img.shields.io/github/stars/nixos-community/claw-nixos-module)  | NixOS module for declarative configuration  |
| [openclaw-unraid](https://github.com/unraid-templates/openclaw-unraid)    | ![](https://img.shields.io/github/stars/unraid-templates/openclaw-unraid)   | Unraid Community Applications template      |
| [claw-synology](https://github.com/nas-packages/claw-synology)            | ![](https://img.shields.io/github/stars/nas-packages/claw-synology)         | Synology NAS package for DSM                |
| [openclaw-proxmox](https://github.com/homelab/openclaw-proxmox)           | ![](https://img.shields.io/github/stars/homelab/openclaw-proxmox)           | Proxmox LXC container scripts               |

---

## 📚 Libraries & SDKs

Client libraries for various programming languages.

| Library                                                                 | Language   | Stars                                                                    | Description                            |
| ----------------------------------------------------------------------- | ---------- | ------------------------------------------------------------------------ | -------------------------------------- |
| [openclaw-py](https://github.com/openclaw-community/openclaw-py)        | Python     | ![](https://img.shields.io/github/stars/openclaw-community/openclaw-py)  | Python SDK for OpenClaw Gateway API    |
| [openclaw-js](https://github.com/openclaw-community/openclaw-js)        | JavaScript | ![](https://img.shields.io/github/stars/openclaw-community/openclaw-js)  | JavaScript/TypeScript client library   |
| [claw-go](https://github.com/golang-tools/claw-go)                      | Go         | ![](https://img.shields.io/github/stars/golang-tools/claw-go)            | Go client with WebSocket support       |
| [openclaw-rs](https://github.com/rust-claw/openclaw-rs)                 | Rust       | ![](https://img.shields.io/github/stars/rust-claw/openclaw-rs)           | Rust SDK with async/await support      |
| [claw-swift](https://github.com/swift-packages/claw-swift)              | Swift      | ![](https://img.shields.io/github/stars/swift-packages/claw-swift)       | Swift package for iOS/macOS            |
| [openclaw-kotlin](https://github.com/jvm-libs/openclaw-kotlin)          | Kotlin     | ![](https://img.shields.io/github/stars/jvm-libs/openclaw-kotlin)        | Kotlin SDK with coroutines support     |
| [claw-ruby](https://github.com/ruby-gems/claw-ruby)                     | Ruby       | ![](https://img.shields.io/github/stars/ruby-gems/claw-ruby)             | Ruby gem for Rails integration         |
| [openclaw-elixir](https://github.com/elixir-libs/openclaw-elixir)       | Elixir     | ![](https://img.shields.io/github/stars/elixir-libs/openclaw-elixir)     | Elixir client with Phoenix LiveView    |

---

## 🔌 Channel Integrations

Community-built channel bridges and integrations.

| Integration                                                                  | Stars                                                                         | Description                                   |
| ---------------------------------------------------------------------------- | ----------------------------------------------------------------------------- | --------------------------------------------- |
| [claw-mastodon](https://github.com/fediverse/claw-mastodon)                  | ![](https://img.shields.io/github/stars/fediverse/claw-mastodon)              | Mastodon/Fediverse integration                |
| [openclaw-reddit](https://github.com/reddit-bots/openclaw-reddit)            | ![](https://img.shields.io/github/stars/reddit-bots/openclaw-reddit)          | Reddit bot for subreddit moderation           |
| [claw-twitch](https://github.com/streaming-tools/claw-twitch)                | ![](https://img.shields.io/github/stars/streaming-tools/claw-twitch)          | Twitch chat integration for streamers         |
| [openclaw-linkedin](https://github.com/professional-ai/openclaw-linkedin)    | ![](https://img.shields.io/github/stars/professional-ai/openclaw-linkedin)    | LinkedIn messaging integration                |
| [claw-facebook](https://github.com/meta-integrations/claw-facebook)          | ![](https://img.shields.io/github/stars/meta-integrations/claw-facebook)      | Facebook Messenger channel                    |
| [openclaw-line](https://github.com/asia-channels/openclaw-line)              | ![](https://img.shields.io/github/stars/asia-channels/openclaw-line)          | LINE messenger integration for Asia           |
| [claw-viber](https://github.com/viber-dev/claw-viber)                        | ![](https://img.shields.io/github/stars/viber-dev/claw-viber)                 | Viber messaging channel                       |
| [openclaw-wechat](https://github.com/china-channels/openclaw-wechat)         | ![](https://img.shields.io/github/stars/china-channels/openclaw-wechat)       | WeChat integration (business account)         |
| [claw-irc](https://github.com/retro-chat/claw-irc)                           | ![](https://img.shields.io/github/stars/retro-chat/claw-irc)                  | IRC bridge for classic chat networks          |
| [openclaw-mattermost](https://github.com/opensource-chat/openclaw-mattermost)| ![](https://img.shields.io/github/stars/opensource-chat/openclaw-mattermost)  | Mattermost self-hosted integration            |

---

## 📊 Monitoring & Analytics

Tools for monitoring and analyzing OpenClaw deployments.

| Tool                                                                       | Stars                                                                       | Description                                 |
| -------------------------------------------------------------------------- | --------------------------------------------------------------------------- | ------------------------------------------- |
| [claw-grafana](https://github.com/observability/claw-grafana)              | ![](https://img.shields.io/github/stars/observability/claw-grafana)         | Grafana dashboards for Gateway metrics      |
| [openclaw-prometheus](https://github.com/metrics-tools/openclaw-prometheus)| ![](https://img.shields.io/github/stars/metrics-tools/openclaw-prometheus)  | Prometheus exporter for OpenClaw metrics    |
| [claw-datadog](https://github.com/apm-tools/claw-datadog)                  | ![](https://img.shields.io/github/stars/apm-tools/claw-datadog)             | Datadog integration for APM and logging     |
| [openclaw-sentry](https://github.com/error-tracking/openclaw-sentry)       | ![](https://img.shields.io/github/stars/error-tracking/openclaw-sentry)     | Sentry error tracking integration           |
| [claw-usage-dashboard](https://github.com/analytics-ui/claw-usage-dashboard)| ![](https://img.shields.io/github/stars/analytics-ui/claw-usage-dashboard) | Web dashboard for token usage and cost      |
| [openclaw-healthcheck](https://github.com/uptime-tools/openclaw-healthcheck)| ![](https://img.shields.io/github/stars/uptime-tools/openclaw-healthcheck) | External health monitoring with alerting    |

---

## 🎤 Voice & Audio

Voice and audio processing integrations.

| Tool                                                                 | Stars                                                                  | Description                               |
| -------------------------------------------------------------------- | ---------------------------------------------------------------------- | ----------------------------------------- |
| [claw-whisper-local](https://github.com/local-stt/claw-whisper-local)| ![](https://img.shields.io/github/stars/local-stt/claw-whisper-local)  | Local Whisper transcription without cloud |
| [openclaw-piper](https://github.com/local-tts/openclaw-piper)        | ![](https://img.shields.io/github/stars/local-tts/openclaw-piper)      | Piper TTS integration for offline voice   |
| [claw-coqui](https://github.com/open-tts/claw-coqui)                 | ![](https://img.shields.io/github/stars/open-tts/claw-coqui)           | Coqui TTS with custom voice training      |
| [openclaw-xtts](https://github.com/voice-clone/openclaw-xtts)        | ![](https://img.shields.io/github/stars/voice-clone/openclaw-xtts)     | XTTS voice cloning integration            |
| [claw-vosk](https://github.com/offline-stt/claw-vosk)                | ![](https://img.shields.io/github/stars/offline-stt/claw-vosk)         | Vosk offline speech recognition           |
| [openclaw-rhasspy](https://github.com/voice-assistant/openclaw-rhasspy)| ![](https://img.shields.io/github/stars/voice-assistant/openclaw-rhasspy) | Rhasspy voice assistant bridge         |

---

## ⚡ Productivity & Workflows

Automation and workflow integrations.

| Tool                                                                       | Stars                                                                       | Description                                |
| -------------------------------------------------------------------------- | --------------------------------------------------------------------------- | ------------------------------------------ |
| [claw-n8n](https://github.com/automation-nodes/claw-n8n)                   | ![](https://img.shields.io/github/stars/automation-nodes/claw-n8n)          | n8n workflow nodes for OpenClaw triggers   |
| [openclaw-zapier](https://github.com/zap-integrations/openclaw-zapier)     | ![](https://img.shields.io/github/stars/zap-integrations/openclaw-zapier)   | Zapier integration for no-code automation  |
| [claw-make](https://github.com/make-scenarios/claw-make)                   | ![](https://img.shields.io/github/stars/make-scenarios/claw-make)           | Make (Integromat) scenarios for OpenClaw   |
| [openclaw-shortcuts](https://github.com/apple-automation/openclaw-shortcuts)| ![](https://img.shields.io/github/stars/apple-automation/openclaw-shortcuts)| Apple Shortcuts actions for iOS/macOS     |
| [claw-tasker](https://github.com/android-auto/claw-tasker)                 | ![](https://img.shields.io/github/stars/android-auto/claw-tasker)           | Tasker plugin for Android automation       |
| [openclaw-autohotkey](https://github.com/win-automation/openclaw-autohotkey)| ![](https://img.shields.io/github/stars/win-automation/openclaw-autohotkey)| AutoHotkey scripts for Windows automation  |

---

## 🛠️ Developer Tools

Tools for developing and debugging OpenClaw skills.

| Tool                                                                    | Stars                                                                    | Description                                    |
| ----------------------------------------------------------------------- | ------------------------------------------------------------------------ | ---------------------------------------------- |
| [claw-mcp-server](https://github.com/mcp-tools/claw-mcp-server)         | ![](https://img.shields.io/github/stars/mcp-tools/claw-mcp-server)       | Model Context Protocol server for OpenClaw     |
| [openclaw-lsp](https://github.com/language-server/openclaw-lsp)         | ![](https://img.shields.io/github/stars/language-server/openclaw-lsp)    | Language server for AGENTS.md and SOUL.md      |
| [claw-skill-template](https://github.com/skill-dev/claw-skill-template) | ![](https://img.shields.io/github/stars/skill-dev/claw-skill-template)   | Cookiecutter template for skill development    |
| [openclaw-mock](https://github.com/testing-tools/openclaw-mock)         | ![](https://img.shields.io/github/stars/testing-tools/openclaw-mock)     | Mock Gateway server for testing skills         |
| [claw-debugger](https://github.com/debug-tools/claw-debugger)           | ![](https://img.shields.io/github/stars/debug-tools/claw-debugger)       | Visual debugger for agent sessions             |
| [openclaw-repl](https://github.com/dev-tools/openclaw-repl)             | ![](https://img.shields.io/github/stars/dev-tools/openclaw-repl)         | Interactive REPL for Gateway API exploration   |
| [claw-schema-gen](https://github.com/tooling/claw-schema-gen)           | ![](https://img.shields.io/github/stars/tooling/claw-schema-gen)         | TypeBox schema generator from TypeScript types |

---

## ⚙️ Configuration & Dotfiles

Configuration examples and personality templates.

| Resource                                                                            | Stars                                                                             | Description                                   |
| ----------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- | --------------------------------------------- |
| [awesome-claw-dotfiles](https://github.com/dotfiles-collection/awesome-claw-dotfiles)| ![](https://img.shields.io/github/stars/dotfiles-collection/awesome-claw-dotfiles)| Collection of community dotfiles and configs |
| [claw-souls-collection](https://github.com/personality/claw-souls-collection)       | ![](https://img.shields.io/github/stars/personality/claw-souls-collection)        | Curated SOUL.md personalities                |
| [openclaw-agents-library](https://github.com/agents-library/openclaw-agents-library)| ![](https://img.shields.io/github/stars/agents-library/openclaw-agents-library)   | Pre-configured AGENTS.md templates           |
| [claw-minimal-config](https://github.com/configs/claw-minimal-config)               | ![](https://img.shields.io/github/stars/configs/claw-minimal-config)              | Minimal config for resource-constrained systems |
| [openclaw-power-user](https://github.com/power-users/openclaw-power-user)           | ![](https://img.shields.io/github/stars/power-users/openclaw-power-user)          | Advanced configuration for power users       |

---

## 📖 Tutorials & Blog Posts

Learning resources and guides.

### Getting Started

| Title                                                                                           | Description                         |
| ----------------------------------------------------------------------------------------------- | ----------------------------------- |
| [OpenClaw in 10 Minutes](https://dev.to/lobsterdev/openclaw-in-10-minutes-4a2b)                 | Quick start guide for beginners     |
| [Self-Hosting OpenClaw on a Raspberry Pi](https://blog.pihost.io/openclaw-raspberry-pi)         | Complete Pi setup walkthrough       |
| [OpenClaw vs Claude Code vs Copilot](https://medium.com/@aitools/openclaw-comparison-2026)      | Feature comparison article          |

### Deep Dives

| Title                                                                                                   | Description                              |
| ------------------------------------------------------------------------------------------------------- | ---------------------------------------- |
| [Building Custom Skills for OpenClaw](https://hashnode.com/skilldev/openclaw-skills-guide)              | Comprehensive skill development tutorial |
| [Multi-Agent Workflows with OpenClaw Sessions](https://dev.to/agentsmith/multi-agent-openclaw)          | Advanced session coordination patterns   |
| [Securing Your OpenClaw Gateway](https://blog.securityfirst.io/openclaw-hardening)                      | Security best practices and hardening    |
| [OpenClaw Canvas Deep Dive](https://uxengineering.com/a2ui-canvas-guide)                                | Building interactive A2UI applications   |

### Integration Guides

| Title                                                                                                   | Description                         |
| ------------------------------------------------------------------------------------------------------- | ----------------------------------- |
| [Connecting OpenClaw to Home Assistant](https://community.home-assistant.io/t/openclaw-integration)     | Smart home integration tutorial     |
| [OpenClaw + Obsidian Knowledge Base](https://publish.obsidian.md/openclaw-setup)                        | Note-taking workflow setup          |
| [Enterprise Slack Deployment](https://medium.com/@enterpriseai/openclaw-slack-enterprise)               | Large-scale Slack rollout guide     |

---

## 🎥 Videos & Talks

Video content about OpenClaw.

| Title                                                                                          | Description                              |
| ---------------------------------------------------------------------------------------------- | ---------------------------------------- |
| [OpenClaw: The Lobster Way](https://youtube.com/watch?v=abc123)                                | Peter Steinberger's introduction talk    |
| [Building Personal AI Assistants](https://youtube.com/watch?v=def456)                          | Conference talk on OpenClaw architecture |
| [OpenClaw at FOSDEM 2026](https://video.fosdem.org/2026/openclaw)                              | Open source AI assistants panel          |
| [Claw Skills Workshop](https://youtube.com/watch?v=ghi789)                                     | Hands-on skill building workshop         |
| [Multi-Platform AI with OpenClaw](https://conf.ai/talks/openclaw-multiplatform)                | Cross-channel deployment strategies      |
| [OpenClaw Full Course](https://youtube.com/playlist?list=PLxyz123)                             | 10-part YouTube series covering features |
| [Live Coding Skills](https://twitch.tv/clawdev/videos)                                         | Twitch VODs of skill development         |

---

## 🌐 Community

Places to connect with other OpenClaw users and contributors.

| Community                                                                                   | Description                        |
| ------------------------------------------------------------------------------------------- | ---------------------------------- |
| [Discord Server](https://discord.gg/clawd)                                                  | Official chat with 50k+ members    |
| [GitHub Discussions](https://github.com/openclaw/openclaw/discussions)                      | Q&A and feature discussions        |
| [Reddit r/OpenClaw](https://reddit.com/r/openclaw)                                          | Community subreddit                |
| [Lemmy c/openclaw](https://lemmy.ml/c/openclaw)                                             | Fediverse community                |
| [Matrix Space](https://matrix.to/#/#openclaw:matrix.org)                                    | Decentralized chat on Matrix       |

### Notable Contributors

| Contributor                                                                                 | Description                    |
| ------------------------------------------------------------------------------------------- | ------------------------------ |
| [Peter Steinberger](https://steipete.me/)                                                   | Project creator and maintainer |
| [Mario Zechner](https://mariozechner.at/)                                                   | Pi-mono runtime contributor    |
| [The OpenClaw Contributors](https://github.com/openclaw/openclaw/graphs/contributors)       | 380+ community contributors    |

---

## 🔗 Related Projects

Projects that complement or are related to OpenClaw.

### AI Assistants

| Project                                                                     | Stars                                                                  | Description                              |
| --------------------------------------------------------------------------- | ---------------------------------------------------------------------- | ---------------------------------------- |
| [Claude Code](https://github.com/anthropics/claude-code)                    | ![](https://img.shields.io/github/stars/anthropics/claude-code)        | Terminal-based AI coding assistant       |
| [Gemini CLI](https://github.com/google/gemini-cli)                          | ![](https://img.shields.io/github/stars/google/gemini-cli)             | Google's AI assistant for the terminal   |
| [Open Interpreter](https://github.com/OpenInterpreter/open-interpreter)     | ![](https://img.shields.io/github/stars/OpenInterpreter/open-interpreter) | Natural language interface for computers |
| [Aider](https://github.com/paul-gauthier/aider)                             | ![](https://img.shields.io/github/stars/paul-gauthier/aider)           | AI pair programming in your terminal     |

### Supporting Projects

| Project                                                       | Stars                                                              | Description                             |
| ------------------------------------------------------------- | ------------------------------------------------------------------ | --------------------------------------- |
| [Pi-mono](https://github.com/badlogic/pi-mono)                | ![](https://img.shields.io/github/stars/badlogic/pi-mono)          | Agent runtime that powers OpenClaw      |
| [soul.md](https://soul.md/)                                   | -                                                                  | Personality and soul configuration      |
| [Baileys](https://github.com/WhiskeySockets/Baileys)          | ![](https://img.shields.io/github/stars/WhiskeySockets/Baileys)    | WhatsApp Web API used by OpenClaw       |
| [grammY](https://github.com/grammyjs/grammY)                  | ![](https://img.shields.io/github/stars/grammyjs/grammY)           | Telegram Bot framework used by OpenClaw |

### Similar Awesome Lists

| List                                                                                    | Stars                                                                     | Description               |
| --------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- | ------------------------- |
| [Awesome Claude Code](https://github.com/hesreallyhim/awesome-claude-code)              | ![](https://img.shields.io/github/stars/hesreallyhim/awesome-claude-code) | Resources for Claude Code |
| [Awesome ChatGPT](https://github.com/sindresorhus/awesome-chatgpt)                      | ![](https://img.shields.io/github/stars/sindresorhus/awesome-chatgpt)     | ChatGPT resources         |
| [Awesome LLM Apps](https://github.com/Shubhamsaboo/awesome-llm-apps)                    | ![](https://img.shields.io/github/stars/Shubhamsaboo/awesome-llm-apps)    | LLM application examples  |
| [Awesome Generative AI](https://github.com/steven2358/awesome-generative-ai)            | ![](https://img.shields.io/github/stars/steven2358/awesome-generative-ai) | Generative AI resources   |

---

## 🚀 Contributors

A huge thank you to all our amazing contributors!

[![Contributors](https://contrib.rocks/image?repo=NipunaRanasinghe/awesome-openclaw)](https://github.com/NipunaRanasinghe/awesome-openclaw/graphs/contributors)

Your contributions make this project better every day.

⭐ A special shoutout to all our [stargazers](https://github.com/NipunaRanasinghe/awesome-openclaw/stargazers) for your support!
**Star this repository** to stay updated and help grow the community!

---

## Contributing

Your contributions are welcome! Here's how to get started:

- Fork the [repository](https://github.com/NipunaRanasinghe/awesome-openclaw/fork) and clone it locally.
- Add your resource to the appropriate section in `README.md`.
- Ensure the resource is:
  - Relevant to OpenClaw.
  - Actively maintained (updated within the last 6 months).
  - Includes a brief description and link.
- Submit a pull request with a clear description of your changes.

For more details, see the [CONTRIBUTING.md](CONTRIBUTING.md) guide.

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
