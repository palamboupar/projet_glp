# 🎮 RPG - Projet de Génie Logiciel

Ce projet est un jeu vidéo de rôle (RPG) en 2D, développé en Java dans le cadre d’un projet universitaire de Génie Logiciel. Le joueur y incarne un héros explorant trois donjons générés aléatoirement, affrontant des ennemis et progressant à travers différentes classes, équipements et compétences.

## 🧩 Fonctionnalités

- Trois classes jouables : Guerrier, Mage, Assassin
- Système de combat en temps réel
- Génération procédurale des donjons
- Système d’expérience, niveaux et compétences
- Équipements variés et objets consommables
- Interface utilisateur simple et efficace
- Mécaniques de magasin, de loot et de boss
- Environnement sonore personnalisé
- Réalisé entièrement en Java sans bibliothèques externes

## 🚀 Lancement du jeu

### Pré-requis

- Java JDK 17 ou supérieur installé

### Compilation & Exécution

```bash
javac TestGame.java
java TestGame
```

Assurez-vous d'exécuter la commande depuis le répertoire `src/` contenant les fichiers sources.

## 🎮 Contrôles

| Action                       | Touche / Souris              |
|-----------------------------|------------------------------|
| Se déplacer                 | Z, Q, S, D ou flèches        |
| Attaquer / Interagir        | Clic gauche                  |
| Utiliser un objet / Ouvrir  | Clic gauche                  |

## 👥 Équipe projet

- **Ali Bouchelaghem** – Rapport, sprites, tests, documentation
- **Amaël Paleologos** – Développement, architecture, gameplay
- **Camil Gaci** – (Absent sur le projet)

## 📁 Structure du code

- `engine/` – Moteur du jeu
- `map/` – Donjons, tuiles, murs
- `player/` – Joueur et statistiques
- `mobile/` – Ennemis, sorts, IA
- `staticObject/` – Objets fixes (coffres, murs, PNJ)
- `stats/` – Équipements, objets, compétences
- `process/` – Gestion des niveaux et logique de jeu
- `TestGame.java` – Point d’entrée du jeu

## ✅ Statut

📦 Version stable — entièrement jouable en solo sur 3 niveaux.

## 📜 Licence

Projet réalisé dans un cadre pédagogique. Utilisation libre à des fins éducatives.
