# Gardening

Organizational system for tracking plants, containers, and supplies.

## Structure

- `data/plants.yaml` — catalog of plant varieties (tomatoes, companions, etc.)
- `data/containers.yaml` — physical containers and what is planted in each
- `data/nursery.yaml` — plants in starter pots, available to be planted out
- `data/wishlist.yaml` — plants we want to grow but have not yet acquired
- `data/supplies.yaml` — inventory of growing supplies (pebbles, soil, amendments)
- `data/mixes.yaml` — premixed soil bases and soil recipes that build on them
- `data/calendar.yaml` — month-by-month garden tasks (seeding, transplants, maintenance)

Data files are YAML so they are easy to read and edit by hand while still being
structured enough to query or render programmatically later.

## Conventions

- IDs use kebab-case and are stable once assigned (e.g. `container-01`).
- Measurements include units (`"0.5 in"`, `"5 gal"`).
- Unknown fields are recorded as `null` with a comment, rather than omitted,
  so gaps in information are visible.
