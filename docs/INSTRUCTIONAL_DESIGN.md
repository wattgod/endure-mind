# Instructional Design Framework — Deliver Course

> Reference document for interaction patterns, learning science, and course design decisions.

---

## Primary Framework: Merrill's First Principles

Every module follows this arc. Every lesson touches at least 3 of 5.

| Principle | What It Means | Rise Implementation |
|-----------|---------------|---------------------|
| **Problem-Centered** | Learning starts with a real problem the learner recognizes | HOOK section — always a scenario the athlete has lived |
| **Activation** | Connect to prior knowledge before new content | Pre-module self-rating, "Think about..." prompts, cross-references to earlier modules |
| **Demonstration** | Show the skill, don't just describe it | Audio-guided exercises, Process blocks, Scenario blocks with modeled responses |
| **Application** | Practice with feedback | Knowledge checks, Sorting activities, Scenario decision points, downloadable practice worksheets |
| **Integration** | Apply to the learner's real life | Commitment prompts, downloadable toolkits, email drip retrieval prompts, The Daily 5 |

---

## Secondary Framework: Gagne's Nine Events (Lesson-Level Checklist)

| Event | Maps To | Rise Block |
|-------|---------|------------|
| 1. Gain Attention | HOOK | Text (scenario), Video, provocative question |
| 2. Inform Objectives | Lesson intro | Statement block with learning outcome |
| 3. Stimulate Recall | Activation | Note block cross-referencing prior lesson, pre-check question |
| 4. Present Content | PRINCIPLE + SCIENCE | Text, Tabs, Accordion, Labeled Graphic |
| 5. Provide Guidance | SCIENCE details | Accordion (expandable depth), Process (worked examples) |
| 6. Elicit Performance | TOOL practice | Scenario, Sorting, Knowledge Check, downloadable worksheet |
| 7. Provide Feedback | Assessment feedback | Knowledge check By Choice feedback, Scenario consequence branches |
| 8. Assess Performance | Module quiz | Quiz Lesson |
| 9. Enhance Retention | CLOSE + follow-up | Statement (takeaway), email drip retrieval prompts |

---

## Motivation Design: ARCS Model

| Component | Strategy | Implementation |
|-----------|----------|----------------|
| **Attention** | Perceptual arousal: hooks that trigger recognition ("you've had this experience"). Inquiry arousal: counterintuitive claims. Variability: alternate block types every 2-3 blocks. | Hooks open with real scenarios. Never 3 text blocks in a row. |
| **Relevance** | Present Worth: "this will change your next race." Future Usefulness: "athletes who practice this..." Familiarity: real sport examples, not lab studies. | Every tool has a "when to use it" context. Science sections lead with sport application. |
| **Confidence** | Incremental challenge. Early wins (first knowledge checks are easy). Mastery-gated progression where appropriate. | Module 1 knowledge checks are recall-level. Module 5-6 checks require application. |
| **Satisfaction** | Immediate application (downloadable tools). Progress visibility. Before/after self-assessment delta. Completion celebration. | Evidence File, Performance Statements card, Night-Before Checklist — all usable immediately. |

---

## Pacing and Spacing

### Lesson Length
- **Target: 8-12 minutes per lesson** (reading + interactions)
- Text blocks: max 150-300 words each (manuscript averages 800-1200 — trim 60-75%)
- Video content (if added): 6 minutes max per segment
- Audio exercises: 3-20 minutes (these are the exception — sustained attention by design)

### Course Cadence
- **Recommended: 2-3 lessons per week**, not all at once
- Drip-feed option: release one module per week (5 lessons/week for 6 weeks)
- Gated progression: each module must be completed before next unlocks

### Spacing and Retrieval
- **Module Quiz Lessons** serve as retrieval practice for that module's content
- **Cross-references** in later modules resurface earlier concepts (natural interleaving)
- **Email drip sequence** (outside Rise): retrieval prompts at Day 1, 3, 7, 21 after each module
- **The Daily 5** (Lesson 6.6) is the course's built-in spaced practice system

### The Testing Effect
- Every lesson includes at least ONE retrieval opportunity (knowledge check, scenario, sorting, or fill-in-the-blank)
- Retrieval practice improves retention more than re-reading — this is the single most evidence-backed learning strategy

---

## Interaction Design Patterns

### Pattern 1: Tell → Show → Do → Check
The core cadence. Never more than 2-3 content blocks without an interactive element.

```
Text (Tell) → Labeled Graphic (Show) → Scenario (Do) → Knowledge Check (Check)
```

### Pattern 2: Progressive Disclosure
Surface summary visible by default. "Go Deeper" expandable content for motivated learners.

```
Statement (key principle) → Accordion (research details, optional depth)
```

### Pattern 3: Before/After Self-Rating
Bookend modules with self-assessment to show growth.

```
Module Start: "Rate yourself 1-10 on [dimension]" (Knowledge Check or Note prompt)
Module End: "Rate yourself again. Notice the change."
```

### Pattern 4: Consequence Branching
Scenario with realistic options, each leading to a different outcome — not just "right/wrong."

