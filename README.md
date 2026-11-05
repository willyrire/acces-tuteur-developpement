# Accès Tuteur — Développement

Bienvenue sur le dépôt public consacré au développement d’**Accès Tuteur**.

Ce dépôt a pour objectif de regrouper différentes ressources liées à la conception, au développement et à l’évolution de la plateforme Accès Tuteur : documentation technique, décisions d’architecture, exemples de code, prototypes, captures d’écran, notes de développement et autres éléments permettant de suivre l’évolution du projet.

## À propos d’Accès Tuteur

**Accès Tuteur** est une plateforme de tutorat conçue afin de faciliter la mise en relation entre des étudiants, des parents et des tuteurs.

La plateforme vise notamment à centraliser plusieurs aspects du tutorat, tels que :

- la recherche de tuteurs;
- la gestion des profils;
- la sélection des cours et matières enseignées;
- la mise en relation entre étudiants et tuteurs;
- la messagerie;
- la gestion des rencontres;
- les paiements;
- le suivi des services de tutorat;
- ainsi que différents outils destinés aux tuteurs, étudiants et parents.

Le projet est développé progressivement avec une attention particulière portée à l’expérience utilisateur, à la sécurité, à la protection des données et à la maintenabilité de l’infrastructure.

## À quoi sert ce dépôt ?

`acces-tuteur-developpement` est avant tout un **dépôt public de documentation et de suivi du développement**.

Il peut contenir, entre autres :

- de la documentation sur l’architecture de la plateforme;
- des explications concernant certains choix techniques;
- des prototypes et preuves de concept;
- des exemples de code;
- des schémas de fonctionnement;
- des notes sur les fonctionnalités en développement;
- des captures d’écran de l’interface;
- des informations sur les technologies utilisées;
- des réflexions concernant l’évolution du projet;
- de la documentation sur l’utilisation de l’intelligence artificielle dans le développement.

Ce dépôt permet donc de rendre une partie du processus de développement **accessible au public**, tout en offrant une meilleure visibilité sur les travaux réalisés, les fonctionnalités en cours de conception et les orientations techniques du projet.

Il constitue également un espace de référence permettant de documenter certaines décisions, de conserver un historique des évolutions et de faciliter la compréhension des différents systèmes qui composent Accès Tuteur.

## Suivi du développement

Le développement d’Accès Tuteur est un processus continu. De nouvelles fonctionnalités, des améliorations et des corrections sont régulièrement envisagées, développées et intégrées à la plateforme.

Les outils de GitHub permettent de suivre une partie de ces activités :

- **Issues :** signalements de bogues, demandes d’amélioration, propositions de fonctionnalités et tâches techniques.
- **Labels :** classification des issues selon le système concerné, leur nature et leur priorité.
- **Milestones :** regroupement des travaux selon les objectifs et les étapes du développement, lorsque applicable.
- **Discussions :** échanges et réflexions autour du projet, lorsque cette fonctionnalité est disponible.

Les informations publiées peuvent concerner des travaux planifiés, en cours de réalisation, terminés ou abandonnés.

### Classification des issues

Afin de faciliter l’organisation du développement, les issues peuvent être classifiées à l’aide de plusieurs catégories de labels.

| Catégorie | Préfixe | Utilisation |
|---|---|---|
| Système | `system:` | Identifie le module ou le système concerné. |
| Type | `type:` | Précise la nature de la tâche ou du signalement. |
| Priorité | `priority:` | Indique le niveau de priorité attribué à une issue. |

Cette classification permet de mieux organiser les travaux, de repérer les problèmes et de suivre les améliorations apportées aux différents systèmes.

**Important :** les priorités, échéances et fonctionnalités présentées dans ce dépôt peuvent être modifiées à tout moment. Elles ne constituent pas des engagements contractuels ou des garanties de livraison.

## Architecture et technologies

Accès Tuteur repose sur une architecture composée de plusieurs services et applications ayant chacun des responsabilités distinctes.

Le développement du projet fait notamment appel aux technologies suivantes :

| Domaine | Technologies |
|---|---|
| Application web | React, JavaScript, Vite |
| Site vitrine | Next.js, React |
| API | PHP 8 |
| Base de données | MariaDB / MySQL |
| Communication en temps réel | WebSocket, Node.js |
| Infrastructure | Linux, Nginx |
| Gestion des dépendances | Composer, npm |
| Versionnement | Git, GitHub |

L’architecture du backend s’inspire notamment des principes de la **conception pilotée par le domaine (Domain-Driven Design — DDD)**, afin de favoriser la séparation des responsabilités, la maintenabilité et l’évolution des différents composants.

