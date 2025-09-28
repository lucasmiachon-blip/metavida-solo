# MetaVida — Week Plan (3–4 h/day)  
Focus: calculus & probability from zero, biostatistics, R/Python, VS Code + GitHub, assistants, and simple Make automations. Designed for beginner PC skills.

## Outcomes
- Basic PC hygiene; ZIP/unZIP; print to PDF.
- PowerShell file navigation.
- Git basics; VS Code ready.
- R/RStudio/Quarto and Python “hello world”.
- Start calculus/probability the right way; biostats from scratch.
- Build 3 Make automations that connect Gmail/Drive ↔ Notion.

## Daily structure (suggested)
- 15 min — PC basics.
- 45–60 min — Programming block (R/Python/VS Code/Git).
- 60–90 min — Math: algebra→logs→pre‑calc→calculus; probability.
- 30–45 min — Biostatistics.
- 30–45 min — Assistants & automations (Gemini, Copilot, Perplexity, Make).

> Tip: Use a timer. One block at a time. Take short breaks.

---

## Day 1 — PC hygiene + setup
**PC (15m):** Task Manager → Startup = disable clutter. Settings → Storage Sense = On. Uninstall unused apps. Install 7‑Zip. Add “Microsoft Print to PDF”.  
**PowerShell (20m):** `pwd`, `ls`, `cd`, `mkdir`, `ni`, `cat`, `rm`, `mv`. Make a practice tree `C:\Practice\week1` and delete it.  
**Programming (50m):** Install Git and VS Code. Configure Git: `git config --global user.name "Lucas Miachon"` and `git config --global user.email "lucas.miachon@fm.usp.br"`. Install VS Code extensions: Python, R, Markdown, GitHub Copilot.  
**Math (60m):** Algebra refresh with logs. Khan Academy: *Logarithms intro* → practice.  
**Biostats (30m):** Data types; mean/median; variance vs SD.  
**Assistants (25m):** Verify Notion, Google, Gmail, Drive logins. Create Notion databases: Tasks, Projects, Evidence (fields from prior plan).

## Day 2 — Shell fluency + R/RStudio/Quarto
**PC (15m):** File types, extensions, hidden files.  
**PowerShell (20m):** `Get-Help`, redirection `>`, pipelines `|`. Practice: list `.pdf` and output to `list.txt`.  
**Programming (60m):** Install R, RStudio, Quarto. Create `hello.R`. Quarto: make a minimal `hello.qmd` and render to HTML.  
**Math (60–75m):** Precalculus: exponents↔logs; functions; graph reading.  
**Biostats (30m):** Sampling vs population. Standard error intuition.  
**Assistants (20m):** Zotero install + Connector + Better BibTeX. Set File Sync = As needed. Collections: 00‑Inbox, To‑Read, Teaching, Research. Save one article and lock citekey.

## Day 3 — Git + Python + probability start
**PC (15m):** Downloads folder hygiene. Bookmarks and “Downloads” location.  
**Programming (60m):** Install Python 3.11. `python -m venv .venv` → activate → `pip install --upgrade pip`. Create `hello.py`.  
**Git (20m):** Create private repo `metavida-sandbox` (not in OneDrive). `git init`, `git add`, `git commit -m "init"`, `git remote add origin ...`, `git push -u origin main`.  
**Math/Prob (60–75m):** Start probability from intuition. Watch first two lectures of Harvard Stat 110 (Blitzstein) or read notes.  
**Biostats (30m):** Confidence intervals vs p‑values.  
**Assistants (20m):** Copilot Pro in PowerPoint: auto‑outline 5 slides for this week’s math topic. Save to OneDrive.

## Day 4 — VS Code workflow + R basics
**PC (15m):** ZIP/unZIP with 7‑Zip; print to PDF test.  
**Programming (60m):** VS Code basics: Command Palette, Integrated Terminal, Settings Sync. Create a workspace.  
**R (30–40m):** Vectors, data frames, `readr` and `dplyr` install. Mini task: compute BMI for a small CSV.  
**Math/Calc (60–75m):** Limits concept. Average vs instantaneous rate of change.  
**Biostats (30m):** Descriptive stats in R; make a small table.  
**Assistants (20m):** Perplexity: 2 “last 7 days” queries with citations on your topic; save links to Notion/Evidence.

