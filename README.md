# Projet 1 : Analyse Statistique des Buts dans le Football International

## Description

Ce projet vise à analyser et comparer le nombre total de buts marqués lors des matchs de football international féminin et masculin, en se concentrant sur les matchs de la Coupe du Monde de la FIFA depuis le 1er janvier 2002. L'objectif est de tester l'hypothèse selon laquelle les matchs de football féminin produisent plus de buts que ceux de football masculin.

## Contexte

En tant que journaliste sportif, j'ai remarqué que le niveau de compétition et le style de jeu dans le football féminin semblent avoir évolué ces dernières années. Ce projet vise à fournir une analyse statistique solide pour valider ou invalider cette intuition.

## Données

Les données utilisées dans ce projet proviennent des résultats des matchs de football féminin et masculin, stockées dans deux fichiers CSV :
- `women_results.csv`
- `men_results.csv`

Ces fichiers contiennent des informations sur chaque match, y compris les scores, les dates et les tournois.

## Méthodologie

1. **Exploration des Données (EDA)**  
   Analyse préliminaire des données pour comprendre les tendances, les valeurs manquantes et les statistiques descriptives.

2. **Filtrage des Données**  
   Limitation des données aux matchs de la Coupe du Monde de la FIFA depuis le 1er janvier 2002.

3. **Calcul du Score Total**  
   Somme des buts marqués à domicile et à l'extérieur pour chaque match.

4. **Tests de Normalité**  
   Utilisation du test de Shapiro-Wilk pour déterminer si les distributions des scores sont normales.

5. **Exclusion des Valeurs Aberrantes**  
   Application d'une méthode d'interquartile (IQR) pour filtrer les valeurs aberrantes.

6. **Test d'Hypothèse**  
   Réalisation d'un test de Mann-Whitney pour comparer les scores totaux des matchs féminins et masculins.

## Résultats

Les résultats de l'analyse incluent :
- Statistiques descriptives pour les scores totaux  
- Graphiques de distribution et boxplots pour visualiser les différences entre les deux ensembles de données  
- P-valeurs issues du test de Mann-Whitney pour évaluer la signification statistique des résultats
