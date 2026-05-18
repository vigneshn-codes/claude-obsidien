# CLAUDE.md — LLM Wiki Operating System

> **Owner:** Vignesh Nagarajan
> **Domain / Niche:** Software-Coding
> **Brain's Purpose:** Workout programming — applying Alex Hormozi's business frameworks to the fitness-software and workout-product space
> **Last Updated:** 2026-05-17

---

## Purpose

This wiki is a **personal knowledge base** built from Alex Hormozi's $100M trilogy (*$100M Offers*, *$100M Leads*, *$100M Money Models*) and *Gym Launch Secrets*. It is structured so an LLM can act as a domain consultant — synthesizing, cross-referencing, and answering questions with the precision of someone who has internalized every framework.

**Primary use cases:**
- "How should I price this workout app feature?" → Value Equation + Trim & Stack
- "How do I get my first 100 users for a fitness product?" → Core Four + Rule of 100
- "Should I offer a free tier?" → Lead Magnet + CAC Payback
- "What makes a gym software offer irresistible?" → Grand Slam Offer + MAGIC Naming
- "Is my SaaS money model broken?" → Four Constraints + CAC Payback

---

## Directory Structure

```
/
├── CLAUDE.md          ← This file. The operating system.
├── log.md             ← Ingest log: what was processed and when.
├── raw/               ← SACRED. Source material. Never modify.
│   ├── 00-author-alex-hormozi.md
│   ├── 01-100m-offers.md
│   ├── 02-100m-leads.md
│   ├── 03-100m-money-models.md
│   ├── 04-gym-launch-secrets.md
│   ├── 05-key-frameworks.md
│   ├── 06-quotes.md
│   ├── 07-concept-value-equation.md
│   ├── 08-concept-grand-slam-offer.md
│   ├── 09-concept-core-four.md
│   ├── 10-concept-rule-of-100.md
│   ├── 11-concept-lead-magnet.md
│   ├── 12-concept-trim-and-stack.md
│   ├── 13-concept-bonuses-stack.md
│   ├── 14-concept-scarcity-urgency.md
│   ├── 15-concept-guarantee-taxonomy.md
│   ├── 16-concept-starving-crowd.md
│   ├── 17-concept-divergent-thinking.md
│   ├── 18-concept-more-better-new.md
│   ├── 19-concept-lead-getters.md
│   ├── 20-concept-magic-naming.md
│   ├── 21-concept-four-constraints.md
│   ├── 22-concept-cac-payback.md
│   ├── 23-company-acquisition-com.md
│   ├── 24-company-gym-launch.md
│   ├── 25-podcast-the-game.md
│   ├── 26-timeline-hormozi-career.md
│   ├── 27-comparison-trilogy-progression.md
│   ├── 28-critique-counterarguments.md
│   ├── 29-glossary.md
│   └── README.md
├── wiki/              ← LLM-owned. All synthesized knowledge lives here.
│   ├── index.md       ← Master index. Every wiki page must appear here.
│   ├── [concept].md   ← One concept per file, kebab-case.
│   └── ...
└── outputs/           ← Query results, generated documents, scratch work.
```

---

## Source Material Inventory

| File | Description |
|---|---|
| `00-author-alex-hormozi.md` | Bio, career arc, books, brand voice |
| `01-100m-offers.md` | Full summary of $100M Offers — offer design playbook |
| `02-100m-leads.md` | Full summary of $100M Leads — lead generation playbook |
| `03-100m-money-models.md` | Full summary of $100M Money Models — unit economics playbook |
| `04-gym-launch-secrets.md` | Full summary of Gym Launch Secrets — fitness-specific prototype |
| `05-key-frameworks.md` | Cross-book consolidated framework reference |
| `06-quotes.md` | Curated quotes, grouped by theme |
| `07-concept-value-equation.md` | Deep dive: the Value Equation formula |
| `08-concept-grand-slam-offer.md` | Deep dive: Grand Slam Offer construction |
| `09-concept-core-four.md` | Deep dive: the four lead generation channels |
| `10-concept-rule-of-100.md` | Deep dive: daily action commitment heuristic |
| `11-concept-lead-magnet.md` | Deep dive: lead magnet design framework |
| `12-concept-trim-and-stack.md` | Deep dive: surgical offer-design technique |
| `13-concept-bonuses-stack.md` | Deep dive: bonus design and the value stack |
| `14-concept-scarcity-urgency.md` | Deep dive: scarcity vs. urgency mechanics |
| `15-concept-guarantee-taxonomy.md` | Deep dive: 4-type guarantee framework |
| `16-concept-starving-crowd.md` | Deep dive: market selection and niche strategy |
| `17-concept-divergent-thinking.md` | Deep dive: divergent vs. convergent thinking in offer design |
| `18-concept-more-better-new.md` | Deep dive: the 3-knob growth diagnostic |
| `19-concept-lead-getters.md` | Deep dive: scaling lead gen via others |
| `20-concept-magic-naming.md` | Deep dive: the MAGIC naming formula |
| `21-concept-four-constraints.md` | Deep dive: diagnostic framework for business bottlenecks |
| `22-concept-cac-payback.md` | Deep dive: CAC payback < 30 days principle |
| `23-company-acquisition-com.md` | Acquisition.com — holding company overview |
| `24-company-gym-launch.md` | Gym Launch — origin, model, exit |
| `25-podcast-the-game.md` | The Game podcast — format, role, notable themes |
| `26-timeline-hormozi-career.md` | Chronological career timeline |
| `27-comparison-trilogy-progression.md` | How the three books build on each other |
| `28-critique-counterarguments.md` | Steel-manned critiques of Hormozi's work |
| `29-glossary.md` | Alphabetical vocabulary reference |

