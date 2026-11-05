# Développement d’Accès Tuteur

## Présentation

Le développement d’Accès Tuteur repose sur une approche progressive visant à produire une plateforme maintenable, évolutive et adaptée aux besoins de ses utilisateurs.

Une attention particulière est accordée à la qualité du code, à la séparation des responsabilités et à la cohérence entre les différents composants.

## Technologies utilisées

| Domaine | Technologies |
|---|---|
| Application web | React, JavaScript, Vite |
| Site vitrine | Next.js, React |
| API | PHP 8 |
| Base de données | MariaDB / MySQL |
| Temps réel | Node.js, WebSocket |
| Infrastructure | Linux, Nginx |
| Dépendances | Composer, npm |
| Gestion du code | Git, GitHub |

Cette liste représente les principales technologies utilisées et peut évoluer.

## Principes de développement

### Séparation des responsabilités

Les composants sont organisés afin de limiter la concentration de responsabilités dans une même classe, fonction ou couche logicielle.

Cette approche vise à faciliter la maintenance, la compréhension et l’évolution du code.

### Maintenabilité

Le développement privilégie des structures permettant de modifier ou d’étendre les fonctionnalités sans nécessiter une réécriture disproportionnée des composants existants.

### Validation des données

Les données reçues par les différentes interfaces doivent faire l’objet de vérifications adaptées à leur nature et à leur contexte d’utilisation.

La validation côté client ne remplace pas les vérifications nécessaires côté serveur.

### Sécurité

La sécurité est prise en considération dans la conception et l’évolution des fonctionnalités.

Elle concerne notamment :

- l’authentification;
- la gestion des autorisations;
- la protection des données;
- la gestion des sessions;
- la validation des entrées;
- la prévention des abus.

### Gestion des erreurs

Les erreurs doivent être traitées de manière à faciliter leur diagnostic tout en évitant l’exposition d’informations internes sensibles aux utilisateurs.

### Documentation

Les fonctionnalités et les décisions techniques importantes peuvent faire l’objet d’une documentation afin de faciliter leur compréhension et leur maintenance.

## Organisation des fonctionnalités

Les fonctionnalités de la plateforme sont réparties selon leurs responsabilités métier.

Cette organisation permet de distinguer les différents systèmes tout en conservant une cohérence dans leurs interactions.

Les conventions internes peuvent varier selon le langage, le framework et les contraintes de chaque composant.

## Suivi du développement

Le suivi public des travaux s’effectue principalement au moyen des GitHub Issues.

Celles-ci peuvent servir à documenter :

- les bogues identifiés;
- les améliorations prévues;
- les nouvelles fonctionnalités;
- les tâches de maintenance;
- certaines réflexions techniques.

Les labels permettent d’identifier les systèmes concernés, les types de tâches et les niveaux de priorité.

## Tests et validation

Les changements apportés à la plateforme doivent faire l’objet de vérifications adaptées à leur portée et à leurs risques.

Ces vérifications peuvent comprendre :

- des tests fonctionnels;
- des tests de validation;
- des vérifications des autorisations;
- des contrôles de régression;
- des examens manuels du comportement des interfaces;
- des analyses de sécurité.

Les pratiques et les outils employés peuvent évoluer avec les besoins du projet.

## Utilisation de l’intelligence artificielle

L’intelligence artificielle peut être employée comme outil complémentaire d’analyse et de vérification.

Son utilisation est encadrée par les principes décrits dans notre [politique d’utilisation de l’intelligence artificielle](../ai-policy.md).

## Évolution des pratiques

Les méthodes et conventions de développement ne sont pas considérées comme immuables.

Elles peuvent évoluer afin de tenir compte des nouvelles exigences, des difficultés rencontrées et de l’expérience acquise au cours du développement.