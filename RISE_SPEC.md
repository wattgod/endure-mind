# Deliver — Rise 360 Course Blueprint v2

## Overview

**Course:** Deliver — Mental Performance for Endurance Athletes
**Platform:** Articulate Rise 360
**Structure:** 6 modules → 30 lessons + 6 quiz lessons → ~5 hours of content
**Lesson architecture:** HOOK → PRINCIPLE → SCIENCE → TOOL → CLOSE
**Design framework:** Merrill's First Principles (Problem → Activation → Demonstration → Application → Integration)
**Interaction cadence:** Tell / Show / Do / Check — never more than 2-3 content blocks without an interactive element
**Target lesson length:** 8-12 minutes (reading + interactions)

---

## Design Principles

### Merrill's First Principles (Module-Level)
| Principle | Course Section | Implementation |
|-----------|---------------|----------------|
| **Problem** | HOOK | Real scenario the athlete has lived — not abstract |
| **Activation** | Module opener | Before/After self-rating, retrieval question from prior module |
| **Demonstration** | SCIENCE + TOOL | Labeled Graphics, Process blocks, Audio-guided exercises |
| **Application** | TOOL + checks | Scenarios, Sorting, Knowledge Checks, downloadable worksheets |
| **Integration** | CLOSE + commitment | Commitment prompt, downloadable toolkit, Daily 5 synthesis |

### Gagne's Nine Events (Lesson-Level Checklist)
Every lesson should hit at least 7 of 9:
1. Gain Attention → HOOK (Text scenario)
2. Inform Objectives → **Learning Objective** (Statement block, NEW — added to every lesson)
3. Stimulate Recall → **Retrieval Opener** (Knowledge Check from prior lesson, NEW)
4. Present Content → PRINCIPLE + SCIENCE
5. Provide Guidance → Accordion deep-dives, Process worked examples
6. Elicit Performance → Scenario, Sorting, worksheet
7. Provide Feedback → Knowledge Check (By Choice feedback mode)
8. Assess Performance → Module Quiz Lesson
9. Enhance Retention → CLOSE takeaway + commitment prompt

### ARCS Motivation Design
| Component | Strategy |
|-----------|----------|
| **Attention** | Hooks that trigger recognition. Block type variety. Counterintuitive claims. |
| **Relevance** | "This will change your next race." Real sport examples, not lab abstractions. |
| **Confidence** | Early knowledge checks are recall-level. Later checks require application. Mastery gating. |
| **Satisfaction** | Immediately usable tools. Progress visibility. Before/after growth evidence. |

---

## New Elements (v2 Additions)

Based on instructional design research, v2 adds these patterns to every lesson:

### 1. Learning Objective (Statement Block)
Opens every lesson after the HOOK. One sentence: "By the end of this lesson, you will be able to [verb] [concept]."

### 2. Retrieval Opener (Knowledge Check)
First block after Learning Objective in Lessons 1.2+ — a single recall question from the PREVIOUS lesson. Activates prior knowledge and leverages the testing effect.

### 3. Commitment Prompt (Note Block)
Closes every TOOL section. "I will practice [tool] at [specific time] for [specific duration]." Not capturable in Rise — the prompt itself creates the intention.

