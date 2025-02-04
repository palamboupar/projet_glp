# Projet RPG et Développement Web

## Informations des Auteurs

- **Projet RPG** : BOUCHELAGHEM Ali, PALEOLOGOS Amaël & GACI Camil (Janvier 2025)
- **Projet Maritime GLP** : Ammad, Zue et Defrance (04/02/2025)

## Introduction au Projet RPG

Le projet vise à créer un jeu de rôle (RPG) en vue du dessus en 2D avec des donjons multi-niveaux, intégrant des éléments tels que des monstres, trésors, magasins et obstacles. Le jeu met en avant un système en temps réel avec une gestion des combats, de l’équipement et des sorts magiques, dans un univers immersif.

## Structure du Site Web

Le site est structuré en plusieurs parties :

1. **Accueil** : Présentation du site et redirection vers les différentes sections.
2. **Implémentation** : Explication des pages techniques du projet.
3. **Spécifications** : Détails techniques sur les fonctionnalités et exigences du code.
4. **Background** : Explication de la génération du décor.
5. **Déplacements** : Détails sur le système de mouvement.
6. **Graphe** : Explication du modèle utilisé pour les déplacements.
7. **Notions de base** : Définitions clés pour le projet.
8. **Fonctionnalités** : Explication des fonctionnalités nécessaires.

## Règles du Jeu

Le joueur choisit entre trois classes :
- **Guerrier** : Forte attaque, magie moyenne, faible défense.
- **Mage** : Faible attaque, forte magie, défense moyenne.
- **Assassin** : Attaque moyenne, faible magie, grande défense.

Le jeu comprend trois donjons de difficulté croissante avec des ennemis variés et un boss final.

## Système de Combat et Magies

Le jeu propose trois types de magie :
- **Feu** : Boule de feu, explosion, zone de feu, éruption volcanique.
- **Eau** : Éclats de glace, gel, tornade, avalanche.
- **Soin** : Soin mineur, soin majeur, invincibilité temporaire, seconde chance.

## Équipement

Chaque personnage peut s’équiper avec :
- **Tête** : Casque, chapeau de mage, capuche d’assassin.
- **Torse** : Plastron, robe de mage, cuirasse.
- **Jambes** : Pantalon en maille, pantalon de discrétion.
- **Pieds** : Bottes de vitesse, bottes de discrétion, bottes en fer.

Certains équipements apportent des bonus spécifiques selon la classe du personnage.

## Exemple de Code

```java
public class Boat extends Entity {
    private int speed;
    private double angle;
    private ArrayList<GraphPoint> path;
    public Boat(String name, int visionRadius, int maxHp, Point position, String idModel, int speed) {
        super(name, visionRadius, maxHp, position, idModel);
        this.speed = speed;
        this.path = new ArrayList<>();
    }
}
```