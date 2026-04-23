# AI Work Ledger

Generate a structured career asset entry at the end of any meaningful AI-assisted work session.

Captures:
- what was built  
- key decisions  
- context and reasoning  
- a reusable portfolio proof statement  

Automatically removes sensitive information before export and formats output for reuse across Notion, Obsidian, Google Docs, or Markdown.

---

## When This Triggers

This skill activates when you say things like:

- "log this session"  
- "add this to my portfolio"  
- "capture this work"  
- "create a ledger entry"  
- "document this build"  
- "end of session"  
- "save this to my work ledger"  
- "export this entry"  

It also triggers naturally when:
- a meaningful deliverable is completed  
- you ask to save or summarize work  
- you say something like: "can you save what we did?"

---

## How to Use This Skill

1. Click the **Raw** button on this page  
2. Select all → copy  
3. Open Claude and create or open a Project  
4. Go to Project Settings → add a new instruction file  
5. Paste this file and save  
6. Use it by saying: **"log this session"** at the end of your work  

No coding required. Works with Claude Pro or Team plans.

---

name: ai-work-ledger
description: >
  Generate a structured career asset entry at the end of an AI-assisted work session.

  Captures:
  - what was built
  - key decisions
  - context and reasoning
  - a reusable portfolio proof statement

  Automatically removes sensitive information before export and formats output for reuse across Notion, Obsidian, Google Docs, or Markdown.

  Trigger this skill when the user asks to log, save, document, or export their work, or at natural session close after completing a meaningful deliverable.
---

# AI Work Ledger

## What This Does

At the end of a substantive AI-assisted work session, this skill generates a structured
**Ledger Entry** — a single portable record that serves three functions:

1. **Portfolio evidence** — what you built and why it matters
2. **Context seed** — what domain/workflow knowledge this session encoded, portable to a new AI
3. **Capability proof** — a plain-language statement usable in interviews, proposals, or bios

Works for any role, industry, or experience level. No personal operating system required.

---

## Step 0: Two Setup Questions

Before generating anything, ask both questions in one message:

