# Learning Analytics for Student Engagement and Success

**MSc Data Analytics dissertation portfolio | Elizabeth Chinyere Kanu**

This repository presents a portfolio-friendly overview of the dissertation *Leveraging Learning Analytics to Enhance Student Engagement and Success in E-Learning Platforms*. It explores how learning-management-system (LMS) activity—such as login frequency, forum participation, video engagement, and assignment activity—may help educators understand engagement and identify students who could benefit from support.

> **Scope note:** This is a documentation-focused portfolio summary, not a fully reproducible analysis package. The original data, scripts, model configuration, and full evaluation outputs are not included. Results are attributed to the dissertation and have not been independently re-run.

## Research question
How can learning analytics help identify behavioral indicators of student engagement, predict academic outcomes, and inform timely, responsible support in e-learning?

## Methods described
- Exploratory data analysis and descriptive statistics
- Pearson correlation and multiple regression
- Logistic regression / classification for course completion or non-completion
- Surveys and semi-structured interviews
- Thematic analysis of qualitative material

## Main findings reported
- Login frequency was positively associated with assignment scores.
- Students who completed courses were described as having higher median forum participation.
- Login frequency, video engagement, and forum participation were reported as predictors of final grades.
- The dissertation reports a multiple-regression model with R² = 0.58.
- A logistic-regression classifier was reported to achieve 84% accuracy, 0.81 precision, and 0.86 recall. These figures are reproduced as reported and cannot be independently verified from the materials in this repository.

## Repository contents
- `docs/research-overview.md` — aims, objectives, and research questions
- `docs/methods.md` — methodology as described in the dissertation
- `docs/results-and-interpretation.md` — reported findings and cautious interpretation
- `docs/ethics-and-limitations.md` — limitations and future work
- `docs/cv-and-application-summary.md` — CV and application wording
- `assets/README.md` — guidance for adding permitted figures

## Reproducibility status
**Documentation-only portfolio.** Do not describe this as a reproducible implementation until the original analysis code and legally shareable data have been located, checked, and documented. The dissertation's methodology contains differing descriptions of interview sample sizes; see `docs/methods.md`.

## Responsible use
- Do not upload identifiable student records, interview transcripts, survey responses, or confidential LMS exports.
- A risk score should prompt supportive human follow-up, not automatically penalize or label a student.
- The dissertation says intervention testing was outside the study's scope; do not claim that this research proved interventions improved retention.
- Do not claim that a formal demographic fairness audit was completed. Limited demographic segmentation is identified as a limitation.

## Author
**Elizabeth Chinyere Kanu** — MSc Data Analytics  
Research interests: learning analytics, predictive modelling, responsible AI, student engagement, and data-informed support.

## Suggested citation
Kanu, E. C. (2024). *Leveraging Learning Analytics to Enhance Student Engagement and Success in E-Learning Platforms*. MSc Data Analytics dissertation.

The cover lists 2024, while the academic ethics declaration is dated 15 June 2025. Verify the official submission/award year before final publication.
