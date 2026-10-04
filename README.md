# Awesome-Command-Line-Shell-Scripting

# Awesome-Command-Line-Shell-Scripting

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Shell Interpreters, Scripting Languages & Terminal Productivity*
**Last updated: October 2026**

This repository tracks notable **commercial shell products** and **open-source projects** for **Command-Line Shell & Scripting**. These tools help developers and system administrators automate tasks, manage systems, and build powerful command-line workflows.

**Examples** include Microsoft PowerShell, Bash, Zsh, Fish Shell, KornShell, tcsh, Dash, Nushell, Oil Shell, and PowerShell Core (the category leaders).

**Open-source emphasis**: Shells are **overwhelmingly open-source** — Bash, Zsh, Fish, Nushell, and virtually every shell interpreter are free software . **Nushell** brings a modern, structured approach with typed pipelines and clean error messages . **Bash** remains the universal default on Linux and macOS , while **Zsh** and **Fish** offer enhanced interactive features. This section documents these production-grade solutions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## 📖 Table of Contents

- [☁️ Commercial Products](#-commercial-products)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚠️ Disclaimer](#-disclaimer)

## ☁️ Commercial Products

> **📊 Market Context**: The shell scripting market is **not a commercial market** — shells are **free, open-source tools** distributed with operating systems or available for download at no cost. Microsoft's PowerShell is the closest to a "vendor-supported" shell, but even PowerShell Core (the cross-platform version) is **open-source under the MIT License** . There is **no SaaS tier, no per-user pricing, and no commercial licensing** for shells themselves. The commercial value lies in **support contracts** (Red Hat for Bash), **training and certification** (Microsoft PowerShell certifications), and **enterprise distributions** (Ubuntu, RHEL) that bundle shells with paid support. No vendor holds a proprietary position.

| Product | Description | Pricing | Free Tier Limits | Company Size |
|---------|-------------|---------|------------------|--------------|
| **[Microsoft PowerShell](https://microsoft.com/powershell)** | Cross-platform task automation and configuration management framework. Consists of a command-line shell, scripting language, and configuration management framework. **PowerShell 7.6** (March 2026) is the latest LTS release based on .NET 10 with 3-year support . | **Free** — PowerShell 7.x is open-source (MIT License). Windows PowerShell 5.1 is bundled with Windows. | **Unlimited** — no usage limits, no time limits, no feature restrictions. PowerShell is free software. | **~$281B revenue (Microsoft FY2025)** |
| **[Windows PowerShell 5.1](https://microsoft.com/powershell)** | The legacy Windows-only version bundled with Windows 10/11. Still supported for existing scripts. | **Free** — bundled with Windows. | **Unlimited** — no restrictions. | **~$281B revenue (Microsoft FY2025)** |

## 🔓 Open-Source GitHub Projects

Sorted by star count (descending). Star badge links to each repo's stargazers page.

| Repo | Description | Stars |
|---|---|---|
| **[Bash](https://git.savannah.gnu.org/cgit/bash.git)** — **The Bourne-Again SHell.** The default shell on most Linux distributions and macOS. Created by Brian Fox in 1988 for the GNU Project . POSIX-compliant with extensive scripting capabilities, history expansion, and programmable completion. | [![Stars](https://img.shields.io/github/stars/bminor/bash?style=social&color=white)](https://github.com/bminor/bash/stargazers) | ~3,500 |
| **[Zsh](https://github.com/zsh-users/zsh)** — **The powerful interactive shell.** Enhanced features including advanced tab completion, themes, plugins (Oh My Zsh), spelling correction, and shared history across sessions. Default on macOS since Catalina. | [![Stars](https://img.shields.io/github/stars/zsh-users/zsh?style=social&color=white)](https://github.com/zsh-users/zsh/stargazers) | ~3,500 |
| **[Fish Shell](https://github.com/fish-shell/fish-shell)** — **The friendly interactive shell.** Syntax highlighting, autosuggestions, web-based configuration, and sane defaults out of the box. No configuration needed for a great experience . | [![Stars](https://img.shields.io/github/stars/fish-shell/fish-shell?style=social&color=white)](https://github.com/fish-shell/fish-shell/stargazers) | ~10,500 |
| **[Nushell](https://github.com/nushell/nushell)** — **The modern structured shell.** Treats data as structured tables rather than text streams. Pipelines carry structured data, not raw bytes . Written in Rust, cross-platform, with clean error messages and IDE support. **40,000+ stars** as of 2026 . | [![Stars](https://img.shields.io/github/stars/nushell/nushell?style=social&color=white)](https://github.com/nushell/nushell/stargazers) | ~40,000 |
| **[PowerShell](https://github.com/PowerShell/PowerShell)** — **Microsoft's cross-platform shell.** Object-oriented pipelines, .NET integration, and extensive module ecosystem. **PowerShell 7.6** is the latest LTS on .NET 10 . MIT License. | [![Stars](https://img.shields.io/github/stars/PowerShell/PowerShell?style=social&color=white)](https://github.com/PowerShell/PowerShell/stargazers) | ~46,000 |
| **[Xonsh](https://github.com/xonsh/xonsh)** — **Python-powered shell.** Combines Python syntax with shell commands. Use Python for complex logic while still running shell commands natively . | [![Stars](https://img.shields.io/github/stars/xonsh/xonsh?style=social&color=white)](https://github.com/xonsh/xonsh/stargazers) | ~8,000 |
| **[Oil Shell](https://github.com/oils-for-unix/oils)** — **Bash-compatible shell with modern language features.** OSH runs existing Bash scripts; YSH adds a new modern shell language with typed data and structured error handling . | [![Stars](https://img.shields.io/github/stars/oils-for-unix/oils?style=social&color=white)](https://github.com/oils-for-unix/oils/stargazers) | ~3,000 |
| **[Elvish](https://github.com/elves/elvish)** — **Friendly, expressive shell.** Features anonymous functions and data structures. Written in Go, cross-platform . | [![Stars](https://img.shields.io/github/stars/elves/elvish?style=social&color=white)](https://github.com/elves/elvish/stargazers) | ~6,000 |
| **[Murex](https://github.com/lmorg/murex)** — **Smarter shell and scripting environment.** Advanced features designed for usability, safety, and productivity. Smarter DevOps tooling . | [![Stars](https://img.shields.io/github/stars/lmorg/murex?style=social&color=white)](https://github.com/lmorg/murex/stargazers) | ~2,000 |
| **[KornShell (ksh93)](https://github.com/ksh93/ksh)** — **The Korn Shell.** POSIX-compliant, compatible with Bourne shell, adds advanced scripting features including associative arrays and floating-point arithmetic . | [![Stars](https://img.shields.io/github/stars/ksh93/ksh?style=social&color=white)](https://github.com/ksh93/ksh/stargazers) | ~600 |
| **[tcsh](https://github.com/tcsh-org/tcsh)** — **C shell with file name completion.** Descended from Bill Joy's csh, adds command-line editing and completion . | [![Stars](https://img.shields.io/github/stars/tcsh-org/tcsh?style=social&color=white)](https://github.com/tcsh-org/tcsh/stargazers) | ~400 |
| **[Dash](https://git.kernel.org/pub/scm/utils/dash/dash.git)** — **The Debian Almquist Shell.** Fast, POSIX-compliant, minimal. Used as `/bin/sh` on Debian/Ubuntu for faster boot times. | [![Stars](https://img.shields.io/github/stars/dash-shell/dash?style=social&color=white)](https://github.com/dash-shell/dash/stargazers) | ~200 |
| **[NYAGOS](https://github.com/nyaosorg/nyagos)** — **Nihongo Yet Another GOing Shell.** Bash-like editing with Windows path integration. Lua scripting, predictive completion, Unicode support . | [![Stars](https://img.shields.io/github/stars/nyaosorg/nyagos?style=social&color=white)](https://github.com/nyaosorg/nyagos/stargazers) | ~800 |
| **[gosh](https://github.com/drewwalton19216801/gosh)** — **Cross-platform shell in Go.** sh-style scripting, Unix and Windows command names, works identically on Windows, macOS, and Linux . | [![Stars](https://img.shields.io/github/stars/drewwalton19216801/gosh?style=social&color=white)](https://github.com/drewwalton19216801/gosh/stargazers) | ~100 |

**Additional open-source options worth exploring:**

| Repo | Description |
|---|---|
| **[Rad](https://github.com/amterp/rad)** — Python-like scripting with CLI essentials built-in. Declarative arguments, JSON processing, HTTP requests . | [![Stars](https://img.shields.io/github/stars/amterp/rad?style=social&color=white)](https://github.com/amterp/rad/stargazers) |
| **[pyesh](https://github.com/eduardoagarcia/pyesh)** — Python Expanded Shell. Cross-platform, Python-oriented interactive shell with typed pipelines . | [![Stars](https://img.shields.io/github/stars/eduardoagarcia/pyesh?style=social&color=white)](https://github.com/eduardoagarcia/pyesh/stargazers) |
| **[bats-core](https://github.com/bats-core/bats-core)** — Bash Automated Testing System. Test framework for Bash scripts . | [![Stars](https://img.shields.io/github/stars/bats-core/bats-core?style=social&color=white)](https://github.com/bats-core/bats-core/stargazers) |
| **[Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh)** — Community-driven framework for managing Zsh configuration. 300+ plugins, 140+ themes. | [![Stars](https://img.shields.io/github/stars/ohmyzsh/ohmyzsh?style=social&color=white)](https://github.com/ohmyzsh/ohmyzsh/stargazers) |

## 🤝 How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's commercial or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Shells execute arbitrary code with the user's privileges; ensure scripts are reviewed and trusted before running.
- **Open-source reality**: Shells are **overwhelmingly open-source** — Bash, Zsh, Fish, Nushell, PowerShell 7.x, and virtually every shell interpreter are **free software** . The "Commercial Products" section is essentially empty because **there are no commercial shells** — even Microsoft's PowerShell 7.x is MIT-licensed open source . The commercial value lies in **support, training, and enterprise distributions**, not the shell itself. The open-source path is **universally viable** for shell scripting.

---

**Made for developers, system administrators, DevOps engineers, and command-line enthusiasts.**
Let's make command-line shell scripting more open, powerful, and productive.
