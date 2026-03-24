# Projet Machine Learning in Healthcare - GOSSIS-1-eICU

## Description du Projet
Ce projet vise à développer un "Fast-Score" de triage pour les unités de soins intensifs (ICU). L'objectif est de prédire le risque de mortalité hospitalière dès les premières heures de l'admission en utilisant un nombre restreint de variables clés (environ une dizaine). L'enjeu est de comparer la performance de ce modèle simplifié, optimisé pour une prise de décision rapide, par rapport au score international de référence GOSSIS-1.

## Context clinique 
* Question clinique : Peut-on prédire le risque de mortalité hospitalière d'un patient dès son admission afin d'aider au triage et à l'allocation des ressources ? 
* Population : 131 051 patients provenant de 204 hôpitaux.
* Variable cible : hospital_death (binaire : 0 pour survie, 1 pour décès).
* Défi méthodologique : Gestion du déséquilibre de classe (mortalité estimée entre 10 et 15%) et sélection rigoureuse des caractéristiques (feature selection).

## Dataset
* **Nom :** GOSSIS-1-eICU (subset of Global Open Source Severity of Illness Score)
* **Source :** [PhysioNet GOSSIS-1](https://physionet.org/content/gossis-1-eicu/1.0.0/)
* **Accès :** Données protégées (nécessite formation CITI)

## Structure du dépôt
* `notebooks/` : Analyses exploratoires et modèles
* `data/` : Instructions pour les données (fichiers CSV exclus pour confidentialité)
* `dashboard/` : Application Streamlit pour les professionnels de santé
* `report/` : Rapport scientifique final
