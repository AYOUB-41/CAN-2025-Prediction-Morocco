# 🏆 AFCON 2025 Prediction: Morocco vs Cameroon

Ce projet utilise le **Machine Learning** pour prédire l'issue du match de quart de finale de la CAN 2025 entre le Maroc et le Cameroun, en se basant sur les données historiques de la CAF depuis 2015.

## 📊 Résultats Clés
- **Modèle :** RandomForestClassifier
- **Précision (Accuracy) :** 53.45% (Modèle robuste et réaliste)
- **Prédiction :** 88% de probabilité de victoire pour le Maroc (Avantage domicile et forme offensive).

## 🛠️ Étapes du Projet
1. **Nettoyage :** Filtrage des données pour la zone Afrique (CAF) après 2015.
2. **Feature Engineering :** Calcul des moyennes mobiles de buts (Rolling Averages) pour mesurer la force des équipes.
3. **Entraînement :** Utilisation de 2608 matchs pour apprendre au modèle les schémas de victoire.
4. **Visualisation :** Création de graphiques d'importance des variables et de probabilités.

## 🚀 Comment l'utiliser
1. Clonez le dépôt.
2. Assurez-vous d'avoir le fichier `results.csv` dans le même dossier.
3. Lancez le Notebook `Morocco vs cameron v-final.ipynb`.
