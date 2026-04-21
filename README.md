# the-authorized-corridor

> Single essay or long-form non-fiction

A **essay** project powered by [writekit](https://www.npmjs.com/package/writekit).

## Getting started

```bash
wk check          # validate project
wk build html     # preview as web page
wk build all      # build all formats (pdf, epub, html, docx, md)
wk stats          # word count and chapter balance
```

For the full command reference, configuration, and guide, see [`docs/writekit.md`](docs/writekit.md).

## Project structure

| Path | Purpose |
|---|---|
| `config.yaml` | Title, author, language, build settings |
| `style.yaml` | Writing rules — POV, tense, tone, text normalization |
| `synopsis.md` | Short summary / pitch |
| `thesis.md` | Central thesis statement |
| `manuscript/` | Your text — chapters, front/back matter |
| `outline/` | Planning and structure |
| `arguments/` | Argument sheets (claim, support, counterpoint) |
| `concepts/` | Key terms and definitions |
| `contributors/` | Author/translator/editor bios |
| `notes/` | Free-form ideas and research |
| `reference/` | External material |
| `assets/` | Cover image, illustrations, fonts |
| `docs/` | writekit guide (auto-generated) |
| `build/` | Generated output |
