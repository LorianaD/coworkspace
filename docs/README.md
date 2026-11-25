
# Documentation — CoWork'Space

Ce dossier regroupe les documents de conception,
les choix techniques et la documentation
du projet CoWork'Space.

## 1. Analyse des besoins

- Cahier des charges
- Fonctionnalités
- Règles de gestion

### Personas

Les personas permettent d'identifier les profils
utilisateurs, leurs objectifs, leurs frustrations
et leurs besoins fonctionnels.

Trois profils ont été définis pour le projet.

#### Persona 01 — Membre régulier

![Persona 01](./personas/Persona_01_Membre_Regulier.png)

#### Persona 02 — Membre organisateur

![Persona 02](./personas/Persona_02_Membre_Organisateur.png)

#### Persona 03 — Administrateur

![Persona 03](./personas/Persona_03_Administrateur.png)

Ces personas sont des profils fictifs construits
à partir des besoins exprimés dans le sujet.

## 2. Conception fonctionnelle

Les diagrammes de cas d'utilisation permettent
d'identifier les acteurs et les fonctionnalités
de l'application.

### Acteurs principaux

- Visiteur
- Membre
- Administrateur

### Acteur secondaire

- Service de messagerie externe

### UC-00 — Diagramme général

![UC-00](./use-cases/UC-00_Diagramme_General.png)

### UC-01 — Authentification

![UC-01](./use-cases/UC-01_Authentification.png)

### UC-02 — Visualisation des espaces

![UC-02](./use-cases/UC-02_Visualisation.png)

### UC-03 — Réservation

![UC-03](./use-cases/UC-03_Reservation.png)

### UC-04 — Administration

![UC-04](./use-cases/UC-04_Administration.png)

### UC-05 — Notifications

![UC-05](./use-cases/UC-05_Notification.png)

### Document collaboratif

[Personas — FigJam](https://www.figma.com/board/VxHVhhsPDKS1uqtyYLYoYj/Personas?node-id=0-1&t=wD8Usq1FBT8lJO35-1)

[Use Cases — FigJam](https://www.figma.com/board/KI3scBqrO79f0HmetPNeKS/Use-Cases?t=wD8Usq1FBT8lJO35-1)

Les diagrammes constituent une base de conception
fonctionnelle à valider collectivement.

## 3. Modélisation des données

La modélisation des données permet de définir
les entités, leurs relations et la structure
de la future base de données.

### Modèle Conceptuel de Données (MCD)

![MCD](./database/CoWorkSpace_MCD_v1.png)

### Modèle Logique de Données (MLD)

![MLD](./database/CoWorkSpace_MLD_v1.png)

### Document collaboratif

[MCD et MLD — FigJam](https://www.figma.com/board/skaVQQVAnksYkEmm584QWI/MCD-MLD?node-id=0-1&t=uAQMQOh1TPQJZuly-1)

Les modèles sont actuellement en version 1.
Ils constituent une base de travail à valider
collectivement et à adapter en fonction du cahier
des charges, des fonctionnalités et des maquettes.

## 4. Maquettes

- Wireframes des écrans principaux
- Maquettes de l'application

Lien Figma : à compléter.

## 5. Choix techniques

- Technologies frontend
- Technologies backend
- Base de données
- Architecture logicielle
- Justification des choix techniques

## 6. Tests

- Tests unitaires de la logique métier critique
- Scénario de test utilisateur :
  inscription jusqu'à la réservation

## 7. Suivi des livrables

| Livrable | Statut |
| --- | --- |
| Cahier des charges | En cours |
| Personas | Réalisés - À valider |
| Diagramme de cas d'utilisation | Réalisé - À valider |
| MCD | V1 - À valider |
| MLD | V1 - À valider |
| Maquettes | En cours |
| Choix techniques | À définir |
| Tests unitaires | À réaliser |
| Scénario de test | À réaliser |

## Liens utiles

- [Trello](https://trello.com/b/vE5fB6EH/coworkspace)
- [FigJam — Personas](https://www.figma.com/board/VxHVhhsPDKS1uqtyYLYoYj/Personas?t=wD8Usq1FBT8lJO35-1)
- [FigJam — Use Cases](https://www.figma.com/board/KI3scBqrO79f0HmetPNeKS/Use-Cases?t=wD8Usq1FBT8lJO35-1)
- Figma — Maquettes : à compléter
- [FigJam — MCD et MLD](https://www.figma.com/board/skaVQQVAnksYkEmm584QWI/MCD-MLD?node-id=0-1&t=uAQMQOh1TPQJZuly-1)
