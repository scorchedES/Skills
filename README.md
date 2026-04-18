# AI Work Ledger

A Claude skill that generates a structured career asset entry at the close of any substantive AI-assisted work session.

Every entry serves three functions at once: portfolio evidence, portable context seed, and capability proof statement you can use in interviews, proposals, or bios.

---

## What It Does

At the end of a work session, trigger this skill and it will:

1. **Scrub the session** — removes any proprietary, identifying, or confidential information before writing anything. Non-negotiable. Runs every time.
2. **Reconstruct what happened** — silently reviews the conversation to identify what was built, what decisions were made, what you directed vs. what the AI generated
3. **Generate a structured entry** — captures the deliverable, your decision reasoning, your demonstrated capability, and the context encoded in the session
4. **Export to your platform** — formats the output for Notion, Obsidian, Google Docs, Markdown file, or manual copy

---

## Why This Exists

Your AI working intelligence is professional capital. Every session encodes domain knowledge, workflow patterns, and decision frameworks that belong to you — not the platform. This skill captures that value before it disappears into chat history.

One entry per session. Filed consistently. That's how a ledger becomes leverage.

---

## Installation

1. Download `SKILL.md`
2. Drop it into your Claude Project's skills folder
3. That's it — the skill is active for that project

---

## How to Trigger It

Say any of the following at the end of a session:

- "Log this session"
- "Add to my portfolio"
- "Capture this work"
- "Create a ledger entry"
- "Document this build"
- "End of session"
- "Save this to my work ledger"
- "Export this entry"

---

## What the Entry Captures

| Field | What It Records |
|---|---|
| Title | Specific name of what was built |
| Session Type | Build / Analysis / Strategy / Training Material / System Design / Policy / Research / Communication / Audit / Other |
| Industry/Domain | Your tags — defined on first use |
| What Was Built | 2–4 sentences describing the artifact, its purpose and scope |
| Decisions Made | Bullet list of tradeoffs, pivots, and choices with reasoning |
| Human Direction vs. AI Contribution | What you directed, what AI generated, what you validated |
| Context Encoded | The domain knowledge and workflow patterns this session represents — portable to a new AI |
| Portfolio Proof Statement | 1–3 sentences, first person, usable verbatim in interviews or proposals |
| Reuse Value | What travels to the next role or client, rated High / Medium / Low |

---

## Export Formats

When you trigger the skill, it asks where you're exporting before generating anything. Supported platforms:

- **Notion** — structured property block + page body
- **Obsidian** — Markdown with YAML frontmatter
- **Google Docs** — plain text with heading labels
- **Markdown file** — clean `.md` block with suggested filename
- **Manual copy** — just the entry, no wrapper

---

## Data Scrub Guardrail

The scrub runs before reconstruction — not after. It generalizes employer names, client names, named individuals, specific financial figures, internal system names, confidential strategy, and identifying geography. What stays: your domain vocabulary, your decision frameworks, your workflow patterns, your demonstrated capability. The entry is designed to be portable and shareable without carrying anything that belongs to a current or former employer.

---

## License

MIT — use it, adapt it, share it.

Built by [Melissa Honeycutt](https://github.com/scorchedES) | AI Workflow Architecture
