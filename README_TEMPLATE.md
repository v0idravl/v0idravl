# GitHub README style template

Uniform style for project READMEs across the v0idravl repos. Canonical
examples: `sdwx`, `lab-writeups`, `dotfiles`. (The profile README itself uses
the separate terminal-box scaffold in `TEMPLATE.md`.)

## Skeleton

````markdown
```text
<ASCII BANNER — figlet "ANSI Shadow" font, project name in caps>
  <tagline · lowercase · middot-separated>
```

![badge1](https://img.shields.io/badge/label-value-COLOR)
![badge2](https://img.shields.io/badge/label-value-COLOR)

One or two short paragraphs: what it is, who it is for, what makes it
notable. Wrap prose at ~80 columns. Lead with the concrete payoff, not
marketing.

---

## ⚡ 30-second demo

```bash
git clone https://github.com/v0idravl/<repo>.git
cd <repo>
<run it>
```

---

## ⌨️ Usage

```bash
<commands with # comments on the right>
```

---

## 🛠 Requirements

<one line or short list>

---

## 🧪 Tests

```bash
<test command>
```
````

## Rules

- **Banner** — figlet font `ansi_shadow`, name in ALL CAPS, inside a
  ```` ```text ```` fenced block, max 78 columns wide. A one-line lowercase
  tagline sits under the art, segments separated by ` · `.
  Generate: `pyfiglet -f ansi_shadow "NAME"`; strip trailing whitespace.
- **Badges** — shields.io static badges, `![label](url)` form (no links
  unless the badge points somewhere real, like the live site). Facts only:
  language/runtime version, dependency count, platform, test count. 3–5
  badges, each its own line.
- **Section headers** — `## <emoji> Title case name`, one emoji per header.
  Conventional picks: ⚡ demo/quickstart, ⌨️ usage/keys, 🛠 requirements,
  🧪 tests, 🗂 contents, 🎯 start here/purpose, 📚 index, 🔒 security,
  ⚙️ configuration, 📡 data sources, 📝 notes. Reuse an emoji for the same
  kind of section across repos.
- **Separators** — a bare `---` rule between major sections.
- **Tables** — pipe tables for key bindings, file inventories, feature
  matrices; not for prose.
- **Code blocks** — `bash` for shell, `text` for captured output/art.
  Comment flags and subcommands inline on the right.
- **Prose** — wrapped at ~80 columns, plain and specific; no emojis inside
  body text, no exclamation points.
- **No** HTML, no centered `<p align>` blocks, no screenshot placeholders,
  no license badge unless a LICENSE file exists.
- Jekyll sites (`hakiki`, `whoami`) keep their YAML front matter block
  above everything else; the style starts below it.
