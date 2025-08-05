# 🎮 Prédiction du succès de jeux vidéo (projet Data & IA)

## 📌 Objectif
Ce projet vise à prédire le succès commercial (ventes mondiales) d’un jeu vidéo à partir de variables telles que son **genre**, **plateforme**, **année de sortie**, **scores critiques** et **scores utilisateurs**.

---

## 🧪 Données utilisées
Le dataset contient 7 variables principales :
- `Name` : Nom du jeu
- `Platform` : Plateforme de sortie (PS4, Xbox, etc.)
- `Genre` : Type de jeu (Action, Sport, etc.)
- `Critic_Score` : Score moyen donné par les professionnels
- `User_Score` : Score moyen donné par les utilisateurs
- `Year` : Année de sortie
- `Global_Sales_M` : Ventes mondiales en millions (variable à prédire)

---

## 🔍 Étapes du projet
1. **Nettoyage et encodage** des données (OneHotEncoding sur les variables catégorielles)
2. **Séparation des données** en jeu d’entraînement/test
3. **Entraînement de plusieurs modèles** de régression :
   - Régression Linéaire
   - Arbre de décision
   - Forêt aléatoire
   - k-Nearest Neighbors (k-NN)
   - Support Vector Regression (SVR)
4. **Évaluation** des performances avec la MAE (Mean Absolute Error)
5. **Sauvegarde du meilleur modèle** (ici : SVR) avec `joblib`
6. **Chargement et test du modèle** pour faire des prédictions futures

---

## 📈 Résultats
- Meilleur modèle : **SVR**
- MAE obtenue : **environ 6.5 millions d’unités**, meilleure précision parmi tous les modèles testés

---

## 💾 Fichiers du projet
- `analyse_jeux_video_data.ipynb` : Notebook principal avec tout le code, les tests et les commentaires
- `modele_svr.pkl` : Modèle entraîné sauvegardé, prêt à l’emploi

---

## 🚀 Prochaine étape possible
- Utiliser plus de données pour améliorer la précision
- Ajouter d’autres variables (éditeur, coût de développement, etc.)
- Créer une interface web pour faire tester le modèle à d'autres utilisateurs

---

## 👤 Réalisé par
*Timothé Belcour* – Étudiant en BUT Informatique  
Projet personnel réalisé en autonomie assistée avec ChatGPT (mode Étudier)
