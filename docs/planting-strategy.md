> **Generated file — do not edit by hand.**
> Sources: `data/companions.yaml`, `data/layout.yaml`, `data/plants.yaml`, `data/containers.yaml`, `data/nursery.yaml`, `data/supplies.yaml`
> Last generated: 2026-04-17

# Planting Strategy

Two decisions go into every pot: **what shares the soil** (companions) and
**where the pot sits** (sun zone). The layout puts the binding constraint
on the plan — only 8 of our 24 five-gallon pots fit in full-sun planter-stand slots.

_See also: [inventory](inventory.md) · [encyclopedia](encyclopedia.md) · [soil recipes](soil-recipes.md)_

## The growing area

- **Location:** 4th-floor townhome, half roof deck, SSE-facing.
- **Planter stands:** 2 × 4-slot stands against the SSE rail. **8 five-gallon slots total, full sun (10am – 4pm, ~6 hours direct).**
- **South side of deck:** floor space with brief midday sun (partial sun / mostly shade).
- **Other deck floor:** varies by placement.
- **Wind:** elevated; stake tall plants and consider securing the stands.
- **Weight check:** ~600–700 lbs for 12 filled 5 gal pots (we have 24 on hand; most will stay empty). Confirm the deck's load rating before loading.

## Companion principles

### Solo — always own pot

