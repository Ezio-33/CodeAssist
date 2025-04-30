# README pour CodeAssist

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

### Fix_Pycode

Ce script vous permet de corriger les erreurs de formatage et de vérifier le style de vos fichiers Python.

### Fix_JS

Ce script vous permet de corriger les erreurs de formatage et de vérifier le style de vos fichiers JavaScript.

### Merge

Ce script facilite le processus de merge entre deux branches Git. Voici ses fonctionnalités :

- Vérifie si le répertoire courant est un dépôt Git valide.
- Affiche les branches disponibles.
- Demande à l'utilisateur de spécifier la branche source et la branche cible pour le merge.
- Vérifie si la branche cible existe.
- Vérifie si la branche source a déjà été mergée dans la branche courante.
- Gère les modifications non commitées avant de procéder au merge.
- Effectue le merge de la branche source dans la branche cible.
- Demande à l'utilisateur s'il souhaite pousser les changements vers le dépôt distant.
- Retourne à la branche originale après le merge.

## Installation

### Téléchargement et préparation

1. **Ouvrez votre terminal en mode super utilisateur** :
   Cela peut généralement être fait en cherchant "terminal" dans les applications de votre système.
   Si vous n’êtes pas en super utilisateur vous pouvez le devenir avec le commande:

   ```bash
   sudo -i
   ```

   Attention il vous faudra entrer votre mot de passe

2. **Télécharge et exécute le script Install_Script**:
   ```bash
   curl -o Install_Script.sh https://raw.githubusercontent.com/Ezio-33/Script_Prod/main/Install_Script && chmod +x Install_Script.sh && bash Install_Script.sh
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

### Fix_Pycode

Après l'installation, vous pouvez formater et vérifier le style de vos fichiers Python.
Assurez-vous que le terminal est ouvert dans le répertoire de votre projet, puis exécutez la commande:

```bash
Fix_Pycode
```

### Fix_JS

Après l'installation, vous pouvez corriger les erreurs de style de vos fichiers JavaScript.
Assurez-vous que le terminal est ouvert dans le répertoire de votre projet, puis exécutez la commande:

```bash
Fix_JS
```

### Merge

Après l'installation, vous pouvez utiliser le script `Merge` pour faciliter le processus de merge entre deux branches Git.
Assurez-vous que le terminal est ouvert dans le répertoire de votre projet, puis exécutez la commande:

```bash
Merge
```

## Contact

Pour toute question ou support, veuillez ouvrir un issue dans le dépôt GitHub du projet.
Ou me contacter par mail : [@Samuel VERSCHUEREN](8691@holbertonstudents.com)

## Authors

| [@Samuel VERSCHUEREN](https://github.com/Ezio-33) |
