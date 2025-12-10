# Projet 2 — Analyse SQL : Performance des ventes e-commerce

## 🎯 Objectif
- Analyser un dataset e-commerce fictif  
- Calculer le chiffre d’affaires global et par ville  
- Identifier les clients les plus importants  

## 📊 Dataset
- Fichier : `dataset_ventes.csv`  
- Colonnes : order_id, client_id, date, produit, quantite, prix_unitaire, ville  

## 🧩 Requêtes SQL exemples
- Chiffre d’affaires total : `SELECT SUM(quantite * prix_unitaire) FROM ventes;`  
- Montant total par ville  
- Top clients par CA

## 📌 Résultat attendu
Rapport SQL clair, insights exploitables pour le business
