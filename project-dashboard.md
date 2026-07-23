---
type: Project
status: Active
owner: "[[luca-rossi]]"
budget: 24000
progress: 0.65
related_to: "[[tolaria]]"
onboarding: 4.75
_organized: true
---
# Project Dashboard

The block below is stored as fenced HTML inside this Markdown note. Tolaria renders it in a sandbox and resolves `{{...}}` expressions from the note's frontmatter.

```html height="360"
<style>
  :root {
    color-scheme: light dark;
    font-family: ui-sans-serif, system-ui, sans-serif;
  }
  .dashboard {
    display: grid;
    gap: 16px;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    padding: 24px;
  }
  .metric {
    border: 1px solid color-mix(in srgb, currentColor 18%, transparent);
    border-radius: 12px;
    padding: 16px;
  }
  .label {
    font-size: 12px;
    opacity: 0.65;
    text-transform: uppercase;
  }
  .value {
    font-size: 24px;
    font-weight: 700;
    margin-top: 8px;
  }
</style>

<section class="dashboard">
  <article class="metric">
    <div class="label">Status</div>
    <div class="value">{{title(status)}}</div>
  </article>
  <article class="metric">
    <div class="label">Budget</div>
    <div class="value">{{formatCurrency(budget, "USD", 0)}}</div>
  </article>
  <article class="metric">
    <div class="label">Progress</div>
    <div class="value">{{formatPercent(progress, 0)}}</div>
  </article>
</section>
```

Try changing `status`, `budget`, or `progress` in the Properties panel. The preview updates from the same file-backed values.

Use raw mode to edit the HTML source. Remote resources, forms, and scripts are blocked unless a fenced block explicitly opts into Tolaria's local script sandbox.
