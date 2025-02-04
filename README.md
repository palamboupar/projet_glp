# Projet RPG : Document de Spécification

## Informations des Auteurs

- **Auteurs** : BOUCHELAGHEM Ali, PALEOLOGOS Amaël & GACI Camil
- **Date** : Janvier 2025

## Introduction

Ce projet a pour but de développer un RPG 2D en vue du dessus, mettant en avant un gameplay d’exploration de donjons multi-niveaux. Il intègre divers éléments classiques du genre, comme les combats en temps réel, la gestion des équipements et des sorts magiques, ainsi qu’un univers immersif et interactif.

## Règles du Jeu

Le jeu propose trois classes de personnages :
- **Guerrier** : Excellente attaque, magie moyenne, faible défense.
- **Mage** : Forte magie, faible attaque, défense moyenne.
- **Assassin** : Attaque moyenne, faible magie, forte défense.

L’objectif est de parcourir trois donjons, vaincre leurs ennemis et affronter le boss final. Si le joueur perd toute sa vie, il recommence depuis le début.

## Système de Combat et Progression

Le jeu fonctionne avec un système d’expérience et de progression :
- **Gain d’expérience** à chaque ennemi vaincu.
- **Montée de niveau** permettant d’améliorer attaque, magie ou défense.
- **Déblocage de compétences** spécifiques à chaque classe.

Le jeu propose également trois types de magie :
- **Feu** : Boule de feu, explosion, éruption volcanique.
- **Eau** : Éclats de glace, tornade, avalanche.
- **Soin** : Soin mineur, soin majeur, invincibilité temporaire.

## Équipement

Le joueur peut s’équiper avec des objets influençant ses statistiques :

| Partie du Corps | Équipements Disponibles |
|---------------|---------------------|
| Tête         | Casque, chapeau de mage, capuche d’assassin |
| Torse        | Plastron, robe de mage, cuirasse |
| Jambes       | Pantalon en maille, pantalon de discrétion |
| Pieds        | Bottes de vitesse, bottes de discrétion, bottes en fer |

Certains équipements offrent des bonus uniques, comme des résistances élémentaires ou une amélioration des capacités offensives.

## Structure des Donjons

Le jeu est composé de trois donjons générés aléatoirement, chacun avec un bestiaire et un boss spécifique :

| Donjon | Ennemis | Boss |
|--------|----------------|--------------|
| Grotte sylvestre | Slimes, zombies, fantômes | Golem de pierre |
| Forteresse enflammée | Esprits, salamandres, squelettes de feu | Cerbère |
| Palais de glace | Esprits, golems, pieuvres de glace | Roi des glaces |

L’aléatoire joue un rôle clé dans la génération des niveaux, les positions des ennemis et les trésors trouvés.

## Économie et Magasins

L’or peut être obtenu en battant des ennemis ou en réussissant des défis secondaires. Il permet d’acheter :
- **Équipement** améliorant les statistiques.
- **Consommables** : potions de soin, invisibilité, augmentation temporaire des statistiques.

Des magasins apparaissent de manière aléatoire dans les donjons, offrant diverses options d’achat et de revente.

## Citation Inspirante

> "Un bon jeu est un jeu où chaque partie est une nouvelle aventure." - *Auteur inconnu*

## Checklist des Tâches

- [ ] Finaliser le développement du RPG
- [X] Définir les mécaniques de combat
- [ ] Tester l’équilibrage des niveaux
- [X] Structurer la documentation