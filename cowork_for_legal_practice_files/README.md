# Claude Cowork Legal Briefing — Practice Files

This folder is set up to practice the tutorial:
"Using Claude Cowork for legal: answer fast questions on past decisions"
https://claude.com/resources/tutorials/using-claude-cowork-for-legal-question-briefing

## Context
These files simulate the legal team working on the **American Worker Protection Act (AWPA)** —
a federal policy proposal making it a felony to hire foreign workers over qualified or
upskillable American workers, with AmericanLaborDefense.org as the registry backbone.

## Folder Structure

| Folder | Contents |
|--------|----------|
| `skills/` | The /brief skill definition — point Cowork here |
| `reviews/` | Past legal reviews and decisions (your "decision history") |
| `memos/` | Internal memos and research notes |
| `inbox/` | Simulated Slack messages and emails from teammates |
| `tasks/` | Open and closed task lists |

## How to Practice the Tutorial

### Step 1 — Set up the /brief skill
Point Cowork at `skills/brief.md` as your skill source.

### Step 2 — Schedule a morning brief
Ask Cowork to run `/brief daily` reading from `inbox/`, `tasks/`, and `reviews/`.

### Step 3 — Run a brief on a question
Try this prompt:
> /brief does the new AI platform certification requirement reopen the January 2025 Commerce Clause review of Section 4(b)?

The answer lives in: `reviews/review_2025_01_h1b_upskilling_clause.md` and `memos/memo_2025_06_new_feature_change_analysis.md`

### Step 4 — Verify before you sign
Find the citation in the brief. Open the source file. Read the line yourself.

### Step 5 — Reply and close the loop
Draft a reply to Jordan (inbox/slack_message_from_policy_team.md) and close TASK-001 in tasks/open_tasks.md
