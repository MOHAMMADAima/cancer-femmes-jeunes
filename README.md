# cancer-femmes-jeunes

`````
cohortes-snds-cancer-femmes-jeunes/
│
├── README.md                      ← Présentation complète du projet
├── requirements.txt               ← Liste des dépendances Python à installer
│
├── data/                          ← Données simulées inspirées du SNDS
│   └── patients_simules.csv       ← Jeu de données synthétique (~2000 patientes)
│
├── notebooks/                     ← Notebooks Jupyter par étape du projet
│   ├── 00_generate_fake_data.ipynb       ← Génération des données simulées
│   ├── 01_definition_cohorte.ipynb       ← Construction de la cohorte d’intérêt
│   ├── 02_analyse_descriptive.ipynb      ← Analyse statistique et visualisation
│   ├── 03_modelisation_predictive.ipynb  ← Modèle prédictif (grossesse post-cancer)
│   └── 04_resultats_interpretation.ipynb ← Synthèse scientifique
│
├── src/                           ← Scripts Python réutilisables
│   ├── preprocessing.py           ← Fonctions de nettoyage et de préparation
│   ├── cohortes.py                ← Création des cohortes selon critères cliniques
│   ├── indicateurs.py             ← Calculs d’indicateurs (toxicité, délais, grossesse)
│   └── modeles.py                 ← Modélisation et évaluation (sklearn)
│
├── figures/                       ← Graphiques générés (PNG, SVG…)
│   └── (ex : histogrammes, heatmaps, courbes ROC)
│
├── outputs/                       ← Données de sortie (fichiers filtrés, métriques, modèles)
│   └── cohortes_filtered.csv
│
└── docs/                          ← Documentation scientifique complémentaire
    ├── bibliographie.md           ← Références scientifiques utilisées
    └── indicateurs_definitions.md ← Glossaire des variables et indicateurs cliniques
`````
