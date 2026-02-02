# 🎮 Analyse du Marché Mondial des Jeux Vidéo — Power BI

## 📝 Présentation du Projet
Ce projet consiste en la création d'un tableau de bord interactif complet sur Power BI. L'objectif est d'analyser les performances commerciales et critiques d'un panel de titres majeurs afin d'identifier les segments de marché les plus porteurs (genres, plateformes) et la corrélation entre succès critique et rentabilité.

## 🛠️ Stack Technique
* **Outil BI :** Power BI Desktop
* **Source de données :** Dataset CSV (Nettoyé et formaté)
* **Méthodologie :** Processus ETL (Extract, Transform, Load) & Data Visualization

## 🚀 Étapes de Réalisation

### 1. Préparation des Données (ETL)
* **Extraction :** Importation du dataset et configuration de l'encodage.
* **Transformation (Power Query) :** * Nettoyage des colonnes et gestion des types de données.
    * Conversion des métriques de ventes et de notations en formats numériques exploitables.
    * Normalisation des catégories de genres et de plateformes.

### 2. Modélisation et Mesures
* Création de mesures pour piloter l'analyse :
    * **Ventes Totales :** Calcul de la somme globale des revenus.
    * **Note Moyenne :** Agrégation de la satisfaction critique par titre et par genre.
    * **Volume de Titres :** Décompte distinct du catalogue analysé.

### 3. Conception du Dashboard (UX/UI)
Le rapport a été conçu pour offrir une navigation fluide et intuitive :
* **Page d'Accueil :** Interface épurée avec contexte du projet et bouton de navigation interactif (Call to Action).
* **Analyse de Performance :**
    * **KPI Cards :** Affichage instantané des indicateurs clés.
    * **Top 5 Sales :** Focus dynamique sur les leaders du marché via des filtres de classement.
    * **Comparaison par Genre :** Histogramme des ventes pour identifier les tendances de consommation.
    * **Répartition Plateforme :** Treemap pour visualiser l'occupation du marché (PC vs Consoles).

## 💡 Fonctionnalités Clés
* **Navigation Interactive :** Système de boutons permettant de passer de l'accueil aux analyses.
* **Filtres Dynamiques (Slicers) :** Possibilité de segmenter l'ensemble du rapport par genre ou par date en un clic.
* **Design Professionnel :** Utilisation d'un thème sombre moderne pour une lisibilité accrue.

## 📂 Organisation du Repository
* `/data` : Contient le dataset source utilisé.
* `/report` : Contient le fichier source `.pbix`.
* `README.md` : Documentation du projet.

* ## Images du Projet
  
  Page d'accueil :
  
<img width="1747" height="981" alt="accueil" src="https://github.com/user-attachments/assets/94daba6d-69b0-404f-8b2b-6508fb4b8827" />


  Dashboard Ventes:
    
<img width="1955" height="1093" alt="dashboard ventes" src="https://github.com/user-attachments/assets/d04e1e29-05eb-4394-87a8-7f9237311b2a" />

