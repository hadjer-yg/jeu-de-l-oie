# Jeu de l'Oie - Carte au Trésor 🏴‍☠️🦜

Un jeu de plateau interactif, éducatif et dynamique sur le thème de la piraterie et des aventures en mer, basé sur les règles traditionnelles du Jeu de l'Oie réinventées.

## 📋 Table des Matières
- [Présentation](#présentation)
- [Fonctionnalités Principales](#fonctionnalités-principales)
- [Structure du Projet](#structure-du-projet)
- [Installation et Utilisation](#installation-et-utilisation)
- [Règles du Jeu](#règles-du-jeu)
- [Personnalisation](#personnalisation)

---

## 🎲 Présentation

**Jeu de l'Oie - Carte au Trésor** permet à 2 jusqu'à 12 joueurs (ou équipes) de s'affronter sur un plateau interactif illustré. Le jeu intègre des événements spéciaux, des cartes d'inventaire, des duels entre pirates, des défis éducatifs et des pièges emblématiques.

## 🚀 Fonctionnalités Principales

* **Nombre de joueurs flexible :** De 2 à 12 équipes avec personnalisation des noms et des avatars (pions).
* **Cartes Événements & Inventaire :** 
  * Option de **jouer immédiatement** une carte piochée ou de la **garder dans son inventaire** pour un usage stratégique ultérieur.
* **Plateau Réactif & Interactif :** Visualisation fluide du parcours en spirale et déplacement automatique des pionts.
* **Mini-jeux et Duels :**
  * **Chifoumi de Pirate** (Pierre-Feuille-Ciseaux) lors des duels entre deux joueurs finissant sur la même case.
  * **Le Puits Profond** et **La Prison** nécessitant de faire un tirage particulier ou d'attendre la délivrance par un autre joueur.
  * **Le Labyrinthe des Crânes** et la **Mort/Squelette** renvoyant le pirate en arrière ou au départ.
* **Lancer de Dé Virtuel :** Animation 3D de lancer de dé.

---

## 📁 Structure du Projet

```text
jeu-de-loie-pirate/
│
├── index.html         # Structure HTML5 principale
├── styles.css         # Styles CSS3, animations et responsive design
├── app.js             # Logique du jeu, gestion du tour, moteur de déplacements
├── cards.js           # Définition de la banque de cartes et des effets
└── README.md          # Guide d'utilisation et documentation
```

---

## 🛠️ Installation et Utilisation

1. **Téléchargement / Clonage :**
   Placez l'ensemble des fichiers (`index.html`, `styles.css`, `app.js`, `cards.js`) dans le même répertoire.

2. **Lancement :**
   Ouvrez le fichier `index.html` directement dans n'importe quel navigateur web moderne (Google Chrome, Firefox, Edge, Safari). Aucune installation de serveur ou de dépendance externe n'est requise.

---

## 📜 Règles du Jeu

### Objectif
Arriver exactement sur la case 63 (**Trésor Final**). Si un joueur dépasse 63, il doit reculer du nombre de cases restant.

### Cases Spéciales
* **L'Oie (Doublon de déplacement) :** Avance immédiatement du même nombre de cases que le jet de dé.
* **L'Auberge du Pirate (Case 19) :** Passez votre tour pendant 2 tours pour vous reposer.
* **Le Puits (Case 31) & La Prison (Case 52) :** Vous y êtes bloqué jusqu'à ce qu'un autre joueur vienne vous en délivrer en s'arrêtant sur la même case.
* **Le Labyrinthe des Crânes (Case 42) :** Retourne à la case 30.
* **La Mort (Case 58) :** Retour immédiat au Départ (case 1).
