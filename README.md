# learn.curiosta.com

Static site for **learn.curiosta.com** — timeless fundamentals (scientific temperament, first principles, mass & energy).

## Status

- **Published** — served by GitHub Pages from `main` `/` of [curiosta/learn](https://github.com/curiosta/learn).
- Intended domain: `learn.curiosta.com` (see `CNAME`).
- Part of the Curiosta family (sand + dark-sea brand). Sibling properties include kinetic.curiosta.com and equity.curiosta.com.

## Files

| Path | Role |
|------|------|
| `index.html` | Home — hero (two lines + Skills that compound), How we teach, curriculum preview, lessons, ideas and tools |
| `curriculum.html` | Publishable curriculum (10 themes + method; themes without lessons marked “Lessons in preparation”) |
| `lessons/index.html` | Lessons hub — every published lesson by theme, themes 03–10 in preparation |
| `lessons/how-to-know/index.html` | Theme 01 lessons index |
| `lessons/how-to-know/01-seeing-vs-believing.html` | Lesson 1 · Seeing vs believing (CDS + Socratic) |
| `lessons/how-to-know/02-falsifiability.html` | Lesson 2 · Falsifiability (CDS + Socratic) |
| `lessons/how-to-know/03-choosing-your-questions.html` | Lesson 3 · Choosing your questions (CDS + Socratic; five checks on a question) |
| `lessons/first-principles/index.html` | Theme 02 lessons index |
| `lessons/first-principles/01-strip-to-what-is-true.html` | Lesson 1 · Strip it to what is true (CDS + Socratic) |
| `lessons/first-principles/02-frame-then-invent.html` | Lesson 2 · Frame the problem, then invent (CDS + Socratic; problem framing + TRIZ ideation) |
| `ideas.html` | Ideas hub — the two lines, Skills that compound, the aiming diagram |
| `made-by-human.html` | Made by human is the new luxury (model page) |
| `tribe-building.html` | Tribe building is the next big thing (model page) |
| `compounding-skills.html` | Skills that compound — eight career skills mapped to the themes |
| `aiming-diagram.html` | The aiming diagram — interactive lead-time SVG + lifespan skill breakdown |
| `resources.html` | Skills & resources index — tools and refreshers that support the lessons |
| `resources/triz-refresher.html` | TRIZ refresher (supports Theme 02 · First principles) |
| `control-map.html` | Control map — five verbs × five objects of practical power over mass and energy, kitchen → industry → ISRO/NASA/CERN/DRDO → record on Earth; Kardashev scale |
| `on-this-day.html` | On this day: mastering mass and energy — 12 month memory cards of dated feats (1644→2025), built from `data/on-this-day.json` |
| `data/on-this-day.json` | Dataset for On this day (events, reserve, dropped) |
| `style.css` | Shared Curiosta tokens and chrome (+ lesson, control map, on this day and hub components) |
| `sitemap.xml`, `robots.txt`, `og-image.png` | Search and social metadata |
| `CNAME` | `learn.curiosta.com` |

## METHOD

Teaching delivery is **Socratic**: guide with questions; the learner reconstructs the model. Ability to explain beats rote formula solving.

Lessons follow a **Concept Development Study (CDS)** arc, adapted from John S. Hutchinson, *Concept Development Studies in Chemistry* (Connexions / Rice, CC BY 2.0):

1. **Foundation** — state assumed knowledge.
2. **Questions that arise** from the Foundation.
3. **Observations + logical deductions** (not memorised facts).
4. **Further questions → refine** until a model answers the questions.
5. **Models are not proven theorems** — prefer the simplest explanation (Occam).
6. **Study by reasoning / outlining / explaining** — not memorising.

Curriculum themes (how to know → agency without wages) are written as publishable copy for that arc; Theme 01 Lessons 1 (*Seeing vs believing*), 2 (*Falsifiability*) and 3 (*Choosing your questions*) are published under `lessons/how-to-know/`; Theme 02 Lessons 1 (*Strip it to what is true*) and 2 (*Frame the problem, then invent*) under `lessons/first-principles/`.

## Site map

Every page carries the same top nav — **Home · Curriculum · Lessons · Ideas · Control map · On this day · Skills & resources** — and the same footer (adds *How we teach*). On phones the nav is a swipeable row of pills. Breadcrumbs: lessons → `Lessons / Theme / Lesson N`; idea pages → `Ideas / …`.

## Brand

Uses exact shared Curiosta tokens (`--ink`, `--sea-*`, `--teal`, `--coral`, `--sand`, …), Fraunces / Inter / JetBrains Mono, sticky dark nav, dark hero, sand body, white cards, coral primary CTA, dark footer. `lang=en-IN`.

## Honesty

No prices. No Giscus. No invented analytics. Footer reads **learn.curiosta.com · a Curiosta brand**.

## Local preview

Open `index.html` or `curriculum.html` in a browser, or serve the folder with any static file server.
