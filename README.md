# 🎮 S104 : Exploitation de Base de Données S104

## 📌 **Description**

Projet réalisé dans le cadre du BUT Informatique (SAE S104) portant sur l'exploitation d'une base de données inspirée du site [IGDB](https://www.igdb.com/).  
Ce projet se divise en deux parties :

1. **Gestionnaire de base de données (individuel)**  
2. **Analyse statistique et tableau de bord (binôme/trinôme)**

---

## 🗂️ **Contenu du repository**

🔹 `tableau_de_bord.ipynb`  
Carnet Jupyter présentant la plateforme attribuée avec analyses graphiques et statistiques.

🔹 `analyse_statistique.ipynb`  
Carnet Jupyter d'analyse statistique approfondie sur une compagnie choisie (ex. Nintendo) avec requêtes SQL et visualisations.

🔹 `analyse_statistique.pdf`  
Version PDF du rapport d'analyse statistique, conforme aux consignes de rendu.

🔹 `README.md`  
Ce fichier de présentation du projet.

---

## ⚙️ **Technologies utilisées**

- **SQL** : création de vues, procédures, fonctions, triggers, extensions de schéma
- **PL/SQL** : gestion avancée côté serveur Oracle
- **Python (Jupyter Notebook)** : requêtes, pandas, matplotlib/seaborn pour l'analyse et la visualisation des données

---

## 🎯 **Objectifs pédagogiques**

✔️ Maîtriser la **création et la gestion d’une base de données**  
✔️ Développer des **vues et procédures stockées** pour faciliter l’utilisation des données  
✔️ Créer un **tableau de bord interactif** sous Jupyter Notebook  
✔️ Réaliser un **rapport analytique complet** sur une plateforme et une compagnie du marché du jeu vidéo

---

## 🔬 **Travaux réalisés**

### **1. Partie Gestionnaire BDD**
- Création et attribution des **droits utilisateurs**
- Conception de **vues fonctionnelles** (ex : fiche jeu, sorties récentes)
- Développement de **fonctions stockées** en JSON (ex : fiche détaillée, top 100 jeux plateforme)
- Rédaction de **procédures stockées** (ajout de dates de sortie, modes multijoueur)
- Mise en place de **déclencheurs** (triggers) pour journaliser les modifications
- **Extension du schéma relationnel** avec ajout de la table `COMPAGNIE_SORTIE` pour lier jeux, sorties et compagnies impliquées

### **2. Partie Analyse et Tableau de Bord**
- Analyse statistique détaillée d’une plateforme (ex : Sega Saturn) et d’une compagnie (ex : Nintendo)
- Génération de **graphiques** (histogrammes, camemberts, bar charts) illustrant :
  - Répartition des jeux par genre
  - Moyenne des notes utilisateurs et critiques
  - Évolution temporelle des sorties
- Rédaction d’un **rapport analytique complet** au format Jupyter + PDF
  -objectif se mettre dans la peau d' un analyste de donnée.
