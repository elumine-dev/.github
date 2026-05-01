<div align="center">

# Elumine

**Open-source developer tools for Kotlin and modern codebases.**

Fast and editor-agnostic. Free of JVM dependencies where it counts.

[![Website](https://img.shields.io/badge/elumine.ca-Website-c160c0?style=flat-square)](https://www.elumine.ca)
[![License](https://img.shields.io/badge/License-MIT_%2F_Apache_2.0-blue?style=flat-square)](#)
[![Editors](https://img.shields.io/badge/Editors-VS_Code_%C2%B7_Cursor_%C2%B7_Neovim_%C2%B7_Helix_%C2%B7_Zed-orange?style=flat-square)](#)

</div>

---

## Tools

### ⚡ [kotlin-jump](https://github.com/elumine-dev/kotlin-jump)

> VS Code Kotlin and Java navigation. No JVM. No language server.

**4 658 installs · ★ 5.0 · v1.18.3 · 1 045 versions shipped**

< 1 ms lookups · 3 000+ files indexed in < 500 ms · 109× faster than JVM parsers. Works in VS Code, Cursor, VSCodium, Windsurf, Gitpod, and most other VS Code forks.

```
ext install elumine.kotlin-jump
```

### 🔍 [SearchDeadCode](https://github.com/KevinDoremy/SearchDeadCode)

> Fast Rust CLI to detect and safely remove dead code in Android projects.

**v0.4.0 · MIT · on Homebrew and Cargo**

< 1 s on 1 000 files · < 5 s on 10 000 files. Hybrid analysis with JaCoCo / Kover / LCOV coverage and R8 `usage.txt`. Inspired by [Periphery](https://github.com/peripheryapp/periphery) for Swift. Maintained under [@KevinDoremy](https://github.com/KevinDoremy).

```bash
brew install KevinDoremy/tap/searchdeadcode
```

### 🩺 [detekt-lsp](https://github.com/elumine-dev/detekt-lsp)

> Live [detekt](https://detekt.dev) diagnostics for any LSP-compatible editor.

**Pre-alpha (M0) · Apache 2.0**

Targets sub-100 ms diagnostics on every keystroke. Embeds `detekt-core` inside an LSP server with a live PSI cache and per-file invalidation. Works in VS Code, Cursor, Neovim, Helix, and Zed.

> Status: M0 skeleton. ETA M2 (live syntactic diagnostics): mid-2026.

---

## Companion mode

The three tools are designed to work together:

| You write Kotlin in... | And get... |
|---|---|
| **VS Code / Cursor** | Navigation via kotlin-jump + diagnostics via detekt-lsp |
| **A standalone CLI** | Dead code audits via SearchDeadCode in CI |
| **Any LSP editor** | detekt-lsp speaks the protocol your editor already understands |

No single tool replaces the others. Use one. Use all three. Same philosophy across the stack.

---

## What we build for

- **Speed first.** No JVM startup, no indexing waits, no language server warming, no background process eating RAM.
- **Multi-editor.** Wherever you code, not just JetBrains IDEs.
- **Honest benchmarks.** Numbers in our READMEs are reproducible, comparisons cite alternatives by name.
- **Open source.** MIT or Apache 2.0. No telemetry. No upsell. No locked features.

---

## Maintainer

Run by [**Kevin Doremy Laferrière**](https://kevindoremy.com), `ing.` (OIQ #6045500, Software and AI practice area). Senior Mobile Engineer at La Presse. 5+ years across iOS and Android, with a focus on Kotlin Multiplatform and mobile DevEx.

[🌐 elumine.ca](https://www.elumine.ca) &nbsp;·&nbsp; [💼 LinkedIn](https://linkedin.com/in/kevindoremy) &nbsp;·&nbsp; [✉️ hello@elumine.ca](mailto:hello@elumine.ca)