### 4. Before/After Self-Rating
Module openers include a self-rating prompt (1-10 on a key dimension). Module closers (final lesson's CLOSE) repeat the rating. The delta shows growth.

### 5. Consequence Branching Scenarios
Upgraded from simple right/wrong to 3-option branching where each path shows realistic consequences — not just "correct/incorrect" but "here's what happens when you choose this."

### 6. Normative Feedback (Note Blocks)
Strategic "Most athletes report..." statements to reduce isolation and normalize the learning gap. Used sparingly — 1-2 per module.

### 7. Embed Blocks for Reflection
Google Form or Typeform embeds for structured reflection at module boundaries. Not required for progression but prompted.

---

## Block Usage Reference

> Full catalog: `docs/RISE_BLOCK_CATALOG.md`
> Design framework: `docs/INSTRUCTIONAL_DESIGN.md`

### Content Blocks
| Block | Use Case | Max Length |
|-------|----------|-----------|
| **Text** | Narrative prose (hooks, principles, closes) | 2-3 paragraphs (~150-300 words) |
| **Statement** | First principles, key quotes, learning objectives | 1-2 sentences |
| **Note** | Coach's Notes, cross-references, commitment prompts, normative feedback | 2-3 sentences |
| **Quote** | Attributed research quotes (Frankl, Noakes, Bandura) | 1-2 sentences + attribution |
| **List** | Steps, inventories, deployment contexts | 4-8 items |
| **Image** | Diagrams, models (use text-and-image for annotated versions) | — |
| **Audio** | Guided exercises from Guided Practice Library | 3-20 min |
| **Attachment** | Downloadable worksheets, printable checklists, practice logs | PDF |
| **Embed** | Google Forms for reflection journals, external tools | — |
| **Columns** | Side-by-side comparisons when Tabs feel too heavy | 2-3 columns |

### Interactive Blocks
| Block | Use Case | Key Constraints |
|-------|----------|-----------------|
| **Accordion** | Expandable science sections, progressive disclosure | Unlimited items |
| **Tabs** | A-vs-B comparisons (System 1 vs. 2, Flow vs. Clutch) | >4 tabs scrolls |
| **Flashcard Grid** | Term definitions, cue card libraries | Accessible (WCAG 2.1) |
| **Flashcard Stack** | Sequential reveal, self-testing | One card at a time |
| **Labeled Graphic** | Annotated diagrams (Identity Tree, Flow Channel, Grit Stack) | Unlimited markers |
| **Process** | Step-by-step protocols (tools, procedures) | Media per step |
| **Timeline** | Sequential progressions (grief stages, burnout trajectory, competence model) | Media per event |
| **Sorting** | Classification exercises (fact/story, coping strategy matching) | Max 4 categories, 80 chars/item, NOT keyboard accessible |
| **Scenario** | Coach-athlete decisions, consequence branching | Max 3 responses/dialogue, stock characters |
| **Continue** | Pacing gates, mastery checkpoints | 3 completion modes |
| **Button** | External links, email, lesson navigation | — |

### Assessment Blocks
| Block | Use Case | Key Constraints |
|-------|----------|-----------------|
| **Multiple Choice** | Recall and comprehension checks | Feedback: By Choice mode for detailed per-answer feedback |
| **Multiple Response** | Multi-factor concepts (Bandura's 4 sources, flow triggers) | Multiple correct |
| **Fill-in-the-Blank** | Formula recall (6-2-7, Grit Stack steps) | Up to 10 acceptable answers |
| **Matching** | Pair concepts to definitions, strategies to situations | Up to 10 pairs |

---

## Global Lesson Template

Every lesson follows this block sequence:

```
1. HOOK
   └── Text (narrative scenario, 2-3 paragraphs max)
   └── Continue (pacing gate — optional, for long hooks)

2. LEARNING OBJECTIVE [NEW v2]
   └── Statement ("By the end of this lesson, you will...")

3. RETRIEVAL OPENER [NEW v2, Lesson 1.2+]
   └── Knowledge Check (one question from PREVIOUS lesson)

4. PRINCIPLE
   └── Statement (first-principle sentence)
   └── Text (elaboration, 1-2 paragraphs)

5. SCIENCE
   └── Interactive (Tabs, Labeled Graphic, or Accordion for primary explanation)
   └── Accordion (deep-dive panels for optional depth)
   └── Knowledge Check (comprehension check, By Choice feedback)

6. TOOL
   └── Statement (tool name)
   └── Process (step-by-step protocol)
   └── [Audio] (if Guided Practice Library entry exists)
   └── [Scenario] (application exercise — consequence branching where possible)
   └── [Attachment] (downloadable worksheet/card)
   └── Note: Commitment Prompt [NEW v2] ("I will practice...")

7. CLOSE
   └── Statement (key takeaway — one sentence)
   └── Note (bridge to next lesson)
```

### Module Opener (First Lesson of Each Module)
Add BEFORE the HOOK:
```
└── Statement: Module title + first principle
└── Note: Before/After Self-Rating prompt [NEW v2]
    "Rate yourself 1-10 on [module's core dimension]. Write it down."
```

### Module Closer (Last Lesson of Each Module)
Add AFTER the CLOSE:
```
└── Note: "Rate yourself again on [dimension]. Compare to your Module start rating."
└── Note: Normative feedback [NEW v2]
    "Most athletes improve 1-3 points after applying these tools for 2 weeks."
```

---

## Module 1: The Two Brains

**Before/After Self-Rating:** "Rate yourself 1-10: How well can you recognize when your reactive brain is in control during training or racing?"

### Lesson 1.1: The Chimp and The Coach

| Section | Block | Content |
|---------|-------|---------|
| MODULE OPENER | **Statement** | "Module 1: The Two Brains. Your brain has two systems — one reacts, one decides." |
| MODULE OPENER | **Note** | Self-Rating: "Rate yourself 1-10: How well can you recognize when your reactive brain is in control? Write it down." |
| HOOK | **Text** | Start-line panic scenario — heart rate at 130, bad highlight reel. Trim to 3 paragraphs. |
| HOOK | **Continue** | "Why is your brain acting like you're about to get eaten by a bear?" |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will understand the two-brain system and be able to catch the reactive brain in the act." |
| PRINCIPLE | **Statement** | "You have two brains. One reacts, one decides. Performance lives in the gap between them." |
| PRINCIPLE | **Tabs** | Tab 1: "The Chimp (System 1)" — fast, emotional, automatic, limbic. Tab 2: "The Coach (System 2)" — deliberate, slower, rational, prefrontal cortex. |
| SCIENCE | **Accordion** | Panel 1: "Kahneman — dual-process theory (2011)." Panel 2: "Marshall & Paterson — The Brave Athlete (2017)." Panel 3: "The fight-or-flight cascade — amygdala → hypothalamus → sympathetic activation." Panel 4: "Ego depletion — prefrontal resources are finite (Baumeister, Hagger 2009)." |
| SCIENCE | **Quote** | Frankl: "Between stimulus and response there is a space." |
| SCIENCE | **Multiple Choice** | "The chimp brain fires before the coach brain because..." → (b) it processes information ~5x faster. Feedback By Choice. |
| TOOL | **Statement** | "The Gap Check" |
| TOOL | **Process** | 4 steps: Next session → Notice one reactive moment → Name it: "That was the chimp" → Don't fix it, just see it. |
| TOOL | **Scenario** | 3-option consequence branch: Car passes close, grip tightens. A: Chase the anger (consequence: wasted energy, elevated stress). B: Name it — "that was the chimp" (consequence: gap created, calm returns). C: Ignore it and push harder (consequence: chimp stays in control, unexamined). |
| TOOL | **Note** | Commitment: "I will practice the Gap Check during my next training session on [date]." |
| CLOSE | **Statement** | "Start seeing the gap, and you've already started training it." |
| CLOSE | **Note** | "Next — why your brain is the biggest limiter on your physical performance." |

---

### Lesson 1.2: Your Brain Is the Limiter

| Section | Block | Content |
|---------|-------|---------|
| HOOK | **Text** | Two sessions, same week, wildly different output. Tuesday = concrete. Saturday = flying. |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will understand how your brain throttles performance and be able to measure its markup." |
| RETRIEVAL | **Multiple Choice** | "From Lesson 1.1: The 'gap' between stimulus and response is: (a) fixed at birth (b) trainable (c) only relevant in racing (d) a personality trait." → (b) |
| PRINCIPLE | **Statement** | "Your brain is the limiter. Not your legs, not your lungs, not your lactate threshold." |
| SCIENCE | **Tabs** | Tab 1: "Central Governor Theory (Noakes)" — brain as governor, sprint finish paradox. Tab 2: "Psychobiological Model (Marcora)" — exhaustion as a decision based on perceived effort + motivation. |
| SCIENCE | **Quote** | Ross: "You cannot improve as an endurance athlete unless you change your relationship with perception of effort." |
| SCIENCE | **Accordion** | Panel 1: Sprint finish paradox. Panel 2: Blanchfield et al. (2014) — self-talk group rode longer at lower RPE. Panel 3: Perception of effort is cognitive — filtered through self-talk, emotion, attention, beliefs. |
| SCIENCE | **Multiple Choice** | "Marcora's model says you stop when: ..." → (c) perceived effort exceeds willingness to tolerate it. |
| TOOL | **Statement** | "The RPE Journal" |
| TOOL | **Process** | 4 steps: After 3 hard sessions → rate RPE at hardest moment → rate again 10 min post → compare the gap. |
| TOOL | **Attachment** | RPE Journal template (3-session log). |
| TOOL | **Note** | Normative: "Most athletes find a 1-3 point gap between in-moment and retrospective RPE." |
| TOOL | **Note** | Commitment: "I will log RPE for my next 3 hard sessions starting [date]." |
| CLOSE | **Statement** | "The point where you think you've given everything is a signal, not a wall." |
| CLOSE | **Note** | "Next — what happens when your brain is too amped up, or not amped up enough." |

---

### Lesson 1.3: The Arousal Dial

| Section | Block | Content |
|---------|-------|---------|
| HOOK | **Text** | Jason (over-aroused, explodes in races) and Sarah (under-aroused, misses splits). |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will know your personal optimal arousal zone." |
| RETRIEVAL | **Fill-in-the-Blank** | "According to the Central Governor Theory, the sprint finish is possible because the brain was holding back ___." → "reserve" / "energy" / "capacity" |
| PRINCIPLE | **Statement** | "Your best performance lives in a specific zone on the arousal dial — and that zone is different for every athlete." |
| SCIENCE | **Labeled Graphic** | Yerkes-Dodson inverted U — annotated: left "Under-aroused," peak "Optimal Zone," right "Over-aroused." |
| SCIENCE | **Accordion** | Panel 1: Yerkes-Dodson (1908). Panel 2: Sympathetic vs. parasympathetic. Panel 3: Individual Zones of Optimal Functioning (Hanin). Panel 4: Task complexity × arousal interaction. |
| SCIENCE | **Multiple Choice** | "Peak performance occurs at..." → (c) a moderate, optimal level specific to the athlete. |
| TOOL | **Statement** | "Know Your Zone" |
| TOOL | **Process** | 4 steps: Rate arousal 1-10 at 3 best performances → rate 3 worst → compare → note tendency (too high or too low). |
| TOOL | **Attachment** | Know Your Zone worksheet (6-row table). |
| TOOL | **Note** | Commitment: "My optimal zone appears to be [X-Y]. I tend to be too [high/low]." |
| CLOSE | **Statement** | "Once you know your zone, you can learn to move the dial there on demand." |
| CLOSE | **Note** | "Next — the fastest tool for moving that dial: your breath." |

---

### Lesson 1.4: The 6-2-7

| Section | Block | Content |
|---------|-------|---------|
| HOOK | **Text** | The moment between the gun and the first step — what if you could reset your nervous system in 15 seconds? |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will have a practiced breathing protocol that shifts your nervous system from reactive to deliberate." |
| RETRIEVAL | **Multiple Choice** | "Your personal optimal arousal zone is: (a) the same for all athletes (b) always at maximum (c) specific to you and identifiable from past performance (d) irrelevant." → (c) |
| PRINCIPLE | **Statement** | "Diaphragmatic breathing is the fastest bridge from the reactive brain to the deliberate brain." |
| PRINCIPLE | **Text** | Why the formula works — exhale > inhale activates parasympathetic. Counting occupies the chimp. |
| SCIENCE | **Accordion** | Panel 1: Vagus nerve stimulation. Panel 2: Diaphragmatic vs. shallow breathing cascade. Panel 3: Dual-task benefit — counting prevents rumination. |
| SCIENCE | **Fill-in-the-Blank** | "The 6-2-7: inhale ___ seconds, hold ___ seconds, exhale ___ seconds." → 6, 2, 7 |
| TOOL | **Statement** | "The 6-2-7 Protocol" |
| TOOL | **Process** | 4 steps: Inhale nose 6s → Hold 2s → Exhale mouth 7s → Repeat 3-5 cycles. |
| TOOL | **Audio** | Guided 6-2-7 Breathing Protocol (5 min). |
| TOOL | **Scenario** | 3-option: Start line, HR 140, 2 minutes to gun. A: Distract by chatting (consequence: chimp still running). B: 3 cycles of 6-2-7 (consequence: HR drops, clarity returns). C: Start running to burn energy (consequence: wasted glycogen, still anxious). |
| TOOL | **Note** | Commitment: "I will practice 6-2-7 for 5 minutes daily this week, starting tonight." |
| CLOSE | **Statement** | "Practice 5 minutes daily for one week. Then deploy before your next hard session." |
| CLOSE | **Note** | "Next — the spotlight you didn't know you controlled." |

---

### Lesson 1.5: Attention — The Spotlight You Control

| Section | Block | Content |
|---------|-------|---------|
| HOOK | **Text** | Attention is a skill, not a given. Most athletes never train it. |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will be able to deliberately shift between attention modes during training." |
| RETRIEVAL | **Fill-in-the-Blank** | "The 6-2-7 works because the exhale is longer than the inhale, activating the ___ nervous system." → "parasympathetic" |
| PRINCIPLE | **Statement** | "Your attention is a spotlight — it can be broad or narrow, internal or external. And you control where it points." |
| SCIENCE | **Labeled Graphic** | 2×2 attention matrix — Broad/Narrow × Internal/External. Each quadrant labeled with sport examples. |
| SCIENCE | **Flashcard Grid** | 4 cards: Broad-External → "Scanning terrain, tracking competitors." Narrow-Internal → "Monitoring effort, pacing, body signals." Narrow-External → "Technical execution — foot placement, cornering line." Broad-Internal → "Strategic thinking, big-picture body check." |
| SCIENCE | **Accordion** | Panel 1: Nideffer (1976). Panel 2: Stuck spotlight — pain fixation, data obsession. Panel 3: Attentional flexibility as trainable. |
| TOOL | **Statement** | "The Spotlight Drill" |
| TOOL | **Process** | 3 steps: During long session, every 10 min shift: body scan → surroundings → technique. Notice which mode is hardest. |
| TOOL | **Note** | Commitment: "I will run the Spotlight Drill during my next long session on [date]." |
| CLOSE | **Statement** | "Attention isn't something that happens to you. It's something you aim." |
| CLOSE | **Note** | "Module 1 complete. You now have the operating manual." |
| MODULE CLOSER | **Note** | "Rate yourself again 1-10: How well can you recognize when your reactive brain is in control? Compare to your Module 1 start rating." |

### Module 1 Quiz Lesson

| # | Type | Question | Bloom's Level |
|---|------|----------|---------------|
| 1 | MC | "What does 'the gap' refer to in the Gap Check?" | Remember |
| 2 | MC | "The sprint finish paradox supports which theory?" | Understand |
| 3 | MR | "Select ALL triggers that shift the arousal dial upward." | Understand |
| 4 | FitB | "The 6-2-7: inhale ___, hold ___, exhale ___." | Remember |
| 5 | Matching | Match attention mode to sport scenario. | Apply |
| 6 | MC | "In-the-moment RPE is typically ___ vs. retrospective RPE." | Understand |
| 7 | MC | "You're in a race, RPE feels like 9. The RPE Journal taught you this is probably a ___." | Apply |

---

## Module 2: The Stories You Tell Yourself

**Before/After Self-Rating:** "Rate yourself 1-10: How clearly can you identify the 'I am' statements driving your athletic identity?"

### Lesson 2.1: The Identity Tree

| Section | Block | Content |
|---------|-------|---------|
| MODULE OPENER | **Statement** | "Module 2: The Stories You Tell Yourself. You will never outperform your self-concept." |
| MODULE OPENER | **Note** | Self-Rating: "Rate yourself 1-10: How clearly can you identify the stories driving your athletic identity?" |
| HOOK | **Text** | Worst race of the year — brain writing identity stories. "I'm just not a racer." |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will have audited your 'I am' statements and identified which are serving you and which are limiting you." |
| PRINCIPLE | **Statement** | "You will never outperform your self-concept. The words after 'I am' set the ceiling." |
| SCIENCE | **Labeled Graphic** | Identity Tree — roots (self-concept), trunk (self-worth), branches (self-esteem), leaves (self-efficacy). Each annotated. |
| SCIENCE | **Accordion** | Panel 1: Ross's tree metaphor. Panel 2: Harter — self-worth vs. self-esteem. Panel 3: Bandura (1977) — self-efficacy. Panel 4: Identity Foreclosure (Brewer, Van Raalte & Linder, 1993). |
| SCIENCE | **Scenario** | Consequence branch: Athlete with serious knee injury, entire identity = training. A: "I'm nothing without running" → Identity Foreclosure consequences. B: "Running is important to me, but I'm also [other things]" → Resilient identity response. C: "This injury doesn't affect me at all" → Denial consequences. |
| TOOL | **Statement** | "The Identity Audit" |
| TOOL | **Process** | 4 steps: Write 5 "I am" statements → Ask: fact or story? → Serving or limiting? → Where did it come from? |
| TOOL | **Attachment** | Identity Audit worksheet. |
| TOOL | **Note** | Commitment: "I will complete the Identity Audit before my next training session." |
| CLOSE | **Statement** | "You can't fix what you can't see. Now you can see it." |
| CLOSE | **Note** | "Next — where confidence actually comes from." |

---

### Lesson 2.2: Where Confidence Actually Comes From

| Section | Block | Content |
|---------|-------|---------|
| HOOK | **Text** | The most confident you've ever felt before a race — why that day was different. Evidence, not magic. |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will have started an Evidence File — a curated collection of proof that you can do hard things." |
| RETRIEVAL | **Matching** | Match tree layer (roots, trunk, branches, leaves) to concept (self-concept, self-worth, self-esteem, self-efficacy). |
| PRINCIPLE | **Statement** | "Confidence isn't a personality trait. It's a judgment based on available evidence." |
| SCIENCE | **Labeled Graphic** | Bandura's 4 sources — ranked pyramid. 1: Past performance. 2: Vicarious experience. 3: Verbal persuasion. 4: Physiological state. |
| SCIENCE | **Accordion** | Panel 1: Past performance — gold standard AND trap (negative spirals). Panel 2: Vicarious experience — training partners. Panel 3: Verbal persuasion — weakest positive, strongest negative. Panel 4: Physiological state — warm-up as confidence signal. |
| SCIENCE | **Multiple Response** | "Select ALL of Bandura's four sources." (6 options, 4 correct) |
| TOOL | **Statement** | "The Evidence File" |
| TOOL | **Process** | 4 steps: Start a list → write 10 moments proving you can do hard things → add weekly → read before every race. |
| TOOL | **Note** | Coach's Note: "Not results. Moments. 'The day I held pace on the last interval when every cell wanted to stop.'" |
| TOOL | **Note** | Commitment: "I will write my first 10 Evidence File entries by [date]." |
| CLOSE | **Statement** | "Confidence isn't magic. It's architecture." |
| CLOSE | **Note** | "Next — when your standards are so high that no evidence feels like enough." |

---

### Lesson 2.3: The Perfectionism Trap

| Section | Block | Content |
|---------|-------|---------|
| HOOK | **Text** | PR in a half marathon — 1:32 — and you're disappointed. Four perfect intervals, one fade, session = "failure." |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will be able to distinguish adaptive from maladaptive perfectionism and deploy the Teammate Test." |
| RETRIEVAL | **MC** | "The strongest source of self-efficacy is: (a) verbal persuasion (b) past performance (c) physiological state (d) vicarious experience." → (b) |
| PRINCIPLE | **Statement** | "High standards + self-compassion = growth. High standards + self-punishment = burnout." |
| SCIENCE | **Tabs** | Tab 1: "Adaptive Perfectionism" — high standards, flexible response, self-compassion. Tab 2: "Maladaptive Perfectionism" — rigid standards, catastrophic response, burnout. |
| SCIENCE | **Accordion** | Panel 1: Stoeber & Otto (2006). Panel 2: Neff's self-compassion research. Panel 3: Burnout link. |
| SCIENCE | **MC** | "The key difference between high standards and maladaptive perfectionism is..." → (b) how you respond to falling short. |
| TOOL | **Statement** | "The Teammate Test" |
| TOOL | **Process** | 4 steps: After bad session → write what you'd say to a teammate → read it back → say it to yourself. |
| TOOL | **Scenario** | 3-option: 4/5 intervals perfect, 5th faded. Training partner texts "How'd it go?" A: "Terrible. Blew the last interval." (consequence: reinforces perfectionist narrative). B: "4 out of 5 perfect, faded on the 5th. Solid day." (consequence: accurate, balanced). C: "Great! Everything was perfect!" (consequence: denial, no learning). |
| TOOL | **Note** | Commitment: "The next time I have a 'bad' session, I will run the Teammate Test before judging myself." |
| CLOSE | **Statement** | "The standard isn't the problem. What you do to yourself when you miss it — that's the problem." |
| CLOSE | **Note** | "Next — building the words that answer the chimp." |

---

### Lesson 2.4: Performance Statements

| Section | Block | Content |
|---------|-------|---------|
| HOOK | **Text** | Five words can change a race. The power of a single pre-planned phrase. |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will have three memorized Performance Statements — one technical, one pain response, one process." |
| RETRIEVAL | **MC** | "The Teammate Test helps you counter: (a) low fitness (b) maladaptive perfectionism (c) over-arousal (d) poor nutrition." → (b) |
| PRINCIPLE | **Statement** | "You can't control your thoughts. But you can answer them." |
| PRINCIPLE | **Text** | Detachment — chessboard metaphor. Performance Statements replace negative thoughts with action-directed ones. |
| SCIENCE | **Tabs** | Tab 1: Technical — "Ass back, heel down." Tab 2: Pain Response — "If you keep pedaling, you'll get there." Tab 3: Process — "Something is better than nothing." |
| SCIENCE | **Accordion** | Panel 1: Hatzigeorgiadis et al. (2011) — 32-study meta-analysis. Panel 2: Planned vs. reactive self-talk. Panel 3: Third-person self-talk for psychological distance. |
| TOOL | **Statement** | "Build Your 3 Performance Statements" |
| TOOL | **Process** | 5 steps: Write one Technical → one Pain Response → one Process → Memorize → Deploy when chess pieces appear. |
| TOOL | **Attachment** | Performance Statements card (wallet-sized). |
| TOOL | **Note** | Commitment: "My 3 Performance Statements: Technical: ___. Pain: ___. Process: ___." |
| CLOSE | **Statement** | "Memorize them. Deploy them. The chimp talks first — you get the last word." |
| CLOSE | **Note** | "Next — defining who you are as an athlete, on purpose." |

---

### Lesson 2.5: The Athletic Schema Statement

| Section | Block | Content |
|---------|-------|---------|
| HOOK | **Text** | The vacuum — if you don't define your athletic identity, negativity fills it. |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will have a written Athletic Schema Statement that you read daily." |
| RETRIEVAL | **Matching** | Match Performance Statement type (Technical, Pain Response, Process) to example phrase. |
| PRINCIPLE | **Statement** | "Your self-schema is the thoughts and feelings you have about yourself as an athlete. Choose it, or it chooses you." |
| SCIENCE | **Accordion** | Panel 1: Schema theory. Panel 2: Why writing it down strengthens belief. Panel 3: Connection to Bandura's self-efficacy. |
| TOOL | **Statement** | "Write Your Athletic Schema Statement" |
| TOOL | **Process** | 4 steps: Identify greatest strength → Name boldest aspiration → Combine → Read daily. |
| TOOL | **Note** | Coach's Note: "Yes, it sounds dumb. Do it anyway." |
| TOOL | **Scenario** | 2-option: Everything feels forced and embarrassing. A: Skip it (consequence: vacuum fills with negativity). B: Write it anyway (consequence: discomfort is the point — the target changes). |
| TOOL | **Note** | Commitment: "My Schema Statement: [strength] + [aspiration]. I will read it daily starting tonight." |
| CLOSE | **Statement** | "The words after 'I am' set the ceiling. Choose them on purpose." |
| CLOSE | **Note** | "Module 2 complete. Identity established." |
| MODULE CLOSER | **Note** | "Rate yourself again: How clearly can you identify the stories driving your athletic identity? Compare to your Module 2 start." |

### Module 2 Quiz Lesson

| # | Type | Question | Bloom's |
|---|------|----------|---------|
| 1 | Matching | Tree layer → concept (roots/trunk/branches/leaves). | Remember |
| 2 | MC | "Identity Foreclosure occurs when..." | Understand |
| 3 | MR | "Select ALL four sources of self-efficacy." | Remember |
| 4 | MC | "The Teammate Test addresses which psychological trap?" | Apply |
| 5 | Matching | Performance Statement type → example phrase. | Apply |
| 6 | FitB | "A Schema Statement has two parts: '___' (strength) and '___' (aspiration)." | Remember |
| 7 | MC | "An athlete who dismisses every compliment and fixates on the one thing that went wrong is exhibiting..." | Apply |

---

## Module 3: Seeing Before Doing

**Before/After Self-Rating:** "Rate yourself 1-10: How skilled are you at deliberately using mental imagery and self-talk during training and racing?"

### Lesson 3.1: Visualization Is Not Daydreaming

| Section | Block | Content |
|---------|-------|---------|
| MODULE OPENER | **Statement** | "Module 3: Seeing Before Doing. The brain doesn't fully distinguish between vividly imagined and actually experienced." |
| MODULE OPENER | **Note** | Self-Rating: "Rate yourself 1-10: How skilled are you at using mental imagery during training and racing?" |
| HOOK | **Text** | The lemon exercise — imaginary lemon, real saliva. Your brain can't tell the difference. |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will be able to perform a 60-second first-person skill rehearsal using the PETTLEP framework." |
| PRINCIPLE | **Statement** | "Mental imagery is a full-sensory cognitive rehearsal — not just seeing, but hearing, feeling, smelling." |
| PRINCIPLE | **Tabs** | Tab 1: "First-Person (Internal)" — activates motor cortex, stronger for execution. Tab 2: "Third-Person (External)" — activates visual areas, useful for form correction. |
| SCIENCE | **Flashcard Grid** | 7 PETTLEP cards: Physical, Environment, Task, Timing, Learning, Emotion, Perspective. |
| SCIENCE | **Accordion** | Panel 1: Holmes & Collins (2001) — PETTLEP model. Panel 2: Process vs. outcome imagery. Panel 3: Neural equivalence — motor circuits fire at lower amplitude. |
| SCIENCE | **MC** | "For motor execution, which perspective is more effective?" → (b) First-person. |
| TOOL | **Statement** | "60-Second Skill Rehearsal" |
| TOOL | **Process** | 4 steps: Pick one technical skill → Close eyes → First-person, full sensory detail → 60 seconds, daily. |
| TOOL | **Note** | Commitment: "I will practice 60-second skill rehearsal daily for [specific skill] starting tonight." |
| CLOSE | **Statement** | "This is not daydreaming. This is rehearsal. And your brain can't tell the difference." |
| CLOSE | **Note** | "Next — building a full highlight reel." |

---

### Lesson 3.2: The Personal Highlight Reel

| Section | Block | Content |
|---------|-------|---------|
| HOOK | **Text** | Watching race footage vs. actually visualizing — one is passive, one is neurologically active. |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will have constructed a 3-part Highlight Reel and practiced running it." |
| RETRIEVAL | **MC** | "PETTLEP imagery should be done in which perspective for motor execution?" → First-person. |
| PRINCIPLE | **Statement** | "The act of visualizing contains the ergogenic value — watching video of yourself is not enough." |
| SCIENCE | **Process** | The 3 parts: 1. Empowering past memory (5-20 sec). 2. Crucial future moment. 3. Upcoming event — your best performance. |
| SCIENCE | **Accordion** | Panel 1: Why 3 parts — past anchors, future programs, upcoming bridges. Panel 2: Rules — first-person, max detail, include emotion. |
| TOOL | **Statement** | "Build Your Highlight Reel" |
| TOOL | **Process** | 5 steps: Choose past memory → Choose future moment → Choose upcoming event → String together → Practice. |
| TOOL | **Audio** | Guided Highlight Reel Visualization (10 min). |
| TOOL | **Note** | Commitment: "I will run my Highlight Reel before my next key session on [date]." |
| CLOSE | **Statement** | "Your brain has been running highlight reels your whole career — mostly the bad kind. Time to curate." |
| CLOSE | **Note** | "Next — visualizing what goes wrong." |

---

### Lesson 3.3: Disaster Planning

| Section | Block | Content |
|---------|-------|---------|
| HOOK | **Text** | Counterintuitive: visualizing what goes WRONG is more valuable than what goes right. |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will have 5 specific If-Then plans for your most likely race-day problems." |
| RETRIEVAL | **MC** | "The Highlight Reel has 3 parts. Which is the FIRST?" → Empowering past memory. |
| PRINCIPLE | **Statement** | "If-Then plans convert coping decisions into pre-programmed responses — eliminating in-race deliberation cost." |
| SCIENCE | **Accordion** | Panel 1: Gollwitzer (1999). Panel 2: 94-study meta-analysis. Panel 3: Specificity matters. |
| SCIENCE | **Sorting** | Sort into "Effective If-Then" vs. "Too Vague": 4 examples (2 each). |
| TOOL | **Statement** | "Build 5 If-Then Plans" |
| TOOL | **Process** | 4 steps: 5 most likely problems → "If [specific], I will [specific]" → Visualize each in first person → Rehearse until automatic. |
| TOOL | **Attachment** | If-Then Plan worksheet (5 rows). |
| TOOL | **Note** | Commitment: "I will have 5 complete If-Then plans written and rehearsed by [race date - 2 weeks]." |
| CLOSE | **Statement** | "Hope is not a race strategy. Preparation is." |
| CLOSE | **Note** | "Next — the soundtrack running in your head." |

---

### Lesson 3.4: Self-Talk — The Soundtrack

| Section | Block | Content |
|---------|-------|---------|
| HOOK | **Text** | The internal monologue — most athletes never script it. |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will have a scripted Race Soundtrack with 6 phrases assigned to specific race moments." |
| RETRIEVAL | **MC** | "An effective If-Then plan must be: ..." → (b) specific in both trigger and response. |
| PRINCIPLE | **Statement** | "System 1 self-talk is reactive. System 2 self-talk is planned. You can choose which runs." |
| SCIENCE | **Tabs** | Tab 1: Instructional — technique cues, better for complex tasks. Tab 2: Motivational — psyche-up, better for endurance/arousal. |
| SCIENCE | **Accordion** | Panel 1: Hatzigeorgiadis et al. (2011). Panel 2: Third-person self-talk. Panel 3: Cross-reference to Lesson 2.4 Performance Statements. |
| SCIENCE | **Note** | "This builds on Performance Statements (2.4). Here we assign them to specific race moments." |
| TOOL | **Statement** | "Script Your Race Soundtrack" |
| TOOL | **Process** | 4 steps: Write 3 instructional cues → 3 motivational phrases → Assign each to a race moment → Rehearse in training. |
| TOOL | **Attachment** | Race Soundtrack card (6 slots with assigned moments). |
| TOOL | **Note** | Commitment: "I will rehearse my Race Soundtrack during 2 training sessions this week." |
| CLOSE | **Statement** | "You're going to talk to yourself during the race anyway. Decide what you're going to say." |
| CLOSE | **Note** | "Next — watching your thoughts without getting caught in them." |

---

### Lesson 3.5: Detachment in Action

| Section | Block | Content |
|---------|-------|---------|
| HOOK | **Text** | The chessboard deepened — you are not your thoughts. |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will have practiced the 3-Minute Breathing Space and understand the five facets of mindfulness." |
| RETRIEVAL | **Matching** | Match self-talk type (Instructional, Motivational) to use case. |
| PRINCIPLE | **Statement** | "Mindfulness: paying attention, on purpose, in the present moment, nonjudgmentally." — Kabat-Zinn |
| SCIENCE | **Flashcard Grid** | 5 cards: Observing, Describing, Acting with Awareness, Non-Judging, Non-Reacting. |
| SCIENCE | **Accordion** | Panel 1: Kabat-Zinn's framework. Panel 2: Five facets. Panel 3: MSPE — performance maintained 12 months post-intervention. |
| TOOL | **Statement** | "3-Minute Breathing Space" |
| TOOL | **Process** | 3 steps: Awareness (1 min) → Gathering (1 min) → Expansion (1 min). |
| TOOL | **Audio** | 3-Minute Breathing Space (3 min). |
| TOOL | **Note** | Commitment: "I will practice the 3-Minute Breathing Space daily for one week starting today." |
| CLOSE | **Statement** | "Practice daily. Then deploy before your next race." |
| CLOSE | **Note** | "Module 3 complete. You can see before doing." |
| MODULE CLOSER | **Note** | "Rate yourself again: mental imagery and self-talk skill. Compare to Module 3 start." |

### Module 3 Quiz Lesson

| # | Type | Question | Bloom's |
|---|------|----------|---------|
| 1 | MC | "Process imagery beats outcome imagery because..." | Understand |
| 2 | FitB | "PETTLEP: Physical, ___, Task, Timing, ___, Emotion, Perspective." | Remember |
| 3 | MC | "The Highlight Reel's three parts are..." | Remember |
| 4 | Sorting | Sort self-talk into "Instructional" vs. "Motivational." | Apply |
| 5 | Matching | Mindfulness facet → definition. | Remember |
| 6 | MC | "An effective If-Then plan must be..." | Apply |
| 7 | Scenario | Race situation requiring If-Then deployment — choose best response. | Evaluate |

---

## Module 4: The Zone and The Red Line

**Before/After Self-Rating:** "Rate yourself 1-10: How consistently can you access peak performance states in training and racing?"

### Lesson 4.1: What Flow Actually Is

| Section | Block | Content |
|---------|-------|---------|
| MODULE OPENER | **Statement** | "Module 4: The Zone and The Red Line. Peak performance isn't about trying harder." |
| MODULE OPENER | **Note** | Self-Rating: "Rate yourself 1-10: How consistently can you access peak performance states?" |
| HOOK | **Text** | That day — everything clicks, an hour vanishes, someone talks and the spell breaks. |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will know the three triggers of flow and be able to audit your training for flow-readiness." |
| PRINCIPLE | **Statement** | "Flow is not about trying harder. Flow is what happens when the trying stops and the doing takes over." |
| SCIENCE | **Labeled Graphic** | Flow Channel — X: Perceived Skill, Y: Challenge. Diagonal band = flow. Below = boredom. Above = anxiety. |
| SCIENCE | **Tabs** | Tab 1: Challenge-Skills Balance. Tab 2: Clear Goals. Tab 3: Unambiguous Feedback. |
| SCIENCE | **Accordion** | Panel 1: Csikszentmihalyi (1975). Panel 2: Jackson (1996) — elite athlete research. Panel 3: Flow State Scale — 36-item validated instrument. |
| SCIENCE | **MR** | "Select ALL three flow triggers." (6 options, 3 correct) |
| TOOL | **Statement** | "Flow Conditions Audit" |
| TOOL | **Process** | 5 steps: After 3 sessions → rate each trigger 1-5 → when closest to flow? → what conditions enabled it? → adjust future sessions. |
| TOOL | **Attachment** | Flow Conditions Audit (3-session log). |
| TOOL | **Note** | Commitment: "I will complete 3 Flow Conditions Audits over the next 2 weeks." |
| CLOSE | **Statement** | "You can't force flow. But you can engineer the conditions." |
| CLOSE | **Note** | "Next — what happens when flow isn't available and you need something harder." |

---

### Lesson 4.2: Clutch vs. Flow

| Section | Block | Content |
|---------|-------|---------|
| HOOK | **Text** | The deciding mile — not effortless, everything. That's not flow. |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will know when to seek flow vs. deploy clutch, and have practiced the clutch trigger." |
| RETRIEVAL | **MR** | "Select the three flow triggers." (Quick reinforcement) |
| PRINCIPLE | **Statement** | "Flow is effortless. Clutch is deliberate. The deciding mile is usually clutch." |
| SCIENCE | **Tabs** | Tab 1: Flow — effortless, automatic, "let it happen." Tab 2: Clutch — deliberate, intense, maximum effort. |
| SCIENCE | **Accordion** | Panel 1: Swann — clutch as distinct state. Panel 2: When to seek each. Panel 3: Clutch uses tools from M1-M3. |
| SCIENCE | **Note** | Cross-reference: "Clutch reappears in Lesson 5.4 (Deliver) as the core race-day mechanism." |
| TOOL | **Statement** | "Clutch Trigger Practice" |
| TOOL | **Process** | 5 steps: Hard interval → narrow focus → max effort cue → commit fully → notice difference from flow. |
| TOOL | **Note** | Commitment: "I will practice the clutch trigger in my next interval session." |
| CLOSE | **Statement** | "Know the difference. Seek flow in training. Deploy clutch when the race demands it." |
| CLOSE | **Note** | "Next — the engine under everything." |

---

### Lesson 4.3: Motivation — The Engine Under Everything

| Section | Block | Content |
|---------|-------|---------|
| HOOK | **Text** | "Why am I doing this?" — the question nobody asks until they need to. |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will have assessed your motivation profile and identified warning signs." |
| RETRIEVAL | **MC** | "Clutch performance is best described as..." → deliberate, intense, maximum focused effort. |
| PRINCIPLE | **Statement** | "Intrinsic motivation is the engine. When it runs dry, no external fuel replaces it." |
| SCIENCE | **Labeled Graphic** | SDT three needs: Autonomy, Competence, Relatedness — annotated with sport examples. |
| SCIENCE | **Timeline** | Burnout trajectory: Intrinsic → Extrinsic shift → Amotivation → Burnout. |
| SCIENCE | **Accordion** | Panel 1: Deci & Ryan — SDT. Panel 2: Harmonious vs. obsessive passion. Panel 3: Task vs. ego orientation. |
| SCIENCE | **MC** | "SDT's three needs are..." → (b) autonomy, competence, relatedness. |
| TOOL | **Statement** | "The Motivation Check" |
| TOOL | **Process** | 4 steps: Write why you do this → categorize intrinsic/extrinsic → warning sign if mostly extrinsic → reconnect with one intrinsic reason. |
| TOOL | **Note** | Commitment: "I will complete the Motivation Check and share my answer with [trusted person]." |
| CLOSE | **Statement** | "If the engine is running on wrong fuel, no pacing strategy saves you." |
| CLOSE | **Note** | "Next — when your data becomes a cage." |

---

### Lesson 4.4: The Data Trap

| Section | Block | Content |
|---------|-------|---------|
| HOOK | **Text** | Checking power meter mid-flow — spell breaks. Watch says 10 seconds off — panic. |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will have committed to one analog session per week." |
| RETRIEVAL | **MC** | "The burnout trajectory moves from..." → intrinsic → extrinsic → amotivation → burnout. |
| PRINCIPLE | **Statement** | "When wearables override body signals, you lose the ability to read yourself." |
| SCIENCE | **Tabs** | Tab 1: When Data Helps — trends, confirmation, post-session. Tab 2: When Data Hurts — mid-flow, override, comparison, dependence. |
| SCIENCE | **Accordion** | Panel 1: Perception discrepancy. Panel 2: Interoceptive suppression. Panel 3: 16 technostress factors (Frontiers, 2024). |
| TOOL | **Statement** | "Analog Sessions" |
| TOOL | **Process** | 4 steps: Once/week, zero devices → rate RPE by feel → compare to data sessions → rebuild internal signal. |
| TOOL | **Scenario** | 3-option: 2 hours in, feeling strong. Glance at power: 15W below target. A: Hammer to hit the number (consequence: override internal signal, break flow). B: Note discrepancy, trust feel, adjust gradually (consequence: preserved flow, maintained internal calibration). C: Stop and recalibrate device (consequence: session disrupted, focus lost). |
| TOOL | **Note** | Commitment: "I will do one analog session this week on [day]." |
| CLOSE | **Statement** | "Data is a tool, not a coach. Learn to read yourself again." |
| CLOSE | **Note** | "Next — the day motivation isn't there." |

---

### Lesson 4.5: Training Monotony and The Unmotivated Day

| Section | Block | Content |
|---------|-------|---------|
| HOOK | **Text** | "I should want to do this but I don't" — not laziness, neurology. |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will have a protocol for unmotivated days that protects both your training and your brain." |
| RETRIEVAL | **MC** | "Interoceptive suppression means..." → heavy data use atrophies internal signal reading. |
| PRINCIPLE | **Statement** | "Mental fatigue is neurological, not a character flaw." |
| SCIENCE | **Accordion** | Panel 1: Adenosine in the ACC. Panel 2: Adenosine antagonizes dopamine — double penalty. Panel 3: Brain Endurance Training. Panel 4: Caffeine as adenosine antagonist. |
| SCIENCE | **MC** | "Training monotony fatigue is caused by..." → (c) adenosine accumulation. |
| TOOL | **Statement** | "The Off-Day Protocol" |
| TOOL | **Process** | 4 steps: Name it ("mental fatigue, not laziness") → Reduce scope 50% → Start with zero commitment → Something > nothing. |
| TOOL | **List** | Additional interventions: autonomy, unpredictability, identity breaks, caffeine timing. |
| TOOL | **Note** | Commitment: "Next time I feel unmotivated, I will name it and start with 50% scope." |
| CLOSE | **Statement** | "Name it. Shrink it. Start it." |
| CLOSE | **Note** | "Module 4 complete. You understand the zone and the red line." |
| MODULE CLOSER | **Note** | "Rate yourself again: peak performance state access. Compare to Module 4 start." |

### Module 4 Quiz Lesson

| # | Type | Question | Bloom's |
|---|------|----------|---------|
| 1 | Matching | State (Flow, Clutch) → characteristic. | Remember |
| 2 | MR | "Select ALL three flow triggers." | Remember |
| 3 | MC | "The burnout trajectory is..." | Understand |
| 4 | MC | "Interoceptive suppression occurs when..." | Understand |
| 5 | FitB | "Off-Day Protocol Step 1: Name it ('___, not laziness')." | Remember |
| 6 | Matching | SDT need → sport example. | Apply |
| 7 | Scenario | Mid-ride data check disrupts flow — best response? | Evaluate |

---

## Module 5: Race Day

**Before/After Self-Rating:** "Rate yourself 1-10: How structured and practiced is your mental preparation for race day?"

### Lesson 5.1: The Night Before

| Section | Block | Content |
|---------|-------|---------|
| MODULE OPENER | **Statement** | "Module 5: Race Day. Race day is not the time to learn mental skills. It's the time to execute." |
| MODULE OPENER | **Note** | Self-Rating: "Rate yourself 1-10: How structured is your mental race-day preparation?" |
| HOOK | **Text** | 9:47 PM. Alarm at 4:30. Doing sleep math. Catastrophizing loop. |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will have a complete Night-Before Checklist combining logistics and mental preparation." |
| PRINCIPLE | **Statement** | "The night before is the first phase of competition. Preparation replaces anxiety." |
| SCIENCE | **Accordion** | Panel 1: Mah et al. (2011) — sleep extension. Panel 2: Kolling (2019) — athletes sleep terribly before events. Panel 3: Sleep banking. Panel 4: Pre-sleep relaxation as most effective strategy. |
| TOOL | **Statement** | "Night-Before Checklist" |
| TOOL | **Process** | 5 steps: Equipment finalized by 7 PM → Worry dump → Highlight Reel → Review If-Then plans → 6-2-7 before lights out. |
| TOOL | **Attachment** | Printable Night-Before Checklist. |
| TOOL | **Note** | Coach's Note: "Stop checking the weather. It hasn't changed in 90 seconds." |
| TOOL | **Note** | Commitment: "I will use this checklist the night before my next race on [date]." |
| CLOSE | **Statement** | "Structure kills anxiety. Have the routine. Trust the routine." |
| CLOSE | **Note** | "Next — the scripted sequence for race morning." |

---

### Lesson 5.2: Race Morning

| Section | Block | Content |
|---------|-------|---------|
| HOOK | **Text** | The final 15 minutes — preparation meets execution. |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will have a scripted 15-minute pre-race protocol using tools from Modules 1-3." |
| RETRIEVAL | **MC** | "The most effective strategy for night-before sleep is..." → pre-sleep relaxation routine + sleep banking. |
| PRINCIPLE | **Statement** | "A Pre-Performance Routine eliminates decision-making when your brain is least equipped." |
| SCIENCE | **Note** | Cross-reference: "This protocol assembles: 6-2-7 (1.4), Highlight Reel (3.2), Schema Statement (2.5), Arousal Calibration (1.3)." |
| TOOL | **Statement** | "The 15-Minute Pre-Race Protocol" |
| TOOL | **Process** | 4 steps: Min 1-5: 6-2-7 → Min 6-8: Highlight Reel → Min 9-10: Schema Statement → Min 11-15: Activation calibration. |
| TOOL | **Audio** | Pre-Race Mental Warm-Up (15 min). |
| TOOL | **Note** | Commitment: "I will practice this protocol before a training session this week as rehearsal." |
| CLOSE | **Statement** | "You don't rise to the occasion. You fall to the level of your preparation." |
| CLOSE | **Note** | "Next — the first hour, where most races are lost." |

---

### Lesson 5.3: The First Hour

| Section | Block | Content |
|---------|-------|---------|
| HOOK | **Text** | Adrenaline surge at mile one — chimp screaming GO, coach saying WAIT. |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will have a pre-written First-Hour Focus Script." |
| RETRIEVAL | **FitB** | "The Pre-Race Protocol: Minutes 1-5 = ___, Minutes 6-8 = ___." → 6-2-7, Highlight Reel. |
| PRINCIPLE | **Statement** | "The first hour is where discipline separates execution from impulse." |
| SCIENCE | **Accordion** | Panel 1: Attentional focus — broad-external for positioning, narrow-internal for pacing. Panel 2: Adrenaline override — why "easy" feels easy. Panel 3: RPE first, data for confirmation. |
| TOOL | **Statement** | "First-Hour Focus Script" |
| TOOL | **Process** | 4 steps: Mantra: "Settle. Execute. The race is long." → Check pacing every 10 min → Deploy Performance Statements → Resist every urge to chase. |
| TOOL | **Scenario** | 3-option: Mile 3, group surges. A: Go with them — can't lose the group (consequence: blow up at mile 30). B: Let them go, execute plan (consequence: pass them at mile 60). C: Half-chase — compromise pace (consequence: worst of both worlds). |
| TOOL | **Note** | Commitment: "My first-hour mantra is: ___." |
| CLOSE | **Statement** | "The race isn't won in the first hour. But it can be lost there." |
| CLOSE | **Note** | "Next — the moment where the race IS decided." |

---

### Lesson 5.4: Deliver

| Section | Block | Content |
|---------|-------|---------|
| HOOK | **Text** | The moment in every endurance race where the decision is made. |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will have memorized the 5-step Grit Stack and be able to deploy it under pressure." |
| RETRIEVAL | **MC** | "In the first hour, you should trust ___ first." → RPE. |
| PRINCIPLE | **Statement** | "This is clutch territory. Maximum deliberate effort. The moment every tool in this course was built for." |
| SCIENCE | **Tabs** | Tab 1: Association — monitor body at high intensity. Tab 2: Dissociation — distract at moderate intensity. |
| SCIENCE | **Accordion** | Panel 1: Segmentation. Panel 2: Perceptual reappraisal. Panel 3: Cross-references — Clutch (4.2), Performance Statements (2.4), 6-2-7 (1.4). |
| TOOL | **Statement** | "The Grit Stack" |
| TOOL | **Labeled Graphic** | 5-layer stack: Breathe → Detach → Reframe → Execute → Segment. |
| TOOL | **Process** | 5 steps: Breathe (6-2-7) → Detach ("that's the chimp") → Reframe (Performance Statement) → Execute (commit) → Segment (next checkpoint only). |
| TOOL | **Audio** | Grit Stack Walk-Through (5 min). |
| TOOL | **Note** | Commitment: "I will rehearse the Grit Stack in my next hard interval session." |
| CLOSE | **Statement** | "This is what you trained for. Not the fitness. This." |
| CLOSE | **Note** | "Next — fueling your head, not just your body." |

---

### Lesson 5.5: Fueling Your Head

| Section | Block | Content |
|---------|-------|---------|
| HOOK | **Text** | The bonk isn't just physical — low glucose impairs the prefrontal cortex. The chimp takes over. |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will have rehearsed your exact race-day nutrition plan in training." |
| RETRIEVAL | **FitB** | "The Grit Stack steps: Breathe → ___ → Reframe → ___ → Segment." → Detach, Execute. |
| PRINCIPLE | **Statement** | "Nutritional anxiety is a distinct psychological construct — not just 'eat right.'" |
| SCIENCE | **Accordion** | Panel 1: Bonking cascade — glucose → prefrontal → negative spirals. Panel 2: Stress → cortisol → gut → GI → more stress. Panel 3: 20-50% GI distress prevalence. Panel 4: Nutritional anxiety (Nutrients, 2025). |
| SCIENCE | **MC** | "'Nothing new on race day' is a psychological rule because..." → (b) unfamiliar nutrition adds decision load and anxiety. |
| TOOL | **Statement** | "The Fueling Rehearsal" |
| TOOL | **Process** | 4 steps: Build exact plan → practice in 3 training sessions → make automatic → on race day, execute. No decisions. No new products. |
| TOOL | **Note** | Commitment: "I will rehearse my race nutrition plan in my next 3 long sessions." |
| CLOSE | **Statement** | "'Nothing new on race day' is psychological, not just physiological." |
| CLOSE | **Note** | "Next — what happens after the finish line." |

---

### Lesson 5.6: After The Line

| Section | Block | Content |
|---------|-------|---------|
| HOOK | **Text** | "Every race has two finish lines" — physical and psychological. The crash is real. |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will have a structured Post-Race Debrief framework." |
| RETRIEVAL | **MC** | "Nutritional anxiety is: ..." → (b) a distinct psychological construct. |
| PRINCIPLE | **Statement** | "Structured debrief, not rumination. Process the race, then put it away." |
| SCIENCE | **Accordion** | Panel 1: Post-event emotional crash. Panel 2: Rumination vs. reflection. Panel 3: Positive reflection → integration → move on. |
| TOOL | **Statement** | "The Post-Race Debrief" |
| TOOL | **Process** | 4 steps: What went well? → What was hard? → What would I do differently? → What am I proud of? Within 24 hours. Write it. Close it. |
| TOOL | **Audio** | Post-Race Debrief (10 min). |
| TOOL | **Attachment** | Post-Race Debrief worksheet. |
| TOOL | **Note** | Commitment: "I will complete a written Post-Race Debrief within 24 hours of my next race." |
| CLOSE | **Statement** | "Write it. Close it. You are not your last result." |
| CLOSE | **Note** | "Module 5 complete. You have the race-day protocol." |
| MODULE CLOSER | **Note** | "Rate yourself again: mental race-day preparation. Compare to Module 5 start." |

### Module 5 Quiz Lesson

| # | Type | Question | Bloom's |
|---|------|----------|---------|
| 1 | MC | "Night-Before Checklist: logistics finalized by what time?" | Remember |
| 2 | FitB | "Pre-Race Protocol: Min 1-5 = ___, Min 6-8 = ___, Min 9-10 = ___." | Remember |
| 3 | MC | "First hour: trust ___ first, ___ for confirmation." | Apply |
| 4 | Matching | Grit Stack step → action. | Apply |
| 5 | MC | "Post-Race Debrief within: ..." → 24 hours. | Remember |
| 6 | MC | "Nutritional anxiety is..." | Understand |
| 7 | Scenario | Mile 50, stomach revolting, lost 2 positions. Deploy Grit Stack — sequence the steps. | Evaluate |

---

## Module 6: When It All Goes Wrong

**Before/After Self-Rating:** "Rate yourself 1-10: How well do you handle setbacks, injury, and adversity in your athletic life?"

### Lesson 6.1: The Emotional Rollercoaster Is Normal

| Section | Block | Content |
|---------|-------|---------|
| MODULE OPENER | **Statement** | "Module 6: When It All Goes Wrong. Adversity is the defining feature. Resilience is a skill." |
| MODULE OPENER | **Note** | Self-Rating: "Rate yourself 1-10: How well do you handle setbacks and adversity?" |
| HOOK | **Text** | Six weeks into a build — something breaks. Injury, burnout, life. |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will recognize the grief stages in athletic setbacks and be able to name your current stage." |
| PRINCIPLE | **Statement** | "The emotional rollercoaster is not weakness. It's a sign that this mattered to you." |
| SCIENCE | **Timeline** | Grief in sport: Denial → Anger → Bargaining → Depression → Acceptance. Each with athlete example. |
| SCIENCE | **Accordion** | Panel 1: Kubler-Ross (1969). Panel 2: Rotella & Heyman (1986) — applied to sport. Panel 3: Heil's Affective Cycle — non-linear. Panel 4: Every experience is unique. |
| SCIENCE | **Note** | "The stages are not linear. You will cycle. Don't compare to anyone else's timeline." |
| TOOL | **Statement** | "Name Your Stage" |
| TOOL | **Process** | 4 steps: Where are you now? → Name it → Write it down → No judgment. All stages are normal. |
| TOOL | **Scenario** | 3-option: Torn hamstring 2 weeks ago. Told coach "I'll run next week." PT says 6 more weeks. A: "I'm fine, it's not that bad" → Denial. B: "Maybe I can still race if I cross-train" → Bargaining. C: "I'm injured. This is where I am." → Acceptance. Each with consequence. |
| TOOL | **Note** | Commitment: "My current stage is: ___. I accept that this is where I am right now." |
| CLOSE | **Statement** | "Name where you are. Stop judging yourself for being on the ride." |
| CLOSE | **Note** | "Next — stress isn't just a feeling." |

---

### Lesson 6.2: Stress Is Physical

| Section | Block | Content |
|---------|-------|---------|
| HOOK | **Text** | Stress isn't abstract — tension, shallow breathing, tunnel vision, poor decisions. |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will have completed a 4-domain Stress Audit and identified where stress is leaking between domains." |
| RETRIEVAL | **MC** | "Heil's Affective Cycle is: (a) linear (b) non-linear — you cycle through stages (c) predictable (d) the same for everyone." → (b) |
| PRINCIPLE | **Statement** | "Mental stress amplifies physical pain. The vicious cycle is real." |
| SCIENCE | **Tabs** | Tab 1: Stress Relievers (Acute) — music, nature, laughter, unplugging. Tab 2: Stress Balancers (Structural) — sleep, social support, meditation, journaling. |
| SCIENCE | **Accordion** | Panel 1: Sympathetic cascade. Panel 2: Stress → sleep → stress → recovery vicious cycle. |
| TOOL | **Statement** | "The Stress Audit" |
| TOOL | **Process** | 4 steps: Rate 1-10 across training, work, relationships, health → which is bleeding? → stress relievers for acute → stress balancers for root cause. |
| TOOL | **Attachment** | Stress Audit worksheet (4-domain grid). |
| TOOL | **Note** | Commitment: "I will complete the Stress Audit today and address the highest-scoring domain this week." |
| CLOSE | **Statement** | "Stress doesn't stay in its lane. Find the leak. Fix the leak." |
| CLOSE | **Note** | "Next — coping strategies matched to what you can control." |

---

### Lesson 6.3: Coping — What Actually Works

| Section | Block | Content |
|---------|-------|---------|
| HOOK | **Text** | Three athletes, same injury, three responses. The difference is coping strategy. |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will be able to match coping strategy to situation based on controllability." |
| RETRIEVAL | **MC** | "The Stress Audit evaluates how many domains?" → 4 (training, work, relationships, health). |
| PRINCIPLE | **Statement** | "Problem-focused when you can control it. Emotion-focused when you can't. Avoidance always backfires." |
| SCIENCE | **Tabs** | Tab 1: Problem-Focused — action, control, plans. Tab 2: Emotion-Focused — acceptance, compassion, reframing. Tab 3: Avoidance — denial, distraction. Short-term relief, long-term damage. |
| SCIENCE | **Sorting** | Sort scenarios: "Bad weather forecast" (emotion) / "Recurring knee pain" (problem) / "Got passed — can't change it" (emotion) / "GI issues from nutrition plan" (problem). |
| SCIENCE | **Accordion** | Panel 1: Lazarus & Folkman. Panel 2: Self-compassion (Mosewich). |
| TOOL | **Statement** | "The Coping Match" |
| TOOL | **Process** | 5 steps: Biggest stressor → Can I control it? → If yes: 3 action steps → If no: acceptance + self-compassion → Watch for avoidance. |
| TOOL | **Note** | Commitment: "My biggest stressor right now is ___. I [can/cannot] control it. My strategy is ___." |
| CLOSE | **Statement** | "Match the strategy to the situation." |
| CLOSE | **Note** | "Next — the uninvited teacher: injury." |

---

### Lesson 6.4: Injury — The Uninvited Teacher

| Section | Block | Content |
|---------|-------|---------|
| HOOK | **Text** | "I am injured" vs. "I am dealing with an injury." Language shapes experience. |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will have a ranked Return Hierarchy for your fears about getting back." |
| RETRIEVAL | **Matching** | Match coping style (Problem, Emotion, Avoidance) to situation. |
| PRINCIPLE | **Statement** | "Injury threatens identity. If the athlete branch is the whole tree, losing it is existential." |
| PRINCIPLE | **Note** | Cross-reference: "Identity Foreclosure (Lesson 2.1) — athletes with diverse branches recover faster." |
| SCIENCE | **Timeline** | Injury arc: Sadness peaks early → Anxiety peaks at return → Fear creates tension → Tension increases re-injury risk. |
| SCIENCE | **Flashcard Grid** | 4 cards: Psychological Support, Physical Support, Informational Support, Motivational Support. |
| TOOL | **Statement** | "The Return Hierarchy" |
| TOOL | **Process** | 4 steps: List fears → Rank least to most scary → Address in order → Each conquered fear = Evidence File entry (Lesson 2.2). |
| TOOL | **Note** | Cross-reference: "Add each conquered fear to your Evidence File from Lesson 2.2." |
| TOOL | **Note** | Commitment: "My top 3 return fears, ranked: 1.___ 2.___ 3.___" |
| CLOSE | **Statement** | "Injury is not the end. It's the chapter where you find out what you're made of." |
| CLOSE | **Note** | "Next — what mental toughness actually is." |

---

### Lesson 6.5: Mental Toughness Is the Sum

| Section | Block | Content |
|---------|-------|---------|
| HOOK | **Text** | Mental toughness includes knowing when to stop. It's not just "pushing through pain." |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will have rated yourself on the 4 C's and identified which module to revisit." |
| RETRIEVAL | **MR** | "Select ALL four types of support an injured athlete needs." |
| PRINCIPLE | **Statement** | "Mental toughness is the integration of every tool in this course." |
| SCIENCE | **Labeled Graphic** | Clough's 4 C's — Control, Commitment, Challenge, Confidence — with self-belief at center. |
| SCIENCE | **Accordion** | Panel 1: Clough's model. Panel 2: Zeiger's flower — self-belief at center. Panel 3: 2017/2020 meta-analyses. Panel 4: MT = integration of all tools. |
| TOOL | **Statement** | "The MT Self-Assessment" |
| TOOL | **Process** | 4 steps: Rate 1-10 on each C → Find weakest → Go to the module that builds it → One tool, five days. |
| TOOL | **List** | Module map: Control → M1. Commitment → M4. Challenge → M3. Confidence → M2. |
| TOOL | **Note** | Normative: "Most athletes completing this course find 1-2 C's noticeably weaker than the others. That's normal." |
| TOOL | **Note** | Commitment: "My weakest C is ___. I will practice [specific tool] for 5 days." |
| CLOSE | **Statement** | "Rate yourself. Find the weak link. Go build it." |
| CLOSE | **Note** | "Next — the final lesson: the habit." |

---

### Lesson 6.6: The Habit, Not The Goal

| Section | Block | Content |
|---------|-------|---------|
| HOOK | **Text** | "Mental game is a habit, not a goal. A habit doesn't have an endpoint." |
| OBJECTIVE | **Statement** | "By the end of this lesson, you will have a Daily 5 routine and commit to starting tonight." |
| RETRIEVAL | **Matching** | Match 4 C's (Control, Commitment, Challenge, Confidence) to module (M1, M4, M3, M2). |
| PRINCIPLE | **Statement** | "Daily micro-practice beats weekly deep sessions. The tools work — but only if you use them." |
| SCIENCE | **Timeline** | 4-stage competence: Unconscious Incompetence → Conscious Incompetence ("feels like getting worse") → Conscious Competence → Unconscious Competence. |
| SCIENCE | **Note** | "Stage 2 feels like getting worse. Expect it. Push through it." |
| SCIENCE | **Accordion** | Panel 1: 5 min daily > 30 min weekly. Panel 2: Habit formation research. Panel 3: The competence valley. |
| TOOL | **Statement** | "The Daily 5" |
| TOOL | **Process** | 5 minutes: Min 1: 6-2-7 → Min 2: Highlight Reel (compressed) → Min 3: Performance Statements → Min 4: Schema Statement → Min 5: Gratitude/Reflection. |
| TOOL | **Audio** | Daily 5 Guided Practice (5 min) — NEW, to be produced. |
| TOOL | **Note** | Coach's Note: "Start tonight. Not next Monday. Tonight." |
| TOOL | **Note** | Commitment: "I will start The Daily 5 tonight at [time]." |
| CLOSE | **Statement** | "The tools in this course work. But only if you use them." |
| CLOSE | **Text** | Course walk-back — brief callback to all 6 modules. |
| MODULE CLOSER | **Note** | "Rate yourself again: handling setbacks and adversity. Compare to Module 6 start." |
| MODULE CLOSER | **Note** | Normative: "Athletes who complete Deliver and practice The Daily 5 for 30 days report 2-4 point improvements across the 4 C's." |

### Module 6 Quiz Lesson

| # | Type | Question | Bloom's |
|---|------|----------|---------|
| 1 | Matching | Grief stage → athlete example. | Apply |
| 2 | Sorting | Coping strategies → Problem-Focused vs. Emotion-Focused. | Apply |
| 3 | MR | "Select ALL four support types for injured athletes." | Remember |
| 4 | Matching | 4 C's → module that builds each. | Apply |
| 5 | FitB | "Daily 5: Min 1=___, Min 2=___, Min 3=___, Min 4=___, Min 5=___." | Remember |
| 6 | MC | "Stage 2 of competence (Conscious Incompetence) feels like..." → getting worse. | Understand |
| 7 | Scenario | Athlete 4 weeks post-injury, says "I'm fine, just need to push through." Identify stage + recommend coping strategy. | Evaluate |

---

## Appendix A: Guided Practice Library → Audio Block Mapping

| Audio Exercise | Duration | Lesson | Status |
|----------------|----------|--------|--------|
| 6-2-7 Breathing Protocol | 5 min | 1.4 | To produce |
| Progressive Muscle Relaxation | 15 min | 1.3 (supplementary) | To produce |
| Highlight Reel Visualization | 10 min | 3.2 | To produce |
| Pre-Race Mental Warm-Up | 15 min | 5.2 | To produce |
| 3-Minute Breathing Space | 3 min | 3.5 | To produce |
| Grit Stack Walk-Through | 5 min | 5.4 | To produce |
| Post-Race Debrief | 10 min | 5.6 | To produce |
| Daily 5 Guided Practice | 5 min | 6.6 | To produce (NEW) |

## Appendix B: Downloadable Attachments

| Attachment | Format | Lesson |
|------------|--------|--------|
| RPE Journal Template | PDF | 1.2 |
| Know Your Zone Worksheet | PDF | 1.3 |
| Identity Audit Worksheet | PDF | 2.1 |
| Evidence File Template | PDF | 2.2 |
| Performance Statements Card | PDF (wallet) | 2.4 |
| If-Then Plan Worksheet | PDF | 3.3 |
| Race Soundtrack Card | PDF (wallet) | 3.4 |
| Flow Conditions Audit | PDF | 4.1 |
| Night-Before Checklist | PDF (printable) | 5.1 |
| Post-Race Debrief Worksheet | PDF | 5.6 |
| Stress Audit Worksheet | PDF | 6.2 |

## Appendix C: Labeled Graphics to Design

| Graphic | Type | Lesson |
|---------|------|--------|
| System 1 vs. System 2 | Comparison tabs | 1.1 |
| Yerkes-Dodson Inverted U | Annotated curve | 1.3 |
| 2×2 Attention Matrix | Quadrant diagram | 1.5 |
| Identity Tree | Layered illustration | 2.1 |
| Bandura's 4 Sources | Ranked pyramid | 2.2 |
| Flow Channel | X-Y zone diagram | 4.1 |
| SDT Three Needs | Venn/triangle | 4.3 |
| Burnout Trajectory | Timeline | 4.3 |
| Grit Stack | 5-layer vertical stack | 5.4 |
| Grief Stages (Sport) | Non-linear cycle | 6.1 |
| Injury Emotional Arc | Timeline | 6.4 |
| 4 C's + Zeiger Flower | Annotated model | 6.5 |
| 4-Stage Competence | Staircase | 6.6 |

## Appendix D: Email Drip Sequence (Outside Rise)

| Timing | Content |
|--------|---------|
| Day 0 | Welcome + course overview + Module 1 unlocked |
| Day 1 post-module | Retrieval: "Can you name the key concepts from Module X?" |
| Day 3 | Practice reminder: "Have you tried [tool] in training yet?" |
| Day 7 | Deeper retrieval: "How did [tool] work? What did you notice?" |
| Day 21 | Long-term retrieval: "How has [concept] changed your training?" |
| Module 3 complete | Halfway celebration + progress acknowledgment |
| Course complete | All tools summary + Daily 5 reminder + community invitation |
| 30 days post | "Are you still doing The Daily 5?" |

## Appendix E: Interaction Count Summary

| Element | Count |
|---------|-------|
| Lessons | 30 |
| Quiz Lessons | 6 |
| Scenarios (consequence branching) | 14 |
| Knowledge Checks (inline) | 30+ (at least 1 per lesson) |
| Retrieval Openers | 29 (every lesson after 1.1) |
| Sorting Activities | 4 |
| Labeled Graphics | 13 |
| Flashcard Sets | 5 |
| Process Blocks | 30 (every tool) |
| Accordion Sections | 30+ |
| Tabs Comparisons | 14 |
| Timeline Blocks | 5 |
| Audio Exercises | 8 |
| Downloadable Attachments | 11 |
| Commitment Prompts | 30 (every lesson) |
| Before/After Self-Ratings | 6 (every module) |
| Learning Objectives | 30 (every lesson) |
| Cross-Reference Notes | 12+ |
| Normative Feedback Notes | 6-8 |
| Embed (Reflection Forms) | 6 (module boundaries, optional) |

## Appendix F: Rise Limitations and Workarounds

| Limitation | Workaround |
|------------|-----------|
| No variables/state tracking | Commitment prompts + downloadable worksheets for learner-captured data |
| No learner input capture | Google Form embeds at module boundaries for reflection |
| 3 responses per scenario | Design scenarios for quality of branching, not quantity |
| Stock characters only | Use custom background images to set sport context |
| Sorting not keyboard accessible | Provide alternative text description for accessibility |
| No gamification | Progress bars (native), before/after self-ratings, streak-friendly Daily 5 |
| No spaced repetition | Email drip sequence (outside Rise) + retrieval openers in every lesson |
| No peer interaction | Embed blocks for Padlet/discussion (optional community layer) |
| Cannot track completion + quiz | Track by course completion; use knowledge checks (ungraded) for formative assessment |
