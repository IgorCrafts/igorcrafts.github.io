---
layout: default
title: Éducation
permalink: /fr/education/
lang: fr
translation_key: education
alt_lang: en
alt_url: /en/education/
subtitle: Math appliquées, IA et neurosciences
---

# Mon parcours académique

<div class="landing-subintro" markdown="1">
De l’école d’ingénieur à un doctorat en mathématiques appliquées, pour prédire l’évolution des maladies neurodégénératives.
</div>

### Une relation étrange avec les maths et la recherche

À 20 ans, en entrant à **l’École des Ponts**, je me suis juré d'arrêter les maths, par manque d'applications concrètes. J’ai envisagé un double diplôme avec une échole de commecer. Mais une diplômée m'en a découragé très clairement : *« Apprends d’abord des compétences techniques. Tu auras le temps pour la partie business plus tard. »*

Alors j’ai redonné une chance aux maths. J’ai étudié l’économie à **l’Université Paris Dauphine**, puis j’ai fait un stage en Machine Learning à Argonne, un laboratoire national américain. C’est là que j'ai enfin trouvé un intérêt aux maths. Intérêt poursuivi en master de Machine Learning à **l’École Polytechnique**.

À la fin du master, je souhaitais mettre à profit mes compétences en rejoignant une entreprise. Mais, en pleine mode du “Big Data", le manque de compétences qui y régnaient m'en a découragé.

Pour cette raison, j’ai démarré une thèse avec [Stanley Durrleman](https://who.rocq.inria.fr/Stanley.Durrleman/) et [Stéphanie Allassonnière](https://sites.google.com/site/stephanieallassonniere/).

### Mes recherches scientifiques : modéliser l’évolution des maladies neurodégénératives

Mes recherches scientifiques portaient sur la modélisation et la prédiction de la progression des maladies neurodégénératives (Alzheimer, Parkinson, Huntington). L’objectif était triple :

- Reconstruire la progression “moyenne” sur de longues échelles de temps
- Caractériser les trajectoires individuelles par rapport à cette moyenne
- Prédire l’évolution individuelle jusqu’à ~5 ans à l’avance

Le tout avec des données multimodales : tests cognitifs, imagerie (IRM, TEP), et biomarqueurs sanguins. Les difficultés à les traiter étaient multiples. Leur progression n’est pas linéaire. Les suivis sont irréguliers, manquants ou incomplets. Chaque personne n’apporte qu’une petite pièce du puzzle, et la variabilité interindividuelle est importante.

Nous avons donc développé un modèle capable de s’adapter à différentes maladies et données, qui tire profit de (1) la géométrie riemannienne, (2) la modélisation probabiliste de l’hétérogénéité, et (3) l’inférence sous incertitude et données manquantes (Monte Carlo / chaînes de Markov, Expectation–Maximization).

L’essentiel de mon travail académique est dans [ma thèse](https://theses.hal.science/tel-02524279v1/file/85395_KOVAL_2020_archivage.pdf) et des articles, notamment :

* applications en imagerie ([Frontiers in Neurology](https://www.frontiersin.org/journals/neurology/articles/10.3389/fneur.2018.00235/full), [MICCAI](https://arxiv.org/pdf/1709.08491))
* applications Alzheimer à large échelle ([Scientific Reports](https://www.nature.com/articles/s41598-021-87434-1))
* applications Huntington ([Scientific Reports](https://www.nature.com/articles/s41598-022-18848-8))

### Faire une recherche qui reste

Dès le début de la thèse, j’ai été frappé par le fait que chaque nouvel étudiant repartait de zéro (concepts, code, logiciels). Chacun apprennait beaucoup, mais collectivement, on perdait des années.

Alors, en parallèle de mes publications, j’ai développé [**Leaspy**](https://leaspy.readthedocs.io/en/stable/), un package Python avec une intention simple : donner aux futurs doctorants et ingénieurs une base qu’ils puissent étendre avec de nouveaux modèles, de nouvelles cohortes, de nouvelles maladies, de nouvelles analyses. 

Ce package a été largement réutilisé dans le laboratoire dans le cadre de :

* nouveaux modèles de progression (voir [R Couronné à MICCAI](https://hal.science/hal-03491692/document), [N Fournier à MICCAI](https://hal.science/hal-04295080v1/file/fournier_durrleman_MICCAI2023.pdf), [S Gruffaz à NIPS](https://proceedings.neurips.cc/paper_files/paper/2021/file/c7b90b0fc23725f299b47c5224e6ec0d-Paper.pdf), [PE Poulet à IPMI](https://inria.hal.science/hal-03276811/document) et [Statistics in Medecine](https://inria.hal.science/hal-04095450/document), [J Ortholand dans Journal of Neurology](https://link.springer.com/article/10.1007/s00415-023-11932-7))
* nouvelles maladies et nouveaux jeux de données (voir [C Di Folco dans Movement Disorders](https://movementdisorders.onlinelibrary.wiley.com/doi/abs/10.1002/mds.29662), [F Cacciamani dans Alzheimer's & Dementia](https://alz-journals.onlinelibrary.wiley.com/doi/full/10.1002/alz.053074), [B Sauty dans Frontiers in Neurology](https://www.frontiersin.org/journals/neurology/articles/10.3389/fneur.2023.1161527/full), [E Petit dans Brain](https://academic.oup.com/brain/advance-article-abstract/doi/10.1093/brain/awaf408/8305366), [S Kaisaridi dans Neurology](https://www.neurology.org/doi/10.1212/WNL.0000000000210193))


Nos travaux les plus poussés et validés ont fait l'objet d'une publication dans [**Nature Communications**](https://www.nature.com/articles/s41467-022-35712-5), montrant que nos modèles pouvaient prédire l’évolution d’Alzheimer jusqu’à cinq ans à l’avance.

Cette intention de "consolider" la recherche a aussi été à l'origine d'un [post Medium à propos de Leaspy](https://medium.com/@igoroa/analysis-of-longitudinal-data-made-easy-with-leaspy-f8d529fcb5f8), [de cours](/en/teaching/), de [Digital-Brain.org](https://project.inria.fr/digitalbrain/), du site [Disease Progression Modeling](https://disease-progression-modelling.github.io/pages/main.html#) et de collaborations avec des équipes académiques et pharma pour analyser des données d’essais cliniques (quantifier des effets de traitement, stratifier des populations).

C’est aussi ce qui m’a poussé vers [la création de ma première entreprise.](/en/startup/){:.internal-link}
