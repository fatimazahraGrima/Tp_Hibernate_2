# TP Hibernate 2

## Description du projet

Ce projet est une application Java utilisant Hibernate comme framework de persistance. Il a été développé dans le cadre du TP Hibernate pour la gestion des entités liées à un domaine spécifique, intégrant MySQL pour la base de données et Maven pour la gestion des dépendances.

**_Image suggérée :_** Capture d'écran de l'interface utilisateur ou d'une vue d'ensemble du projet (ex. diagramme UML).

## Technologies utilisées

- **Langage** : Java
- **Framework de persistance** : Hibernate
- **Base de données** : MySQL
- **Gestion de projet** : Maven
- **Environnement de développement** : IntelliJ IDEA

## Fonctionnalités principales

1. **Gestion des entités** :
   - Création et gestion des entités associées aux différentes classes du projet.
   - Configuration de la persistance via des annotations et des fichiers de configuration Hibernate.

**_Image suggérée :_** Capture d'écran montrant un extrait du code Java des entités ou du fichier de configuration `hibernate.cfg.xml`.

2. **Opérations CRUD** :
   - Implémentation des opérations Create, Read, Update, Delete (CRUD) pour chaque entité.

**_Image suggérée :_** Capture d'écran d'une requête CRUD exécutée avec succès dans la console ou à l'aide de l'interface.

3. **Transactions** :
   - Gestion des transactions avec Hibernate.
   - Utilisation des sessions Hibernate pour la gestion des données dans la base.

**_Image suggérée :_** Diagramme montrant le flux des transactions ou l'architecture des couches du projet.

4. **Relations entre entités** :
   - Mapping des relations (OneToOne, OneToMany, ManyToMany) entre les différentes entités.

**_Image suggérée :_** Diagramme de base de données illustrant les relations entre les entités.

## Structure du projet

- **src/main/java** : Contient les classes Java du projet, notamment les entités et le code de gestion des transactions.
- **src/main/resources** : Fichiers de configuration Hibernate et autres ressources (fichiers `.xml` ou `.properties`).
- **pom.xml** : Fichier de configuration Maven, listant les dépendances comme Hibernate et MySQL Connector.

**_Image suggérée :_** Capture d'écran montrant l'arborescence du projet dans l'IDE IntelliJ.

## Configuration

1. **Base de données MySQL** :
   - Créer une base de données MySQL.
   - Configurer les informations de connexion (nom d'utilisateur, mot de passe) dans le fichier de configuration Hibernate (`hibernate.cfg.xml`).

**_Image suggérée :_** Capture d'écran de la configuration `hibernate.cfg.xml` avec les informations de connexion MySQL.