```
Scenario: "You're at mile 60 and your stomach is revolting. What do you do?"
→ Option A: Push through → Scene: consequences of ignoring signals
→ Option B: Slow down and address it → Scene: strategic recovery
→ Option C: Pull over and quit → Scene: when stopping IS the right call
```

### Pattern 5: Commitment Device
After every TOOL section, prompt the learner to commit.

```
Process (tool steps) → Note: "I will practice [tool] at [time] for [duration]."
→ Attachment: downloadable practice log
```

### Pattern 6: Normative Feedback
Reduce anxiety and increase engagement with aggregate context.

```
Note: "Most athletes rate themselves 4-6 on this dimension when starting the course."
```

### Pattern 7: Retrieval Sandwich
Open a lesson with a recall question from the previous lesson. Close with a forward prompt.

```
Lesson open: Knowledge Check — "What are the three flow triggers from Lesson 4.1?"
Lesson close: Note — "Next lesson, we'll challenge the assumption that flow is always the goal."
```

---

## Gamification Decisions

### What We Use
- **Progress bars** — module-level and course-level (Rise native)
- **Mastery gating** — require correct answers on key knowledge checks to proceed
- **Before/after self-assessment** — show personal growth (self-competition)
- **Streak-friendly design** — Daily 5 as the built-in habit system
- **Completion celebration** — final module close acknowledges the full journey

### What We Skip
- Points and badges — superficial gamification reduces intrinsic motivation in adults
- Leaderboards — contradicts the course's mastery orientation (task > ego)
- Arbitrary rewards — participation trophies undermine the Stoic Coach voice
- Timed quizzes — adds anxiety without pedagogical value for this content

---

## Content Adaptation Rules

### Manuscript → Rise
1. **Trim aggressively.** 800-1200 word sections → 150-300 word blocks. Cut repetition, reduce examples from 3 to 1-2, eliminate filler.
2. **Preserve the voice.** The Stoic Coach — terse, direct, earned authority, dry wit. Cut word count, not personality. No corporate e-learning tone.
3. **Break long science into Accordions.** Default experience should be lean. Motivated learners click to go deep.
4. **Every tool → Process block + Attachment.** Steps must be explicit, numbered, actionable. Downloadable worksheet for real-world use.
5. **Cross-references → Note blocks.** When lessons build on earlier concepts, surface the connection explicitly.
6. **Hooks stay narrative.** Don't convert hooks to bullet points. The story IS the learning trigger.

### What NOT to Trim
- The opening hook scenario (Merrill's problem-centered principle)
- First-principle Statement blocks (the anchor for each lesson)
- Tool steps (the actionable output)
- Voice — the personality is the brand differentiator

---

## Kolb's Cycle Applied to Each Module

| Stage | Module Section | Block Pattern |
|-------|---------------|---------------|
| **Concrete Experience** | HOOK — the athlete has lived this | Text (narrative scenario) |
| **Reflective Observation** | PRINCIPLE — what's actually happening | Statement + Text |
| **Abstract Conceptualization** | SCIENCE — the research framework | Accordion, Tabs, Labeled Graphic |
| **Active Experimentation** | TOOL — try it yourself | Process, Scenario, Audio, Attachment |

---

## Bloom's Taxonomy Across Course Arc

| Level | Where It Lives | Block Types |
|-------|---------------|-------------|
| **Remember** | Module 1-2 knowledge checks | Fill-in-the-Blank, Multiple Choice (recall) |
| **Understand** | Module 1-3 science sections | Accordion, Tabs, Flashcard |
| **Apply** | Module 3-4 tools | Process, Scenario, Sorting |
| **Analyze** | Module 4-5 self-assessments | Labeled Graphic (analysis), Knowledge Check (application) |
| **Evaluate** | Module 5-6 race-day decisions | Scenario (consequence branching), Sorting (strategy selection) |
| **Create** | Module 6 — build your own system | Daily 5 (synthesis), MT Self-Assessment (self-directed review), Schema Statement (creation) |

---

## Email Drip Sequence (Outside Rise)

Not a Rise feature — requires external email system (ConvertKit, Mailchimp, etc.)

| Timing | Content |
|--------|---------|
| Day 0 | Welcome + course overview + first module unlocked |
| Day 1 after each module | Retrieval prompt: "Can you name the 3 key concepts from Module X?" |
| Day 3 | Practice reminder: "Have you tried [tool] in training yet?" |
| Day 7 | Deeper retrieval: "How did [tool] work? What did you notice?" |
| Day 21 | Long-term retrieval + connection: "How has [concept] changed how you think about training?" |
| Halfway (Module 3 complete) | Celebration + progress acknowledgment + preview of what's ahead |
| Course complete | Summary of all tools, The Daily 5 reminder, invitation to community |
| 30 days post-completion | "Are you still doing The Daily 5? Here's why it matters." |

---

## Accessibility Commitments

- All images have descriptive alt text
- All videos have WebVTT captions
- Audio exercises have text transcripts available as Attachments
- Avoid Sorting blocks for critical content (not keyboard accessible)
- Use Flashcard Grid (not Stack) when keyboard access matters
- Test all Scenarios with screen readers before publishing
- Labeled Graphics use descriptive marker titles (not just numbers)
