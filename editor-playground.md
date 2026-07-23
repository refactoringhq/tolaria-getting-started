---
type: Note
related_to: "[[tolaria]]"
onboarding: 4.25
_organized: true
---
# Editor Playground

This note contains durable Markdown examples you can edit, select, move, collapse, and inspect in raw mode.

> [!NOTE] Rich in Tolaria, portable everywhere
> This callout stays a normal Markdown blockquote when another editor opens the file.

> [!TIP]- Expand this callout
> The `-` marker makes it start collapsed. Change the marker in raw mode.

## A section to collapse

Move the pointer beside this heading and use its disclosure control. You can also press `Esc` to select the heading, then `Cmd+Enter` on macOS or `Ctrl+Enter` on Windows and Linux.

Everything until the next heading at the same or higher level belongs to the section. Collapsing it changes only the editor—not the Markdown.

### Try block selection

1. Put the cursor in this paragraph and press `Esc`.
2. Use the arrow keys to move the selected block.
3. Hold `Shift` while using the arrows to select more blocks.
4. Press `Enter` to edit text again.

Use `Cmd+Shift+Up` or `Cmd+Shift+Down` to move selected blocks on macOS. Use `Ctrl` instead of `Cmd` on Windows and Linux.

## Formatting that round-trips

This sentence contains ==Markdown highlight==. Select other text and press `Cmd+Shift+M` on macOS or `Ctrl+Shift+M` on Windows and Linux.

- [ ] Press `Cmd+T` or `Ctrl+T` in a paragraph to turn it into a todo
- [ ] Type `/date` or `/time` to insert the current value

Create a code block with the slash menu, a triple-backtick fence, or `Cmd+Shift+Backtick` / `Ctrl+Shift+Backtick`:

```typescript
const vault = {
  format: "Markdown",
  history: "Git",
  lockedIn: false,
}
```

Use the language control to change syntax highlighting. Line numbers are editor presentation and never enter the file.

## Look underneath

Toggle raw mode with `Cmd+\` or `Ctrl+\`. The callouts, highlight, todos, and code block remain ordinary Markdown you can read with any editor.
