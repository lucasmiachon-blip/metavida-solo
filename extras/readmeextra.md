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
- R/RStudio install; finish **[Posit Primers (archived/alternatives)](https://github.com/rstudio-education/primers)** “Basics” (free).  
- Coursera: **[R Programming (JHU)](https://www.coursera.org/learn/r-programming)** (JHU) — intro modules.  
- Deliverable: R project with `README.md`, `here::here()`, `renv::init()`.

### Week 2 — Data + Visualization
- Coursera: **[Data Science: Foundations using R (Specialization, JHU)](https://www.coursera.org/specializations/data-science-foundations-r)** (selected R modules).  
- Udemy: **Tidyverse Masterclass** (or equivalent).  
- Deliverable: Quarto notebook with `dplyr`, `ggplot2`, `gtsummary` table.

### Week 3 — Statistics Essentials
- Coursera: **[Data Analysis with R (Duke) — formerly *Statistics with R* Specialization](https://www.coursera.org/specializations/statistics)** (Duke) — inference + regression.  
- Free: **[R for Data Science (2e)](https://r4ds.hadley.nz/)** chapters on tidy model workflow.  
- Deliverable: regression report with diagnostics and interpretation.

### Week 4 — Clinical Reasoning + AI
- Coursera: **[[AI for Medicine (DeepLearning.AI)](https://www.coursera.org/specializations/ai-for-medicine) (DeepLearning.AI)](https://www.coursera.org/specializations/ai-for-medicine)** (DL.ai) — Dx/Prognosis module.  
- Free: draw DAGs with `dagitty` or `ggdag`.  
- Deliverable: tiny Shiny app with risk calculator + pre/post‑test flow.

### Week 5 — Patient Safety & QI
- Coursera: **[Developing a Systems View (Patient Safety I) — JHU](https://www.coursera.org/learn/patient-safety-systems-view)** or **[Patient Safety Specialization (JHU)](https://www.coursera.org/specializations/patient-safety)** (Plus).  
- Free: [IHI Open School](https://www.ihi.org/education/ihi-open-school) sample lessons (if available).  
- Deliverable: A3 or driver diagram; PDSA checklist in README.

### Week 6 — Decision Theory
- Coursera: **[[Mindware: Critical Thinking for the Information Age](https://www.coursera.org/learn/mindware): Critical Thinking for the Information Age](https://www.coursera.org/learn/mindware)** (biases + decision skills).  
- Free: [MIT OCW: Decisions, Games, and Rational Choice](https://ocw.mit.edu/courses/24-222-decisions-games-and-rational-choice-spring-2008/) (selected lectures).  
- Deliverable: payoff matrix + expected utility mini‑note; SEJ checklist.

### Week 7 — Adult Teaching & Assessment
- Coursera: **[Assessment in Higher Education (Erasmus)](https://www.coursera.org/learn/assessment-higher-education)** (Erasmus) + **[Assessment for Learning (Erasmus hub)](https://www.coursera.org/learn/assessmentforlearning)**.  
- Udemy: **R Markdown/Quarto Crash** for teaching artifacts.  
- Deliverable: rubric for case‑based OSCE station + retrieval‑practice plan.

### Week 8 — Cognitive Biases + Diagnostic Excellence
- Coursera: **[[Mindware: Critical Thinking for the Information Age](https://www.coursera.org/learn/mindware): Critical Thinking for the Information Age](https://www.coursera.org/learn/mindware)** review; free modules ([University of Pittsburgh — Diagnostic Error & Medical Decision Making](https://clinicalreasoning.pitt.edu/online-course/modules/) or [CHOP: Cognitive Bias & Diagnostic Error (open courses)](https://open.chop.edu/)).  
- Deliverable: bias checklist for rounds; implement diagnostic timeout.

### Weeks 9–10 — IRT & Evaluation Methods (overview level)
- Short course or seminar: **Intro to Item Response Theory** (statistics.com / Statistical Horizons) when discounted, or university open slides.  
- Coursera hub: **[Monitoring & Evaluation — Coursera topic](https://www.coursera.org/courses?query=monitoring%20and%20evaluation)**; **[Survey Data Collection and Analytics (UMD Specialization)](https://www.coursera.org/specializations/survey-data)**.  
- Deliverable: mock standard setting (Modified Angoff) + short IRT reflection (1PL vs 2PL vs 3PL).

### Weeks 11–12 — Capstones & Publication‑ready Outputs
- Finalize **Shiny dashboard**, **Quarto report**, and **Assessment blueprint**.  
- Add CI render (GitHub Actions), tag release, and write a 1‑page README summary.

---

## C) Course shortlists (pick 1–2 per section)

### R/RStudio
- **[R Programming (JHU)](https://www.coursera.org/learn/r-programming)**; **Data Science Foundations using R**; **[Data Analysis with R (Duke) — formerly *Statistics with R* Specialization](https://www.coursera.org/specializations/statistics)** (Coursera Plus).  
- **Tidyverse Masterclass**, **[R Programming (JHU)](https://www.coursera.org/learn/r-programming) A‑Z**, **Shiny Dashboard** (Udemy).  
- Free: **[Posit Primers (archived/alternatives)](https://github.com/rstudio-education/primers)**, **[R for Data Science (2e)](https://r4ds.hadley.nz/)**, **[swirl](https://swirlstats.com/)**, **[Happy Git with R](https://happygitwithr.com/)**.

### Patient Safety
- **[Developing a Systems View (Patient Safety I) — JHU](https://www.coursera.org/learn/patient-safety-systems-view) / Specialization** (Coursera Plus).  
- Free: **[IHI Open School](https://www.ihi.org/education/ihi-open-school)** samples; **[WHO Patient Safety Curriculum/Resources](https://www.who.int/teams/integrated-health-services/patient-safety)** materials.

### Decision Theory
- **[[Mindware: Critical Thinking for the Information Age](https://www.coursera.org/learn/mindware): Critical Thinking for the Information Age](https://www.coursera.org/learn/mindware)** (Coursera Plus).  
- Free: **MIT OCW Decisions, Games, and Rational Choice**.

### Clinical Reasoning + AI
- **[[AI for Medicine (DeepLearning.AI)](https://www.coursera.org/specializations/ai-for-medicine) (DeepLearning.AI)](https://www.coursera.org/specializations/ai-for-medicine)** (Coursera Plus).  
- Free: **[Aquifer: Diagnostic Excellence](https://aquifer.org/courses/aquifer-diagnostic-excellence/)** overview pages (if accessible).

### Cognitive Biases
- **[[Mindware: Critical Thinking for the Information Age](https://www.coursera.org/learn/mindware): Critical Thinking for the Information Age](https://www.coursera.org/learn/mindware)** (bias modules).  
- Free: **[University of Pittsburgh — Diagnostic Error & Medical Decision Making](https://clinicalreasoning.pitt.edu/online-course/modules/)** or **[CHOP: Cognitive Bias & Diagnostic Error (open courses)](https://open.chop.edu/) diagnostic error** sessions.

### Adult Teaching & Assessment
- **[Assessment in Higher Education (Erasmus)](https://www.coursera.org/learn/assessment-higher-education)**; **[Assessment for Learning (Erasmus hub)](https://www.coursera.org/learn/assessmentforlearning)** (Coursera Plus).  
- Udemy: **Instructional Design / e‑Learning** when on sale.

### IRT / Evaluation
- **Intro to IRT** (short seminar) or **university open slides**; pair with readings.  
- Coursera: **[Monitoring & Evaluation — Coursera topic](https://www.coursera.org/courses?query=monitoring%20and%20evaluation)**; **[Survey Data Collection and Analytics (UMD Specialization)](https://www.coursera.org/specializations/survey-data)**.

---

## D) Rubrics and checklists (paste into each repo)

**Project rubric (0–2 each):** Reproducible, Clean code, Narrative clarity, Figures, Tables, Bias checks, Causality stance, Decision framing, Assessment plan, README quality, CI passing.  
**Teaching checklist:** learning outcomes → retrieval activities → feedback loops → assessment alignment → accessibility.

---

## E) Minimal tool stack
R, RStudio, Quarto, Git, GitHub; R packages: `tidyverse`, `gtsummary`, `survival`, `MatchIt`, `WeightIt`, `gt`, `quarto`, `shiny`, `DT`. CI: GitHub Actions Quarto render.

*Maintainer: Lucas Miachon.*
