# Robotique LEGO - Résolution Automatique de Labyrinthe avec EV3 et ev3dev2

Bienvenue dans ce projet dédié à la robotique, où j'ai conçu et programmé un robot LEGO Mindstorms EV3 capable de parcourir et de résoudre un labyrinthe de manière autonome. Ce projet utilise la bibliothèque **ev3dev2**, un ensemble de commandes Python pour piloter les moteurs, les capteurs et d'autres composants du robot. Grâce à des capteurs de couleurs et une programmation avancée, le robot peut détecter son environnement, naviguer à travers les obstacles et trouver la sortie du labyrinthe sans intervention humaine.

#### Groupe
- SOUDANI Younes
- BELUCHE Quentin

## Objectif du projet

L'objectif de ce projet était de construire un robot LEGO capable d'analyser son environnement, de prendre des décisions autonomes et de résoudre un labyrinthe en temps réel. Le projet combine construction physique et programmation, illustrant les concepts de robotique, d'automatisation et d'intelligence embarquée.

## Fonctionnalités principales

- **Capteurs de couleurs** : Utilisation de capteurs de couleurs pour détecter les lignes ou les marqueurs au sol, permettant au robot d'ajuster sa trajectoire.
- **Moteurs et mouvements** : Programmation des moteurs pour contrôler les mouvements du robot, incluant la vitesse, la direction, et la gestion des virages.
- **Algorithme de résolution de labyrinthe** : Le robot implémente un algorithme de type "suivi de mur" ou "droite-gauche" pour explorer le labyrinthe et éventuellement trouver la sortie.
- **Réactivité en temps réel** : Adaptation du comportement du robot en fonction des changements dans l'environnement du labyrinthe, avec des décisions prises en fonction des informations reçues par les capteurs.

## Technologie utilisée

- **LEGO Mindstorms EV3** : Un kit de robotique modulaire permettant de construire et de programmer des robots.
- **ev3dev2** : Une bibliothèque Python dédiée à la programmation des robots LEGO EV3. Elle permet de contrôler les moteurs, les capteurs et de communiquer avec le cerveau du robot (la brique EV3).
- **Python** : Langage utilisé pour écrire les scripts qui contrôlent le robot et son comportement dans le labyrinthe.

## Construction du robot

Le robot a été conçu avec les éléments LEGO Mindstorms EV3 suivants :

- **Capteur de couleurs** : Utilisé pour détecter des marqueurs ou lignes au sol, et pour identifier des changements de terrain.
- **Moteurs de rotation** : Contrôlent les roues du robot pour gérer les déplacements et les virages.
- **Châssis personnalisable** : Construit avec des briques LEGO EV3 pour offrir stabilité et flexibilité.

## Algorithme de résolution

L'algorithme implémenté dans ce projet permet au robot de naviguer à travers un labyrinthe en suivant une série d'étapes simples :

1. **Détection des intersections** : Le robot scanne son environnement grâce aux capteurs pour détecter les intersections ou les virages.
2. **Suivi d’un mur** : L’algorithme de "suivi de mur" permet au robot de maintenir sa direction tout en longeant les parois du labyrinthe.
3. **Décision de mouvement** : Selon les informations reçues des capteurs (virage détecté, impasse, etc.), le robot décide s'il doit tourner à gauche, à droite, ou reculer pour explorer d'autres chemins.
4. **Sortie du labyrinthe** : Une fois la sortie détectée, le robot cesse de scanner et se dirige vers la sortie de manière optimale.

## Installation et exécution

### Prérequis

- **EV3 Mindstorms** avec micro-programme compatible avec ev3dev.
- **Python 3** installé sur la brique EV3.
- **Bibliothèque ev3dev2** : Disponible sur la brique EV3 via `apt-get` ou via une installation Python.

### Instructions

1. Clonez ce dépôt sur votre ordinateur :
   ```bash
   git clone https://github.com/yourusername/lego-maze-robot.git

   Exécutez le programme principal sur l'EV3 :
2. Copiez le code et exécutez le programme principal sur l'EV3:
   ```bash
   python3 main.py
