# Analyse de l’activité client – Arkose

## Objectif

Ce projet vise à analyser l’activité des clients d’Arkose afin de :

* Comprendre les comportements de fréquentation
* Identifier les clients actifs, à risque et inactifs
* Analyser les performances des offres et des établissements
* Proposer des axes d’amélioration pour la fidélisation

---

##  Méthodologie

### 🔹 1. Analyse des données (SQL / Python)

* Analyse des volumes de passages par période
* Étude des préférences (type de forfait, établissement)
* Nettoyage et préparation des données

### 🔹 2. Segmentation client (Python)

* Calcul de la récence, fréquence et volume
* Classification des clients en :

  * Très actif
  * Actif
  * À risque
  * Inactif

### 🔹 3. Data Modeling & DAX (Power BI)

* Création d’un modèle de données relationnel
* Développement de mesures DAX :

  * Nombre de clients
  * Volume total
  * Volume moyen
  * Taux d’inactivité
  * Clients actifs / à risque

### 🔹 4. Visualisation (Power BI)

* Création d’un dashboard interactif
* Analyse par segment, période, offre et établissement

---

##  Dashboard

![Dashboard](image_dashboard.png)

---

## 🔍 Insights clés

* Les clients très actifs génèrent le volume le plus important
* Une partie des clients est à risque de désengagement
* Les abonnements sont les offres les plus utilisées
* Certains établissements sont plus performants que d’autres

---

##  Recommandations

* Mettre en place des campagnes de réactivation pour les clients inactifs
* Cibler les clients à risque avec des offres personnalisées
* Optimiser les offres les moins performantes
* S’appuyer sur les établissements les plus performants

---

##  Outils utilisés

* Python (Pandas)
* SQL
* Power BI (DAX)
* Excel / CSV

---
