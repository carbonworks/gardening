> **Generated file — do not edit by hand.**
> Sources: `data/companions.yaml`, `data/layout.yaml`, `data/plants.yaml`, `data/containers.yaml`, `data/nursery.yaml`, `data/supplies.yaml`
> Last generated: 2026-04-17

# Planting Strategy

Two decisions go into every pot: **what shares the soil** (companions) and
**where the pot sits** (sun zone). The layout puts the binding constraint
on the plan — only 8 of our 12 five-gallon pots fit in full-sun slots.

## The growing area

- **Location:** 4th-floor townhome, half roof deck, SSE-facing.
- **Planter stands:** 2 × 4-slot stands against the SSE rail. **8 five-gallon slots total, full sun (10am – 4pm, ~6 hours direct).**
- **South side of deck:** floor space with brief midday sun (partial sun / mostly shade).
- **Other deck floor:** varies by placement.
- **Wind:** elevated; stake tall plants and consider securing the stands.
- **Weight check:** 12 filled 5 gal pots = ~600–700 lbs. Confirm the deck's load rating.

## Companion principles

### Solo — always own pot

| Plant | Why |
|---|---|
| Lemon balm | Mint-family rhizomes outcompete neighbors. |
| Lavender 'Provence' | Lean, alkaline, dry soil clashes with everything else. |
| Russet potato | Large root volume; nightshade disease overlap with tomatoes/peppers. |
| Citronella | Goal is maximum size; no competition. |

### Good pairings

- **Tomatoes** ↔ basil, marigold, nasturtium. **Avoid potatoes.**
- **Peppers** ↔ basil, marigold, nasturtium. **Avoid potatoes.**
- **Lettuce (mesclun)** can undercrop tomatoes or peppers while weather is cool.
- **Strawberries** stay in their own pots. Avoid pairing with brassicas.

## Placement plan — full-sun planter stands (8 slots)

All 8 slots are now pre-reserved in `data/containers.yaml`. Status is `planted` or `proposed`.

| Container | Slot | Plantings | Soil recipe | Status |
|---|---|---|---|---|
| `container-01` | planter-stand-1 | Dora Red + Joy Red + 2 marigolds + 2 nasturtium seeds | Tomato & Pepper Mix | planted 2026-04-13 |
| `container-02` | planter-stand-1 | Hartman's Yellow Gooseberry tomato, solo | Tomato & Pepper Mix | planted 2026-04-13 |
| `container-03` | planter-stand-1 | **Pepper 'Orange Blaze'** + 1 basil + 2 marigolds | Tomato & Pepper Mix | proposed |
| `container-04` | planter-stand-1 | **Pepper 'Lunch Box Orange'** + 2 marigolds (+ mesclun undercrop while cool) | Tomato & Pepper Mix | proposed |
| `container-05` | planter-stand-2 | **Lavender 'Provence'**, solo | Mediterranean Herb Mix | proposed |
| `container-06` | planter-stand-2 | **Citronella** (slot reserved; citronella up-pots from 6 in → 2–3 gal → 5 gal over time) | General Herb Mix | proposed |
| `container-07` | planter-stand-2 | **3 russet seed potatoes** | Potato Mix (no lime / no Mag-I-Cal) | proposed |
| `container-08` | planter-stand-2 | **2 russet seed potatoes** | Potato Mix | proposed |

Exact slot assignment within each stand is flexible — group the two pepper pots together if you want them to cross-pollinate, and keep the potato pots side by side for easier hilling/harvest.

## Placement plan — outside the planter stands

| Container / item | Location | Plantings | Soil | Status |
|---|---|---|---|---|
| `container-09` (5 gal) | Deck floor / partial sun | 1× lemon balm, solo | General Herb Mix | proposed |
| `container-10` (5 gal) | Deck floor / partial sun | 1× lemon balm, solo | General Herb Mix | proposed |
| existing 8 in pot | Deck surface near rail (sunnier) | Strawberry 'Ever Sweet' | existing mix | in nursery |
| existing 12 in pot | Deck surface near rail (sunnier) | Strawberry basket (unlabeled) | existing mix | in nursery |
| shallow tray or small pot (TBD) | South-deck / partial sun, or as undercrop in `container-04` | Mesclun mix lettuce | Lettuce / Salad Greens Mix | needs container decision |

**5 gal pot tally:** 12 total − 2 planted − 8 proposed = **2 spare** (one earmarked for cucumber when purchased).

## Plant sun requirements (quick reference)

| Plant | Needs | Where it goes |
|---|---|---|
| Tomato, pepper, citronella, lavender, potato, cucumber, marigold, basil, nasturtium | Full sun (6+ hr) | Planter stands |
| Strawberries | Full sun | Deck surface in sun zone |
| Lemon balm | Partial sun OK | Deck floor, partial-sun area |
| Mesclun lettuce | Partial sun preferred (cooler) | South side or undercrop |

## Open questions

- **Cucumber variety:** still unselected. When purchased, it takes one of the 2 spare 5 gal pots and needs a full-sun slot — we can swap it in place of a potato pot or displace one of the lemon balm pots outward to the floor.
- **Basil quantity:** we have 1 starter but `container-03` and `container-04` both want a basil companion. Either accept one pepper without basil, or acquire a second basil start.
- **Mesclun container:** needs either a shallow dedicated container or a commitment to undercrop `container-04`. Undercropping is simpler, but the starters must be removed before summer heat to avoid bolting.
