---
type: Note
related_to: "[[tolaria]]"
onboarding: 1
---
# Principles

Tolaria is built on a few core principles that guide our design decisions:

### 📑 Files-first

Your notes are plain markdown files. They're portable, work with any editor, and require no export step. Your data belongs to you, not to any app.

### 🔌 Git-first

Git is Tolaria's recommended history and sync layer, not a requirement. A plain Markdown folder works as a vault; enabling Git adds diffs, local history, recovery, remotes, and multi-device sync without depending on Tolaria servers.

### 🛜 Offline-first, zero lock-in

No accounts, no subscriptions, no cloud dependencies. Your vault works completely offline and always will. If you stop using Tolaria, you lose nothing.

### 🔬 Open source

Tolaria is free and [open source](https://github.com/refactoringhq/tolaria). I built this for myself ([[luca-rossi]]) and for sharing it with others.

### 📋 Standards-based

Notes are markdown files with YAML frontmatter. No proprietary formats, no locked-in data. Everything works with standard tools if you decide to move away from Tolaria.

### 🔍 Types as lenses — not schemas

Types in Tolaria are navigation aids, not enforcement mechanisms. There's no required fields, no validation, just helpful categories for finding notes.

### 🪄AI-first — but not AI-only

A vault of files works very well with AI agents, but you are free to use whatever you want. Tolaria supports several local coding agents plus direct local and API models. The vault's `AGENTS.md` explains its conventions to external tools without making AI a prerequisite.

### ⌨️ Keyboard-first

Tolaria is designed for power-users who want to use keyboard as much as possible. A lot of how we designed [[tolaria-editor]] and [[command-palette]] is based on this.

### 💪 Built from real use

Tolaria was created to manage my personal vault of 10,000+ notes, and I use it every day. Every feature exists because it solved a real problem.
