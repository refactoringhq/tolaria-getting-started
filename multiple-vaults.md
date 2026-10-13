---
type: Note
related_to: "[[tolaria]]"
onboarding: 6.5
---
# Multiple Vaults

Tolaria can manage more than one vault at the same time. This is useful when you want to keep separate folders or Git repositories, but still search and navigate across them as one knowledge graph.

To turn it on:

1. Open Settings.
2. Go to Vaults.
3. Enable `Use multiple vaults at the same time`.
4. Open the bottom-left vault menu.
5. Check the vaults you want to include in the unified graph.

Included vaults appear together in note lists, search, quick open, backlinks, and wikilink navigation. When a note could be ambiguous, Tolaria shows a small vault label so you know where it lives.

Each vault keeps its own files and Git repository. Commits, sync, saved views, folder navigation, and vault repair actions still belong to the selected vault. Use `Manage vaults` to rename vaults, choose colors, and set the default vault for new notes.

Cross-vault wikilinks use the target vault's stable alias when Tolaria needs one, such as `[[team/projects/alpha]]`. Links inside the same vault stay simple.

If you'd rather keep vaults completely separate, open one in its own window instead: use the bottom-left vault menu to open it in a new window. Each window works on its own vault.
