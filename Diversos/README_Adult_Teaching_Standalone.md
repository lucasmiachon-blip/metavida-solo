
# README — Adult Teaching, Assessment, and IRT (stand‑alone, zero‑to‑pro, unlimited budget)

## Outcomes
- Design, deliver, and evaluate a 2‑hour adult learning session with measurable gains.
- Build reliable assessments; run a basic IRT analysis and item review cycle.
- Publish a complete teaching package with versioning and quality gates.

## Assumptions
- Budget is not a constraint. Use best‑in‑class platforms and analytics.
- Audience: adult learners. Modality: blended or online.

## Stack (reference)
- **LMS**: Canvas (enterprise) or MoodleCloud. SCORM/xAPI enabled.
- **Authoring**: Articulate 360 (Rise, Storyline) and H5P. Slide design with Google Slides or PowerPoint.
- **Design**: Figma for visuals and handouts; accessibility checks (WCAG 2.2 AA).
- **Engagement**: Poll Everywhere or Slido; discussion in Circle/Discord/Teams.
- **Assessment**: Forms/Qualtrics for pre/post; Proctoring if needed; item bank in Git.
- **Analytics**: Learning Record Store (LRS) for xAPI; dashboards in Metabase/Looker; survey analytics in Qualtrics.
- **Psychometrics**: R (mirt, TAM, ltm, psych), jMetrik; optional Winsteps/IRTPRO.
- **Video**: Studio setup, teleprompter, dual audio, auto‑captions, transcripts.
- **Compliance**: IRB if researching outcomes; data privacy SOPs.

## Learning path (16 weeks)
**Weeks 1–2 — Learning science**
- Course: Learning How to Learn. Extract spacing, retrieval, and dual‑coding tactics.
- Draft session objectives with Bloom’s verbs and alignment map (UbD).

**Weeks 3–4 — Instructional design**
- Course: Instructional Design Foundations (Illinois).
- Build lesson plan with time boxes; choose CATs (Classroom Assessment Techniques).

**Weeks 5–6 — Assessment basics**
- Course: Assessment in Higher Education (Erasmus).
- Create pre/post test; build analytic rubric; pilot with 5 learners.
- Reliability target ≥0.7 (Cronbach’s alpha) at pilot scale.

**Weeks 7–8 — Delivery + iteration**
- Deliver the session. Collect pre/post, confidence ratings, and open‑text feedback.
- Use “Solve a Teaching Problem” guide to address top issue next run.

**Weeks 9–10 — IRT primer**
- Course: Introduction to Item Response Theory (Statistics.com) or equivalent.
- Run Rasch or 2PL in R. Produce item difficulty, discrimination, and fit indices.
- Write a 1‑page item review memo with keep/revise/drop decisions.

**Weeks 11–12 — Program evaluation**
- Frameworks: Kirkpatrick and CIPP. Define success metrics and detectable effect.
- Set up LRS events, dashboard, and a change log.

**Weeks 13–14 — Scale and quality**
- Standard setting: Angoff or Bookmark. Build blueprinting by objective.
- Accessibility and UDL audit; scenario‑based assessment pilot.

**Weeks 15–16 — Capstone**
- Publish full teaching package: objectives, slides, facilitator guide, assessments, scoring key, IRT memo, improvement plan.

## Design curriculum (run alongside)
- Google UX Design Certificate; UCSD Interaction Design; CalArts Graphic Design.
- “Storytelling with Data” course; Duarte slide design.
- Milestones: Week 2 low‑fi slides; Week 6 usability test (think‑aloud); Week 10 accessibility pass; Week 16 before/after redesign deck.

## AI‑assisted teaching loop (daily, 45 minutes)
1) Objectives in → model suggests aligned activities and diverse assessments.
2) Draft slides → model flags cognitive load issues and a11y risks.
3) Build 10‑item quiz → model outputs distractor rationales and item‑writing checklist.
4) Analyze data → model computes effect size and reliability; suggests revisions.
5) Generate 10 flashcards per session for your own mastery.

## Psychometrics quickstart (R)
- Import responses. Check missingness. Compute alpha (reliability). Inspect item difficulty p‑values.
- Fit Rasch using **TAM** or **mirt**. Review infit/outfit. Plot item/person maps.
- Revise items with poor discrimination or misfit. Re‑test on next cohort.

## KPIs
- Learning gains: standardized effect size ≥0.5 on pre/post.
- Assessment quality: item difficulty spread 0.2–0.8; reliability ≥0.8 after iteration.
- Engagement: attendance ≥90%; completion ≥80%.
- Accessibility: WCAG 2.2 AA checks pass; captions and transcripts complete.

## Checklists (minimum)
- Lesson blueprint, alignment map, and rubric in repo.
- Assessment security SOP; versioning of item bank; bias review.
- Data retention policy and anonymization of learner data.

## License
Personal use. Fork and adapt.
