# The Deciding Mile — App Design

## Philosophy

The course teaches. The app trains. The audiobook immerses.

Most sport psych courses fail because athletes consume the content and never practice it. The app solves this by treating mental skills the same way athletes treat physical training: daily, structured, progressive, measurable.

## Core Engagement Architecture

### Duolingo Mechanics (Adapted)

| Duolingo | The Deciding Mile | Purpose |
|---|---|---|
| Daily streak | **Mental Streak** | Loss aversion — protecting your streak drives daily engagement |
| XP points | **Grit Points (GP)** | Variable reward for completing sessions, exercises, and reflections |
| Leagues | **Accountability Circles** | Small group (5-8 athletes) with weekly leaderboard — social motivation without toxic comparison |
| Hearts | **Focus Credits** | Limited daily skips — forces deliberate engagement, not mindless tapping |
| Spaced repetition | **Recall Engine** | Re-surfaces concepts at optimal intervals before forgetting occurs |
| Bite-sized lessons | **5-Minute Sessions** | One concept, one tool, one practice. Every day. |
| Adaptive difficulty | **Skill Assessment** | App identifies weak areas and prioritizes content accordingly |

### Noom Mechanics (Adapted)

| Noom | The Deciding Mile | Purpose |
|---|---|---|
| CBT micro-lessons | **First Principle Cards** | 2-3 min concept explanation, one idea at a time |
| Daily logging | **Session Debrief** | Post-training RPE + mental state + tool deployment log |
| Coach chat | **Coach Mode** (future) | Async coaching integration for premium tier |
| Peer circles | **Accountability Circles** | Same-goal athlete groups with weekly check-ins |
| Behavior chain | **The Habit Loop** | Cue (training session starts) → Routine (deploy tool) → Reward (log + reflect) |

## Daily Flow (5-10 minutes)

```
┌─────────────────────────────────────────────┐
│  MORNING CHECK-IN (1 min)                   │
│  "How are you feeling today?" (1-5 scale)   │
│  Mental energy / motivation / stress         │
│                                             │
│  TODAY'S LESSON (2-3 min)                   │
│  One First Principle Card                    │
│  Quick comprehension check (quiz/reflection) │
│                                             │
│  TODAY'S PRACTICE (2-3 min)                 │
│  Guided exercise tied to today's lesson      │
│  (breathing, visualization, self-talk drill) │
│                                             │
│  TRAINING TIE-IN (30 sec)                   │
│  "During today's session, try this: ___"     │
│  Specific homework for the workout ahead     │
│                                             │
│  POST-SESSION DEBRIEF (1-2 min, evening)    │
│  Did you use the tool? How did it go?        │
│  RPE + mental state log                      │
│  Grit Points awarded                         │
└─────────────────────────────────────────────┘
```

## Content Delivery Schedule

The app follows the 6-module course structure but delivers it in daily micro-doses:

| Week | Module | Daily Focus |
|---|---|---|
| 1-2 | The Two Brains | Breathing, arousal awareness, attention drills |
| 3-4 | The Stories You Tell Yourself | Identity audit, confidence building, performance statements |
| 5-6 | Seeing Before Doing | Visualization practice, self-talk scripting, mindfulness |
| 7-8 | The Zone and The Red Line | Flow conditions, motivation check, data relationship |
| 9-10 | Race Day | Pre-race protocols, in-race tools, fueling psychology |
| 11-12 | When It All Goes Wrong | Stress management, coping skills, resilience building |
| 13+ | Maintenance Mode | Spaced repetition of all tools, seasonal check-ins |

## Engagement Loops

### The Streak
- Daily streak counter (prominently displayed)
- Streak Freeze: 1 free per week, earn more with GP
- Streak milestones: 7, 30, 60, 100, 365 days
- Streak recovery: miss 1 day = "Come back stronger" prompt (not guilt)

### Grit Points
- Earned by: completing daily session (+10), post-training debrief (+5), streak milestone (+25), helping a circle member (+5)
- Spent on: streak freezes, bonus guided exercises, unlocking advanced content
- Weekly summary: "This week you practiced 35 minutes of mental training — that's more than 95% of athletes."

### Accountability Circles
- Matched by: sport, experience level, time zone
- Weekly circle challenge (e.g., "Everyone complete 5 visualization sessions this week")
- Anonymous participation OK — no Strava-style public profiles
- Coach-led option for premium tier

### Progress Tracking
- **Skill Radar Chart**: 6 axes matching the 6 modules — visual representation of growth
- **Session Log**: Training sessions with mental tool deployment tracked
- **Weekly Insights**: "You used your performance statements 4 times this week. Last week: 1."
- **Pre/Post Assessment**: Take the MT self-assessment at start and every 30 days

## Audio Integration

Every guided exercise from the course is available as an audio track in the app:
- Can be played inline during daily session
- Can be downloaded for offline use during training
- Can be set as pre-race routine (alarm-triggered sequence)

## Monetization Model

See `PRICING.md` for full strategy and funnel logic.

| Tier | Price | Access |
|---|---|---|
| **Free** | $0 | Module 1 (The Two Brains) complete, 1 guided exercise, streak tracking |
| **Athlete** | $6.99/mo or $49.99/yr | Full course, all guided exercises, streak + circles, progress tracking |
| **Pro** | $14.99/mo or $99.99/yr | Everything + coach mode, advanced analytics, race-day protocol builder |

The Bundle ($119 one-time) includes 3 months of Athlete tier — this is how most users enter the app.

## Technical Notes

- React Native + Expo (shared stack with endure-mobile)
- Supabase backend (shared infrastructure with athlete-os-web)
- Audio: local playback with offline support
- Push notifications: time-of-day personalized (when user typically trains)
- Spaced repetition: custom algorithm based on Duolingo's SRS research (Settles & Meeder, 2016)
