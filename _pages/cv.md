---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

You can download a PDF copy of my CV [here]({{ base_path }}/files/CV_Jiahui_Zhang.pdf).

Education
======
* M.S. in Statistics, University of Washington, Seattle, 2025 (GPA: 3.86/4.0)
* B.S. with Honours in Mathematics (Class I), University of Liverpool, 2023 (GPA 3.94/4.0)

Research Experience
======

<div class="cv-exp" markdown="1">

<div class="cv-exp-date">May 2025 – Present</div>

<h2 class="cv-exp-title">Covariate Similarity Driven Multi-Graph Approach for Treatment Effect Estimation under Interference</h2>

<p class="cv-exp-meta">Research Assistant · Advisor: Prof. Ruoqing Zhu, University of Illinois Urbana–Champaign</p>

- Developed a covariate-similarity-driven multi-graph approach modeling interference via similarity graphs, for both known- and unknown-network settings.
- Formulated multi-dimensional exposure vectors capturing heterogeneous spillovers, negative peer effects, and nonlinear interference (tanh + PReLU).
- Introduced treatment-intensity-based ATEs; ran large-scale simulations (ER and covariate-driven graphs, n = 4000) showing near-zero bias and gains over SNIPE, LS, and difference-in-means.

</div>

<div class="cv-exp" markdown="1">

<div class="cv-exp-date">Aug 2025 – Present</div>

<h2 class="cv-exp-title">Heteroscedastic Personalized Regression for Individualized Genomic Analysis</h2>

<p class="cv-exp-meta">Research Assistant · Advisor: Prof. Haohan Wang, University of Illinois Urbana–Champaign</p>

- Developed Het-PR, reformulating personalized modeling as a mixed-effects model with sample-specific variance terms for individualized SNP effects.
- Conducted simulations showing ~30–60% MSE reduction, 82–94% AUROC, and ~90–100% subgroup-recovery accuracy.
- Applied Het-PR to the ADNI GWAS cohort to stratify Alzheimer's patients into cognition-linked clusters.
- Performed pathway enrichment analysis revealing distinct architectures and a candidate Alzheimer's–epilepsy genetic axis.

</div>

<div class="cv-exp" markdown="1">

<div class="cv-exp-date">May 2024 – Present</div>

<h2 class="cv-exp-title">Modeling Per-Exposure Efficacy of Immune-Based Therapies for HIV-1 Prevention</h2>

<p class="cv-exp-meta">Research Assistant · Advisor: Prof. Bo Zhang, Fred Hutch / University of Washington</p>

- Built a microsimulation model of HIV-1 acquisition after bnAb infusion incorporating viral exposures, pharmacokinetics, and viral sensitivity.
- Calibrated the model via Bayesian rejection sampling on AMP trial data.
- Improved inference with ABC-MCMC integrating case counts and IC80 distributions.
- Built a [Shiny app](https://zjh68688.shinyapps.io/BayesShiny/) to simulate trial scenarios.

</div>

<div class="cv-exp" markdown="1">

<div class="cv-exp-date">Oct 2023 – Apr 2025</div>

<h2 class="cv-exp-title">Classifying Cerebral vs. Non-Cerebral Malaria from EEG with Machine Learning</h2>

<p class="cv-exp-meta">Research Assistant · Advisor: Prof. Bo Zhang, Fred Hutch / University of Washington</p>

- Conducted EDA, biomarker selection, imputation, and encoding on EEG signals.
- Trained ensemble models including GLM, GAM, and Random Forest with ten-fold cross-validation.
- Evaluated models via ROC/AUC, showing strong discrimination including retinopathy-negative cerebral malaria.
- Co-authored two peer-reviewed papers in *Clinical Infectious Diseases* and the *American Journal of Tropical Medicine and Hygiene*.

</div>


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
