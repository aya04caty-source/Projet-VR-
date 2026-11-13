# Odino VR

## Présentation du projet

**Odino VR** est un projet de réalité virtuelle développé avec Unity et Blender, destiné au casque Meta Quest 3.

Le joueur évolue dans une forêt fantastique peuplée d'éléments naturels aux dimensions inhabituelles et accompagne Odino, une créature sensible aux sons et aux vibrations de son environnement.

L'objectif est de découvrir et d'interagir avec cet univers tout en aidant Odino à gérer les nuisances sonores.

## Concept et gameplay

Odino est une créature dont les réactions dépendent de l'intensité des vibrations environnantes.

- **Bruit faible :** Odino oriente ses oreilles vers la source sonore.
- **Bruit modéré :** son corps se tourne vers la source.
- **Bruit intense :** ses oreilles se replient et il commence à manifester de l'agitation.
- **Bruit très intense :** Odino se recroqueville et roule vers le lac, son refuge naturel.

Le joueur dispose d'une **pierre magique** qui lui permet de protéger Odino temporairement des effets du bruit.

Lorsqu'il tient la pierre :
- Les bruits ambiants deviennent inaudibles pour le joueur.
- Odino ne réagit plus aux vibrations.
- La jauge de bruit reste active.
- La protection est limitée dans le temps.

Le lac constitue un espace de refuge où Odino peut retrouver son calme.

## Technologies utilisées

| Technologie | Utilisation |
|---|---|
| Unity 6.3 LTS | Développement du jeu |
| C# | Programmation des mécaniques |
| Blender | Modélisation et animation 3D |
| OpenXR | Compatibilité VR |
| XR Interaction Toolkit | Interactions et contrôleurs VR |
| Meta Quest 3/3S | Plateforme cible |
| Git / GitHub | Gestion du code et collaboration |

## Répartition du travail

### Meryem
- Configuration du projet Unity et de l'environnement VR.
- Création de l'environnement 3D.
- Développement des interactions VR.
- Gestion du système sonore et de la jauge de bruit.
- Programmation des mécaniques de gameplay.
- Intégration et tests dans Unity.

### Aya
- Modélisation 3D du personnage Odino.
- Création des animations du personnage dans Blender.
- Préparation et exportation des modèles pour Unity.
- Participation à l'intégration et aux tests.

## Structure du projet

```text
Odino-VR/
├── Assets/
│   ├── Scenes/
│   ├── Scripts/
│   ├── Models/
│   ├── Materials/
│   ├── Prefabs/
│   ├── Animations/
│   ├── Audio/
│   ├── Textures/
│   └── UI/
├── Packages/
├── ProjectSettings/
├── Documentation/
│   ├── Compte-rendus/
│   ├── Conception/
│   └── Captures/
└── README.md
```

## État d'avancement 

- [x] Création de la mascotte "Odino" sur Blender (encore à finaliser).
- [x] Création du dépôt GitHub.
- [x] Création initiale du projet Unity.
- [x] Installation de XR Plug-in Management.
- [x] Installation de XR Interaction Toolkit.
- [ ] Configuration complète d'OpenXR.
- [ ] Mise en place du XR Origin et des contrôleurs.
- [ ] Création de l'environnement forestier.
- [ ] Modélisation et intégration d'Odino.
- [ ] Développement de la pierre magique.
- [ ] Implémentation du système sonore et de la jauge.
- [ ] Développement des réactions d'Odino.
- [ ] Tests sur Meta Quest 3.

## Collaboration

Le projet est développé en équipe avec Git et GitHub.

Les contributions sont organisées autour de la programmation Unity, de la modélisation 3D et de l'intégration des éléments du jeu.
