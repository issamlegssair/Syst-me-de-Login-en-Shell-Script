# Système de Login en Shell Script

Ce projet est un mini système de login développé en Shell script sous environnement Linux Debian. Il permet à un utilisateur de s'inscrire, de se connecter, et protège les mots de passe via un hachage SHA256.

## Fonctionnalités

- Inscription d'un nouvel utilisateur avec vérification de l'existence du nom.
- Connexion sécurisée avec comparaison des mots de passe hachés.
- Stockage des utilisateurs dans un fichier local (`users.db`).
- Menu interactif simple dans le terminal.

## Prérequis

- Système Linux (testé sur Debian).
- Bash shell.
- Utilitaire `sha256sum` (généralement préinstallé).
