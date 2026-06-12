# /brief Skill

## Purpose
Answer questions about past legal decisions by pulling from the review history, with a citation for every claim.

## Two Modes

### Daily Mode
Run every morning. Reads inbox, calendar, and task tracker. Outputs a short memo:
- What's due today
- What's new and urgent
- Any reviews that need follow-up

**Trigger:** `/brief daily`

### Topic Mode
Run on demand. Takes a specific question and returns a cited answer from past reviews and memos.

**Trigger:** `/brief [your question here]`

## Sources to Search
- `/reviews/` — all past legal reviews and decision memos
- `/memos/` — internal legal memos and written opinions
- `/inbox/` — recent messages and requests from teammates
- `/tasks/` — open and closed action items

## Output Format
Return a short structured brief:
1. **Question** — restate the question asked
2. **Prior Decision** — what was concluded before, with citation
3. **What's Changed** — anything new that affects the prior conclusion
4. **Gaps / Flags** — anything that reopens the prior review
5. **Recommended Next Step** — what the attorney should do before replying

Every factual claim must include a citation: [Source: filename, section]

## Tone
Concise, professional. Written for a busy attorney who has 3 minutes, not 30.
