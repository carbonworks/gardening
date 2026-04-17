# Gardening

Personal garden organization system. Two layers:

- **Data layer** (`data/*.yaml`) — single source of truth, managed by the assistant.
- **Docs layer** (`docs/*.md`) — pre-generated, read-only views for browsing on GitHub.

The user typically does not edit either directly. They communicate changes
in chat; the assistant updates `data/` and regenerates the affected `docs/`.
See [`CLAUDE.md`](CLAUDE.md) for the full workflow.

## Read on GitHub (humans start here)

- [`docs/inventory.md`](docs/inventory.md) — site, plants, containers, nursery, supplies
- [`docs/soil-recipes.md`](docs/soil-recipes.md) — base mix and per-plant soil recipes
- [`docs/planting-strategy.md`](docs/planting-strategy.md) — pot-sharing and companion planting plan
- [`docs/tasks.md`](docs/tasks.md) — open work and recent completions
- [`docs/journal.md`](docs/journal.md) — dated observations and events
- [`docs/calendar.md`](docs/calendar.md) — month-by-month garden task calendar

## Data files

- `data/site.yaml` — location, hardiness zone, frost dates
- `data/plants.yaml` — catalog of plant varieties
- `data/containers.yaml` — physical containers and their plantings
- `data/nursery.yaml` — plants in starter pots, available to be planted out
- `data/wishlist.yaml` — plants we want to grow but have not yet acquired
- `data/supplies.yaml` — inventory of growing supplies
- `data/mixes.yaml` — premixed soil bases and per-plant soil recipes
- `data/companions.yaml` — pot-sharing / companion planting knowledge
- `data/calendar.yaml` — month-by-month garden tasks
- `data/tasks.yaml` — open work and recent completions
- `data/journal.yaml` — dated observations and events
- `data/generated.yaml` — registry of every generated doc and its data sources

## Conventions

- IDs use kebab-case and are stable once assigned (e.g. `container-01`).
- Measurements include units (`"0.5 in"`, `"5 gal"`, `"1 tbsp per gal"`).
- Unknown fields are recorded as `null` with a comment, rather than omitted,
  so gaps in information are visible.
- After editing any `data/*.yaml`, check `data/generated.yaml` to see which
  `docs/*.md` files need to be regenerated.
