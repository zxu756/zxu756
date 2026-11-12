### Zhenhan Xu (`zxu756`)

Systems software, multi-agent coding infrastructure, and native macOS utilities.

```bash
brew tap zxu756/tap
brew install --cask agentbar crystaldiskinfo-mac crystaldiskmark-mac
```

---

#### Agent Infrastructure & Verification

- **[diy-harness](https://github.com/zxu756/diy-harness)** — Lightweight coding agent harness (`dh`) with multi-provider routing, ACP server, network/filesystem sandboxing, prompt-token auto-compaction, and hard USD/token budget gates.
- **[AgentBar](https://github.com/zxu756/AgentBar)** — Native macOS 14+ Menu Bar & `Swift Charts` telemetry monitor for **Claude Code**, **Codex CLI**, **OpenCode**, **Mistral Vibe**, and **Antigravity** (`SQLITE_OPEN_READONLY`, zero network calls).
- **[agent-relay](https://github.com/zxu756/agent-relay)** — Headless cross-vendor CLI relay (`claude` + `codex` + `vibe` + `agy`) with file-only baton handoffs, secret egress blocking, process-group timeouts, and per-step cost accounting.
- **[rea-build-guard](https://github.com/zxu756/rea-build-guard)** — Pre-release reverse-engineering and security self-audit gate for `dist/`, `.wasm`, Electron, and macOS `.app` artifacts powered by [REA](https://github.com/morluto/rea).

#### Native macOS Systems Tools

- **[CrystalDiskMarkMac](https://github.com/zxu756/CrystalDiskMarkMac)** — Native SwiftUI + C++17 POSIX storage benchmark (`SEQ1M Q8T1/Q1T1`, `RND4K Q32T1/Q1T1`) built purely with SwiftPM.
- **[CrystalDiskInfoMac](https://github.com/zxu756/CrystalDiskInfoMac)** — Native NVMe/SATA disk health, temperature, remaining life, SMART attribute table, and 30-day history monitor.
- **[homebrew-tap](https://github.com/zxu756/homebrew-tap)** — Official Homebrew Cask tap for one-command macOS installation.

#### Real-Time 3D & Graphics

- **[Aetherfront](https://github.com/zxu756/aetherfront-site)** — Real-time 3D isometric tactical arena technical preview built with Three.js, Rapier3D physics, custom GLSL terrain/water shaders, and skeletal animation pipelines.
