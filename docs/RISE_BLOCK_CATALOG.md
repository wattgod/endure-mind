# Rise 360 — Complete Block Catalog

> Last updated: 2026-03-12. Reflects Rise 360 features through Q1 2026.

---

## Lesson Types

| Type | Description |
|------|-------------|
| **Blocks Lesson** | Freeform stacking of any blocks. Primary lesson type. |
| **Quiz Lesson** | Graded assessment. SCORM reporting. Pass/fail configurable. Question banks supported. |
| **Storyline Lesson** | Full Storyline 360 project embedded as its own lesson. Unlimited interactivity. |

---

## Content Blocks

### Text
- **Paragraph** — standard rich text, formatting toolbar
- **Header** — H1-H5, customizable styles
- **Columns** — 2, 3, or 4 columns; optional image at top of each
- **Table** — structured data, 3 content widths, adjustable padding

### Statement
- 4 styled layouts + Note block
- Supports images and audio
- Use for bold single-sentence callouts, first principles, "remember this" moments

### Quote
- Multiple visual styles including carousel for multiple quotes
- No media embedding inside quotes

### List
- Numbered, checkbox, and bulleted
- Supports audio

### Image
| Variant | Behavior |
|---------|----------|
| Full-width | Crops responsively |
| Centered | Preserves aspect ratio, no crop |
| Text-and-image | Image size: 25%, 50%, 75% |
| Text-on-image | Overlay |
| Quote-on-image | Overlay |
| Click-to-zoom | Accessible (alt text + zoom button) |

### Gallery
- Carousel, 2/3/4-column grid
- All support audio

---

## Multimedia Blocks

| Block | Details |
|-------|---------|
| **Audio** | Upload, record in-browser, or AI-generated. All major formats. Max 5 GB/file. |
| **Video** | Upload. Captions (WebVTT). Playback speed 0.25x-2x. Floating window. Forward-seeking disable option. Max 5 GB. |
| **Embed** | URL or iframe. YouTube, Scribd, H5P, Genially, Padlet, Google Forms, etc. |
| **Attachment** | Downloadable files (PDF, DOCX, PPTX, etc.) |
| **Code Snippet** | Display-only code formatting |

---

## Interactive Blocks

### Accordion
- Unlimited items
- Each item: text + image + audio + video + web content
- No character limit on labels
- Use for: expandable science sections, "deep dive" optional content, FAQ patterns

### Tabs
- Unlimited tabs (>4 requires scrolling)
- Each tab: text + image + audio + video + web content
- Use for: side-by-side comparisons, category views, A-vs-B presentations

### Labeled Graphic
- Upload image (widths: small 760px, medium 1100px, full)
- Unlimited markers
- Marker styles: numbers 0-9 + icons
- Each marker: title, description, image, audio, video, web embed
- Customizable marker color via hex
- Use for: annotated diagrams, models, anatomical/physiological illustrations

### Process
- Carousel of media-rich steps
- Each step: image + audio + video + web content
- Step label toggle (can turn off for non-sequential interactions)
- Use for: protocols, procedures, step-by-step tools

### Timeline
- Interactive timeline of events
- Each event: text + image + audio + video + web content
- Use for: sequential progressions, historical arcs, development stages

### Flashcard Grid
- All cards visible at once
- Image + audio per card
- WCAG 2.1 conformant (100% Fable score)
- Use for: term definitions, concept drills, cue card libraries

### Flashcard Stack
- Cards appear one at a time
- Image + audio per card
- Fully keyboard navigable
- Use for: sequential reveal, self-testing, spaced practice

### Sorting Activity
- Drag-and-drop into categories
- Max 4 categories
- Unlimited items per category
- 80 characters per item (max 3 lines in mobile portrait)
- Ungraded; immediate visual feedback (checkmark/shake)
- **NOT keyboard accessible**
- Use for: classification exercises, fact-vs-story, strategy matching

### Scenario
- Branching dialogue with Content Library 360 characters
- Up to 3 responses per dialogue
- Character limits REMOVED (as of Oct 2025)
- Go To options: next content, different scene, end scenario, retry
- One character per scene (filter by clothing, gender, age)
- Custom background images
- Scene descriptions for screen readers
- Use for: coach-athlete dialogues, decision-point simulations, consequence branching

