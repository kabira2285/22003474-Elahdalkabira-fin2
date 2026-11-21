# 22003474-Elahdalkabira-fin2
# Analyse des données financières – Projet de clustering

## 1. Présentation du projet

Ce projet consiste à analyser des données financières en utilisant des techniques de Machine Learning non supervisé (clustering).

L'objectif est d'identifier des groupes d'observations similaires et de comparer plusieurs algorithmes de classification non supervisée.

## 2. Algorithmes utilisés

Quatre algorithmes ont été étudiés :

- **K-Means** : partitionnement des données en 3 clusters.
- **Classification hiérarchique ascendante** : regroupement des observations avec la méthode de Ward.
- **DBSCAN** : identification des zones denses et détection des observations considérées comme du bruit.
- **Gaussian Mixture Models (GMM)** : classification probabiliste des observations.

## 3. Résultats obtenus

| Algorithme | Résultat |
|---|---|
| K-Means | Silhouette : 0,39 |
| Classification hiérarchique | Silhouette : 0,4782 |
| DBSCAN | 1 cluster et 108 points de bruit |
| GMM | Probabilité maximale moyenne : 93,61 % |

La classification hiérarchique a obtenu le meilleur score de silhouette parmi les méthodes évaluées avec cet indicateur.

## 4. Outils et bibliothèques

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

## 5. Structure du projet

```text
22003474-Elahdalkabira-fin2/
│
├── notebook/
│   └── finance_data_analysis_F9_complete.ipynb
│
└── README.md
```

## 6. Exécution du notebook

Le notebook peut être ouvert avec Google Colab.

1. Télécharger le fichier `.ipynb`.
2. Ouvrir Google Colab.
3. Importer le notebook.
4. Exécuter toutes les cellules.

## 7. Conclusion

Ce projet permet de comparer différentes méthodes de clustering appliquées aux données financières. Les résultats montrent que la classification hiérarchique offre la meilleure séparation selon le score de silhouette obtenu, tandis que GMM fournit des probabilités d'appartenance aux groupes.

L'étude met en évidence les avantages et les limites de chaque algorithme.