---

## Ingest Workflow

When a new file is added to `raw/`, do the following:

1. **Read the file completely** — do not skim.
2. **Identify distinct concepts** — each major concept, framework, or topic becomes its own wiki page.
3. **Check `wiki/index.md`** — if a concept already has a page, enrich it rather than duplicate.
4. **Create wiki pages** using the template below.
5. **Update `wiki/index.md`** — add every new page with category, filename, and one-line summary.
6. **Update `log.md`** — record the raw file name, date processed, and pages created/updated.
7. **Cross-reference aggressively** — every new page should link to existing pages using `[[page-name]]` notation.

### Wiki Page Template
```markdown
# [Title]

**Summary:** One or two sentences.

**Category:** [category name]
**Sources:** [raw file(s)]
**Related:** [[page-name]], [[page-name]]

---

## [Section]
...
```

---

## Query Workflow

When a user asks a question:

1. **Identify the relevant category** (see below).
2. **Load the primary wiki pages** for that category.
3. **Load cross-referenced pages** linked in those pages.
4. **Synthesize an answer** using specific frameworks, formulas, and examples — never vague advice.
5. **Cite wiki pages** at the end of the response.
6. **If the answer requires a document**, save it to `outputs/` with a timestamped filename.

---

## Wiki Page Categories

| # | Category | Covers |
|---|---|---|
| 1 | **Offer Design** | Value Equation, Grand Slam Offer, Trim & Stack, Bonuses, Guarantees, MAGIC Naming |
| 2 | **Lead Generation** | Core Four, Rule of 100, Lead Magnet, Lead Getters, More-Better-New |
| 3 | **Money Models** | CAC Payback, Four Constraints, Front/Back End, LTV mechanics |
| 4 | **Market Strategy** | Starving Crowd, Niche Selection, Market Indicators |
| 5 | **Mindset & Identity** | Standards heuristic, Skill Stacking, Divergent Thinking, Quotes |
| 6 | **Fitness / Gym Applications** | Gym Launch model, 6-Week Challenge, local service business applications |
| 7 | **Author & Companies** | Alex Hormozi bio, Acquisition.com, Gym Launch, The Game podcast |
| 8 | **Book Summaries** | $100M Offers, $100M Leads, $100M Money Models, Gym Launch Secrets |
| 9 | **Critique & Analysis** | Counterarguments, comparative analysis, trilogy progression |
| 10 | **Vocabulary** | Glossary terms, definitions |

---

## Rules

1. **`raw/` is sacred.** Never modify, rename, or delete any file in `raw/`.
2. **`wiki/` is LLM-owned.** All synthesis, organization, and expansion happens here.
3. **One concept per page.** If a page exceeds ~2000 words, split it.
4. **Always update the index.** No wiki page is valid unless it appears in `wiki/index.md`.
5. **Cross-reference aggressively.** Every concept that appears in another page should be linked using `[[page-name]]` notation.
6. **Frameworks over theory.** Specific steps, formulas, and worked examples over generalizations.
7. **Numbers over vibes.** "< 30 days CAC payback" beats "pay back costs quickly."
8. **Sources at the bottom.** Every wiki page lists the raw file(s) it was built from.
9. **Kebab-case filenames.** `value-equation.md`, not `Value Equation.md`.
10. **No broken links.** Before creating a cross-reference, verify the target file exists.