| Plant | Why |
|---|---|
| [Lemon balm](encyclopedia.md#lemon-balm) | Mint-family rhizomes outcompete neighbors. |
| [Lavender 'Provence'](encyclopedia.md#lavender-provence) | Lean, alkaline, dry soil clashes with everything else. |
| [Russet potato](encyclopedia.md#russet-potato) | Large root volume; nightshade disease overlap with tomatoes/peppers. |
| [Citronella](encyclopedia.md#citronella) | Goal is maximum size; no competition. |

### Good pairings

- **Tomatoes** ↔ [basil](encyclopedia.md#basil), [marigold](encyclopedia.md#marigold-antigua-mix), [nasturtium](encyclopedia.md#nasturtium). **Avoid potatoes.**
- **Peppers** ↔ [basil](encyclopedia.md#basil), [marigold](encyclopedia.md#marigold-antigua-mix), [nasturtium](encyclopedia.md#nasturtium). **Avoid potatoes.**
- **[Lettuce (mesclun)](encyclopedia.md#mesclun-mix-lettuce)** can undercrop tomatoes or peppers while weather is cool.
- **[Strawberries](encyclopedia.md#strawberry-ever-sweet)** stay in their own pots. Avoid pairing with brassicas.

## Placement plan — full-sun planter stands (8 slots)

All 8 slots are pre-reserved in `data/containers.yaml`. Status is `planted` or `proposed`.

| Container | Slot | Plantings | Soil recipe | Status |
|---|---|---|---|---|
| `container-01` | planter-stand-1 | [Dora Red](encyclopedia.md#heartbreakers-dora-red-tomato) + [Joy Red](encyclopedia.md#pillar-joy-red-tomato) + 2 [marigolds](encyclopedia.md#marigold-antigua-mix) + 2 [nasturtium](encyclopedia.md#nasturtium) seeds | Tomato & Pepper Mix | planted 2026-04-13 |
| `container-02` | planter-stand-1 | [Hartman's Yellow Gooseberry](encyclopedia.md#tomato-hartmans-yellow-gooseberry) tomato, solo | Tomato & Pepper Mix | planted 2026-04-13 |
| `container-03` | planter-stand-1 | **[Pepper 'Orange Blaze'](encyclopedia.md#pepper-orange-blaze)** + 1 [basil](encyclopedia.md#basil) + 2 [marigolds](encyclopedia.md#marigold-antigua-mix) | Tomato & Pepper Mix | proposed |
| `container-04` | planter-stand-1 | **[Pepper 'Lunch Box Orange'](encyclopedia.md#pepper-lunch-box-orange)** + 2 [marigolds](encyclopedia.md#marigold-antigua-mix) (+ [mesclun](encyclopedia.md#mesclun-mix-lettuce) undercrop while cool) | Tomato & Pepper Mix | proposed |
| `container-05` | planter-stand-2 | **[Lavender 'Provence'](encyclopedia.md#lavender-provence)**, solo | Mediterranean Herb Mix | proposed |
| `container-06` | planter-stand-2 | **[Citronella](encyclopedia.md#citronella)** (slot reserved; up-pots from 6 in → 2–3 gal → 5 gal over time) | General Herb Mix | proposed |
| `container-07` | planter-stand-2 | **3 [russet seed potatoes](encyclopedia.md#russet-potato)** | Potato Mix (no lime / no Mag-I-Cal) | proposed |
| `container-08` | planter-stand-2 | **2 [russet seed potatoes](encyclopedia.md#russet-potato)** | Potato Mix | proposed |

Exact slot assignment within each stand is flexible — group the two pepper pots together if you want them to cross-pollinate, and keep the potato pots side by side for easier hilling/harvest.

## Placement plan — outside the planter stands

| Container / item | Location | Plantings | Soil | Status |
|---|---|---|---|---|
| `container-09` (5 gal) | Deck floor / partial sun | 1× [lemon balm](encyclopedia.md#lemon-balm), solo | General Herb Mix | proposed |
| `container-10` (5 gal) | Deck floor / partial sun | 1× [lemon balm](encyclopedia.md#lemon-balm), solo | General Herb Mix | proposed |
| `container-12` (5 gal) | Deck floor / next to SSE rail (full sun) | 1× [FLO BIOorganic sweet pepper](encyclopedia.md#flo-bioorganic-sweet-pepper) (+ 1 [marigold](encyclopedia.md#marigold-antigua-mix) if available) | Tomato & Pepper Mix | proposed |
| existing 8 in pot | Deck surface near rail (sunnier) | [Strawberry 'Ever Sweet'](encyclopedia.md#strawberry-ever-sweet) | existing mix | in nursery |
| existing 12 in pot | Deck surface near rail (sunnier) | [Strawberry basket](encyclopedia.md#strawberry-unknown-basket) (unlabeled) | existing mix | in nursery |
| `container-11` (6 in) | deck / overwinters indoors | [Makrut lime](encyclopedia.md#makrut-lime-kaffir-lime), ~2 ft, up-pots toward 3–4 ft | Citrus Mix at next up-pot | planted (6+ yrs) |
| shallow tray or small pot (TBD) | South-deck / partial sun, or as undercrop in `container-04` | [Mesclun mix lettuce](encyclopedia.md#mesclun-mix-lettuce) | Lettuce / Salad Greens Mix | needs container decision |

**5 gal pot tally:** 24 total − 2 planted − 9 proposed = **13 spare** (one earmarked for [cucumber](encyclopedia.md#cucumber) when purchased).

## Plant sun requirements (quick reference)

| Plant | Needs | Where it goes |
|---|---|---|
| Tomato, pepper, citronella, lavender, potato, cucumber, marigold, basil, nasturtium, makrut lime | Full sun (6+ hr) | Planter stands / deck surface near rail |
| Strawberries | Full sun | Deck surface in sun zone |
| Lemon balm | Partial sun OK | Deck floor, partial-sun area |
| Mesclun lettuce | Partial sun preferred (cooler) | South side or undercrop |

## Open questions

- **Cucumber variety:** still unselected. When purchased, it takes one of the spare 5 gal pots and needs a full-sun slot — plan is to place it on the deck floor next to the SSE rail (like `container-12`).
- **Basil quantity:** we have 1 starter but `container-03` wants a basil companion; `container-04` would too. Either accept one pepper without basil, or acquire a second basil start.
- **Mesclun container:** needs either a shallow dedicated container or a commitment to undercrop `container-04`. Undercropping is simpler, but the starters must be removed before summer heat to avoid bolting.
