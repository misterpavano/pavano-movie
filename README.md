# pavano-movie

**A production-grade Hollywood screenplay development environment.**

This repo is your complete writing toolkit: an 11-agent AI team, deep craft guides, real market intel, pitch templates, beat sheets, and submission tracking — everything you need to write a screenplay that could actually sell.

Built on the [Words To Film By™](https://github.com/bybren-llc/story-systems-template) harness with a full layer of market research, craft education, and business infrastructure layered on top.

---

## What This Is

Most screenplay repos are template dumps. This one is different. It contains:

- **Real craft education** — not "three acts go here" platitudes but the actual mechanics of how structure, character, and dialogue work at a professional level
- **Current market intel** — what's selling right now, who's buying it, and how the business actually works in 2025-2026
- **Business infrastructure** — query letters, pitch documents, submission tracking, contest calendars
- **11 AI agents** — specialized writing partners you can invoke with Claude to get expert help on any aspect of the script
- **Fountain-native workflow** — write in `.fountain` files, export to industry-standard PDF and FDX

This is not a beginner tutorial. It's a professional workspace.

---

## The AI Agent Team

This project ships with 11 specialized AI agents. Invoke them in Claude Code or Claude.ai by saying "Acting as the [Agent], do X":

| Agent | Role |
|---|---|
| **Story Architect** | Structure, beats, three-act integrity |
| **Dialogue Writer** | Voice differentiation, subtext, rhythm |
| **Scene Writer** | Scene-level construction, pacing, visual storytelling |
| **Story Analyst** | Big-picture notes, thematic coherence |
| **Research Specialist** | Factual accuracy, world-building, market research |
| **Continuity Editor** | Tracking props, timeline, character details |
| **Script Supervisor** | Format compliance, industry standards |
| **Scene Annotator** | Scene-by-scene notes and analysis |
| **Session Manager** | Git workflow, session tracking |
| **Production Coordinator** | Exports, deliverables, file management |
| **Standards Reviewer** | Final quality pass before submission |

Agent files live in `.claude/agents/`. See [AGENTS.md](AGENTS.md) for full team reference.

---

## Repository Structure

```
pavano-movie/
│
├── script/                         Your .fountain screenplay files
│   └── FOUNTAIN-CHEATSHEET.md      Quick Fountain syntax reference
│
├── research/
│   ├── craft/                      Deep craft education
│   │   ├── STORY-STRUCTURE.md      Three-act, Save the Cat, Hero's Journey
│   │   ├── CHARACTER.md            Want vs need, arc types, voice
│   │   ├── DIALOGUE.md             Subtext, exposition, voice differentiation
│   │   └── SCENE-CONSTRUCTION.md   Scene goals, turns, visual storytelling
│   │
│   └── market/                     Business intelligence
│       ├── WHATS-SELLING-2025-2026.md  What Hollywood is buying right now
│       ├── HOW-TO-SELL.md          The full business of selling a script
│       ├── WHO-TO-PITCH.md         Managers, prodcos, streaming programs
│       └── CONTESTS-AND-FELLOWSHIPS.md  Competition guide with ROI analysis
│
├── pitch/
│   └── templates/                  Ready-to-fill pitch documents
│       ├── LOGLINE-TEMPLATE.md     20 logline breakdowns + formula
│       ├── QUERY-LETTER-TEMPLATE.md  Cold email template + full example
│       ├── ONE-PAGER-TEMPLATE.md   One-page pitch document
│       └── TREATMENT-TEMPLATE.md   How to write a treatment
│
├── notes/
│   ├── beat-sheets/                Fillable beat sheet templates
│   │   ├── THREE-ACT-BEAT-SHEET.md
│   │   ├── SAVE-THE-CAT-BEAT-SHEET.md
│   │   └── HEROS-JOURNEY-BEAT-SHEET.md
│   │
│   └── character-arcs/
│       └── CHARACTER-PROFILE-TEMPLATE.md
│
├── submissions/
│   └── TRACKER.md                  Submission log with full columns
│
├── exports/                        Generated PDF, FDX, HTML output
├── templates/                      WTFB built-in templates
├── patterns/                       Story, character, dialogue, scene patterns
├── .claude/                        AI agent configs (11 agents, skills, commands)
├── docs/                           WTFB documentation
├── scripts/                        Validation and export scripts
│
├── CLAUDE.md                       Claude Code instructions (this project)
├── AGENTS.md                       Full agent team reference
└── RESOURCES.md                    Books, software, websites, podcasts
```

---

## How to Use This

### Start a New Script

1. Create a new `.fountain` file in `script/`:
   ```
   script/my-title.fountain
   ```

2. Fill out your beat sheet first — pick one from `notes/beat-sheets/`

3. Build your characters using `notes/character-arcs/CHARACTER-PROFILE-TEMPLATE.md`

4. Write your logline using `pitch/templates/LOGLINE-TEMPLATE.md` — if you can't write the logline, you don't know your story yet

5. Open Claude Code in this directory and say:
   ```
   Acting as the Story Architect, review my beat sheet and identify structural problems.
   ```

### Research Before You Write

Read in this order:
1. `research/market/WHATS-SELLING-2025-2026.md` — know what the market wants
2. `research/craft/STORY-STRUCTURE.md` — understand the structure you're working in
3. `research/craft/CHARACTER.md` — build a protagonist worth following

### Submit When Ready

1. Track every submission in `submissions/TRACKER.md`
2. Build your pitch package from `pitch/templates/`
3. Find targets in `research/market/WHO-TO-PITCH.md`
4. Enter contests from `research/market/CONTESTS-AND-FELLOWSHIPS.md` — this is the fastest path to getting read

---

## Quick Commands

With Claude Code open in this directory:

```
/writers-room          - Convene all 11 agents for pre-production
/story-check           - Validate structure against 12 critical questions
/analyze-structure     - Deep structure analysis
/analyze-character [name]  - Full character arc analysis
/logline               - Get help crafting your logline
/export-pdf            - Generate industry-standard PDF
```

---

## The Philosophy

Every word in this repo comes from a working assumption: **craft + market knowledge = career**. You can write a brilliant script and never sell it because you don't know how the business works. You can know the business perfectly and never sell because you can't write. Both matter. This repo covers both.

Read the craft files before you write. Read the market files before you submit. Update your tracker every time.

---

## Resources

See [RESOURCES.md](RESOURCES.md) for the full reading list, software recommendations, and online communities.

---

*Built on the [WTFB harness](https://github.com/bybren-llc/story-systems-template) by J. Scott Graham / Bybren LLC. Extended for production-grade screenplay development.*
