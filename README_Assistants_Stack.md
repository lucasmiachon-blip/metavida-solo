# Assistants & Tools Stack — README

Purpose: one-glance map of roles, setup, and when to use each tool. Keep experiments in a repo; avoid sync locks.

## Stack
AI assistants: ChatGPT, Gemini Advanced, Copilot Pro, Perplexity Pro, Elicit, Consensus, ChatPDF Pro.
Clinical: Isabel Pro.
Research capture: Zotero + Better BibTeX, Research Rabbit, Feedly, scite.
Slides/boards: Canva Pro, Miro Pro, PowerPoint (Copilot).
Dev: VS Code, GitHub Pro.
Automation: Make, rclone.
Data/ML: Orange Data Mining.
Hub: Notion.

## Roles
- ChatGPT: structured reasoning, code help, stats walkthroughs.
- Gemini Advanced: Gmail/Drive/Docs summaries and Q&A.
- Copilot Pro: PPT/Word drafting.
- Perplexity Pro: fresh web with citations (“Past 7 days”).
- Elicit/Consensus: paper discovery, evidence-first answers.
- ChatPDF Pro: interrogate a single PDF.
- Isabel Pro: differential generator; document rationale.
- Zotero+BBT: capture, tag, cite; file sync “As needed”.
- Research Rabbit/Feedly/scite: find, track, verify.
- Canva/Miro: style decks, map ideas.
- VS Code/GitHub Pro: code + versioning.
- Make/rclone: glue Gmail/Drive/Notion; bulk copy across clouds.
- Orange: no-code ML.
- Notion: Tasks, Projects, Evidence.

## Daily flow (default)
1) Gmail triage → Gemini summary → label Action/Evidence.
2) Discovery → Perplexity “Past 7 days” + Feedly → move 3 items to Zotero To-Read.
3) Evidence → ChatPDF a PDF → add 2-line takeaway to Notion/Evidence.
4) Teaching → Copilot outline → Canva style → export PPTX/PDF.
5) Coding → VS Code commit to GitHub.
6) Automate → Make: A/B/C to Notion.

## Make scenarios
A Action→Tasks: Gmail label **Action** → Notion/Tasks. Key = MessageID.
B Evidence→Evidence: Gmail label **Evidence** → Notion/Evidence. First URL + takeaway.
C Drive drop→Tasks: new file in “Teaching Drop” → Notion/Tasks with link.

## Security
2FA everywhere. Use GitHub PAT (repo scope). No PHI to third-party AIs. rclone with --dry-run first.
