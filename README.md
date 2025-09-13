# Projet de Base de Données : Contrats et Régions

## Description

Ce projet met à disposition un environnement de base de données MySQL complet et fonctionnel via Docker. Il contient deux tables, `contrats` et `region`, avec leurs données et relations, prêtes à être interrogées.

Cet environnement est destiné à servir de base pour les exercices SQL du cours.

---

## Prérequis

Avant de commencer, assurez-vous d'avoir les outils suivants installés sur votre machine :

1.  **Git** : Pour cloner ce dépôt.
2.  **Docker Desktop** : Pour lancer l'environnement. Assurez-vous que Docker est bien en cours d'exécution.

---

## Instructions d'Installation

Suivez ces étapes pour lancer la base de données sur votre ordinateur :

1.  **Clonez ce dépôt GitHub**
    Ouvrez un terminal et exécutez la commande suivante :
    ```bash
    git clone [URL_DU_DEPOT_GITHUB]
    ```

2.  **Naviguez dans le dossier du projet**
    ```bash
    cd nom-du-dossier-clone
    ```

3.  **Lancez l'environnement Docker**
    Cette commande va télécharger l'image de MySQL et construire votre base de données en arrière-plan. L'importation des données se fera automatiquement.
    ```bash
    docker-compose up -d
    ```

La première fois, le téléchargement peut prendre quelques minutes. Une fois terminé, votre base de données est prête !

---

## Comment se connecter à la Base de Données

Vous pouvez utiliser n'importe quel client SQL (DBeaver, MySQL Workbench, etc.) avec les informations suivantes :

- **Hôte (Host)**: `localhost`
- **Port**: `3307`
- **Base de données (Database)**: `oc_projet_3` 
- **Utilisateur (User)**: `root`
- **Mot de passe (Password)**: `un-mot-de-passe-simple` (et oui j'adore les blagues nulles ;) )