Ces choix technologiques peuvent évoluer en fonction des besoins techniques et opérationnels de la plateforme.

## Documentation technique

Une partie de la documentation technique d’Accès Tuteur peut être publiée dans ce dépôt afin d’expliquer le fonctionnement de certains composants.

Elle peut notamment couvrir :

- l’organisation générale de l’architecture;
- les responsabilités des différents services;
- les modèles de données;
- les communications entre applications;
- les mécanismes de gestion des événements;
- les conventions de développement;
- les décisions d’architecture;
- le cycle de vie de certaines fonctionnalités.

Les documents peuvent être accompagnés de diagrammes, d’exemples de requêtes, de représentations des flux de données et de portions de code illustratives.

La documentation publiée ici n’a pas nécessairement vocation à représenter l’intégralité de la documentation technique interne.

## Transparence et sécurité

Accès Tuteur souhaite favoriser une certaine transparence dans son processus de développement, tout en maintenant un niveau élevé de sécurité et de confidentialité.

Par conséquent, certaines informations demeurent privées, notamment :

- le code source complet de l’application et de ses services internes;
- les configurations sensibles des serveurs et de l’infrastructure;
- les clés d’API, identifiants et autres secrets;
- les données personnelles des utilisateurs;
- les mécanismes internes dont la divulgation pourrait compromettre la sécurité de la plateforme.

La publication de documentation, d’extraits de code ou de schémas techniques est effectuée de manière sélective.

**Ce dépôt public ne constitue donc pas une publication intégrale du code source d’Accès Tuteur.**

La présence d’exemples de code dans ce dépôt ne signifie pas non plus que les composants correspondants sont directement accessibles, réutilisables ou déployables de manière indépendante.

## Contributions et signalements

Les utilisateurs, développeurs et autres personnes intéressées par le projet peuvent participer à son amélioration en soumettant des signalements ou des suggestions par l’intermédiaire des GitHub Issues.

Avant de créer une nouvelle issue, il est recommandé de vérifier si une demande similaire existe déjà.

Les contributions peuvent notamment concerner :

- un bogue ou un comportement inattendu;
- une amélioration de l’expérience utilisateur;
- une proposition de nouvelle fonctionnalité;
- une incohérence dans la documentation;
- une suggestion technique ou architecturale.

Afin de faciliter le traitement d’un signalement, il est recommandé de fournir une description claire du problème, les étapes permettant de le reproduire ainsi que le comportement attendu, lorsque ces renseignements sont pertinents.

L’ouverture d’une issue ne garantit pas sa prise en charge, son acceptation ou son intégration à la plateforme.

L’équipe responsable du développement se réserve le droit de modifier, regrouper, fermer ou refuser certaines demandes.

### Signalement de vulnérabilités

Pour des raisons de sécurité, **les vulnérabilités potentielles ne doivent pas être divulguées publiquement dans les issues**.

Les problèmes de sécurité doivent être communiqués de manière privée à l’équipe d’Accès Tuteur, par l’intermédiaire d’un canal de signalement sécurisé.

Il est également demandé de ne pas publier de données personnelles, de jetons d’authentification, de clés d’accès ou de renseignements confidentiels dans les issues et les discussions publiques.

## Utilisation de l’intelligence artificielle

L’intelligence artificielle peut être utilisée comme outil d’assistance dans certaines étapes du développement d’Accès Tuteur, notamment pour :

- l’analyse et la résolution de problèmes techniques;
- la recherche de solutions architecturales;
- l’assistance à la rédaction de documentation;
- la génération et la révision de portions de code;
- l’exploration et la comparaison de différentes approches techniques;
- l’identification de problèmes potentiels dans certaines implémentations.

L’utilisation de ces outils ne remplace pas la responsabilité humaine dans les décisions techniques, la validation du code, la protection des données et la sécurité des systèmes.

Les propositions produites avec l’assistance de l’intelligence artificielle peuvent être adaptées, corrigées ou rejetées selon les besoins du projet.

## Évolution du dépôt

Le contenu de ce dépôt est susceptible d’évoluer parallèlement au développement d’Accès Tuteur.

Certains documents peuvent présenter des fonctionnalités expérimentales, des propositions non retenues ou des architectures qui ne correspondent plus à l’implémentation actuelle.

Dans la mesure du possible, les ressources concernées seront identifiées afin de distinguer les éléments en cours de conception, les fonctionnalités implémentées et les informations devenues obsolètes.

Les documents et exemples publiés sont fournis à titre informatif. Ils peuvent être incomplets, modifiés ou retirés sans préavis.

## Propriété intellectuelle

Sauf indication contraire ou présence d’une licence spécifique, les documents, exemples, sch
