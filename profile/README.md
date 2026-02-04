<p align="center">
  <img src="https://raw.githubusercontent.com/clash-sh/clash/main/demos/logo.png" alt="Clash Logo" width="120"/>
</p>

<h1 align="center">Clash</h1>

<p align="center">
  <strong>Manage merge conflicts across git worktrees for parallel AI coding agents</strong>
</p>

<p align="center">
  <a href="https://github.com/clash-sh/clash">Main Repository</a> •
  <a href="https://clash.sh">Website</a> •
  <a href="https://github.com/clash-sh/clash#installation">Installation</a> •
  <a href="https://github.com/clash-sh/clash#quick-start">Quick Start</a>
</p>

---

Clash is a CLI tool that detects merge conflicts **between all worktree pairs** during development, helping developers and AI agents work in parallel without conflicts.

## Quick Install

```bash
# macOS/Linux
curl -fsSL https://clash.sh/install.sh | sh

# Homebrew
brew install clash-sh/tap/clash

# Cargo
cargo install clash-sh
```

## Why Clash?

When running multiple AI coding agents (Claude Code, Cursor, etc.) in parallel worktrees, conflicts only surface at merge time. Clash detects them **in real-time** so you can adapt early.

```bash
# Check conflicts across all worktrees
clash status

# Monitor in real-time
clash watch

# JSON output for automation
clash status --json
```

## Features

✅ Real-time conflict detection across all worktrees
✅ Beautiful conflict matrix visualization
✅ JSON output for CI/CD and AI agents
✅ 100% read-only (never modifies your repository)
✅ Fast: Status checks < 2 seconds

## Learn More

Check out the [full documentation](https://github.com/clash-sh/clash) to get started!
