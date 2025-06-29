# Analyse de l’évolution de la fréquentation des cinémas – Dashboard Power BI

## Présentation

Ce projet Power BI permet d’analyser l’évolution de la fréquentation des cinémas sur plusieurs années à partir de différentes sources de données.  
Le dashboard offre une vue détaillée des entrées journalières, des séances mensuelles, des recettes, ainsi que la répartition des entrées par origine des films.  
L’objectif est d’accompagner la prise de décision grâce à un suivi visuel dynamique et interactif.

## Fonctionnalités principales

- **Nettoyage et transformation des données** avec Power Query : suppression des lignes et colonnes vides, uniformisation des formats, retraitement des données erronées  
- **Modélisation des données** : création des relations entre les tables, gestion des filtres croisés bidirectionnels, et création d’un rôle de sécurité limitant l’accès aux données des 10 dernières années  
- **Mesures DAX** : calcul d’indicateurs clés tels que les entrées par origine, la fréquentation globale, et la gestion des valeurs manquantes  
- **Visualisations dynamiques** : histogrammes, graphiques en courbes et en anneaux, tableaux avec mises en forme conditionnelle et filtres interactifs  
- **Publication** : rapport publié sur Power BI Pro pour partage et collaboration

## Technologies utilisées

- Power BI Desktop (Power Query, Power Pivot, DAX)  
- Power BI Pro (publishing & sharing)

## Utilisation

1. Ouvrir le fichier Power BI (.pbix) dans Power BI Desktop  
2. Explorer les différentes pages du rapport pour visualiser les tendances et indicateurs  
3. Utiliser les filtres interactifs pour affiner l’analyse selon les années ou catégories  
4. Publier et partager via Power BI Pro si besoin

## Structure des données

- Table `Entrées par jour` : données des entrées cinéma par jour et par jour de la semaine  
- Table `Séances par mois` : nombre de séances mensuelles et recettes associées  
- Table `Entrées par origine` : répartition des entrées selon l’origine des films  
- Table `Fréquentation cinéma global` : données globales de fréquentation avec séances et recettes

---

*Ce projet est un exercice d’analyse de données avec Power BI, incluant la préparation, la modélisation et la visualisation des données.

---


