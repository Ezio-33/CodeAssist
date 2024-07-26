# README pour Script_Prod

## Description

Ce dépôt contient des scripts automatisés pour faciliter la gestion et la mise à jour de projets sur GitHub.

## Scripts

### Install_Script

Ce script permet de configurer automatiquement l'environnement nécessaire pour utiliser les scripts de production. Voici ce qu'il fait :

- Crée le dossier nécessaire pour stocker les scripts si ce dernier n'existe pas déjà.
- Télécharge le script `git_auto` depuis le dépôt GitHub spécifié.
- Attribue les droits d'exécution au script téléchargé.
- Ajoute le dossier des scripts au PATH pour un accès facile.
- Se supprime lui-même après l'exécution.

### Git_Auto

Ce script facilite la gestion des mises à jour des projets sur GitHub. Voici ses fonctionnalités :

- Effectue un `git pull` pour éviter les conflits avant de commencer les modifications.
- Permet à l'utilisateur de choisir entre ajouter tous les fichiers ou seulement un fichier spécifique au commit.
- Demande un commentaire de commit à l'utilisateur et effectue le commit et le push avec ce commentaire.
- Affiche des messages de confirmation en couleur pour une meilleure visibilité.

### Preparation_Projet

Ce script permet de créer automatiquement plusieurs fichiers avec une extension spécifiée par l'utilisateur, ainsi que des fichiers de test et des fichiers `main.py` si souhaité. Voici ses fonctionnalités :

- Demande à l'utilisateur le nom de son projet pour crée un README avec ce nom a l’intérieur.
- Demande à l'utilisateur combien de fichiers il souhaite créer.
- Vérifie que l'entrée est un nombre positif.
- Demande l'extension des fichiers à créer.
- Demande si l'utilisateur souhaite créer des fichiers de test.
- Demande si l'utilisateur souhaite créer des fichiers `main`avec l’extension choisi précédemment.
- Crée les fichiers avec les noms et extensions spécifiés, ainsi que les fichiers de test et `main` si demandé.

## Installation

### Téléchargement et préparation

1. **Ouvrez votre terminal en mode super utilisateur** :
   Cela peut généralement être fait en cherchant "terminal" dans les applications de votre système.
   Si vous n’êtes pas en super utilisateur vous pouvez le devenir avec le commande:

   ```bash
   sudo -i
   ```

   Attention il vous faudra entrer votre mot de passe

2. **Téléchargez le script Install_Script**:
   ```bash
   curl -o Install_Script.sh https://raw.githubusercontent.com/Ezio-33/Script_Prod/master/Install_Script
   ```
3. **Rendez le script exécutable**:
   Une fois dans le dossier ou vous avez téléchargé le Script d'installation
   ```bash
   chmod +x Install_Script.sh
   ```
4. **Exécutez le script Install_Script dans le shell actuel en utilisant la commande**:
   ```bash
   source ./Install_Script.sh
   ```

## Utilisation

### Git_Auto

Après l'installation, vous pouvez utiliser git_auto pour gérer vos projets.
Assurez-vous que le terminal est ouvert dans le répertoire de votre projet, puis exécutez la commande:

```bash
git_auto
```

### Preparation_Projet

Après l'installation, vous pouvez créer vos fichiers de façon automatique pour vos projets.
Assurez-vous que le terminal est ouvert dans le répertoire de votre projet, puis exécutez la commande:

```bash
Preparation_Projet
```

Pour quitter le script, tapez la commande:

```bash
exit
```

## Contact

Pour toute question ou support, veuillez ouvrir un issue dans le dépôt GitHub du projet.
Ou me contacter par mail : [@Samuel VERSCHUEREN](8691@holbertonstudents.com)

## Authors

| [@Samuel VERSCHUEREN](https://github.com/Ezio-33) |
