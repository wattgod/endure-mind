# Deliver — Platform Mapping (Glide Labs)

> Maps RISE_SPEC block types to Glide Labs platform block types.
> The Deliver course is built on the Glide Labs platform, NOT Rise 360.

## Platform: Glide Labs

- **Repo:** `wattgod/glide-labs-platform`
- **Content format:** Single JSON file per course (`deliver.json`)
- **Rendering:** Python static generator (Jinja2) + Alpine.js
- **Delivery:** WordPress/LearnDash with Stripe, or standalone static HTML
- **Design system:** Røkt (neo-brutalist) — Deliver will need its own theme variant

---

## Block Type Mapping

| RISE_SPEC Block | Glide Labs Block | Variant/Notes |
|-----------------|------------------|---------------|
| Text | `text` | variant: `heading-paragraph`, `paragraph`, `subheading-paragraph` |
| Statement | `callout` | variant: `highlight` — bold single-sentence callout |
| Note | `callout` | variant: `tip` (Coach's Note), `info` (cross-reference), `warning` |
| Quote | `callout` | variant: `quote` — or dedicated `quote` block (Phase 1) |
| List | `text` | HTML `<ul>` or `<ol>` inside text content |
| Image | `image` | variant: `hero`, `full`, `figure` |
| Audio | `audio` | Phase 2 block — guided exercises |
| Attachment | `download` | PDF worksheets, checklists, cards |
| Accordion | `accordion` | Science deep-dives, progressive disclosure |
| Tabs | `tabs` | Side-by-side comparisons (System 1/2, Flow/Clutch) |
| Flashcard Grid/Stack | `flashcard` | Term definitions, PETTLEP cards |
| Labeled Graphic | `labeled_graphic` | Phase 2 — Identity Tree, Flow Channel, Yerkes-Dodson |
| Process | `process` | Tool protocols, step-by-step procedures |
| Timeline | `timeline` | Phase 1 — grief stages, burnout trajectory, competence model |
| Sorting | `sorting` | Phase 2 — fact/story, coping strategy classification |
| Scenario | `scenario` | Phase 2 — coach-athlete branching decisions |
| Button | `button` | Phase 1 — external links, lesson navigation |
| Continue | `continue` | Phase 1 — progress gate |
| Multiple Choice | `quiz` | Single correct answer |
| Multiple Response | `knowledge-check` | Multiple correct answers (Phase 2) |
| Fill-in-the-Blank | `fill-in-blank` | Recall drills (Phase 2) |
| Matching | `matching` | Pair concepts to definitions (Phase 2) |
| Before/After Self-Rating | `self-assessment` | Phase 2 — Likert-scale reflection, no right answer |
| Commitment Prompt | `callout` | variant: `highlight` — "I will practice..." |
| Normative Feedback | `callout` | variant: `info` — "Most athletes report..." |
| Learning Objective | `callout` | variant: `info` — "By the end of this lesson..." |
| Retrieval Opener | `quiz` | Single recall question from prior lesson |

---

## Block Availability

### Ready Now (12 blocks)
`text`, `image`, `video`, `callout`, `tabs`, `accordion`, `process`, `quiz`, `flashcard`, `download`, `divider`, `checklist`

### Phase 1 — Rise Parity (needed for Sprint 1)
`quote`, `timeline`, `button`, `continue`, `statement`, `numbered-divider`

### Phase 2 — Beyond Rise (needed for Sprint 2+)
`audio`, `labeled_graphic`, `sorting`, `scenario`, `knowledge-check` (multiple-response), `fill-in-blank`, `matching`, `self-assessment`, `practice-loop`

---

## Design System: Deliver Theme

The XC ski course uses Røkt (neo-brutalist, Norwegian). Deliver needs its own visual identity while sharing the platform architecture.

### Proposed: Stoic Theme

| Token | Røkt (XC Ski) | Stoic (Deliver) |
|-------|---------------|-----------------|
| `--gl-primary` | `#0e0e0c` Expedition Black | `#1a1a2e` Deep Navy |
| `--gl-accent` | `#d08a70` Smoked Salmon | Gradient midpoint `#50B5E7` (Endure Labs teal-blue) |
| `--gl-gold` | `#c49a5a` Birch Gold | `#c49a5a` (keep — warm accent) |
| `--gl-paper` | `#f8f6f2` Warm Snow | `#f5f7fa` Cool Cloud |
| `--gl-paper-warm` | `#f0ece6` Parchment | `#eef1f5` Slate Mist |
| `--gl-muted` | `#8a8878` Lichen | `#7a8599` Steel |
| `--gl-font-data` | Sometype Mono | Sometype Mono (keep) |
| `--gl-font-editorial` | Literata | Literata (keep) |
| `--gl-font-ui` | Inter | Inter (keep) |
| Border radius | 0 (neo-brutalist) | TBD — may soften to 2-4px for sport psych warmth |

### Voice Adaptation
- XC Ski: "Knowledgeable peer"
- Deliver: "The Stoic Coach" — terse, direct, earned authority, dry wit

---

## Content Authoring Workflow

1. Write lesson content in `deliver.json` following the schema
2. Place images in `course/static/img/deliver/`
3. Run `python scripts/generate_course.py --course course/content/deliver.json --output output/deliver`
4. Preview in browser
5. When ready, deploy via LearnDash or static hosting

---

## What Needs Building Before Sprint 1

### Platform blocks needed (contribute to glide-labs-platform repo):
1. `timeline` block template (Phase 1 — needed for grief stages, burnout, competence)
2. `audio` block template (Phase 2 — needed for guided exercises)
3. `self-assessment` block template (Phase 2 — needed for before/after ratings, MT assessment)
4. `scenario` block template (Phase 2 — needed for consequence branching)

### Can launch Sprint 1 with existing blocks:
`text`, `callout`, `tabs`, `accordion`, `process`, `quiz`, `flashcard`, `download`, `divider`

Module 1 only needs `labeled_graphic` (Yerkes-Dodson, Attention Matrix) from Phase 2 — can substitute with `image` + `callout` annotations until built.
