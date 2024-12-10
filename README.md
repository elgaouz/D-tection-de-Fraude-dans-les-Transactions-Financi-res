# Détection de Fraude par Approche Multimodèle

Ce projet utilise plusieurs modèles de machine learning pour détecter les fraudes dans des transactions. L'objectif est d'identifier les transactions suspectes avec une grande précision, tout en minimisant les faux négatifs.

## Fonctionnalités
- Prétraitement des données pour gérer les classes déséquilibrées.
- Comparaison de plusieurs modèles : 
  - Régression Logistique
  - KNN
  - Random Forest
  - XGBoost
  - LightGBM
  - CatBoost
- Évaluation des performances avec des métriques comme la précision, le rappel, le F1-score et le ROC-AUC.
- Visualisation des résultats, notamment les courbes PR (Precision-Recall) et ROC.

## Résultats
- Le modèle **XGBoost** a montré les meilleures performances globales avec un bon équilibre entre rappel et précision.
- Des techniques d'oversampling (SMOTE) ont été utilisées pour améliorer la détection des classes minoritaires.

