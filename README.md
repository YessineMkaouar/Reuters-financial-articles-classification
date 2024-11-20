# Reuters Financial Articles Classification

## Description  

Ce projet vise à classer automatiquement des articles financiers du dataset **Reuters-21578** dans l'une des cinq catégories sélectionnées :  
1. **Money/Foreign Exchange (MONEY-FX)**  
2. **Shipping (SHIP)**  
3. **Interest Rates (INTEREST)**  
4. **Mergers/Acquisitions (ACQ)**  
5. **Earnings and Earnings Forecasts (EARN)**  

L’objectif principal est de fournir une analyse descriptive et prédictive basée sur ce dataset.  

## Structure du Projet  

### Étapes de l'Analyse  

1. **Analyse descriptive**  
   - Identifier les principales caractéristiques associées à chaque catégorie.  

2. **Analyse prédictive**  
   - Implémenter et comparer différents algorithmes de classification pour déterminer le meilleur modèle.  

### Données  

- Le dataset contient **21 578 articles** répartis dans **22 fichiers au format SGM**.  
- D'autres fichiers texte complémentaires sont disponibles pour mieux comprendre l'organisation des données.  
- Dataset disponible ici : [Reuters-21578 Dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/reuters21578-mld/reuters21578.tar.gz)  

## Préparation des Données  

- Utiliser des bibliothèques Python telles que `BeautifulSoup` pour le nettoyage des fichiers HTML, si nécessaire.  
- Documenter toutes les étapes de préparation des données dans le code.  

## Environnement et Langage  

- **Langage préféré** : Python  
- Bibliothèques recommandées :  
  - Pour le nettoyage des données : `BeautifulSoup`  
  - Pour l’analyse et la modélisation : `pandas`, `numpy`, `scikit-learn`, etc.  