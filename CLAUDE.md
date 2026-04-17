# Project operating guide (for the assistant)

This is a personal garden organization system. The assistant (Claude)
owns the `data/` directory and keeps `docs/` in sync. The user does not
usually edit these files directly — they communicate changes in chat,
and the assistant updates the data and regenerates the docs.

## Directory roles

- `data/*.yaml` — single source of truth. Structured data.
- `docs/*.md` — generated, human-readable views for GitHub. Read-only.
- `data/generated.yaml` — registry of every generated doc and its sources.

## Workflow when the user provides new information

1. Update the relevant `data/*.yaml` file(s).
2. Check `data/generated.yaml` to find which `docs/*.md` files depend on
   the changed sources.
3. Regenerate every affected doc and update its `last_generated` date in
   `data/generated.yaml`.
4. Commit (one logical change per commit) and push to the working branch.

## Generated-file rules

Every file under `docs/` must begin with a header like:

```
> **Generated file — do not edit by hand.**
> Sources: `data/foo.yaml`, `data/bar.yaml`
> Last generated: YYYY-MM-DD
```

If a doc is edited by hand by mistake, prefer the data in `data/` and
regenerate rather than preserving the hand edit.

## Conventions

- IDs are kebab-case and stable once assigned.
- Measurements include units (`"0.5 in"`, `"5 gal"`, `"1 tbsp per gal"`).
- Unknown / TBD fields use `null` with an explanatory `# comment`, not
  omission, so gaps in information are visible.
- Use the current session date (from context) for dated events.

## Adding a new data file

1. Create `data/<name>.yaml`.
2. Reference its `id` values from any file that depends on them.
3. Add any new generated docs to `data/generated.yaml` with explicit
   source list.
4. Add it to the file list in `README.md`.
