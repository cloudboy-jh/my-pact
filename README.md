<p align="center">
</p>

<h1 align="center">my-pact</h1>

<p align="center">
  <strong>My portable dev identity — managed by <a href="https://github.com/cloudboy-jh/pact">Pact</a></strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/shell-oh--my--posh-blue?style=flat-square&logo=windowsterminal" alt="oh-my-posh"/>
  <img src="https://img.shields.io/badge/editor-Zed-green?style=flat-square&logo=zedindustries" alt="Zed"/>
  <img src="https://img.shields.io/badge/runtime-Bun-orange?style=flat-square&logo=bun" alt="Bun"/>
  <img src="https://img.shields.io/badge/ai-Claude-blueviolet?style=flat-square&logo=anthropic" alt="Claude"/>
  <img src="https://img.shields.io/badge/local--ai-Ollama-white?style=flat-square&logo=ollama" alt="Ollama"/>
  <img src="https://img.shields.io/badge/platform-Windows%20%7C%20macOS-lightgrey?style=flat-square" alt="Platform"/>
</p>

---

## About Me

I'm **Jack** — an AI-Centric Product Engineer who builds developer tools and ships focused, lightweight software. I work at [Zyris](https://zyris.com) building complex data infrastructure, and in my spare time I create terminal-native utilities that solve real problems without the bloat.

### Philosophy

**Build for independence, optimize for optionality.**

I gravitate toward lightweight tools over bloated platforms, open source over vendor lock-in, and terminal-native over Electron apps. My approach: minimize dependencies, maximize portability, maintain control. Whether that's a codebase, a dev environment, or a career — stay light, stay free, ship things that last.

### What I Build

| Project | Description |
|---------|-------------|
| [**Pact**](https://github.com/cloudboy-jh/pact) | Cross-platform dev environment manager |
| [**Churn**](https://github.com/cloudboy-jh/churn) | Terminal-native code analysis with multi-model AI |
| [**Annotr**](https://github.com/cloudboy-jh/annotr) | Automated code commenting via tree-sitter + LLMs |

---

## What's In My Pact

This repo contains my complete portable dev identity. One config to rule them all.

### Shell

| Component | Choice |
|-----------|--------|
| Prompt | [oh-my-posh](https://ohmyposh.dev/) with [capr4n](https://github.com/JanDeDobbeleer/oh-my-posh/blob/main/themes/capr4n.omp.json) theme |
| Navigation | [zoxide](https://github.com/ajeetdsouza/zoxide) |
| Font | JetBrainsMono Nerd Font / MesloLGS Nerd Font |

### Editor

| Component | Choice |
|-----------|--------|
| Primary | [Zed](https://zed.dev) |
| Theme | Catppuccin Frappé (Blur) [Heavy] |
| Keymap | VSCode base |
| Icons | Catppuccin Mocha |

### Git

| Setting | Value |
|---------|-------|
| User | `cloudboy-jh` |
| Default Branch | `master` |
| LFS | Enabled |

### LLM Stack

**Providers**
- Claude (primary)
- OpenAI
- Gemini
- Grok

**Coding Agents**
- [Claude Code](https://docs.anthropic.com/en/docs/claude-code)
- [OpenCode](https://github.com/opencode-ai/opencode)
- [Droid](https://github.com/droidhq/droid)

**Models**
- Claude Opus / Sonnet — heavy lifting
- Grok — quick chat
- Local via Ollama: `qwen-coder`, `mistral`, `kimi`

### CLI Tools

**Package Managers & Runtimes**
- [Bun](https://bun.sh) — fast JS runtime
- Node.js

**Dev Tools**
- [lazygit](https://github.com/jesseduffield/lazygit) — terminal git UI
- [oh-my-posh](https://ohmyposh.dev/) — prompt theming
- [zoxide](https://github.com/ajeetdsouza/zoxide) — smarter cd

**My Tools**
- [Pact](https://github.com/cloudboy-jh/pact) — this very config system
- [Churn](https://github.com/cloudboy-jh/churn) — code analysis
- [Annotr](https://github.com/cloudboy-jh/annotr) — code commenting

### App Shortcuts (Windows)

Quick launch functions in my PowerShell profile:

```powershell
brave     # Brave Browser
cursor    # Cursor Editor  
spotify   # Spotify
steam     # Steam
files     # File Explorer
discord   # Discord
```

### Utility Functions

```powershell
killport <port>   # Kill process on a specific port
```

---

## Quick Start

```bash
# Clone this repo
git clone https://github.com/cloudboy-jh/my-pact.git

# Or when Pact CLI is ready:
pact run jackhortonlol
```

---

## Structure

```
my-pact/
├── pact.json           # Main config file
├── shell/              # Shell configs (zsh, PowerShell)
├── cli/                # CLI tool configs
├── docs/               # Documentation
└── web/                # Web dashboard (coming soon)
```

---

## Connect

- GitHub: [@cloudboy-jh](https://github.com/cloudboy-jh)
- Building in public, shipping solo.

---

<p align="center">
  <sub>Stay light. Stay free. Ship things that last.</sub>
</p>
