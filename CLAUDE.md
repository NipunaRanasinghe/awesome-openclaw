# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## About This Repository

This is an **awesome list** — a curated Markdown-only repository of OpenClaw resources. There is no build system, package.json, or source code. The entire content is `README.md`.

## Linting

The README is validated by `awesome-lint` on every push/PR:

```bash
npx awesome-lint@2.2.3
```

Links are checked daily via a scheduled `lychee` workflow.

## Contributing Guidelines

All changes happen in `README.md`. Key rules from `CONTRIBUTING.md`:

- Add items as new rows in the appropriate Markdown table, matching existing column order and formatting.
- Keep descriptions short, simple, and descriptive — match the existing punctuation style (no trailing periods).
- Each item must be related to OpenClaw and actively maintained.
- Make one PR per suggestion.

### Table format

Tables use this structure (pipe-aligned, no trailing whitespace):

```markdown
| [Project Name](https://link)  | Brief description without trailing period  |
```

### Sections in README.md

1. **Official Resources** — official OpenClaw team projects
2. **Community** — forums and chat communities
3. **Community Tools** — third-party tools and utilities
4. **Channel Plugins** — npm channel integrations
5. **Localization & Forks** — regional adaptations
6. **Related Projects** — complementary projects (AI Assistants / Supporting Projects)
