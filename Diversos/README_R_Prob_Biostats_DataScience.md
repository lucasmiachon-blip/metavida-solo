# Probability • Biostatistics • Data Science in R — Roadmap to Research Excellence

**Objective.** Build depth from fundamentals to publishable, reproducible research in R, targeting advanced expertise across probability, biostatistics, causal inference, Bayesian methods, clinical trials, meta‑analysis, and machine learning.

---

## 0) Fast Placement and Proof Refresh
- **Precalculus/Algebra refresh (as needed):** Khan Academy Precalculus. <https://www.khanacademy.org/math/precalculus>
- **Proofs and logic (short bridge):** *Book of Proof* (free PDF). <https://richardhammack.github.io/BookOfProof/Main.pdf>

**Outcome:** Ready for probability, linear algebra, and analysis‑style reasoning.

---

## 1) Core R Workflow and Reproducibility
- **R for Data Science (R4DS, 2e):** tidyverse, data wrangling, ggplot2, modeling basics. <https://r4ds.hadley.nz/>
- **Quarto:** literate programming, reports, manuscripts, slides. <https://quarto.org/>
- **targets:** reproducible pipelines for analyses. <https://books.ropensci.org/targets/>
- **renv:** project‑local package management. <https://rstudio.github.io/renv/>
- **Happy Git with R:** version control workflow. <https://happygitwithr.com/>

**Milestone:** All projects use Quarto + targets + renv + Git from day 1.

---

## 2) Probability and Mathematical Statistics (with R)
- **Harvard Stat 110 (videos + notes):** rigorous probability foundations. <https://stat110.hiteshish.com/> (mirror) and course site <https://stat110.net/>
- **Introduction to Probability (MIT 6.041/6.431 OCW):** applied probability, transforms, Markov chains. <https://ocw.mit.edu/courses/6-041sc-probabilistic-systems-analysis-and-applied-probability-fall-2013/>
- **ModernDive (Statistical Inference via Data Science in R):** simulation‑first inference. <https://moderndive.com/>
- **All of Statistics (supplemental text):** Wasserman (conceptual companion). (Find via library access)

**Practice in R:** simulate laws of large numbers, CLT, Markov chains; bootstrap CIs; compare analytic vs simulation.

---

## 3) Statistical Inference and Modeling in R
- **OpenIntro Statistics (with R labs):** foundations + tidyverse workflows. <https://www.openintro.org/book/os/>
- **An Introduction to Statistical Learning (ISLR):** linear/logistic regression, resampling, trees. R labs + datasets. <https://www.statlearning.com/>
- **GLMs and GLMMs with R:**
  - *GLM* (family, link, deviance) with **glm()**, diagnostics.
  - *Mixed models* via **lme4**. <https://cran.r-project.org/package=lme4>
  - *glmmTMB* for zero‑inflation and flexible random effects. <https://cran.r-project.org/package=glmmTMB>

**Milestone:** Fit, diagnose, and interpret GLM/GLMM; write a Quarto report with code appendix.

---

## 4) Bayesian Data Analysis in R
- **Bayes Rules! (free online book):** Bayesian workflow with R and tidyverse. <https://www.bayesrulesbook.com/>
- **Statistical Rethinking (course + R/Stan):** generative modeling; prior‑posterior practice. Code: <https://github.com/rmcelreath/rethinking>
- **brms / rstanarm / CmdStanR:** high‑level and low‑level Bayesian modeling. <https://cran.r-project.org/package=brms> <https://mc-stan.org/cmdstanr/>

**Milestone:** Fit hierarchical models with priors, posterior predictive checks, and sensitivity analyses.

---

## 5) Causal Inference (with R)
- **Causal Inference: What If (Hernán & Robins, free PDF):** potential outcomes, DAGs, g‑methods. <https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/>
- **The Effect (Cunningham’s Mixtape, open resources):** IV, DiD, RCTs vs observational. <https://www.theeffectbook.net/>
- **Tools:** **dagitty** (DAGs), **MatchIt** (matching), **grf** (causal forests), **did** (difference‑in‑differences).  
  CRAN: <https://cran.r-project.org/package=dagitty> <https://cran.r-project.org/package=MatchIt> <https://cran.r-project.org/package=grf> <https://cran.r-project.org/package=did>

**Milestone:** Identify adjustment sets from DAGs; estimate ATE with robust diagnostics; write a causal DAG‑first analysis.

---

## 6) Survival, Longitudinal, and Clinical Trials
- **Survival analysis:** **survival** + **survminer** packages; Cox model, competing risks.  
  <https://cran.r-project.org/package=survival> <https://cran.r-project.org/package=survminer>
- **Longitudinal/mixed:** **lme4**, **nlme**, **glmmTMB**; marginal models via **geepack**.  
  <https://cran.r-project.org/package=nlme> <https://cran.r-project.org/package=geepack>
- **Group‑sequential trials/power:** **gsDesign**, **rpact**.  
  <https://cran.r-project.org/package=gsDesign> <https://cran.r-project.org/package=rpact>

**Milestone:** Plan a group‑sequential RCT, simulate power, analyze time‑to‑event endpoints.

---

## 7) Evidence Synthesis: Meta‑Analysis and Network Meta‑Analysis
- **Doing Meta‑Analysis with R (free book):** practical guide with **metafor**. <https://bookdown.org/MathiasHarrer/Doing_Meta_Analysis_in_R/>
- **Pairwise MA:** **metafor**, **meta**. <https://cran.r-project.org/package=metafor> <https://cran.r-project.org/package=meta>
- **Network MA:** **netmeta** (frequentist), **gemtc** and **BUGSnet** (Bayesian).  
  <https://cran.r-project.org/package=netmeta> <https://cran.r-project.org/package=gemtc> <https://cran.r-project.org/package=BUGSnet>
