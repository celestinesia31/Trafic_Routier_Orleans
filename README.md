# Trafic_Routier_Orleans
Analyse automatisée du trafic routier Département du Loiret

## Contexte
Projet réalisé dans le cadre d'une candidature au poste de **Stagiaire Data Analyst** à Orléans Métropole (PCRT).

L'objectif est de démontrer la faisabilité d'une automatisation du traitement des données de trafic routier
générées par les stations de comptage du réseau départemental.

## Objectif
Créer un pipeline Python capable de transformer les données  brutes de 617 stations de comptage en un rapport
d'aide à la décision, avec détection automatique des anomalies.

## Structure du projet
trafic-routier-orleans/
│
├── data/
│   └── TRAFIC_POINT_2023.xlsx    # Données open data Loiret
│
├── notebooks/
│   └── 01_analyse_exploratoire.ipynb
│
├── scripts/
│   └── analyse_trafic.py
│
├── outputs/
│   └── (graphiques générés)
│
└── README.md

## Stack technique
- **Python** : pandas, numpy, matplotlib, seaborn, folium
- **Jupyter Notebook**
- **Source données** : Open Data Orléans Métropole / Département du Loiret

## Analyses réalisées
1. Nettoyage et fiabilisation des données
2. Identification des axes les plus chargés
3. Analyse par catégorie de réseau
4. Détection automatique des anomalies (méthode ±2σ)
5. Identification des axes logistiques (% Poids Lourds)
6. Carte interactive des 617 points de comptage

## Résultats clés
- **617** points de comptage analysés
- **53 979** véh/jour sur l'axe le plus chargé
- **17** anomalies détectées automatiquement
- **6.5%** de part Poids Lourds en moyenne

## Réalisé par:
**Célestine LENO**  
Master 2 Exploration Informatique des Doonées et Décisionnel et Data Science / Université Sorbonne Paris Nord & USMBA de Fès 
celestinesialeno@gmail.com
