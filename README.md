# Binary Logistic Regression from Scratch

Ce projet implémente un **modèle de régression logistique** développé **from scratch** (sans utiliser de bibliothèque de machine learning) pour effectuer une **classification binaire** sur un dataset concernant la détection de la présence d’un virus.

## 🧪 Objectif

- Développer un modèle de régression logistique sans utiliser `scikit-learn`.
- Appliquer ce modèle pour détecter la **présence ou non d’un virus** chez des souris.
- Évaluer la performance du modèle sur des jeux de données d'entraînement et de test.

## 🗃️ Dataset

Le fichier `mouse_viral_study.csv` contient les données biologiques de souris avec une étiquette indiquant la **présence (1)** ou **absence (0)** d’un virus.

Variables d’entrée (features) :
- Exemple : `Gene_1`, `Gene_2`, ..., etc. *(dépend du dataset exact)*

Variable cible :
- `Virus_Presence` (0 ou 1)

## 🧠 Méthodologie

1. Prétraitement des données
2. Implémentation de la régression logistique :
   - Fonction sigmoïde
   - Fonction coût (log-loss)
   - Descente de gradient
3. Entraînement du modèle
4. Prédiction et évaluation :
   - Accuracy
   - Matrice de confusion
   - Courbe de décision

## 📈 Résultats

Les performances du modèle sont analysées en termes de précision (accuracy), pertes (loss), et visualisation de la séparation binaire.

## 📁 Fichiers

- `binary-logistic-regression-scratch.ipynb` : Notebook principal contenant le code complet.
- `mouse_viral_study.csv` : Dataset utilisé pour l'entraînement et les tests.

## 🛠️ Technologies

- Python
- NumPy, Pandas
- Matplotlib
- Jupyter Notebook

## 👤 Auteur

**Labrini Ouiam**  

---

> Pour toute suggestion ou contribution, merci de créer une issue ou un pull request sur le dépôt.
