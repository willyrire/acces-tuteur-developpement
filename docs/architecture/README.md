# Architecture d’Accès Tuteur

## Présentation

Accès Tuteur repose sur une architecture composée de plusieurs applications et services qui collaborent afin d’assurer le fonctionnement de la plateforme.

Cette organisation vise à favoriser :

- la séparation des responsabilités;
- la maintenabilité des composants;
- l’évolution indépendante de certains services;
- la fiabilité des communications;
- la sécurité des échanges;
- la réutilisation de la logique métier.

La présente documentation fournit une vue d’ensemble de l’architecture technique.

Elle ne constitue pas une description exhaustive de l’infrastructure interne.

## Principaux composants

### Site vitrine

Le site vitrine constitue le point d’entrée public d’Accès Tuteur.

Il présente la plateforme, ses fonctionnalités et les informations utiles aux visiteurs.

**Technologies principales :** Next.js et React.

### Application web

L’application web permet aux utilisateurs d’interagir avec les fonctionnalités de la plateforme.

Elle comprend notamment les interfaces de gestion des profils, de mise en relation, de messagerie et d’organisation des rencontres.

**Technologies principales :** React, JavaScript et Vite.

### Interface de programmation (API)

L’API constitue un composant central du système.

Elle assure le traitement des requêtes, l’application des règles métier, la gestion des autorisations et la communication avec les mécanismes de persistance des données.

**Technologie principale :** PHP 8.

Son architecture s’inspire notamment des principes du Domain-Driven Design (DDD).

### Base de données

La persistance des données repose principalement sur MariaDB / MySQL.

La base de données permet de conserver les informations nécessaires au fonctionnement des différents modules de la plateforme.

L’accès aux données est encadré par des composants dédiés afin de limiter le couplage entre les règles métier et les mécanismes de persistance.

### Communication en temps réel

Un service de communication WebSocket permet la transmission de certains événements aux clients connectés.

Il intervient notamment dans les fonctionnalités nécessitant une mise à jour rapide des interfaces, comme la messagerie.

**Technologies principales :** Node.js et WebSocket.

### Infrastructure

Les services s’appuient sur une infrastructure serveur Linux et différents composants logiciels nécessaires à leur fonctionnement.

Nginx est notamment utilisé pour certaines fonctions de distribution des requêtes et de communication réseau.

Les configurations détaillées de l’infrastructure ne sont pas rendues publiques.

## Organisation du backend

Le backend est organisé autour de responsabilités distinctes.

### Domaine

Le domaine contient les modèles métier et les concepts fondamentaux de la plateforme.

Il vise à représenter les règles propres au fonctionnement d’Accès Tuteur.

### Application

La couche application coordonne les opérations nécessaires à l’exécution des différents cas d’utilisation.

Elle organise les interactions entre les composants sans concentrer l’ensemble des responsabilités dans les contrôleurs.

### Infrastructure

La couche infrastructure regroupe les mécanismes techniques nécessaires au fonctionnement de l’application.

Elle peut notamment comprendre les repositories, l’accès aux bases de données et les intégrations avec des services externes.

## Communication entre les systèmes

Les composants communiquent au moyen de mécanismes adaptés à leurs responsabilités.

Les échanges peuvent notamment reposer sur :

- des requêtes HTTP;
- des réponses JSON;
- des communications WebSocket;
- des événements applicatifs;
- des échanges internes entre services.

Le choix d’un mécanisme dépend des besoins fonctionnels, de la fiabilité attendue et des contraintes techniques.

## Documentation complémentaire

Des documents spécifiques pourront être ajoutés pour présenter certains systèmes, notamment :

- l’authentification;
- les permissions;
- la messagerie;
- la modération;
- la gestion des rencontres;
- les notifications;
- les événements applicatifs.

Les documents seront publiés selon leur pertinence et les exigences de sécurité applicables.

## Évolution de l’architecture

L’architecture d’Accès Tuteur est appelée à évoluer.

Les choix techniques peuvent être révisés afin de répondre à de nouveaux besoins, de simplifier la maintenance ou d’améliorer la fiabilité du système.

La documentation publique pourra être mise à jour pour refléter les changements significatifs.