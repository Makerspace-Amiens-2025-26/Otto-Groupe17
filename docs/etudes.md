---
layout: default
nav_order: 4
title: Études et choix techniques
---

# Études et choix techniques

Pour réaliser l'Otto Ninja, nous avons sélectionné des composants et des solutions logicielles permettant de maximiser l'accessibilité tout en garantissant une grande fiabilité.

## Architecture Électronique

Le choix des composants repose sur la standardisation et le coût abordable :

- **Cerveau (Contrôleur)** : Utilisation de l'**Arduino Nano** pour son format compact, idéal pour le corps du robot.
- **Actionneurs** : Servomoteurs **SG90** pour leur excellent rapport poids/puissance, parfaits pour les mouvements du bipède.
- **Communication** : Module **HC-05** ou **HC-06 (Bluetooth)**, choisi pour sa compatibilité universelle avec les smartphones Android et sa facilité de mise en œuvre avec RemoteXY.
- **Perception** : Capteur à ultrasons **HC-SR04** pour la détection d'obstacles, offrant une précision suffisante pour le gabarit du robot.
- **Alimentation** : Batterie Li-ion/LiPo avec module régulateur pour assurer une tension stable aux moteurs.

## Solutions Logicielles

Le choix des outils de programmation a été guidé par la volonté de rendre le robot évolutif :

- **Environnement de développement** : **Arduino IDE**, standard de fait, permettant une prise en main rapide grâce à une vaste bibliothèque de ressources.
- **Interface de pilotage** : **RemoteXY**, choisie pour sa capacité à créer des interfaces graphiques personnalisables sans avoir à coder une application native complexe.
- **Conception mécanique** : **Onshape**, pour son approche collaborative et son accessibilité via navigateur web, permettant à n'importe quel maker de modifier les pièces 3D.

## Justification des choix

- **Modularité** : Le choix d'une structure "Open-Source" permet aux utilisateurs de créer leurs propres extensions (ex: support pour caméra ou capteur infrarouge supplémentaire).
- **Maintenance** : L'utilisation de composants "Plug & Play" facilite le remplacement de n'importe quel élément en cas de casse ou d'usure.
- **Accessibilité** : L'intégration de la technologie Bluetooth via RemoteXY permet d'utiliser n'importe quel smartphone comme télécommande, évitant ainsi la construction d'une manette dédiée.
