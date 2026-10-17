---
type: Note
related_to: "[[tolaria]]"
onboarding: 4
---
# Editor

The editor is where you write and edit your notes. Tolaria supports two modes:

### WYSIWYG Mode

The default experience. Similar to Notion — type naturally and see formatted output.

Supports slash commands for quick formatting, current date and time, live Markdown rendering, editable callouts, inline previews, drag and drop of images, collapsible sections, block selection, code blocks, Mermaid diagrams, math, sandboxed HTML blocks, colored highlights, and more.

Open editor-playground for examples you can manipulate directly.

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

Shows the actual file characters. Access it with `Cmd+\` or `Ctrl+\`, or use the source button in the breadcrumb bar. It is useful when you need precise control over Markdown or YAML frontmatter.

Invalid YAML frontmatter is highlighted so structural mistakes are easier to locate.

### Filename Display

The note's filename is always visible at the top of the editor. This keeps you aware of how the note will be named and linked.

### H1-to-Filename Sync

When you create a new untitled note, the first H1 heading automatically sets its filename as soon as it becomes a real title. After that, the filename stays put until you rename it yourself from the breadcrumb bar or the note list.

You can turn this off in Settings → Titles & Filenames (`Cmd+,` or `Ctrl+,`).

### Wikilinks

Type `[[` to trigger autocomplete from your entire vault. This creates links to other notes, enabling the knowledge graph.

Wikilinks also auto-update if the filename changes. If a wikilink points to a note that doesn't exist yet, you can create that note straight from the link.

![BlockNote image](attachments/1776508281809-CleanShot_2026-04-18_at_12.30.44_2x.png)

### Breadcrumb Bar Actions

The breadcrumb bar (above the editor) is the hub for note-level actions: favoriting, marking organized, switching editor modes, viewing git diff, and accessing properties.

### Whiteboards

Notes can contain tldraw whiteboards for sketches and diagrams. The board is still stored in the Markdown file, so it lives in the vault and is versioned by Git like everything else. Expand a board to work on it full screen.

### Export as PDF

Use the export button in the editor toolbar, or run `Export note as PDF` from the command-palette, to turn the current note into a PDF.