> "Quick setup before I build your entry:
> 1. Where are you exporting this? (Notion / Obsidian / Google Docs / Markdown file / Just show me — I'll copy manually)
> 2. Is any of the work from this session tied to an employer or client? (Yes / No / Not sure)"

Wait for both answers before proceeding. The second question determines scrub depth in Step 1.

---

## Step 1: Data Scrub — ALWAYS REQUIRED

This step runs regardless of whether the user said "Yes" to client/employer work.
It protects proprietary, identifying, and confidential information from appearing in a
portable asset the user may share, publish, or bring to a future role.

**Remove or generalize any of the following found in the session:**

| Category | Examples | Replace With |
|---|---|---|
| Employer or client names | Company names, org names, brand names | "a [type] organization", "a client", "my employer" |
| Named individuals | Employee names, executive names, client contacts | "a team member", "a stakeholder", "the client" |
| Specific financial data | Revenue, budgets, pricing, commissions | "the relevant financial metrics" |
| Internal systems or tools | Proprietary software, internal platform names | "their internal system", "the platform" |
| Confidential strategy | Unreleased products, M&A, expansion plans | "a strategic initiative under development" |
| Entity-specific compliance details | Named regulatory exceptions tied to a specific org | "a compliance consideration in the workflow" |
| Identifying geography | Specific addresses, internal location codes | "the target area", "a regional market" |

**Keep everything that demonstrates the user's capability:**
- Their domain vocabulary and industry knowledge
- Their decision frameworks and reasoning
- Their workflow patterns and structural logic
- What they directed, validated, and corrected
- General industry or regulatory context that is publicly known

**Note at top of entry:**
`[Data scrub applied — proprietary details generalized]`
or
`[Data scrub applied — no proprietary content identified]`

If the user flags that nothing is employer/client-related and no proprietary content is found,
still note the scrub was run. This builds the habit.

---

## Step 2: Session Reconstruction

Using only scrubbed content, reconstruct the session:

- What was the starting problem or request?
- What was produced? (name it specifically)
- What decisions were made and why? (tradeoffs, pivots, choices)
- What did the user direct vs. what did the AI generate?
- What domain knowledge was applied or encoded?
- What workflow pattern was used?
- What would be hard to replicate without this context?

Do this silently. Use it to populate Step 3.

---

## Step 3: Generate the Ledger Entry

Every field is required. Write "Not specified" if a field can't be determined.
Never leave a field blank.




LEDGER ENTRY
[Data scrub status line]
TITLE:
[Specific name for what was built. Not a category — name the artifact.
Good: “Client Onboarding Email Sequence — AI-Assisted Draft”
Bad: “AI writing session” or “workflow project”]
DATE: [Today’s date]
SESSION TYPE:
[Choose one: Build | Analysis | Strategy | Training Material | System Design |
Policy/Compliance | Research | Communication | Audit Output | Other: _____]
INDUSTRY / DOMAIN:
[User’s own terms. 2–5 tags. Examples: Healthcare, Legal, Marketing, Finance,
Real Estate, Education, Tech, Operations, HR, Consulting, Other: _____]

WHAT WAS BUILT:
[2–4 sentences. Describe the artifact — its purpose, scope, and intended user.
Write as if explaining to a hiring manager assessing your capability.
Use scrubbed language only — no identifying client or employer detail.]
DECISIONS MADE:
[Bullet list. Each bullet = one decision point, tradeoff, or pivot + the reasoning.
Example: Chose a checklist format over prose because the end user is time-constrained
Example: Narrowed scope to three use cases after determining full coverage exceeded one session]
HUMAN DIRECTION vs. AI CONTRIBUTION:
	•	You directed: [what you set up, scoped, constrained, or corrected]
	•	AI generated: [what Claude or another AI produced, structured, or drafted]
	•	You validated: [what you approved, edited, or pushed back on]
CONTEXT ENCODED:
[What domain knowledge, workflow preferences, or behavioral patterns does this session
represent? Write as if you were seeding a brand-new AI with your working style.
No identifying details. Focus on transferable patterns.]
PORTFOLIO PROOF STATEMENT:
[1–3 sentences. Plain language. First person. Usable verbatim in an interview, proposal,
consulting bio, or LinkedIn post. Answer: what did you build, what was challenging,
and what does it demonstrate about your capability?]
REUSE VALUE:
[What from this session can be repurposed, templated, or carried to the next role or client?
List specific components, frameworks, prompt patterns, or structural logic.
Rate: High / Medium / Low — one sentence rationale.]

END ENTRY



### Reader-Friendly Transformation (Optional)

If the user selects readable format:

Apply the following transformations AFTER generating the entry:

1. Move Impact to the top of the entry
2. Convert Impact from sentence format to bullet points
3. Replace section titles as follows:

- WHAT WAS BUILT → What I Built
- DECISIONS MADE → Key Decisions
- HUMAN DIRECTION VS. AI CONTRIBUTION → My Role vs AI Support
- CONTEXT ENCODED → What This System Is Designed For
- PORTFOLIO PROOF STATEMENT → What This Demonstrates
- REUSE VALUE → Where This Can Be Used Again
- FITNESS FUNCTION → Is This Worth Continuing?
- WHY THIS MATTERS → Why This Matters

4. Simplify language for readability
5. Break long paragraphs into bullet points where helpful
6. Emphasize real-world meaning over internal phrasing

Do not remove content. Only transform presentation.

---

## Step 4: Platform Export Block

Format based on the platform confirmed in Step 0.

### NOTION



NOTION EXPORT — AI Work Ledger
Page Title: [TITLE]
Properties:
Date: [DATE]
Session Type: [select]
Industry/Domain: [multi-select — user’s own tags]
Deliverable Exists: Yes / No
Reuse Rating: High / Medium / Low
Portfolio Published: No (default — user flips when published)
Page Body:
[Full entry with ## headers per section]
END NOTION EXPORT


### OBSIDIAN

Output as Markdown with YAML frontmatter. Suggested folder: `/Work Ledger/`



title: [TITLE]
date: [DATE]
session_type: [SESSION TYPE]
tags: [industry/domain tags as #hashtags]
deliverable: true/false
reuse: high / medium / low
published: false
[Full entry body in Markdown]


### GOOGLE DOCS

Output plain text with labeled section headers. Instruct user:
- Paste into a new Doc
- Apply Heading 2 to each section label using Format > Paragraph Styles
- File in: AI Work Ledger > [Year]

### MARKDOWN FILE

Output a clean `.md` block ready to save.
Suggested filename: `YYYY-MM-DD-[slug-of-title].md`
Suggest filing in a `/ledger/` directory the user controls locally or in a repo.

### MANUAL COPY

Output only the entry — no export wrapper. Add a note:
"Copy the entry above into your system of record. Tag by date, domain, and session type
for future retrieval."

---

## Output Rules

- Never summarize vaguely. Name the deliverable specifically.
- Never write the Proof Statement in third person.
- Never skip Human Direction vs. AI Contribution — this is the most important capability
  signal and hardest to reconstruct after the fact.
- The data scrub is non-negotiable. Never include proprietary or identifying details
  even if the user seems to want them in the entry.
- Keep the full entry under 650 words excluding the export block.
- After outputting, ask: "Ready to copy to [platform], or do you want to edit anything first?"

---

## Why This Matters

Your AI working intelligence is professional capital. The context you've built in this session —
domain knowledge, workflow preferences, decision patterns — is a portable asset. This entry
captures it in a format you can carry to your next role, next client, or next AI tool.

One entry per session. Filed consistently. Reviewed quarterly.
That's how the ledger becomes leverage.
