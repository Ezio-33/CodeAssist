# README pour Script_Prod

## Description

Ce dépôt contient des scripts automatisés pour faciliter la gestion et la mise à jour de projets sur GitHub. Les scripts sont sécurisés et chiffrés pour protéger leur contenu.

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

## Installation

### Téléchargement et préparation

1. **Ouvrez votre terminal** : Cela peut généralement être fait en cherchant "terminal" dans les applications de votre système.

2. **Naviguez jusqu'au répertoire où vous souhaitez télécharger le script par exemple** :
   ```bash
   cd ~/Téléchargements
   ```
3. **Téléchargez le script Install_Script**:
   ```bash
   curl -o Install_Script.sh https://raw.githubusercontent.com/Ezio-33/Script_Prod/master/Install_Script.sh
   ```
4. **Rendez le script exécutable**:
   Une fois dans le dossier ou vous avez télécharger le Script d'installation
   ```bash
   chmod +x Install_Script
   ```
5. **Exécutez le script Install_Script**:
   ```bash
   ./Install_Script
   ```

## Utilisation

Après l'installation, vous pouvez utiliser git_auto pour gérer vos projets.
Assurez-vous que le terminal est ouvert dans le répertoire de votre projet, puis exécutez :

```bash
git_auto
```

## Contact

Pour toute question ou support, veuillez ouvrir un issue dans le dépôt GitHub du projet.
Ou me contacter par mail : [@Samuel VERSCHUEREN](8691@holbertonstudents.com)

## Authors

| [@Samuel VERSCHUEREN](https://github.com/Ezio-33) |
