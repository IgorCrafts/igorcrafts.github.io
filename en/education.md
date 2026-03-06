---
layout: default
title: Education
permalink: /en/education/
lang: en
translation_key: education
alt_lang: fr
alt_url: /fr/education/
subtitle: Applied math, AI, and neuroscience
---

# My academic journey


<div class="landing-subintro" markdown="1">
From engineering school to a PhD in applied math, forecasting neurodegenerative disease progression.
</div>


### A strange relationship with math and research

At 20, when I entered **École des Ponts**, I swore I’d never do math again. The lack of real-world applications was killing me. I seriously considered switching to business through a dual degree. But a business school graduate stopped me cold: *“Build technical skills first. You’ll have time for business later.”*

So I gave math a second chance. I studied economics at **Université Paris Dauphine**, then did a Machine Learning internship at Argonne, a U.S. national laboratory. That’s where maths clicked. It led me to a Machine learning master at **École Polytechnique**.

At that point, I wanted to build tangible things—research wasn’t an option. But it was peak “Big Data / ML hype.” Everyone wanted it, and I was struck by the shallow understanding and lack of mentorship in industry.

So, a few coffees later, I started a PhD with [Stanley Durrleman](https://who.rocq.inria.fr/Stanley.Durrleman/) and [Stéphanie Allassonnière](https://sites.google.com/site/stephanieallassonniere/).

### My research: modeling neurodegenerative disease progression

My research focused on modeling how neurodegenerative diseases progress (Alzheimer’s, Parkinson’s, Huntington). The objective was threefold:

- Reconstruct the “average” progression over long time horizons  
- Characterize individual trajectories relative to that average  
- Predict individual evolution up to ~5 years ahead  

All of that with multimodal data: cognitive assessments, imaging (MRI, PET), and blood biomarkers. The hard part is that real biomedical data refuses to behave. Progression isn’t linear; its pace changes. Follow-ups are irregular, missing, or incomplete. Each person provides only a small piece of the puzzle, and variability across individuals is massive.

So we built a single modeling backbone that could adapt across diseases and modalities, grounded in (1) geometry (Riemannian formalism), (2) probabilistic modeling of heterogeneity, and (3) inference under uncertainty and missingness (Monte Carlo / Markov chains, Expectation–Maximization).

My main academic work lives in [my thesis](https://theses.hal.science/tel-02524279v1/file/85395_KOVAL_2020_archivage.pdf) and papers, including:

- imaging applications ([Frontiers in Neurology](https://www.frontiersin.org/journals/neurology/articles/10.3389/fneur.2018.00235/full), [MICCAI](https://arxiv.org/pdf/1709.08491))  
- broad Alzheimer applications ([Scientific Reports](https://www.nature.com/articles/s41598-021-87434-1))  
- Huntington applications ([Scientific Reports](https://www.nature.com/articles/s41598-022-18848-8))  

### Making research that doesn’t evaporate after publication

Early in the PhD, I noticed something wasteful: every new student restarted from scratch (concepts, code, tooling). You learn a lot, but collectively you lose years.

So alongside papers, I built [**Leaspy**](https://leaspy.readthedocs.io/en/stable/), a Python package with a simple intention: give future PhDs and engineers a foundation they could extend with new models, new cohorts, new diseases, new analyses. It became a base for follow-up work, including:

- new progression models (see [R Couronné in MICCAI](https://hal.science/hal-03491692/document), [N Fournier in MICCAI](https://hal.science/hal-04295080v1/file/fournier_durrleman_MICCAI2023.pdf), [S Gruffaz in NIPS](https://proceedings.neurips.cc/paper_files/paper/2021/file/c7b90b0fc23725f299b47c5224e6ec0d-Paper.pdf), [PE Poulet in IPMI](https://inria.hal.science/hal-03276811/document) and [Statistics in Medecine](https://inria.hal.science/hal-04095450/document), [J Ortholand in Journal of Neurology](https://link.springer.com/article/10.1007/s00415-023-11932-7))  
- new diseases and datasets (see [C Di Folco in Movement Disorders](https://movementdisorders.onlinelibrary.wiley.com/doi/abs/10.1002/mds.29662), [F Cacciamani in Alzheimer's & Dementia](https://alz-journals.onlinelibrary.wiley.com/doi/full/10.1002/alz.053074), [B Sauty in Frontiers in Neurology](https://www.frontiersin.org/journals/neurology/articles/10.3389/fneur.2023.1161527/full), [E Petit in Brain](https://academic.oup.com/brain/advance-article-abstract/doi/10.1093/brain/awaf408/8305366), [S Kaisaridi in Neurology](https://www.neurology.org/doi/10.1212/WNL.0000000000210193))  

At its best, that mindset supported a large-scale prediction paper published in [**Nature Communications**](https://www.nature.com/articles/s41467-022-35712-5), showing our models could forecast Alzheimer's progression up to five years ahead. 

The same “make it last” instinct showed up elsewhere too: [Medium post about Leaspy](https://medium.com/@igoroa/analysis-of-longitudinal-data-made-easy-with-leaspy-f8d529fcb5f8), [teaching](/en/teaching/), [Digital-Brain.org](https://project.inria.fr/digitalbrain/), the [Disease Progression Modeling](https://disease-progression-modelling.github.io/pages/main.html#) website, and collaborations with academic and pharma teams to analyze clinical trial data (quantifying drug effects, stratifying populations).

It’s also what pushed me toward [building my first company.](/en/startup/){:.internal-link}

