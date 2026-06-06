---
layout: default
nav_order: 3
title: Objectifs du projet
---

# Introduction

Ce projet consiste en la création d'un robot bipède autonome basé sur le modèle Otto. Le robot est conçu pour être une plateforme d'apprentissage ouverte, permettant de découvrir la robotique, l'impression 3D et le codage de manière ludique.

## Contexte du Projet

Dans le cadre de ce projet réalisé au MakerSpace, nous avons souhaité proposer un projet accessible qui combine mécanique, électronique et programmation. L'Otto Ninja permet d'éclairer le fonctionnement d'un robot mobile en offrant une structure simple et facile à assembler.

## Objectifs du Projet

- **Apprentissage** : Initier les utilisateurs aux bases de l'électronique (servomoteurs, capteurs) et de la logique de programmation.
- **Modularité** : Permettre l'ajout de nouvelles fonctionnalités (Bluetooth, capteurs supplémentaires, accessoires).
- **Accessibilité** : Proposer un robot dont toutes les pièces sont imprimables en 3D et dont les composants électroniques sont standardisés.
- **Partage** : Documenter l'intégralité du processus de fabrication pour permettre à n'importe qui de reproduire le robot.

# Existant

Le projet se base sur le modèle open-source OttoDIY, reconnu pour sa fiabilité et sa simplicité.

Pour cette version "Ninja", nous avons fait évoluer le modèle classique en y intégrant :  

- **Interface de pilotage intuitive** : Grâce à l'utilisation de RemoteXY, nous avons remplacé le pilotage autonome basique par une télécommande mobile personnalisable.
- **Connectivité Bluetooth** : L'ajout d'un module de communication permet une liaison sans fil stable avec un smartphone, transformant le robot en un modèle télécommandé à distance.

# Cahier des Charges

Le robot doit répondre aux contraintes suivantes :  

- **Dimensions** : Taille adaptée (doit rentrer dans une boite témoin).
- **Mobilité** : Capacité à avancer, reculer et tourner.
- **Interaction** : Détection d'obstacles via un capteur à ultrasons.
- **Autonomie** : Alimentation par batterie intégrée au corps du robot.
- **Évolutivité** : Code source ouvert (sous licence) et structure CAO modifiable.

