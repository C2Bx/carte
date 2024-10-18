# Carte Interactive des Clubs et Jeu de Football en Nouvelle-Calédonie

## Contexte

Ce projet propose deux fonctionnalités principales :

1. **Carte Interactive des Clubs et Stades de Football en Nouvelle-Calédonie** : Une carte interactive qui permet de visualiser les clubs et stades de football en Nouvelle-Calédonie. La carte permet de filtrer les clubs par région (Nord, Sud, Îles) et offre des informations détaillées sur chaque club, comme le nom, l'année de fondation, le stade, et une description.

2. **Jeu de Football** : Un mini-jeu de football où le joueur peut contrôler une équipe, essayer de marquer des buts et affronter l'équipe adverse contrôlée par l'IA. Le jeu inclut un tableau des scores et une boîte modale pour afficher les règles du jeu.

## Prérequis

Avant de commencer, assurez-vous d'avoir les éléments suivants installés sur votre machine :

- Un serveur web local (comme [XAMPP](https://www.apachefriends.org/index.html) ou [MAMP](https://www.mamp.info/en/)) ou un hébergement web pour servir les fichiers HTML.
- Un navigateur moderne (Google Chrome, Firefox, Safari, etc.).

## Installation

### 1. Clonez le dépôt ou téléchargez le projet

'''bash
git clone https://github.com/votre-depot.git
'''

Ou téléchargez l'archive ZIP du projet, puis extrayez-la.

### 2. Déplacement dans le répertoire

Allez dans le dossier du projet.

'''bash
cd chemin/vers/le/projet
'''

### 3. Démarrez un serveur web local

Si vous utilisez un serveur local comme XAMPP ou MAMP, placez les fichiers du projet dans le répertoire racine de votre serveur web (par exemple '''htdocs''' pour XAMPP).

### 4. Accédez à la carte interactive

Ouvrez votre navigateur et entrez l'URL suivante (si vous utilisez un serveur local comme XAMPP ou MAMP) :

'''http://localhost/chemin/vers/le/projet/carte.html'''

Cette page affichera la carte interactive des clubs de football en Nouvelle-Calédonie. Vous pouvez utiliser les boutons de filtre pour afficher les clubs selon leur région (Nord, Sud, Îles) ou tous les clubs.

### 5. Accédez au jeu de football

Vous pouvez accéder au mini-jeu de football à l'adresse suivante :

'''http://localhost/chemin/vers/le/projet/jeu.html'''

## Fonctionnalités

### Carte Interactive

- Visualisation des clubs et stades de football sur une carte de la Nouvelle-Calédonie.
- Filtrage par région (Nord, Sud, Îles).
- Informations sur chaque club avec une image du logo du club.
- Navigation fluide grâce à l'utilisation de la bibliothèque [Leaflet.js](https://leafletjs.com/).

### Jeu de Football

- Contrôle des joueurs à l'aide des touches directionnelles ('''↑''', '''↓''', '''←''', '''→''') ou '''Z''', '''Q''', '''S''', '''D'''.
- Objectif : Marquer des buts contre l'équipe adverse.
- Tableau des scores mis à jour en temps réel.
- IA pour contrôler les joueurs adverses.
- Instructions détaillées dans une boîte modale pour les règles du jeu.

## Scripts

- **Leaflet.js** pour la gestion de la carte interactive.
- JavaScript pour la gestion du jeu de football, avec gestion de l'IA et des événements de clic et de clavier.

## Personnalisation

Si vous souhaitez personnaliser la carte ou ajouter d'autres clubs :

1. Ajoutez/modifiez les clubs dans le tableau '''clubs''' situé dans le fichier '''carte.html'''.
2. Mettez à jour les coordonnées GPS, les noms et les descriptions des clubs selon vos besoins.

## Crédits

- Icônes de carte : [OpenStreetMap](https://www.openstreetmap.org/).
- Animation des joueurs : Utilisation d'images animées créées à l'aide de [Piskel](https://www.piskelapp.com/).

