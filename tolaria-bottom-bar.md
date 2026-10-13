---
type: Note
related_to: "[[tolaria]]"
onboarding: 6
---
# Bottom Bar

The bottom bar is Tolaria's status bar — more informational than interactive. It keeps you aware of your current state without getting in your way.

### 📂 Vault selection

By clicking on the vault bottom left you can change the active vault, open a vault in a new window, open a new local folder, create a new one by cloning a Git repo, or manage which vaults are included in your graph.

![CleanShot 2026-04-17 at 15.35.16@2x.png](attachments/1776432929539-CleanShot_2026-04-17_at_15.35.16_2x.png)

When `Use multiple vaults at the same time` is enabled in Settings → Vaults, this menu shows checkboxes for the vaults Tolaria should load together. Included vaults appear in search, note lists, quick open, backlinks, and wikilink navigation. The selected vault still controls repository-specific actions such as commits, sync, saved views, and folder navigation.

### 🔄 Git Sync Status

Shows pending uncommitted changes in your vault. When you see a count, you have uncommitted edits. Click to see what's changed or commit directly by clicking on `commit`.

The commit dialog can draft a message from your changes, and pushes when the vault has a remote. If you have [[autogit]] enabled, Tolaria creates these checkpoints for you automatically.

### ⚡ History

A lightweight git history view shows recent changes across all notes. See when notes were modified, by whom, and get quick access to change details.

![CleanShot 2026-04-17 at 15.32.38@2x.png](attachments/1776432798617-CleanShot_2026-04-17_at_15.32.38_2x.png)

### 🧮 App Version

The current Tolaria version. Useful when debugging or checking for new features.

### 🪄 AI Status

Shows which AI target is selected and whether an installed coding agent is available. Tolaria supports Claude Code, Codex, GitHub Copilot, OpenCode, Pi, Antigravity CLI, Kiro, and Hermes Agent, plus configured direct models.

![CleanShot 2026-04-17 at 15.51.39@2x.png](attachments/1776433913782-CleanShot_2026-04-17_at_15.51.39_2x.png)

### 📣 Feedback

The Contribute button opens a small menu where you can report a bug, request features, join discussions, contribute code, or support Tolaria as a sponsor.
