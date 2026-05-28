# /raw — Alex Hormozi Books (LLM Wiki Source Material)

Raw, atomic source notes for the "Alex Hormozi Books" topic — structured as a Karpathy-style LLM wiki seed corpus. One concept (or book, or company, or critique) per file. Cross-linked.

## Total: 30 files

### 📘 Books (5)
| File | Topic |
|---|---|
| `00-author-alex-hormozi.md` | Author bio, career arc, ventures |
| `01-100m-offers.md` | $100M Offers (2021) — full book breakdown |
| `02-100m-leads.md` | $100M Leads (2023) — full book breakdown |
| `03-100m-money-models.md` | $100M Money Models (2025) — full book breakdown |
| `04-gym-launch-secrets.md` | Gym Launch Secrets (2019) — full book breakdown |

### 🧩 Frameworks (cross-cutting) (2)
| File | Topic |
|---|---|
| `05-key-frameworks.md` | Consolidated frameworks reference |
| `06-quotes.md` | Notable quotes corpus, grouped by theme |

### 🔑 Atomic Concepts (16)
| File | Concept |
|---|---|
| `07-concept-value-equation.md` | The Value Equation formula |
| `08-concept-grand-slam-offer.md` | Grand Slam Offer (5 parts + construction) |
| `09-concept-core-four.md` | The Core Four lead-gen channels |
| `10-concept-rule-of-100.md` | The Rule of 100 daily action rule |
| `11-concept-lead-magnet.md` | Lead Magnet design (5 steps + 6 types) |
| `12-concept-trim-and-stack.md` | Trim & Stack offer-design technique |
| `13-concept-bonuses-stack.md` | Bonuses & the Value Stack |
| `14-concept-scarcity-urgency.md` | Scarcity & Urgency mechanics |
| `15-concept-guarantee-taxonomy.md` | The 4 guarantee types |
| `16-concept-starving-crowd.md` | Starving Crowd market-selection principle |
| `17-concept-divergent-thinking.md` | Divergent vs Convergent thinking |
| `18-concept-more-better-new.md` | More-Better-New growth heuristic |
| `19-concept-lead-getters.md` | The 4 Lead Getter types |
| `20-concept-magic-naming.md` | MAGIC naming formula |
| `21-concept-four-constraints.md` | Leads / Sales / Delivery / Profit |
| `22-concept-cac-payback.md` | CAC Payback < 30 days |

### 🏢 Companies & Media (3)
| File | Entity |
|---|---|
| `23-company-acquisition-com.md` | Acquisition.com holding company |
| `24-company-gym-launch.md` | Gym Launch (2017–2021) |
| `25-podcast-the-game.md` | *The Game* podcast |

### 📚 Meta (4)
| File | Purpose |
|---|---|
| `26-timeline-hormozi-career.md` | Chronological career timeline |
| `27-comparison-trilogy-progression.md` | How the 3 books compose |
| `28-critique-counterarguments.md` | Steel-manned critiques and defenses |
| `29-glossary.md` | A–Z vocabulary index |

## Design Notes
These files are the **raw input layer** for an Andrej-Karpathy-style LLM Wiki. They are intentionally:

- **Atomic** — one concept per file, so each file can be embedded, retrieved, and cited independently.
- **Cross-linked** — every file lists `Related Files` so a downstream wiki builder can construct the entity graph automatically.
- **Verbose-but-skimmable** — favor over-inclusion over editorial trimming; use clear H2/H3 headers so chunking is clean.
- **Source-cited (where applicable)** — book files link the URLs the notes were synthesized from.
- **Balanced** — `28-critique-counterarguments.md` is included so the eventual wiki isn't hagiographic.

## Suggested Downstream Wiki Structure (`/wiki/`)
Once these raw files are processed, the wiki layer might hold:

- `alex-hormozi.md` — author entity page (synthesized from 00 + 26)
- `100m-offers.md`, `100m-leads.md`, `100m-money-models.md`, `gym-launch-secrets.md` — book entity pages
- One page per concept file (`value-equation.md`, `core-four.md`, `grand-slam-offer.md`, …)
- `acquisition-com.md`, `gym-launch.md` — company entity pages
- `critiques.md` — the steel-manned-counterarguments page
- A `_glossary.md` index page

Inbound links: each book page links to its concept pages.
Outbound links: each concept page links back to the books that introduced it and to neighboring concepts.

## Provenance
Synthesized from public summaries, book listings, podcast transcripts, and Hormozi's own published materials. See individual book files for source URLs.
