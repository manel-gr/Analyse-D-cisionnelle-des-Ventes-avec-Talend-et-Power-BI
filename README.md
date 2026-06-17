
# Analyse Décisionnelle des Ventes avec Talend et Power BI

## Description du projet

Ce projet consiste à concevoir un système d'information décisionnel complet à partir de la base de données Northwind.

L'objectif est de transformer les données opérationnelles en informations exploitables afin d'aider à la prise de décision grâce à un processus ETL développé avec Talend Open Studio et un tableau de bord interactif réalisé avec Power BI.

---

## Objectifs

- Analyser la base de données Northwind
- Concevoir un DataMart en schéma étoile
- Développer un processus ETL avec Talend
- Nettoyer et transformer les données
- Alimenter un Data Warehouse
- Créer des indicateurs KPI
- Concevoir un dashboard interactif avec Power BI

---

## Technologies utilisées

- Talend Open Studio
- MySQL
- Power BI
- SQL
- Business Intelligence (BI)

---

## Architecture du projet

Northwind Database

↓

Talend ETL 

↓

Data Warehouse (MySQL)

↓

DataMart (Schéma en étoile)

↓

Power BI Dashboard

---

## Modèle décisionnel

Le DataMart est basé sur un schéma en étoile composé de :

### Table de faits

- fact_ventes

### Dimensions

- dim_client
- dim_produit
- dim_date
- dim_employe
- dim_categorie
- dim_fournisseur

---

## Processus ETL

Le processus ETL réalisé avec Talend comprend :

### Extraction

- Customers
- Products
- Orders
- Order Details
- Employees
- Categories
- Suppliers

### Transformation

- Suppression des doublons
- Gestion des valeurs nulles
- Nettoyage des données (TRIM)
- Conversion des types
- Création de mesures calculées

### Chargement

- Chargement des dimensions
- Chargement de la table de faits

---

## Tableau de bord Power BI

Le dashboard permet l'analyse des :

- Ventes
- Clients
- Produits
- Fournisseurs
- Catégories
- Zones géographiques

### KPI principaux

- Chiffre d'affaires total
- Nombre de commandes
- Quantité vendue
- Panier moyen

---

## Résultats

### Performance globale

- Chiffre d'affaires : 1,27 M
- Nombre de commandes : 2 155
- Quantité vendue : 51 K
- Panier moyen : 587,41

### Analyses réalisées

- Évolution temporelle des ventes
- Top clients
- Top produits
- Répartition géographique
- Répartition par catégorie
- Analyse des fournisseurs

---

## Compétences développées

- Business Intelligence
- ETL avec Talend
- Data Warehousing
- Modélisation décisionnelle
- Power BI
- Création de KPI
- Data Visualization
- Analyse des données

---

## Réalisé par

**Manel Garmachi**

**manel.garmmachi@esen.tn**

**+216 20 407 649**

**www.linkedin.com/in/manel-garmachi**

Junior Data Analyst

2025 - 2026