### Button
- Destinations: another lesson, external URL, email
- Customizable styling
- Use for: navigation branching, external tool links, gated reveal when prev/next disabled

### Continue
- 3 completion modes:
  - **None** — click to proceed (visual pacing only)
  - **Complete Block Directly Above** — targeted gate
  - **Complete All Blocks Above** — strict gate (forces all interactions)
- Compatible with: carousels, checklists, audio, video, accordions, tabs, labeled graphics, processes, sorting, flashcards, knowledge checks, scenarios
- Use for: pacing gates, mastery checkpoints, progressive disclosure

---

## Knowledge Check Blocks (Ungraded, Inline)

| Type | Details |
|------|---------|
| **Multiple Choice** | Unlimited choices. Media per question (image, video, web). Feedback: Any Response, Correct/Incorrect, By Choice. |
| **Multiple Response** | Unlimited choices, multiple correct. Media support. Feedback: Any Response, Correct/Incorrect. |
| **Fill-in-the-Blank** | Up to 10 acceptable answers. Case sensitivity toggle. Media support. |
| **Matching** | Up to 10 text-based pairs. Drag-and-drop. Keyboard accessible (Jan 2025). Character limits REMOVED. |

### Knowledge Check Settings
- Require correct answer to proceed: toggle
- Configurable retry limits
- Customizable correct/incorrect colors

---

## Quiz Lesson Settings

- Passing score: customizable percentage (default 80%)
- Retry attempts: unlimited (default) or limited
- Require passing to continue: toggle
- Randomize question order: toggle
- Shuffle answer choices: toggle
- Reveal answers: All, Incorrect only, or None
- Exclude from lesson count: toggle
- Question banks: create multiple banks; draw random or specific questions
- SCORM tracking: by course completion, quiz result, or Storyline block

---

## New Blocks (2025-2026)

### Custom Block
- Blank canvas with drag/drop elements
- Shapes (color, rounding, border, shadow, overlay), lines, text, images (AI-generated, Content Library, upload), video
- Grouping, rotation, flip
- Resize by dragging or entering W/H values
- **NOT fully mobile responsive**

### Code Block (Enhanced)
- Custom HTML/CSS/JavaScript
- Enhanced JavaScript API for custom animations and dynamic interactions
- Use for: custom interactive widgets, animations, specialized UIs

### AI Features
- **AI Course Drafts** — upload source doc or prompt, generates full course with interactivity
- **AI Writer** — contextual content generation referencing surrounding material
- **AI Audio** — generate narration from text
- **Equation Editor** — math/science equations, accessible

---

## Navigation Controls

| Feature | Effect |
|---------|--------|
| **Restrict Navigation** | Forces sequential lesson order |
| **Disable Prev/Next** | Removes built-in navigation; use Button blocks for custom routing |
| **Continue Blocks** | Gate sections within a lesson |
| **Block Entrance Animations** | All-or-nothing per course (not per block) |

---

## Accessibility Notes

| Block | Status |
|-------|--------|
| Sorting Activity | **NOT keyboard accessible** |
| Process | Visible focus indicator issues during keyboard nav |
| Continue | Can interfere with screen reader focus |
| Custom Block | Limited accessibility support |
| Matching | Redesigned for keyboard access (Jan 2025) |
| Flashcard Grid | WCAG 2.1 conformant |

---

## Key Limitations

- No variables, conditions, or state tracking
- No custom CSS on standard blocks (only via Code/Custom Block)
- Custom Blocks not mobile responsive
- iFrame/embed height issues on mobile
- No background audio
- Cannot nest interactive blocks inside other interactive blocks
- No drag-and-drop ordering (only sorting into categories)
- Scenario: max 3 responses per dialogue, one character on screen, stock characters only, no scoring
- Quiz: 4 question types only, no essay/open-response, no question-level branching
- SCORM 2004 does not support passing grade scores
- Cannot track both completion AND quiz score simultaneously
- No version control for individual blocks
