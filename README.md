# Longstaff-Schwartz vs Deep Optimal Stopping (Deep Learning)

## Objectif du Projet
Reproduction, implémentation et comparaison comparative de deux méthodes numériques de résolution de problèmes d'optimisation stochastique et de pricing d'options / d'actifs :
1. **La méthode de Monte Carlo par régression de Longstaff-Schwartz (LSMC)** : approche classique par moindres carrés pour l'évaluation d'options américaines.
2. **Une approche par Deep Learning / Contrôle stochastique (PyTorch)** : résolution par réseaux de neurones pour l'apprentissage de la règle d'arrêt optimal.

---

## Structure du Dépôt
* `LSCHWZ/` : Contient les scripts d'implémentation, de simulation de trajectoires sous-jacentes et les notebooks de test.
* Traitement des données, simulations Monte-Carlo et scripts de visualisation/tracés.

---

## Méthodologie & Approche
* **Modélisation des trajectoires** : Génération de processus stochastiques sous mesure risque-neutre (mouvement brownien géométrique / modèles de diffusion).
* **Régression (LSMC)** : Utilisation de bases de fonctions de projection (polynômes de Laguerre/Hermite) pour estimer la valeur de continuation aux dates d'exercice.
* **Deep Optimal Stopping (PyTorch)** : Approximation de la fonction d'arrêt par paramétrage réseaux de neurones profonds.

---

## Stack Technique
* **Langage** : Python 3.11
* **Bibliothèques principales** : `NumPy`, `PyTorch`, `Matplotlib`, `SciPy`

---

## Auteur
**Ryan Zahni**  
Étudiant en L3 Informatique & Mathématiques pour la Décision et les Données (IM2D) — Université Paris-Dauphine - PSL  
