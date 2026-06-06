---
layout: default
nav_order: 5
title: Conception et prototypage
---

# Conception et prototypage

La création de l'Otto Ninja s'appuie sur une démarche de prototypage rapide, typique des environnements Maker, visant à valider chaque étape avant la finalisation du robot.

## Conception Mécanique (CAO)

La structure a été pensée pour être à la fois robuste et légère :

- **Modélisation 3D** : Réalisée sous **Onshape**, permettant de tester les emboîtements et les jeux mécaniques de manière virtuelle avant toute impression.
- **Impression 3D** : Choix du filament **PLA** pour sa facilité d'impression, son éco-conception et sa rigidité suffisante pour maintenir les composants.
- **Optimisation du châssis** : Le design a été affiné pour loger l'intégralité de l'électronique (batterie, câbles, contrôleur) à l'intérieur du corps, garantissant une esthétique propre.

## Phase de Prototypage

Notre processus a suivi trois grandes étapes de validation :

1.  **Validation Électronique (Breadboard)** : Câblage complet des composants sur une platine d'essai pour vérifier la compatibilité du code et le fonctionnement des moteurs.
2.  **Itération Mécanique** : Impression des premières pièces pour tester les angles de rotation des servomoteurs et s'assurer qu'aucune pièce ne bloque le mouvement.
3.  **Test d'Intégration** : Assemblage final des composants dans le corps imprimé, gestion du cheminement des câbles (Cable Management) et vérification du centre de gravité pour la stabilité du bipède.

## Défis rencontrés

- **Équilibre mécanique et accessoires** : L’ajout du katana dans le dos et du bandana a modifié la répartition des masses d'origine. Il a fallu ajuster l'assemblage pour que ces éléments esthétiques ne déséquilibrent pas le robot vers l'arrière lors de ses déplacements.
- **Calibrage des servomoteurs (SG90)** : L’ajustement des angles et la recherche du "point zéro" de chaque servomoteur ont constitué un défi technique important. Un alignement logiciel rigoureux a été nécessaire pour obtenir une marche fluide, synchronisée, et éviter que le robot ne bascule.
- **Gestion de l’espace interne** : L'intégration de l'ESP32 et d'une batterie autonome dans un espace restreint a demandé une optimisation poussée du câblage pour ne pas gêner le débattement mécanique des servomoteurs des jambes.
