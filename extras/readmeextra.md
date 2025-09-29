# readmeextra — Integrated Learning Pathway

Scope: management in medicine, patient safety, decision theory, clinical reasoning with AI, cognitive biases, adult teaching, IRT, evaluation methods, and R/RStudio programming. Preference: Coursera Plus, Udemy, and free/low‑cost resources.

---

## A) Outcome targets (8–12 weeks)
- Ship 3 artifacts: (1) **Shiny dashboard** (diagnostic support), (2) **Quarto report** (observational study), (3) **Assessment blueprint** (Modified Angoff + rubric).
- Pass 4 Coursera Plus modules, 2 Udemy boosters, and 1 free capstone reading list.
- Set up reproducibility: `renv`, GitHub Actions CI render, README with rubric.

---

## B) Weekly pathway (concise)

### Week 1 — Foundation + Tools
- R/RStudio install; finish **Posit Primers** “Basics” (free).  
- Coursera: **R Programming** (JHU) — intro modules.  
- Deliverable: R project with `README.md`, `here::here()`, `renv::init()`.

### Week 2 — Data + Visualization
- Coursera: **Data Science: Foundations using R** (selected R modules).  
- Udemy: **Tidyverse Masterclass** (or equivalent).  
- Deliverable: Quarto notebook with `dplyr`, `ggplot2`, `gtsummary` table.

### Week 3 — Statistics Essentials
- Coursera: **Statistics with R** (Duke) — inference + regression.  
- Free: **R for Data Science (2e)** chapters on tidy model workflow.  
- Deliverable: regression report with diagnostics and interpretation.

### Week 4 — Clinical Reasoning + AI
- Coursera: **AI for Medicine** (DL.ai) — Dx/Prognosis module.  
- Free: draw DAGs with `dagitty` or `ggdag`.  
- Deliverable: tiny Shiny app with risk calculator + pre/post‑test flow.

### Week 5 — Patient Safety & QI
- Coursera: **Patient Safety I** or **Patient Safety Specialization** (Plus).  
- Free: IHI Open School sample lessons (if available).  
- Deliverable: A3 or driver diagram; PDSA checklist in README.

### Week 6 — Decision Theory
- Coursera: **Mindware** (biases + decision skills).  
- Free: MIT OCW **Decisions, Games, and Rational Choice** (selected lectures).  
- Deliverable: payoff matrix + expected utility mini‑note; SEJ checklist.

### Week 7 — Adult Teaching & Assessment
- Coursera: **Assessment in Higher Education** (Erasmus) + **Assessment for Learning**.  
- Udemy: **R Markdown/Quarto Crash** for teaching artifacts.  
- Deliverable: rubric for case‑based OSCE station + retrieval‑practice plan.

### Week 8 — Cognitive Biases + Diagnostic Excellence
- Coursera: **Mindware** review; free modules (Pitt DEMDM or CHOP).  
- Deliverable: bias checklist for rounds; implement diagnostic timeout.

### Weeks 9–10 — IRT & Evaluation Methods (overview level)
- Short course or seminar: **Intro to Item Response Theory** (statistics.com / Statistical Horizons) when discounted, or university open slides.  
- Coursera hub: **Monitoring & Evaluation**; **Survey Data Collection and Analytics**.  
- Deliverable: mock standard setting (Modified Angoff) + short IRT reflection (1PL vs 2PL vs 3PL).

### Weeks 11–12 — Capstones & Publication‑ready Outputs
- Finalize **Shiny dashboard**, **Quarto report**, and **Assessment blueprint**.  
- Add CI render (GitHub Actions), tag release, and write a 1‑page README summary.

---

## C) Course shortlists (pick 1–2 per section)

### R/RStudio
- **R Programming**; **Data Science Foundations using R**; **Statistics with R** (Coursera Plus).  
- **Tidyverse Masterclass**, **R Programming A‑Z**, **Shiny Dashboard** (Udemy).  
- Free: **Posit Primers**, **R for Data Science (2e)**, **swirl**, **Happy Git with R**.

### Patient Safety
- **Patient Safety I / Specialization** (Coursera Plus).  
- Free: **IHI Open School** samples; **WHO patient safety** materials.

### Decision Theory
- **Mindware** (Coursera Plus).  
- Free: **MIT OCW Decisions, Games, and Rational Choice**.

### Clinical Reasoning + AI
- **AI for Medicine** (Coursera Plus).  
- Free: **Aquifer Diagnostic Excellence** overview pages (if accessible).

### Cognitive Biases
- **Mindware** (bias modules).  
- Free: **Pitt DEMDM** or **CHOP diagnostic error** sessions.

### Adult Teaching & Assessment
- **Assessment in Higher Education**; **Assessment for Learning** (Coursera Plus).  
- Udemy: **Instructional Design / e‑Learning** when on sale.

### IRT / Evaluation
- **Intro to IRT** (short seminar) or **university open slides**; pair with readings.  
- Coursera: **Monitoring & Evaluation**; **Survey Data Collection and Analytics**.

---

## D) Rubrics and checklists (paste into each repo)

**Project rubric (0–2 each):** Reproducible, Clean code, Narrative clarity, Figures, Tables, Bias checks, Causality stance, Decision framing, Assessment plan, README quality, CI passing.  
**Teaching checklist:** learning outcomes → retrieval activities → feedback loops → assessment alignment → accessibility.

---

## E) Minimal tool stack
R, RStudio, Quarto, Git, GitHub; R packages: `tidyverse`, `gtsummary`, `survival`, `MatchIt`, `WeightIt`, `gt`, `quarto`, `shiny`, `DT`. CI: GitHub Actions Quarto render.

*Maintainer: Lucas Miachon.*
