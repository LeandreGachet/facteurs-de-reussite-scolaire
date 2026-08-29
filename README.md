# Ce qui explique la note finale : famille, vie sociale, habitudes de travail

*Understanding final grades using family, social and study factors.*

Un jeu de données scolaire portugais très utilisé — et presque toujours pour la même chose : la consommation d'alcool des élèves. Le parti pris ici est d'aller chercher ailleurs, du côté du niveau d'éducation des parents, de la structure familiale et du temps de travail.

Projet de Master mené et présenté **en anglais**.

## Démarche

**Données** — *Student Alcohol Consumption* (Kaggle), volet mathématiques : **395 élèves, 33 variables** décrivant l'entourage familial, la vie sociale, les habitudes d'étude et les notes.

**Préparation, avec une décision assumée** — aucune valeur manquante, mais les élèves dont la note finale vaut 0 sont retirés. Ce zéro n'est pas une mauvaise note : c'est une absence à l'épreuve. Le garder tirerait toutes les moyennes vers le bas en mesurant la présence plutôt que le niveau.

Recodage de la variable de temps d'étude en modalités interprétables, et ajout d'un index.

**Statistiques descriptives sous RStudio** — moyennes, écarts-types, distributions par facteur.

**Restitution prévue sous Power BI**, organisée en trois thèmes : situation familiale, résultats scolaires, habitudes de travail. *Le fichier de restitution ne figure pas dans l'archive ; le dépôt contient le cadrage, les données et le support oral.*

## Ce que ça produit

Une lecture des déterminants sociaux de la réussite scolaire à partir d'un jeu de données ouvert, sur un angle que la plupart des travaux publiés sur ces mêmes données laissent de côté. L'exercice porte autant sur le choix de la question que sur son traitement — et sur sa présentation en anglais.

## Contenu

| | |
|---|---|
| `donnees/student_mat.xlsx` | les données |
| `documents/project_summary.docx` | le cadrage du projet |
| `documents/oral.docx` | le support de présentation |

## Source

[Student Alcohol Consumption](https://www.kaggle.com/datasets/uciml/student-alcohol-consumption), Kaggle / UCI Machine Learning Repository.

---

**Léandre Gachet** — Master Mathématiques appliquées, statistique, Université de Rennes
