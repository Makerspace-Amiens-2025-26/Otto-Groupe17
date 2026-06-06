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

# Evolution Ninja

Le projet se base sur le modèle open-source OttoDIY, reconnu pour sa fiabilité et sa simplicité.

Pour cette version "Ninja", nous avons poussé plus loin le modèle classique OttoDIY en retravaillant son apparence et en transformant radicalement son mode de contrôle :

- **Pilotage sur-mesure (RemoteXY)** : Au lieu d'un simple contrôle Bluetooth standard, nous avons développé une interface spécifique sur l'application. Le robot se pilote désormais précisément à l'aide d'un joystick virtuel pour les déplacements et d'un bouton d'action pour déclencher des comportements spécifiques.
- **Design & Accessoires Ninja** : L'esthétique du robot a été entièrement personnalisée en modifiant la structure CAO. Il arbore fièrement un **bandana**, des **inscriptions en japonais** gravées sur sa coque, ainsi qu'un **katana** fixé dans son dos.

# Cahier des Charges

Le robot doit répondre aux contraintes suivantes :  

- **Dimensions** : Taille adaptée (doit rentrer dans une boite témoin).
- **Mobilité** : Capacité à avancer, reculer et tourner.
- **Interaction** : Détection d'obstacles via un capteur à ultrasons.
- **Autonomie** : Alimentation par batterie intégrée au corps du robot.
- **Évolutivité** : Code source ouvert (sous licence) et structure CAO modifiable.

