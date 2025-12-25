# 📍 AI-Route-Optimization : Recherche du Chemin Optimal

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Algorithm](https://img.shields.io/badge/Logic-Dijkstra-green.svg)

## 📋 Présentation du Projet
**AI-Route-Optimization** est un moteur de calcul d'itinéraires basé sur l'intelligence artificielle. Ce projet simule un réseau routier urbain (inspiré des axes majeurs de Kinshasa) pour déterminer le trajet le plus court entre deux points géographiques en minimisant le coût (distance/temps).

## 🧠 Focus Algorithmique : Dijkstra
Le cœur de ce projet repose sur l'implémentation de **l'algorithme de Dijkstra**. 

Pourquoi ce choix ?
- **Calcul de poids** : Contrairement à une recherche simple (BFS), Dijkstra permet de prendre en compte la distance réelle entre les carrefours.
- **Optimisation** : Il garantit de trouver le chemin le plus court dans un graphe avec des poids positifs.
- **Complexité** : L'implémentation a été pensée pour être efficace, utilisant des structures de données adaptées pour une exécution rapide.

## 🚀 Fonctionnalités
- **Modélisation Topologique** : Transformation des routes (Rond-point Victoire, Huilerie, Gare Centrale, etc.) en un graphe pondéré.
- **Moteur de Recherche** : Utilisation de Dijkstra pour calculer l'itinéraire optimal.
- **Comparaison Interactive** : Génération d'un fichier HTML permettant de visualiser et comparer les différents chemins explorés.

## 📂 Structure du Projet
- `trajet_graphe.py` : Implémentation de Dijkstra et logique du graphe.
- `trajet_victoire_gare_comparaison_finale.html` : Visualisation des résultats.
- `Résumé sur les algorithmes de recherche.pdf` : Documentation théorique.

---

## 👨‍💻 Développé par
**Ruben Mwanza** *Ingénieur Backend & DevOps*

> **Expertise** : Algorithmique avancée, Python, Architecture système.

📩 **Email** : [rubenthedevs@gmail.com](mailto:rubenthedevs@gmail.com)  
📍 **Localisation** : Kinshasa, RDC

---
*Ce projet démontre ma capacité à résoudre des problèmes d'optimisation complexes via le code.*
