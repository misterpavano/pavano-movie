# Fountain Syntax Cheatsheet

Fountain is a plain-text markup language for screenplays. Write in any text editor. Export to industry-standard format. This repo uses `.fountain` files.

Install **BetterFountain** in VS Code to see your script render in real time.

---

## Scene Headings (Sluglines)

Start with `INT.` or `EXT.` followed by location and time of day.

```
INT. POLICE STATION - NIGHT

EXT. ABANDONED WAREHOUSE - DAY

INT./EXT. MOVING CAR - CONTINUOUS
```

**Time of day options:** `DAY` / `NIGHT` / `CONTINUOUS` / `LATER` / `MOMENTS LATER` / `DAWN` / `DUSK`

**Force a slugline** (when it doesn't start with INT/EXT):
```
.DREAM SEQUENCE
```

---

## Action Lines

Just write them. Plain paragraphs that aren't dialogue.

```
Marcus walks through the empty office. The fluorescent lights flicker. 
He stops at the last cubicle — his — and sits down in the dark.

On his desk: a coffee mug, a rubber band, and an AA chip. Where a 
photograph used to be, there's nothing.
```

**Style rules:**
- Present tense. Always.
- Keep it lean — max 3-4 lines per action block
- Active verbs, not passive
- Write what we SEE and HEAR — not what characters think or feel

---

## Character Names

Type the character name in ALL CAPS on its own line before their dialogue.

```
MARCUS
You called this number. That means you need help. That's all I need to know.
```

**Extension** (V.O., O.S.):
```
HARROW (V.O.)
You know who this is.

DISPATCHER (O.S.)
Webb. Line three.
```

---

## Dialogue

The line directly below the character name.

```
MARCUS
Are you in a safe location right now?

HARROW
Define safe.

MARCUS
Are you alive?

HARROW
For now.
```

---

## Parentheticals

Used sparingly for performance direction. Only when absolutely necessary — if the line reading is genuinely ambiguous without it.

```
MARCUS
(quietly)
I remember your voice.
```

**Don't overuse.** Trust your dialogue. If you need a parenthetical on every line, rewrite the lines.

---

## Transitions

```
CUT TO:

DISSOLVE TO:

SMASH CUT TO:

FADE OUT.

FADE IN:
```

By default, cuts are assumed. Only write a transition when it's intentional and specific. `CUT TO:` between every scene is amateur.

---

## Title Page

```
Title: Last Call
Credit: Written by
Author: James Moretti
Draft date: March 2026
Contact: james@email.com
```

---

## Scene Numbers

```
INT. CRISIS HOTLINE - NIGHT #1#

EXT. PARKING GARAGE - CONTINUOUS #2#
```

Typically added in production drafts, not spec drafts.

---

## Notes and Comments (Invisible in Output)

```
[[This scene needs a better button — come back to it]]

/* 
   This whole sequence might be cut.
   Keep for now, revisit in second draft.
*/
```

Single brackets `[[...]]` are notes.  
`/* */` are block comments — don't appear in output.

---

## Lyrics and Centered Text

```
> THE END <

> TITLE CARD: Three years earlier <
```

Centering: wrap with `>`...`<`

---

## Dual Dialogue

Two characters speaking simultaneously:

```
MARCUS ^
Don't hang up.

HARROW ^
I'm already gone.
```

Both get `^` after the name.

---

## Page Breaks (Forced)

```
===
```

Three equal signs force a page break. Use for act breaks if needed.

---

## Sections and Synopses (for outlining — don't appear in PDF)

```
# ACT ONE

## Setup

### The Ordinary World

= Marcus in his cubicle, in the dark. We understand immediately: he is a man who has retreated from the world.
```

`#` / `##` / `###` = section headers (navigation only)  
`=` = synopsis line (notes visible in BetterFountain outline, not in script output)

---

## BetterFountain — VS Code Workflow

**Install:** VS Code → Extensions → search "Better Fountain" → Install

**Live preview:** Open a `.fountain` file → `Cmd+Shift+P` (Mac) or `Ctrl+Shift+P` (Win) → "Fountain: Show Preview"

**Export to PDF:** Same command palette → "Fountain: Export to PDF"

**Keyboard shortcut for preview:** `Option+Shift+F` (Mac) / `Alt+Shift+F` (Win) — check your keybindings

**What BetterFountain shows you:**
- Formatted screenplay in real time (proper margins, Courier font, page breaks)
- Scene outline in sidebar (navigate by slugline)
- Character stats and dialogue distribution
- Running page count and estimated runtime
- Syntax highlighting in the editor

---

## The Screenplay Template

See `templates/screenplay-template.fountain` for a starter file with the title page and first scene already formatted.

---

## Quick Format Rules (Industry Standard)

| Element | Format |
|---------|--------|
| Page size | 8.5 x 11 |
| Font | 12pt Courier (handled by export) |
| Top/bottom margins | 1 inch |
| Left margin | 1.5 inches |
| Right margin | 1 inch |
| Character cue | 3.7 inches from left |
| Dialogue | 2.5 to 6 inches |
| Parenthetical | 3.1 to 5.9 inches |
| One page | ~1 minute of screen time |
| Feature length | 90-120 pages |
