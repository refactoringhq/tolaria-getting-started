---
type: Note
related_to: "[[tolaria]]"
onboarding: 2
---
# Sidebar

The sidebar is your primary navigation tool. It groups notes in different ways so you can find what you need quickly.

### 📥 Inbox

Notes that aren't *organized* yet.

This is inspired by [Tiago Forte](https://www.buildingasecondbrain.com/)'s concept of separating capture from organize. An “organized” note is a note that you know what you will do with. It may belong to a project, to a responsibility, a topic, or any concept related to how you organize work.

Review your inbox (e.g.) weekly to keep it from growing too large. You can disable the Inbox in Settings (`Cmd+,` or `Ctrl+,`) if you don’t like this workflow.

You can flag a note as *organized* by clicking on the “circle task” icon in the breadcrumbs bar, or with `Cmd+E` (`Ctrl+E` on Windows and Linux).

### 🗃️ All Notes

As the name suggests, that’s the entire vault — every single note.

### 📦 Archive

A permanent home for notes you don't want to delete but don't want to see regularly. Archive aggressively to keep your vault clean. Archived notes still appear in search results, but not in sidebar sections.

### ⭐ Favorites

Notes you've manually pinned to keep them top-of-mind. Great for active projects, journal entries, or reference notes you access frequently.

You can reorder them by dragging them in the sidebar.

Toggle a favorite note from the ⭐ button in the breadcrumbs bar, or with `Cmd+D` (`Ctrl+D` on Windows and Linux).

### 🔍 Views

You can create custom views that filter notes by complex, nested criteria. The view editor fetches all available properties, plus allows for some tricks (like regexes and natural language dates)

![CleanShot 2026-04-16 at 22.02.51@2x.png](attachments/1776369786040-CleanShot_2026-04-16_at_22.02.51_2x.png)

Views are simple yaml files that get stored in the views folder (e.g. [[views/active-projects.yml]]). They can be edited easily and even created by the AI 👇

```yaml
name: Active Projects
icon: 🚀
filters:
  all:
  - field: type
    op: equals
    value: Project
  - field: Status
    op: equals
    value: Active
  - any:
    - field: status
      op: equals
      value: active
    - field: date
      op: after
      value: in 1 week
```

### 🧩 Types

The main organizational device in Tolaria. Each note has a type, which by default is [[note]].

Each type can have its own icon and color, which you can change by right-clicking on it in the sidebar, or manually changing it in the properties or frontmatter of the type file.

Types are simply stored as markdown files, like [[topic]], or [[project]].

Click any type on the sidebar to see all notes of that type in the note list.

### 📂 Folders

Tolaria stores notes in the root of the vault by default, but also scans your vault’s folder structure, which you can navigate at the bottom of the sidebar.

Folders are listed last because they are a secondary organization method—not the primary one.

### 🗑️ Trash

There is no trash bin: when you delete a note (`Cmd+Backspace` or `Ctrl+Backspace`), it’s gone — but your git history is your safety net. You can always recover deleted notes from git if needed.
