# 🚀 TD Ordonnancement Temps Réel - Cosmic Edition

Ce dépôt contient la résolution complète, interactive et détaillée de la **Série 03** d'exercices sur l'ordonnancement des systèmes temps réel et des systèmes d'exploitation. 

Cette version spéciale **"Cosmic Edition"** se distingue par une interface immersive sur le thème de l'espace, utilisant des effets de *glassmorphism*, des couleurs néon, et des visualisations interactives 100% natives.

## ✨ Fonctionnalités Principales

* **🌌 Thème Astronomique :** Interface utilisateur moderne avec un arrière-plan spatial animé, des bordures luminescentes (néon violet, cyan, rose) et des panneaux semi-transparents.
* **🖱️ Diagrammes de Gantt Interactifs :** Les séquencements des tâches ne sont plus statiques ! Survolez les blocs d'exécution avec votre souris pour faire apparaître des **infobulles détaillées** (tooltips) indiquant les intervalles de temps, les échéances et l'état des préemptions.
* **🧮 Démonstrations Mathématiques Détaillées :** Chaque étape de calcul (facteur d'utilisation, test de Liu & Layland, temps de rotation) est expliquée clairement dans des boîtes de code textuelles, sans dépendre de bibliothèques externes lourdes.
* **⚡ Zéro Dépendance :** Tout est codé en **HTML pur et CSS3**. Aucun framework JavaScript (comme React ou Vue), ni bibliothèque graphique (comme D3.js) n'est requis. Le fichier est ultra-léger et rapide.

## 📋 Contenu des Exercices

Le document couvre les algorithmes d'ordonnancement suivants :

* **Exercice 1 :** Rate Monotonic (RM) et test d'ordonnançabilité de Liu & Layland.
* **Exercice 2 :** Analyse de l'échec de RM et résolution optimale via Earliest Deadline First (EDF).
* **Exercice 3 :** Comparaison des comportements de RM, EDF et LLF (Least Laxity First).
* **Exercice 4 :** Systèmes sous tension où l'échéance est inférieure à la période (D < P) analysés avec RMA, DMA et EDF.
* **Exercice 6 :** Ordonnancement processeur (OS) classique avec First-Come First-Served (FCFS), Round Robin (RR) et Shortest Remaining Time First (SRTF/SJF Préemptif).

## 🚀 Comment lancer le projet

Puisqu'il s'agit d'un projet "Single-Page" autonome, le déploiement est instantané :

### En local sur votre machine
1. Clonez ce dépôt : `git clone [URL_DE_VOTRE_DEPOT]`
2. Ouvrez le dossier sur votre ordinateur.
3. Double-cliquez simplement sur le fichier `index.html` pour l'ouvrir dans n'importe quel navigateur web moderne.

### Hébergement via GitHub Pages (Recommandé)
Faites profiter tout le monde de votre interface cosmique :
1. Allez dans l'onglet **Settings** de votre dépôt GitHub.
2. Dans le menu de gauche, cliquez sur **Pages**.
3. Dans la section *Build and deployment*, choisissez **Deploy from a branch**.
4. Sélectionnez la branche `main` (ou `master`) et le dossier `/root`, puis sauvegardez.
5. Votre site sera en ligne à l'URL fournie par GitHub dans les minutes qui suivent !

## 👨‍💻 Technologies Utilisées

* **HTML5** (Structure sémantique)
* **CSS3** (Flexbox, Animations Keyframes, Pseudo-éléments `::after` pour les tooltips, Variables CSS pour la gestion du thème néon)
