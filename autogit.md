---
type: Note
onboarding: 8
belongs_to: "[[tolaria]]"
---
# Git and AutoGit

Tolaria vaults have first-class, optional Git support. You retain control over when to create local history, connect a remote, commit, and push.

You can look at current changes and Git history from [[tolaria-bottom-bar]], create new commits and push them directly without ever leaving the app.

The manual commit dialog can draft a message from the changed files. Review and edit the draft before committing.

If you do not want to manage checkpoints manually, Tolaria also has an opt-in **AutoGit mode**. It creates conservative commits after an editing pause or when the app becomes inactive, then pushes when the vault has a configured remote.

![CleanShot 2026-04-17 at 17.44.08@2x.png](attachments/1776440668823-CleanShot_2026-04-17_at_17.44.08_2x.png)

You can enable AutoGit, choose whether it drafts messages with AI, and adjust its timing in Settings (`Cmd+,` or `Ctrl+,`).

Git also works when this vault is a folder inside a larger repository. Tolaria keeps app-created commits scoped to vault files, while pull and push still operate on the parent repository.
