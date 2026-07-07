---
type: Note
related_to: "[[tolaria]]"
onboarding: 4
---
# Editor

The editor is where you write and edit your notes. Tolaria supports two modes:

### WYSIWYG Mode

The default experience. Similar to Notion — type naturally and see formatted output.

Supports slash commands for quick formatting, live markdown rendering, inline previews, drag and drop of images, `inline code`, and so on.

- List **item** 1
  - Nested *italic item*
1. **Numbered item** in bold
2. Numbered second item

> Quote from a wise author

- [ ] Task 1
- [ ] Task 2

```javascript
(param) => (return 3*2) /* code block */
```

### Raw Mode

Shows the actual file characters. Access it with `Cmd+\` or the code button in the breadcrumb bar. Useful when you need precise control over markdown syntax.

### Filename Display

The note's filename is always visible at the top of the editor. This keeps you aware of how the note will be named and linked.

### H1-to-Filename Sync

The first H1 heading in your document automatically sets the filename. After the first sync, changes to the H1 require a manual sync—a refresh button appears next to the title to sync them manually.

You can turn off the H1-to+filename sync in the settings

### Wikilinks

Type `[[` to trigger autocomplete from your entire vault. This creates links to other notes, enabling the knowledge graph.

Wikilinks also auto-update if the filename changes.

![BlockNote image](attachments/1776508281809-CleanShot_2026-04-18_at_12.30.44_2x.png)

### Breadcrumb Bar Actions

The breadcrumb bar (above the editor) is the hub for note-level actions: favoriting, marking organized, switching editor modes, viewing git diff, and accessing properties.
