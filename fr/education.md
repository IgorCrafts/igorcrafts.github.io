---
layout: default
title: Parcours académique
permalink: /fr/education/
lang: fr
translation_key: education
alt_lang: en
alt_url: /en/education/
subtitle: Mathématiques appliquées, IA et neurosciences
---

# Mon parcours académique

<div class="landing-subintro" markdown="1">
De l'école d'ingénieur à la thèse en Machine Learning, appliquée aux maladies neurodégénératives
</div>

### Un rapport complexe aux mathématiques et à la recherche

À 20 ans, en entrant à l'**École des Ponts**, je m'étais juré d'arrêter les maths. Le manque d'applications concrètes me pesait. Et j'ai envisagé de bifurquer vers les écoles de commerce. Mais une diplômée m'en a découragé : *« Apprends d’abord des compétences techniques. Tu auras le temps pour la partie business plus tard. »*

J'ai donc donné une seconde chance aux mathématiques. J'ai étudié l'économie à l'**Université Paris Dauphine**, puis j'ai effectué un stage en Machine Learning à [Argonne](https://www.anl.gov/), un laboratoire de recherche américain. C'est là que le déclic s'est produit, me conduisant à faire un Master de Machine Learning de l'**École Polytechnique**.

À la fin du master, je souhaitais mettre à profit mes compétences en rejoignant une entreprise. Mais, en pleine mode du “Big Data”, le manque de compétences qui y régnaient m’en a découragé.

Pour cette raison, je me suis tourné vers la recherche et j'ai commencé un doctorat avec [Stanley Durrleman](https://who.rocq.inria.fr/Stanley.Durrleman/) et [Stéphanie Allassonnière](https://sites.google.com/site/stephanieallassonniere/).

### Modéliser la progression des maladies neurodégénératives

Mes travaux portaient sur la modélisation de l'évolution des maladies neurodégénératives comme Alzheimer, Parkinson ou Huntington. L'objectif était triple :

- Reconstruire la progression « moyenne » sur de longs horizons temporels,
- Caractériser les trajectoires individuelles par rapport à cette moyenne,
- Prédire l'évolution individuelle jusqu'à ~5 ans à l'avance.

Tout cela à partir de données multimodales : évaluations cognitives, imagerie (IRM, TEP) et biomarqueurs sanguins. Les difficultés étaient multiples. Les données biomédicales réelles sont imprévisibles. La progression n'est pas linéaire, son rythme change. Les suivis sont irréguliers, manquants ou incomplets. Chaque patient ne fournit qu'une petite pièce du puzzle et la variabilité inter-individuelle est importante.

Nous avons donc construit un modèle unique capable de s'adapter aux différentes maladies et modalités, reposant sur (1) la géométrie riemannienne, (2) la modélisation probabiliste de l'hétérogénéité, et (3) l'inférence sous incertitude et données manquantes (chaînes de Markov / Monte Carlo, Expectation–Maximization).

L'essentiel de mes travaux académiques se trouve dans [ma thèse](https://theses.hal.science/tel-02524279v1/file/85395_KOVAL_2020_archivage.pdf) et mes publications, notamment :

- Applications en imagerie ([Frontiers in Neurology](https://www.frontiersin.org/journals/neurology/articles/10.3389/fneur.2018.00235/full), [MICCAI](https://arxiv.org/pdf/1709.08491))  
- Applications larges sur Alzheimer ([Scientific Reports](https://www.nature.com/articles/s41598-021-87434-1))  
- Applications sur Huntington ([Scientific Reports](https://www.nature.com/articles/s41598-022-18848-8))  

À son apogée, cette approche a permis un travail de prédiction à grande échelle, publié dans [**Nature Communications**](https://www.nature.com/articles/s41467-022-35712-5), démontrant que nos modèles pouvaient prévoir la progression d'Alzheimer jusqu'à cinq ans à l'avance. 

### Créer une recherche qui ne disparaît pas après la publication

Dès le début de la thèse, j’ai été frappé par le fait que chaque nouvel étudiant repartait quasiment de zéro.

Parallèlement à mes publications, j'ai donc décidé de créer [**Leaspy**](https://leaspy.readthedocs.io/en/stable/), une librairie Python avec une intention simple : donner aux futurs doctorants et ingénieurs une base qu'ils pourraient étendre avec de nouveaux modèles, de nouvelles cohortes, de nouvelles maladies et de nouvelles analyses. 

C'est devenu le socle de nombreux travaux ultérieurs, incluant :

- de nouveaux modèles de progression (voir [R Couronné dans MICCAI](https://hal.science/hal-03491692/document), [N Fournier dans MICCAI](https://hal.science/hal-04295080v1/file/fournier_durrleman_MICCAI2023.pdf), [S Gruffaz dans NIPS](https://proceedings.neurips.cc/paper_files/paper/2021/file/c7b90b0fc23725f299b47c5224e6ec0d-Paper.pdf), [PE Poulet dans IPMI](https://inria.hal.science/hal-03276811/document) et [Statistics in Medicine](https://inria.hal.science/hal-04095450/document), [J Ortholand dans Journal of Neurology](https://link.springer.com/article/10.1007/s00415-023-11932-7))  
- de nouvelles maladies et jeux de données (voir [C Di Folco dans Movement Disorders](https://movementdisorders.onlinelibrary.wiley.com/doi/abs/10.1002/mds.29662), [F Cacciamani dans Alzheimer's & Dementia](https://alz-journals.onlinelibrary.wiley.com/doi/full/10.1002/alz.053074), [B Sauty dans Frontiers in Neurology](https://www.frontiersin.org/journals/neurology/articles/10.3389/fneur.2023.1161527/full), [E Petit dans Brain](https://academic.oup.com/brain/advance-article-abstract/doi/10.1093/brain/awaf408/8305366), [S Kaisaridi dans Neurology](https://www.neurology.org/doi/10.1212/WNL.0000000000210193))  

Ce même instinct de « durabilité » s'est manifesté ailleurs : [article Medium sur Leaspy](https://medium.com/@igoroa/analysis-of-longitudinal-data-made-easy-with-leaspy-f8d529fcb5f8), [enseignement](/fr/teaching/), [Digital-Brain.org](https://project.inria.fr/digitalbrain/), le site [Disease Progression Modeling](https://disease-progression-modelling.github.io/pages/main.html#), et des collaborations avec des équipes académiques et pharmaceutiques pour analyser des données d'essais cliniques (quantification des effets des médicaments, stratification des populations).

C'est aussi ce qui m'a poussé à [créer ma première entreprise.](/fr/startup/){:.internal-link}