- **Certainty:** **CINeMA** web app. <https://cinema.ispm.unibe.ch/>

**Milestone:** Build a league table, ranks (SUCRA/P‑score), and a Summary‑of‑Findings table with certainty judgments.

---

## 8) Time Series and Forecasting (R‑native)
- **Forecasting: Principles and Practice (fpp3, free):** tsibble/fable/feasts. <https://otexts.com/fpp3/>
- **State‑space models:** fable + KFAS; intervention/structural time series. <https://cran.r-project.org/package=KFAS>

**Milestone:** End‑to‑end forecast project with accuracy benchmarking and MAPE/CRPS reporting.

---

## 9) High‑Dimensional Learning and ML in R
- **tidymodels:** unified modeling, resampling, tuning. <https://www.tidymodels.org/>
- **glmnet / xgboost / ranger / lightgbm:** regularized GLMs and tree ensembles.  
  <https://cran.r-project.org/package=glmnet> <https://cran.r-project.org/package=xgboost> <https://cran.r-project.org/package=ranger> <https://github.com/microsoft/LightGBM/tree/master/R-package>
- **mlr3:** modular ML framework. <https://mlr3.mlr-org.com/>

**Milestone:** Build tuned, cross‑validated pipelines with proper leakage control and report calibrated performance.

---

## 10) Health Economics and Value of Information (VOI) in R
- **voi (Value of Information):** EVPI/EVPPI/EVSI workflows. <https://cran.r-project.org/package=voi>
- **BCEA (Bayesian Cost‑Effectiveness Analysis):** decision‑analytic modeling. <https://cran.r-project.org/package=BCEA>
- **hesim:** patient‑level simulation for cost‑effectiveness. <https://hesim-dev.github.io/hesim/>

**Milestone:** Compute EVSI for a proposed trial and decide “research yes/no” against cost.

---

## 11) Visualization and Communication
- **ggplot2:** grammar of graphics; extensions. <https://ggplot2-book.org/>
- **Fundamentals of Data Visualization (free):** design, perception. <https://clauswilke.com/dataviz/>

**Milestone:** Journal‑ready figures with reproducible code; color‑blind‑safe palettes; data availability statement.

---

## 12) Performance and Big Data in R
- **data.table:** high‑performance tables. <https://rdatatable.io/>
- **arrow:** columnar data + interoperability. <https://arrow.apache.org/docs/r/>
- **parallel/future/furrr:** multicore workflows. <https://cran.r-project.org/package=future> <https://cran.r-project.org/package=furrr>
- **Advanced R:** performance, environments, metaprogramming. <https://adv-r.hadley.nz/>
- **R Packages (2e):** build, test, document, release. <https://r-pkgs.org/>

**Milestone:** Profile and speed up a pipeline 10×; ship one internal R package with tests and CI.

---

## 13) Clinical Reporting and Open Science
- **EQUATOR network:** CONSORT (trials), STROBE (observational), PRISMA (reviews). <https://www.equator-network.org/>
- **OSF (Open Science Framework):** preregistration and data/code sharing. <https://osf.io/>

**Milestone:** One preregistered study; one fully reproducible paper repository.

---

## Capstones (pick 3–5 over the program)
1. **Replicate** a published NEJM/JAMA/ICMJE trial analysis in R with open data/simulated data.  
2. **NMA project:** reproduce a network meta‑analysis with netmeta/gemtc; create league tables and SUCRA.  
3. **Causal study:** DAG‑first observational study, matching/IPW, sensitivity to unmeasured confounding.  
4. **Bayesian hierarchical model:** brms/rstanarm with prior elicitation and posterior predictive checks.  
5. **VOI analysis:** compute EVSI for a proposed trial and write a one‑page decision brief.  
6. **Package:** build and release an R package for a niche biostat method; add vignettes and CI.

---

## Suggested Sequence (18–24 months, adaptable)
- **Months 1–2:** Sections 1–2 (workflow + probability foundations).  
- **Months 3–5:** Sections 3–4 (inference + Bayesian) with one capstone.  
- **Months 6–8:** Sections 5–6 (causal + survival/longitudinal + trials).  
- **Months 9–11:** Sections 7–8 (meta‑analysis + time series).  
- **Months 12–15:** Section 9 (ML) + Section 12 (performance) + package delivery.  
- **Months 16–18:** Section 10 (VOI) + Section 13 (open science) + 2 capstones.  
- **Months 19–24:** Independent research + submissions; teach a short workshop.

---

## Daily/Weekly Operating Rules
- **Daily:** 2 hours deep work (proofs or derivations) + 2 hours coding.  
- **Weekly:** 1 reproducible report + 1 public note (blog/Quarto) + 1 code review.  
- **Monthly:** 1 capstone milestone + 1 preprint draft segment.

---

## Reading List (selected, open or widely available)
- Wasserman, *All of Statistics*.  
- Hyndman & Athanasopoulos, *Forecasting: Principles and Practice (fpp3)*.  
- Hernán & Robins, *Causal Inference: What If*.  
- McElreath, *Statistical Rethinking* (videos/code).  
- Wickham et al., *R for Data Science (2e)*; *Advanced R*; *R Packages (2e)*.  
- Harrer et al., *Doing Meta‑Analysis in R*.  
- Boyd & Vandenberghe, *Convex Optimization* (for ML foundations). <https://web.stanford.edu/~boyd/cvxbook/>

---

## Research Habits
- Pre‑register, version data/code, and automate with targets.  
- Keep a definitions/lemmas notebook; reproduce at least one paper per quarter.  
- Write negatives/nulls; practice transparent uncertainty statements.

