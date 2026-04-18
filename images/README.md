# Images

Photos live here so the generated docs in `docs/` and the data in
`data/` can reference them with relative paths.

## Layout

| Folder | For | Example filename |
|---|---|---|
| `plants/` | Plant tags, labels, and plant-specific photos | `pepper-flo-organic-sweet-tag.jpg` |
| `supplies/` | Product labels and supply photos | `gypsum-earth-science-label.jpg` |
| `journal/` | Dated photos tied to a journal entry or event | `2026-04-17-container-01-02-planted.jpg` |

## Naming conventions

- **Lowercase kebab-case.**
- **Plants:** start with the plant's `id` from `data/plants.yaml`.
  Suffixes: `-tag` (the store tag), `-label`, `-habit` (whole plant),
  `-fruit`, `-leaf`, `-pest`, etc.
- **Supplies:** start with the supply's `id` from
  `data/supplies.yaml`. Suffixes: `-label`, `-front`, `-back`.
- **Journal:** start with `YYYY-MM-DD-` followed by a short,
  hyphen-separated slug.

## Referencing from markdown

From a file in `docs/`, use a relative path:

```markdown
![FLO organic sweet pepper tag](../images/plants/pepper-flo-organic-sweet-tag.jpg)
```

## A note on file size

Git isn't great at storing many large binaries. For this project's
scale (a few dozen photos), plain git is fine. Resize photos to
~1600 px wide before upload when convenient — that keeps the repo
lean while staying readable on GitHub.
