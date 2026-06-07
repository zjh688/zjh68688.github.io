---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

You can download a PDF copy of my CV [here](/files/CV_Jiahui_Zhang.pdf).

Education
======
* M.S. in Statistics, University of Washington, Seattle, 2025 (GPA: 3.86/4.0)
* B.S. with Honours in Mathematics (Class I), University of Liverpool, 2023 (Top 5%; WES-evaluated GPA 3.94/4.0)
* B.S. with Honours in Applied Mathematics (Class I), Xi'an Jiaotong-Liverpool University, 2021 (Top 8%)

Research Experience
======
* **Research Assistant**, University of Illinois Urbana–Champaign (May 2025 – Present)
  * *Covariate similarity driven multi-graph approach for treatment effect estimation under interference* — Advisor: Prof. Ruoqing Zhu
  * Developed a covariate-similarity-driven multi-graph approach modeling interference via similarity graphs, for both known- and unknown-network settings.
  * Formulated multi-dimensional exposure vectors capturing heterogeneous spillovers, negative peer effects, and nonlinear interference (tanh + PReLU).
  * Introduced treatment-intensity-based ATEs; ran large-scale simulations (ER and covariate-driven graphs, n = 4000) showing near-zero bias and gains over SNIPE, LS, and difference-in-means.

* **Research Assistant**, University of Illinois Urbana–Champaign (Aug 2025 – Present)
  * *Heteroscedastic Personalized Regression (Het-PR) framework* — Advisor: Prof. Haohan Wang
  * Developed Het-PR, reformulating personalized modeling as a mixed-effects model with sample-specific variance terms for individualized SNP effects.
  * Simulations: ~30–60% MSE reduction, 82–94% AUROC, ~90–100% subgroup-recovery accuracy.
  * Applied to the ADNI GWAS cohort to stratify Alzheimer's patients into cognition-linked clusters; pathway enrichment revealed distinct architectures and a candidate Alzheimer's–epilepsy genetic axis.

* **Research Assistant**, Fred Hutch / University of Washington (May 2024 – Present)
  * *Modeling per-exposure efficacy of immune-based therapies for HIV-1 prevention* — Advisor: Prof. Bo Zhang
  * Built a microsimulation model of HIV-1 acquisition after bnAb infusion incorporating viral exposures, pharmacokinetics, and viral sensitivity.
  * Calibrated via Bayesian rejection sampling on AMP trial data; improved inference with ABC-MCMC integrating case counts and IC80 distributions.
  * Built a [Shiny app](https://zjh68688.shinyapps.io/BayesShiny/) to simulate trial scenarios.

* **Research Assistant**, Fred Hutch / University of Washington (Oct 2023 – Apr 2025)
  * *Classifying cerebral vs. non-cerebral malaria from EEG with machine learning* — Advisor: Prof. Bo Zhang
  * Conducted EDA, biomarker selection, imputation, and encoding on EEG signals.
  * Trained ensemble models (GLM, GAM, Random Forest) with ten-fold CV; evaluated via ROC/AUC, showing strong discrimination including retinopathy-negative cerebral malaria.
  * Co-authored two peer-reviewed papers (*Clinical Infectious Diseases*; *American Journal of Tropical Medicine and Hygiene*).

* **Project Team Leader**, University of Washington (Apr 2024 – Jun 2024)
  * *Causal relationship between job-training programs and income* — Advisor: Prof. Thomas Richardson
  * Implemented IPW, outcome regression, doubly robust, and DiD estimators on the NSW and PSID datasets; diagnosed overlap violations causing unstable ATEs in observational data.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Skills
======
* Programming: Python, R, C++, LaTeX, Java, MATLAB
* Methods: personalized / mixed-effects modeling, causal inference, Bayesian computation (ABC-MCMC), ensemble machine learning, statistical genomics (GWAS)
* Languages: Mandarin Chinese (native), English (fluent)

Leadership &amp; Activities
======
* Vice President, XJTLU Mathematics Society (2019–2020) — organized academic lectures with professors and senior students as guest speakers.

Interests
======
* Badminton, running, movies, travel
