<!-- writekit:start — DO NOT REMOVE THIS SECTION -->
Read `node_modules/writekit/agents/instructions.md` before working on this project.
<!-- writekit:end -->

## Translation Project

This is a **translation project** created by `wk translate init`.

- Source project: `../../`
- Source language: it
- Target language: en

### Translation workflow

1. Read `translation-glossary.yaml` — fill in translations for all proper names and terms before starting.
2. For each file in `manuscript/`:
   - The `source_path` in frontmatter points to the original file in the source project.
   - Read the source file for context, then write the translation in the target file body.
   - Do NOT modify `source_path` or `source_hash` fields.
3. Translate chapter titles in the frontmatter.
4. Run `wk check` to validate the translated project.
5. Run `wk build` to generate output in the target language.

### Rules

- Do NOT modify `translation.yaml` or `source_hash` values.
- Do NOT add or remove manuscript files — structure mirrors the source.
- Do NOT translate proper names without consulting `translation-glossary.yaml`.
- Preserve all markdown formatting, footnotes, and image references.
