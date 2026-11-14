# Hephaestus-Zero

Independent systems researcher, building **sub-millisecond AI agent developer tools**, **Linux kernel containment systems**, and **adversarial software verification pipelines**.

- Institutional Contact: `326907217+Hephaestus-Zero@users.noreply.github.com`

---

### Open-Source Systems & AI Tooling

- **[`hslice`](https://github.com/Hephaestus-Zero/hslice)** *(C11 · Linux & macOS · AI Agent Tooling)* [![CI](https://github.com/Hephaestus-Zero/hslice/actions/workflows/ci.yml/badge.svg)](https://github.com/Hephaestus-Zero/hslice/actions/workflows/ci.yml) [![Release](https://img.shields.io/github/v/release/Hephaestus-Zero/hslice)](https://github.com/Hephaestus-Zero/hslice/releases/latest)  
  Sub-2ms `mmap` 262k-bucket 3-gram indexer & structural AST code slicer (`hslice`, `hfind`, `hsearch`) for coding agents. Collapses 4–6 sequential `find`/`grep`/`read` tool turns into a single deterministic call (`93–96%` context token reduction on live codebases) across Python, C/C++, Rust, Go, JavaScript/TypeScript, and Java.
  ```bash
  brew install Hephaestus-Zero/tap/hslice && npx skills add Hephaestus-Zero/hslice
  ```

- **[`hshield`](https://github.com/Hephaestus-Zero/hshield)** *(C11 · Linux Kernel Security · GitHub Action)* [![CI](https://github.com/Hephaestus-Zero/hshield/actions/workflows/ci.yml/badge.svg)](https://github.com/Hephaestus-Zero/hshield/actions/workflows/ci.yml) [![Release](https://img.shields.io/github/v/release/Hephaestus-Zero/hshield)](https://github.com/Hephaestus-Zero/hshield/releases/latest)  
  Unprivileged **Landlock LSM** (`ABI v1–v6`) filesystem, TCP port (`--deny-net`, `--allow-tcp-connect`, `hshield agent`), and IPC process sandboxing, coding-agent repository trap & Trojan-Source Unicode auditing (`.mcp.json` / `.claude` hook & bidi detection), `fanotify`/`CN_PROC` runtime execution containment with `AES-256-GCM` forensic quarantine, and zero-extract **Pickle VM (Protocols 0–5) / PyTorch ZIP** static RCE scanning.
  ```bash
  brew install Hephaestus-Zero/tap/hshield && npx skills add Hephaestus-Zero/hshield
  ```

- **[`hveritas`](https://github.com/Hephaestus-Zero/hveritas)** *(Python 3.12 · Adversarial Verification)* [![CI](https://github.com/Hephaestus-Zero/hveritas/actions/workflows/ci.yml/badge.svg)](https://github.com/Hephaestus-Zero/hveritas/actions/workflows/ci.yml)  
  Container-isolated (`--network=none`) multi-tier software verification harness featuring `O_NOFOLLOW` symlink/hardlink-safe staging, `AES-256-GCM` encrypted held-out test vaults, `O(log n)` deterministic replay bisection, 200-seed differential fuzzing, `mutmut` mutation gates, and `Bandit` SAST self-auditing.

- **[`ocx-plasma`](https://github.com/Hephaestus-Zero/ocx-plasma)** *(QML / Python · KDE Plasma 6)*  
  Local-only KDE Plasma 6 panel telemetry widget for tracking multi-provider developer API rate-limit windows on Linux workstations.
