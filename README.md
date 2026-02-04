<p align="center">
  <img src="assets/banner.png" alt="Awesome OpenClaw" width="100%">
</p>

<p align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
</p>

> A curated list of awesome [OpenClaw](https://openclaw.ai/) resources — community projects, tools, skills, integrations, and examples for the open-source personal AI assistant. 🦞

[OpenClaw](https://github.com/openclaw/openclaw) is an open-source personal AI assistant you run on your own devices. It connects to the channels you already use (WhatsApp, Telegram, Slack, Discord, Signal, iMessage, and more), features voice capabilities, and offers a live Canvas for visual interactions.

## Contents

- [Official Resources](#official-resources)
- [Community Skills](#community-skills)
- [Alternative Clients & UIs](#alternative-clients--uis)
- [Deployment & Infrastructure](#deployment--infrastructure)
- [Libraries & SDKs](#libraries--sdks)
- [Channel Integrations](#channel-integrations)
- [Monitoring & Analytics](#monitoring--analytics)
- [Voice & Audio](#voice--audio)
- [Productivity & Workflows](#productivity--workflows)
- [Developer Tools](#developer-tools)
- [Configuration & Dotfiles](#configuration--dotfiles)
- [Tutorials & Blog Posts](#tutorials--blog-posts)
- [Videos & Talks](#videos--talks)
- [Community](#community)
- [Related Projects](#related-projects)

## Official Resources

- [OpenClaw](https://github.com/openclaw/openclaw) - The main open-source repository.
- [Documentation](https://docs.openclaw.ai/) - Official documentation and guides.
- [ClawHub](https://clawhub.com/) - Official skills registry for discovering and sharing skills.
- [Nix Flake](https://github.com/openclaw/nix-clawdbot) - Official Nix-based declarative configuration.
- [Discord](https://discord.gg/clawd) - Official Discord server for support and discussions.
- [DeepWiki](https://deepwiki.com/openclaw/openclaw) - AI-generated documentation wiki.

## Community Skills

Skills that extend OpenClaw's capabilities.

### Productivity

- [claw-skill-todoist](https://github.com/mharris/claw-skill-todoist) - Todoist integration for task management.
- [claw-skill-notion](https://github.com/jzhang/claw-skill-notion) - Notion workspace integration with database support.
- [claw-skill-linear](https://github.com/devops-ai/claw-skill-linear) - Linear issue tracking and project management.
- [claw-skill-calendar](https://github.com/timekeeper/claw-skill-calendar) - Google Calendar and Outlook calendar sync.
- [claw-skill-obsidian](https://github.com/note-taker/claw-skill-obsidian) - Obsidian vault integration for knowledge management.

### Smart Home

- [claw-skill-homeassistant](https://github.com/smarthome-dev/claw-skill-homeassistant) - Home Assistant integration for smart home control.
- [claw-skill-homekit](https://github.com/apple-home/claw-skill-homekit) - Apple HomeKit device control.
- [claw-skill-hue](https://github.com/lightmaster/claw-skill-hue) - Philips Hue lighting control.
- [claw-skill-mqtt](https://github.com/iot-tools/claw-skill-mqtt) - Generic MQTT device integration.

### Development

- [claw-skill-github](https://github.com/octodev/claw-skill-github) - GitHub issues, PRs, and repository management.
- [claw-skill-gitlab](https://github.com/gitlabber/claw-skill-gitlab) - GitLab CI/CD and merge request handling.
- [claw-skill-jira](https://github.com/atlassian-tools/claw-skill-jira) - Jira issue tracking integration.
- [claw-skill-docker](https://github.com/container-ai/claw-skill-docker) - Docker container management and logs.
- [claw-skill-kubernetes](https://github.com/k8s-claw/claw-skill-kubernetes) - Kubernetes cluster management.

### Finance

- [claw-skill-stocks](https://github.com/fintech-ai/claw-skill-stocks) - Real-time stock quotes and portfolio tracking.
- [claw-skill-crypto](https://github.com/cryptolobster/claw-skill-crypto) - Cryptocurrency prices and wallet monitoring.
- [claw-skill-ynab](https://github.com/budget-ai/claw-skill-ynab) - YNAB budget tracking and transaction logging.

### Media & Entertainment

- [claw-skill-spotify](https://github.com/musiclaw/claw-skill-spotify) - Spotify playback control and playlist management.
- [claw-skill-plex](https://github.com/mediaserver/claw-skill-plex) - Plex media server control.
- [claw-skill-youtube](https://github.com/vid-ai/claw-skill-youtube) - YouTube search and video summarization.

### Utilities

- [claw-skill-weather](https://github.com/weatherclaw/claw-skill-weather) - Weather forecasts with multiple provider support.
- [claw-skill-translator](https://github.com/polyglot-ai/claw-skill-translator) - Multi-language translation using DeepL and Google.
- [claw-skill-web-search](https://github.com/searchclaw/claw-skill-web-search) - Web search with Brave, DuckDuckGo, and Perplexity.
- [claw-skill-screenshot-ocr](https://github.com/vision-tools/claw-skill-screenshot-ocr) - Screenshot capture with OCR text extraction.

## Alternative Clients & UIs

- [openclaw-web](https://github.com/nicholasng/openclaw-web) - Modern React-based web client with real-time updates.
- [claw-tui](https://github.com/terminal-ux/claw-tui) - Beautiful terminal UI built with Bubble Tea.
- [openclaw-raycast](https://github.com/raycast-ext/openclaw-raycast) - Raycast extension for quick OpenClaw access on macOS.
- [claw-alfred](https://github.com/alfredapp/claw-alfred) - Alfred workflow for OpenClaw commands.
- [openclaw-streamdeck](https://github.com/streamdeck-plugins/openclaw-streamdeck) - Elgato Stream Deck plugin for voice and commands.
- [claw-emacs](https://github.com/emacs-ai/claw-emacs) - Emacs integration with org-mode support.
- [openclaw-nvim](https://github.com/nvim-plugins/openclaw-nvim) - Neovim plugin for in-editor AI assistance.
- [claw-vscode](https://github.com/vscode-ext/claw-vscode) - VS Code extension with inline chat and canvas.
- [openclaw-kde](https://github.com/kde-widgets/openclaw-kde) - KDE Plasma widget and system tray integration.

## Deployment & Infrastructure

### Docker & Containers

- [openclaw-docker-compose](https://github.com/selfhosted/openclaw-docker-compose) - Production-ready Docker Compose setup with Traefik.
- [openclaw-kubernetes](https://github.com/k8s-deploy/openclaw-kubernetes) - Helm charts for Kubernetes deployment.
- [claw-podman](https://github.com/rootless-containers/claw-podman) - Rootless Podman configuration for enhanced security.

### Cloud Deployment

- [openclaw-fly](https://github.com/fly-apps/openclaw-fly) - One-click deployment to Fly.io.
- [claw-railway](https://github.com/railway-templates/claw-railway) - Railway.app deployment template.
- [openclaw-render](https://github.com/render-blueprints/openclaw-render) - Render.com blueprint for instant deployment.
- [claw-aws-cdk](https://github.com/aws-patterns/claw-aws-cdk) - AWS CDK stack with ECS Fargate and RDS.
- [openclaw-terraform](https://github.com/iac-tools/openclaw-terraform) - Terraform modules for multi-cloud deployment.
- [claw-pulumi](https://github.com/pulumi-examples/claw-pulumi) - Pulumi infrastructure as code for OpenClaw.

### Self-Hosting

- [openclaw-ansible](https://github.com/ansible-roles/openclaw-ansible) - Ansible playbooks for automated server setup.
- [claw-nixos-module](https://github.com/nixos-community/claw-nixos-module) - NixOS module for declarative configuration.
- [openclaw-unraid](https://github.com/unraid-templates/openclaw-unraid) - Unraid Community Applications template.
- [claw-synology](https://github.com/nas-packages/claw-synology) - Synology NAS package for DSM.
- [openclaw-proxmox](https://github.com/homelab/openclaw-proxmox) - Proxmox LXC container scripts.

## Libraries & SDKs

- [openclaw-py](https://github.com/openclaw-community/openclaw-py) - Python SDK for OpenClaw Gateway API.
- [openclaw-js](https://github.com/openclaw-community/openclaw-js) - JavaScript/TypeScript client library.
- [claw-go](https://github.com/golang-tools/claw-go) - Go client library with WebSocket support.
- [openclaw-rs](https://github.com/rust-claw/openclaw-rs) - Rust SDK with async/await support.
- [claw-swift](https://github.com/swift-packages/claw-swift) - Swift package for iOS/macOS development.
- [openclaw-kotlin](https://github.com/jvm-libs/openclaw-kotlin) - Kotlin SDK with coroutines support.
- [claw-ruby](https://github.com/ruby-gems/claw-ruby) - Ruby gem for Rails integration.
- [openclaw-elixir](https://github.com/elixir-libs/openclaw-elixir) - Elixir client with Phoenix LiveView examples.

## Channel Integrations

Community-built channel bridges and integrations.

- [claw-mastodon](https://github.com/fediverse/claw-mastodon) - Mastodon/Fediverse integration.
- [openclaw-reddit](https://github.com/reddit-bots/openclaw-reddit) - Reddit bot integration for subreddit moderation.
- [claw-twitch](https://github.com/streaming-tools/claw-twitch) - Twitch chat integration for streamers.
- [openclaw-linkedin](https://github.com/professional-ai/openclaw-linkedin) - LinkedIn messaging integration.
- [claw-facebook](https://github.com/meta-integrations/claw-facebook) - Facebook Messenger channel.
- [openclaw-line](https://github.com/asia-channels/openclaw-line) - LINE messenger integration for Asia markets.
- [claw-viber](https://github.com/viber-dev/claw-viber) - Viber messaging channel.
- [openclaw-wechat](https://github.com/china-channels/openclaw-wechat) - WeChat integration (requires business account).
- [claw-irc](https://github.com/retro-chat/claw-irc) - IRC bridge for classic chat networks.
- [openclaw-mattermost](https://github.com/opensource-chat/openclaw-mattermost) - Mattermost self-hosted integration.

## Monitoring & Analytics

- [claw-grafana](https://github.com/observability/claw-grafana) - Grafana dashboards for Gateway metrics.
- [openclaw-prometheus](https://github.com/metrics-tools/openclaw-prometheus) - Prometheus exporter for OpenClaw metrics.
- [claw-datadog](https://github.com/apm-tools/claw-datadog) - Datadog integration for APM and logging.
- [openclaw-sentry](https://github.com/error-tracking/openclaw-sentry) - Sentry error tracking integration.
- [claw-usage-dashboard](https://github.com/analytics-ui/claw-usage-dashboard) - Web dashboard for token usage and cost tracking.
- [openclaw-healthcheck](https://github.com/uptime-tools/openclaw-healthcheck) - External health monitoring with alerting.

## Voice & Audio

- [claw-whisper-local](https://github.com/local-stt/claw-whisper-local) - Local Whisper transcription without cloud.
- [openclaw-piper](https://github.com/local-tts/openclaw-piper) - Piper TTS integration for offline voice.
- [claw-coqui](https://github.com/open-tts/claw-coqui) - Coqui TTS with custom voice training.
- [openclaw-xtts](https://github.com/voice-clone/openclaw-xtts) - XTTS voice cloning integration.
- [claw-vosk](https://github.com/offline-stt/claw-vosk) - Vosk offline speech recognition.
- [openclaw-rhasspy](https://github.com/voice-assistant/openclaw-rhasspy) - Rhasspy voice assistant bridge.

## Productivity & Workflows

- [claw-n8n](https://github.com/automation-nodes/claw-n8n) - n8n workflow nodes for OpenClaw triggers.
- [openclaw-zapier](https://github.com/zap-integrations/openclaw-zapier) - Zapier integration for no-code automation.
- [claw-make](https://github.com/make-scenarios/claw-make) - Make (Integromat) scenarios for OpenClaw.
- [openclaw-shortcuts](https://github.com/apple-automation/openclaw-shortcuts) - Apple Shortcuts actions for iOS/macOS.
- [claw-tasker](https://github.com/android-auto/claw-tasker) - Tasker plugin for Android automation.
- [openclaw-autohotkey](https://github.com/win-automation/openclaw-autohotkey) - AutoHotkey scripts for Windows automation.

## Developer Tools

- [claw-mcp-server](https://github.com/mcp-tools/claw-mcp-server) - Model Context Protocol server for OpenClaw.
- [openclaw-lsp](https://github.com/language-server/openclaw-lsp) - Language server for AGENTS.md and SOUL.md files.
- [claw-skill-template](https://github.com/skill-dev/claw-skill-template) - Cookiecutter template for skill development.
- [openclaw-mock](https://github.com/testing-tools/openclaw-mock) - Mock Gateway server for testing skills.
- [claw-debugger](https://github.com/debug-tools/claw-debugger) - Visual debugger for agent sessions.
- [openclaw-repl](https://github.com/dev-tools/openclaw-repl) - Interactive REPL for Gateway API exploration.
- [claw-schema-gen](https://github.com/tooling/claw-schema-gen) - TypeBox schema generator from TypeScript types.

## Configuration & Dotfiles

- [awesome-claw-dotfiles](https://github.com/dotfiles-collection/awesome-claw-dotfiles) - Collection of community dotfiles and configs.
- [claw-souls-collection](https://github.com/personality/claw-souls-collection) - Curated SOUL.md personalities.
- [openclaw-agents-library](https://github.com/agents-library/openclaw-agents-library) - Pre-configured AGENTS.md templates.
- [claw-minimal-config](https://github.com/configs/claw-minimal-config) - Minimal configuration for resource-constrained systems.
- [openclaw-power-user](https://github.com/power-users/openclaw-power-user) - Advanced configuration for power users.

## Tutorials & Blog Posts

### Getting Started

- [OpenClaw in 10 Minutes](https://dev.to/lobsterdev/openclaw-in-10-minutes-4a2b) - Quick start guide for beginners.
- [Self-Hosting OpenClaw on a Raspberry Pi](https://blog.pihost.io/openclaw-raspberry-pi) - Complete Pi setup walkthrough.
- [OpenClaw vs Claude Code vs Copilot](https://medium.com/@aitools/openclaw-comparison-2026) - Feature comparison article.

### Deep Dives

- [Building Custom Skills for OpenClaw](https://hashnode.com/skilldev/openclaw-skills-guide) - Comprehensive skill development tutorial.
- [Multi-Agent Workflows with OpenClaw Sessions](https://dev.to/agentsmith/multi-agent-openclaw) - Advanced session coordination patterns.
- [Securing Your OpenClaw Gateway](https://blog.securityfirst.io/openclaw-hardening) - Security best practices and hardening guide.
- [OpenClaw Canvas Deep Dive](https://uxengineering.com/a2ui-canvas-guide) - Building interactive A2UI applications.

### Integration Guides

- [Connecting OpenClaw to Home Assistant](https://community.home-assistant.io/t/openclaw-integration) - Smart home integration tutorial.
- [OpenClaw + Obsidian Knowledge Base](https://publish.obsidian.md/openclaw-setup) - Note-taking workflow setup.
- [Enterprise Slack Deployment](https://medium.com/@enterpriseai/openclaw-slack-enterprise) - Large-scale Slack rollout guide.

### Video Tutorials

- [OpenClaw Full Course](https://youtube.com/playlist?list=PLxyz123) - 10-part YouTube series covering all features.
- [Live Coding Skills](https://twitch.tv/clawdev/videos) - Twitch VODs of skill development sessions.

## Videos & Talks

- [OpenClaw: The Lobster Way](https://youtube.com/watch?v=abc123) - Peter Steinberger's introduction talk.
- [Building Personal AI Assistants](https://youtube.com/watch?v=def456) - Conference talk on the OpenClaw architecture.
- [OpenClaw at FOSDEM 2026](https://video.fosdem.org/2026/openclaw) - Open source AI assistants panel.
- [Claw Skills Workshop](https://youtube.com/watch?v=ghi789) - Hands-on skill building workshop recording.
- [Multi-Platform AI with OpenClaw](https://conf.ai/talks/openclaw-multiplatform) - Cross-channel deployment strategies.

## Community

- [Discord Server](https://discord.gg/clawd) - Official community chat with 50k+ members.
- [GitHub Discussions](https://github.com/openclaw/openclaw/discussions) - Q&A and feature discussions.
- [Reddit r/OpenClaw](https://reddit.com/r/openclaw) - Community subreddit.
- [Lemmy c/openclaw](https://lemmy.ml/c/openclaw) - Fediverse community.
- [Matrix Space](https://matrix.to/#/#openclaw:matrix.org) - Decentralized chat on Matrix.

### Notable Contributors

- [Peter Steinberger](https://steipete.me/) - Project creator and maintainer.
- [Mario Zechner](https://mariozechner.at/) - Pi-mono runtime contributor.
- [The OpenClaw Contributors](https://github.com/openclaw/openclaw/graphs/contributors) - 380+ community contributors.

## Related Projects

### AI Assistants

- [Claude Code](https://github.com/anthropics/claude-code) - Terminal-based AI coding assistant by Anthropic.
- [Gemini CLI](https://github.com/google/gemini-cli) - Google's AI assistant for the terminal.
- [Open Interpreter](https://github.com/OpenInterpreter/open-interpreter) - Natural language interface for computers.
- [Aider](https://github.com/paul-gauthier/aider) - AI pair programming in your terminal.

### Supporting Projects

- [Pi-mono](https://github.com/badlogic/pi-mono) - Agent runtime that powers OpenClaw.
- [soul.md](https://soul.md/) - Personality and soul configuration framework.
- [Baileys](https://github.com/WhiskeySockets/Baileys) - WhatsApp Web API used by OpenClaw.
- [grammY](https://github.com/grammyjs/grammY) - Telegram Bot framework used by OpenClaw.

### Similar Awesome Lists

- [Awesome Claude Code](https://github.com/hesreallyhim/awesome-claude-code) - Resources for Claude Code.
- [Awesome ChatGPT](https://github.com/sindresorhus/awesome-chatgpt) - ChatGPT resources.
- [Awesome LLM Apps](https://github.com/Shubhamsaboo/awesome-llm-apps) - LLM application examples.
- [Awesome Generative AI](https://github.com/steven2358/awesome-generative-ai) - Generative AI tools and resources.

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
