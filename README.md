### nom du projet
Tic Tac Toe

## installation
cloner le repository

### Préparer son environnement
- A partir du docker-compose disponible sur le repository [docker-gitlab-jenkins](https://github.com/June-Ruth/docker-gitlab-jenkins)

### Récupérer le projet en local
- Clôner le projet en local
- Mettre en place le projet sur le GitLab local avec le nom formaté selon le schéma suivant : **_nom_prenom_tic-tac-toe_**

## Workflow gitlab utilisé est GitFlow :

Le schéma de travail GitFlow que nous avons adopté crée un cadre de branches précis, composé de deux branches principales : la branche principale, communément appelée "main", et une branche de développement spécifique (projet) pour les travaux en cours et la gestion des versions de l'application. Lorsque les fonctionnalités sur la branche de développement sont prêtes à être déployées, chaque demande de fusion est examinée et validée avant d'être intégrée dans la branche principale en vue du déploiement final.

Ce modèle présente plusieurs avantages. Tout d'abord, il fournit une structure claire et organisée pour le développement logiciel, ce qui est particulièrement efficace pour les projets comportant plusieurs versions et des cycles de développement complexes. De plus, il permet le développement simultané de fonctionnalités tout en maintenant la stabilité de la branche de développement, facilitant ainsi la collaboration et la gestion des versions.