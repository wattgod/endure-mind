# Deliver — Production Plan

## Audiobook Production (ElevenLabs)

### Voice Setup
- **Platform**: ElevenLabs (existing account, voice already cloned)
- **Voice improvement**: Record 10-15 min reading Gravel Grit material in natural coaching register. Upload as additional training data to improve clone fidelity.
- **Target voice**: Coffee-shop coaching tone — not narrator, not lecturer, not podcast host. The Stoic Coach.

### Production Pipeline

```
Scripts (markdown)
    │
    ▼
Review & polish (Matt reads aloud, flags awkward phrasing)
    │
    ▼
ElevenLabs long-form API
    │
    ▼
Review passes (pacing, emphasis, pronunciation)
    │
    ▼
Audio editing (chapter markers, intro/outro, levels)
    │
    ▼
Master files (mp3 + m4b for Audible)
    │
    ▼
Distribution
```

### Audio Outputs

| Track | Duration | Source |
|---|---|---|
| **Module 1**: The Two Brains | ~45-60 min | 5 lessons |
| **Module 2**: The Stories You Tell Yourself | ~45-60 min | 5 lessons |
| **Module 3**: Seeing Before Doing | ~45-60 min | 5 lessons |
| **Module 4**: The Zone and The Red Line | ~45-60 min | 5 lessons |
| **Module 5**: Race Day | ~45-60 min | 6 lessons |
| **Module 6**: When It All Goes Wrong | ~45-60 min | 6 lessons |
| **Guided: 6-2-7 Breathing** | 5 min | Standalone exercise |
| **Guided: Progressive Muscle Relaxation** | 15 min | Standalone exercise |
| **Guided: Highlight Reel Visualization** | 10 min | Standalone exercise |
| **Guided: Pre-Race Mental Warm-Up** | 15 min | Standalone exercise |
| **Guided: 3-Minute Breathing Space** | 3 min | Standalone exercise |
| **Guided: The Grit Stack Walk-Through** | 5 min | Standalone exercise |
| **Guided: Post-Race Debrief** | 10 min | Standalone exercise |
| **Total** | ~6-7 hours | |

All tracks generated via ElevenLabs API in Matt's cloned voice.

### Distribution Channels

| Platform | Format | Notes |
|---|---|---|
| **Audible** | m4b (ACX submission) | Largest audiobook marketplace |
| **Apple Books** | m4a | Direct upload via Apple Books for Authors |
| **Google Play Books** | mp3 | Direct upload |
| **gravelgodcycling.com** | mp3 download | Direct sales, highest margin |
| **Endure Labs app** | Streaming + offline | Integrated with course/app |

### ElevenLabs Technical Notes
- Use Projects API for long-form (better pacing than text-to-speech endpoint)
- Set stability: 0.5, similarity_boost: 0.75 (natural coaching variance)
- Generate at 44.1kHz for Audible compliance
- Batch generate by lesson, not by module (easier review)
- API cost estimate: ~$30-50 for full 6-7 hours at Pro tier

## Content Production Sequence

```
Phase 1: Foundation (NOW)
├── Citation database ← IN PROGRESS
├── Module 1 script ← IN PROGRESS
└── Voice clone improvement (Matt records 10-15 min Gravel Grit reading)

Phase 2: Validate (Module 1 complete)
├── Matt reviews Module 1 script
├── Generate Module 1 audio via ElevenLabs
├── Listen-through on a ride — does it work?
├── Adjust voice settings / script as needed
└── Landing page live on gravelgodcycling.com (email capture)

Phase 3: Build Out
├── Modules 2-6 scripts (one at a time, review each)
├── Generate audio for each module as approved
├── Guided exercise scripts + audio generation
└── Citation verification pass

Phase 4: Package
├── Audiobook master (chapter markers, intro/outro)
├── Course platform setup (video versions of lessons if needed)
├── App MVP (Module 1 free, streak tracking)
└── Landing page: full product suite live

Phase 5: Launch
├── Email warm list (Gravel Grit alumni)
├── Audiobook → Audible/Apple/Google + direct
├── Course → gravelgodcycling.com
├── App → App Store / Google Play
└── Cross-promote across all Endure coaching businesses
```

## Landing Page: gravelgodcycling.com

The landing page for Deliver lives on gravelgodcycling.com — not a separate domain.
This keeps it within the existing coaching business and leverages existing traffic/SEO.

Options:
- `gravelgodcycling.com/deliver` — clean subpath
- `deliver.gravelgodcycling.com` — subdomain (more brand separation)

Recommendation: `gravelgodcycling.com/deliver` — simpler, no DNS config, benefits from domain authority.

Deploy via existing endure-plan-engine pipeline (Python static site → SiteGround via SSH).