## Day 5 — GitHub flow + Python basics + combinatorics
**PC (15m):** Keyboard shortcuts: Ctrl+L, Ctrl+T, Ctrl+Shift+T, Ctrl+J.  
**Git (30m):** Branch → edit → commit → PR → merge (even if solo).  
**Python (30m):** Functions, f‑strings. Write a BMI function and quick tests.  
**Math/Prob (60–75m):** Counting rules, permutations, combinations.  
**Biostats (30m):** Study design types. Bias vs confounding.  
**Assistants (20m):** Build 3 more slides in PowerPoint; import to Canva; apply brand style.

## Day 6 — R + Quarto slides + distributions
**PC (15m):** Screenshots and snipping tool; paste into slides.  
**R/Quarto (45m):** Create a Quarto slide deck; add two plots with `ggplot2`.  
**Math/Prob (60–75m):** Discrete distributions: Bernoulli, Binomial; expectation/variance.  
**Biostats (30m):** Normal vs Binomial; when CLT applies.  
**Assistants (30m):** Isabel: 1 real case → capture differential and terse rationale into Notion/Evidence.

## Day 7 — Make automations + review
**PC (15m):** Folder structure sanity check.  
**Make (60–75m):**  
- **A:** Gmail label **Action** → Notion/Tasks (dedupe by MessageID).  
- **B:** Gmail label **Evidence** → Notion/Evidence (first URL + Key takeaway field).  
- **C:** Google Drive “Teaching Drop” → Notion/Tasks (file link).  
**Biostats (30m):** Proportions and CI for a Binomial.  
**Math/Calc (45–60m):** Derivative as limit; derivative rules intro.  
**Weekly review (20m):** Clear inboxes, set next topic and 3 goals.

---

## Course tracks (choose primary + backups)
**Algebra & Precalculus:** Khan Academy Algebra I/II and Precalculus. Coursera: *Precalculus: Periodic Functions* (JHU).  
**Calculus from zero:** Coursera *Calculus One* (Ohio State) or UPenn *Calculus: Single Variable*.  
**Probability** (beginner→solid): Harvard Stat 110 (YouTube + official notes). MITx *Probability: The Science of Uncertainty and Data*.  
**Biostatistics:** JHU *Biostatistics in Public Health* or Duke *Statistics with R* (first two courses).  
**Programming:** RStudio primers; Datacamp’s free intros; Automate the Boring Stuff (Python) chapters 1–4 for basics.  
**Assistants:** Microsoft Copilot in PowerPoint docs; Google Gemini for Gmail/Drive summarization; Perplexity for newest with citations.

> Optional “with history/context” supplements: 3Blue1Brown calculus series; “The Story of Mathematics” (book/website) for historical notes alongside your study.

---

## Make: scenario sketches
- **A. Action→Tasks:** Trigger: Gmail new email with label *Action*. Steps: get thread id, subject, sender, link. Create/update Notion/Tasks by MessageID.  
- **B. Evidence→Evidence:** Trigger: Gmail new with label *Evidence*. Steps: grab first URL from body, create Notion/Evidence with Source URL and a placeholder “Key takeaway”.  
- **C. Drive drop→Tasks:** Trigger: new file in Drive folder *Teaching Drop*. Create Notion/Tasks with file name, link, and Project tag.

---

## Repo & files
- Keep this README at `OneDrive/Documentos/AssistantStack/MetaVida/Assets/plans/`.  
- Repo suggestion: `metavida-sandbox` for exercises and notes.  

### Push workflow (one-time then repeat)
```powershell
# In a clean folder outside OneDrive
git clone https://github.com/<your-username>/metavida-sandbox.git
cd metavida-sandbox

# Copy the README into the repo root, then:
git add README_MetaVida_Week_Plan.md
git commit -m "Add week plan"
git push
```

---

## Daily micro‑routine (≤20 min)
Label 3 emails → Notion Inbox sweep → tag 1 Zotero item → write a 2‑line Evidence takeaway.

## Keyboard quicklist
- Address bar: Ctrl+L. New tab: Ctrl+T. Reopen tab: Ctrl+Shift+T. Downloads: Ctrl+J.  
- Copy: Ctrl+C. Paste: Ctrl+V. Undo: Ctrl+Z. Screenshot: Win+Shift+S.

---

## Notes
- Go slow. One block per day is fine. Consistency beats volume.
- Keep a single “Study Log” note in Notion with day, blocks done, and next step.
