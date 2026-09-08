# Document formatting scaffold

Copy the block below as the skeleton for any document in this style.

````markdown
```text
╔══════════════════════════════════════════════════════════════════════════════╗
║  <ASCII BANNER — up to 76 columns wide, centered inside the side borders>    ║
╚══════════════════════════════════════════════════════════════════════════════╝

───[ section-name ]─────────────────────────────────────────────────────────//──

Body text, hard-wrapped at 76 columns. Blank line between paragraphs and
between sections.

[-] Feature-list item - description starts after the dash
    continuation lines indent four spaces to align under the text

- Plain dash bullet for short, single-line items.

───[ contact ]──────────────────────────────────────────────────────────────//──

email     you@example.com
web       example.com
```
````

## Rules

- Everything lives inside a single ```` ```text ```` fenced block.
- Hard limit: 80 display columns per line. Body text wraps at 76.
- Banner: `╔═...╗` / `╚═...╝` box, 80 columns total; art padded so the `║`
  borders land in columns 1 and 80.
- Section header: `───[ name ]` + `─` fill + `//──`, exactly 80 columns.
  Fill count = 76 − len("───[ name ]").
- `[-]` marks feature/project list items; `-` marks simple bullets;
  continuation lines indent to align under the item text.
- Key/value rows (contact block): label padded to 10 columns, then the value.
- No trailing whitespace on any line.
