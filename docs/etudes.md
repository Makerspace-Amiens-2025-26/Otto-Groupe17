---
layout: default
nav_order: 4
title: Études et choix techniques
---

# Études et choix techniques

Pour réaliser l'Otto Ninja, nous avons sélectionné des composants et des solutions logicielles permettant de maximiser l'accessibilité tout en garantissant une grande fiabilité.

## Architecture Électronique

Le choix des composants repose sur la standardisation et le coût abordable :

- **Cerveau (Contrôleur)** : Utilisation de l'**ESP32** pour son format compact, idéal pour le corps du robot.
- **Actionneurs** : Servomoteurs **SG90** pour leur excellent rapport poids/puissance, parfaits pour les mouvements du bipède.
- **Perception** : Capteur à ultrasons **HC-SR04** pour la détection d'obstacles, offrant une précision suffisante pour le gabarit du robot.
- **Alimentation** : Batterie intégrée avec module régulateur pour assurer une tension stable aux moteurs et à la carte électronique.

## Solutions Logicielles

Le choix des outils de programmation a été guidé par la volonté de rendre le robot évolutif :

- **Environnement de développement** : **Arduino IDE**, standard de fait, permettant une prise en main rapide grâce à une vaste bibliothèque de ressources.
- **Interface de pilotage** : **RemoteXY**, choisie pour sa capacité à créer des interfaces graphiques personnalisables sans avoir à coder une application native complexe.
- **Conception mécanique** : **Onshape**, pour son approche collaborative et son accessibilité via navigateur web, permettant à n'importe quel maker de modifier les pièces 3D.

## Justification des choix

- **Ergonomie et Pilotage** : L'intégration de la technologie Bluetooth native de l'ESP32 via RemoteXY permet d'utiliser n'importe quel smartphone comme une télécommande réactive et intuitive (grâce au joystick), évitant ainsi la construction complexe d'une manette physique dédiée.
- **Maintenance** : L'utilisation de composants standards et très répandus (servos SG90, capteur HC-SR04) facilite le remplacement rapide de n'importe quel élément en cas de casse ou d'usure au MakerSpace.
- **Personnalisation et Modularité** : Le travail effectué sur Onshape prouve la flexibilité du modèle. La structure reste ouverte, permettant aux utilisateurs d'adapter de nouveaux accessoires esthétiques ou techniques sans compromettre l'équilibre mécanique du robot.
