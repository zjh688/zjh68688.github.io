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

<p class="cv-exp-meta">Research Assistant · Advisor: Ruoqing Zhu (Professor, Department of Statistics, University of Illinois Urbana–Champaign)</p>

- Developed a covariate similarity driven multi-graph approach that models interference through covariate-based similarity graphs, extending applicability to both known and unknown-network settings.
- Formulated multi-dimensional exposure vectors to capture heterogeneous spillovers, negative peer effects, and nonlinear interference via linear and neural network forms (incorporating tanh + PReLU activation functions) for broader application.
- Introduced ATEs based on treatment intensity to evaluate treatment effects under varying coverage levels, generalizing beyond traditional all-or-none contrasts.
- Conducted large-scale simulations (ER and covariate-driven graphs, n = 4000) demonstrating that new approach achieves near-zero bias and outperforms SNIPE, LS, and difference-in-means estimators.

</div>

<div class="cv-exp" markdown="1">

<div class="cv-exp-date">Aug 2025 – Present</div>

<h2 class="cv-exp-title">Heteroscedastic Personalized Regression for Individualized Genomic Analysis</h2>

<p class="cv-exp-meta">Research Assistant · Advisor: Haohan Wang (Assistant Professor, School of Information Sciences, University of Illinois Urbana–Champaign)</p>

- Developed the Heteroscedastic Personalized Regression (Het-PR) framework, reformulating personalized modeling as a linear mixed-effects model with sample-specific variance terms to estimate individualized SNP effect profiles.
- Conducted extensive simulations demonstrating that Het-PR outperforms population-level models: it reduced estimation MSE by ~30–60% and achieved 82–94% AUROC in identifying subject-specific genetic effects, while enabling recovery of latent patient subgroups (≈90–100% accuracy via hierarchical clustering).
- Applied Het-PR to the ADNI cohort (GWAS data), stratifying Alzheimer’s patients into two genetically distinct clusters with consistently divergent cognitive performance across five domains, thereby linking fine-scale genetic signatures to the severity of cognitive impairment.
- Identified cluster-specific SNP sets and performed pathway enrichment analysis, revealing distinct functional architectures.
- Discovered that variants previously associated with epilepsy powerfully separate the two AD clusters, indicating a shared cross-disease genetic axis and suggesting new genetic links between Alzheimer’s and epilepsy.

</div>

<div class="cv-exp" markdown="1">

<div class="cv-exp-date">May 2024 – Present</div>

<h2 class="cv-exp-title">Modeling Per-Exposure Efficacy of Immune-Based Therapies for HIV-1 Prevention</h2>

<p class="cv-exp-meta">Research Assistant · Advisor: Bo Zhang (Assistant Professor, Fred Hutch; Affiliate Assistant Professor, Department of Biostatistics, University of Washington)</p>

- Developed a microsimulation model to predict HIV-1 acquisition risks following neutralizing antibody (bnAb) infusion, incorporating viral exposures, individual pharmacokinetics, and viral sensitivity.
- Calibrated the model with Bayesian rejection sampling using AMP trial data, estimating key parameters governing infection risk and neutralization efficacy.
- Enhanced inference by implementing ABC-MCMC, integrating both case counts and IC80 (virus neutralization sensitivity) distributions to improve posterior accuracy and acceptance rates.
- Designed a [Shiny app](https://zjh68688.shinyapps.io/BayesShiny/) to simulate trial scenarios, producing efficacy and sensitivity distribution plots.

</div>

<div class="cv-exp" markdown="1">

<div class="cv-exp-date">Oct 2023 – Apr 2025</div>

<h2 class="cv-exp-title">Classifying Cerebral vs. Non-Cerebral Malaria from EEG with Machine Learning</h2>

<p class="cv-exp-meta">Research Assistant · Advisor: Bo Zhang (Assistant Professor, Fred Hutch; Affiliate Assistant Professor, Department of Biostatistics, University of Washington)</p>

- Conducted exploratory data analysis (EDA) on EEG signals, including biomarker selection, missing data imputation, and categorical encoding.
- Trained ensemble machine learning models (GLM, GAM, Random Forest) with ten-fold cross- validation across baseline, qualitative, and quantitative EEG features.
- Evaluated predictive performance using ROC curves and AUC, showing strong discrimination between cerebral malaria (CM) and non-malarial cases, including retinopathy-negative CM.
- Co-authored two peer-reviewed manuscripts in *Clinical Infectious Diseases* and the *American Journal of Tropical Medicine and Hygiene*.

</div>


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Skills
======
* Programming: Python, R, C++, LaTeX, Java, MATLAB
* Methods: causal inference, Optimization, Bayesian Modeling, machine learning, linear mixed effect model, Biomedical Data Analysis
* Languages: Mandarin Chinese (native), English (fluent)

Leadership &amp; Activities
======
* Vice President, XJTLU Mathematics Society (2019–2020) — organized academic lectures with professors and senior students as guest speakers.

Interests
======
* Badminton, running, movies, travel
