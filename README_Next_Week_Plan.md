# MetaVida — Next Week Plan (Week 2, 3–4 h/day)

Focus: WSL2 + Docker; Git branching; tiny local RAG demo; Make↔Notion A; Zotero→Quarto citations.

## Outcomes
- WSL2 Ubuntu + Docker Desktop working.
- Branch→PR→merge practiced.
- Minimal RAG over two local files (CPU).
- Make A (Gmail→Notion/Tasks) live.
- Zotero→BBT→Quarto citations render.

## Daily blocks
15m PC basics · 45–60m DevOps · 60–90m Math/Prob · 30–45m Biostats · 30–45m Assistants.

### Day 1 — WSL2
Enable “Virtual Machine Platform” + “Windows Subsystem for Linux”. Install: `wsl --install -d Ubuntu`. Update packages.

### Day 2 — Docker
Install Docker Desktop. Test: `docker run hello-world`. Optional: run postgres:alpine.

### Day 3 — Git branching
`git checkout -b week2-notes` → edit → commit → push → PR → merge → delete branch.

### Day 4 — Tiny RAG (local)
Python venv; `pip install langchain faiss-cpu pypdf`. Put 2 PDFs in `data/`. Index + answer 1 question; save transcript.

### Day 5 — Make A
Trigger: Gmail new email with label **Action**. Map Subject, From, Thread link, MessageID → Notion/Tasks upsert by MessageID.

### Day 6 — Zotero→Quarto
BBT auto-export `.bib` from “Teaching”; lock citekeys. Quarto project uses `bibliography:` and a CSL. Render citations.

### Day 7 — Review
Update README; tag a release. Optional rclone dry-run backup. Plan next 3 goals.

## Micro-routine (≤20m)
Label 3 emails → Notion Inbox sweep → tag 1 Zotero item → write a 2-line Evidence takeaway.
