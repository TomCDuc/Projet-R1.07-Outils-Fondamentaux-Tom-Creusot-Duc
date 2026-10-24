# 📄 **Rapport : Solveur de Sudoku avec Backtracking**
**Projet R1.07 - Outils Fondamentaux**
**Auteur** : [Ton Prénom Nom]
**Date** : [Date]

---

## **📌 1. Introduction**
### **Contexte**
Le Sudoku est un **jeu de logique** basé sur une grille 9×9, où l'objectif est de remplir les cellules vides avec des chiffres de 1 à 9, sans répétition dans les **lignes**, **colonnes** ou **sous-grilles 3×3**.

Ce projet implémente un **solveur automatique** utilisant des algorithmes de **recherche avec retour arrière (backtracking)**, en exploitant les **notions du module R1.07** :
- **Matrices** : Représentation de la grille.
- **Backtracking** : Algorithme de résolution.
- **Optimisation** : Réduction de l'espace de recherche.
- **Complexité** : Analyse des performances.

---

## **🎯 2. Objectifs**
- **Résoudre** des grilles Sudoku de difficulté variable.
- **Comparer** deux méthodes de backtracking (naïve vs optimisée).
- **Mesurer** les performances en fonction de la difficulté.
- **Générer** des grilles aléatoires pour les tests.

---

## **🔧 3. Méthodes Implémentées**

---
### **3.1 Représentation de la grille**
La grille Sudoku est stockée sous forme de **matrice 9×9** en Python :
```python
grid = [
    [5, 3, 0, 0, 7, 0, 0, 0, 0],
    [6, 0, 0, 1, 9, 5, 0, 0, 0],
    # ...
]
