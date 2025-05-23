# 🧠 Analyse Data-Driven : La pérennité de Booba dans le rap français

## 📌 Objectif

Ce projet explore les raisons de la longévité de Booba dans le paysage du rap français à travers une approche analytique basée sur les données de ses morceaux, ses collaborations, et l’évolution de ses thématiques artistiques.

---

## RAPPORT 

Rapport présent dans `output/` contenant le storytelling à partir des données.

## 📂 Contenu

```
booba_perennite_project/
│
├── DATA/
│   └── RAW/
│       └── DATA_booba_song/            # Données brutes (lyrics, métadonnées, etc.)
│
├── notebook/
│   ├── notebook_create_df.ipynb        # Notebook de création du DataFrame principal
│   └── analyse_carriere_booba.ipynb    # Notebook d’analyse complète (visuel + interprétation)
│
├── output/
│   ├── RAPPORT.ipynb                   # Rapport final complet enrichi
│   ├── boxplot_durée_année.png
│   ├── boxplot_feat_popularité.png
│   ├── coherence.png
│   ├── diversité_lexical.png
│   ├── feat_populaire.png
│   ├── heatmap_theme1.png
│   ├── pie_collab.png
│   ├── plot_pattern.png
│   ├── popularité_mean.png
│   ├── reseau_collab.png
│   └── theme_fil_du_temps.png
│
├── README.md                           # Description du projet
└── requirements.txt                    # (optionnel) Librairies Python utilisées
```

## 🧰 Technologies

- Python (Pandas, Seaborn, Matplotlib, NetworkX, Spacy, Scikit-learn, Numpy)
- Jupyter Notebook
- APIs : Spotify, Genius
- NLP : Tokenization, vectorization, topic modeling

---

## 📈 Exemples de visualisations à retrouver dans le notebook

- Heatmap des thématiques par période
- Boxplot de la durée des morceaux
- Graphe de réseau des collaborations
- Popularité moyenne avec/sans featuring

---


