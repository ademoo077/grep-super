# Grep Super

**Grep Super** est une version personnalisée de la commande `grep`, conçue pour effectuer des recherches avancées et récursives dans les fichiers. Il est idéal pour les développeurs et les utilisateurs Linux qui souhaitent un outil de recherche rapide et performant.

## Fonctionnalités
- Recherche récursive dans un répertoire spécifié
- Affiche les lignes correspondantes avec leur numéro et chemin complet
- Peut être utilisé avec un répertoire spécifique ou le répertoire courant

## Prérequis

Avant de commencer, assurez-vous que votre système dispose de :
- **Linux** ou **WSL (Windows Subsystem for Linux)** installé
- **Git** installé sur votre machine

## Installation

### 1. Cloner le dépôt
Commencez par cloner ce dépôt sur votre machine locale :
```bash
git clone https://github.com/ton-utilisateur/grep-super.git
cd grep-super
````
### 2. Rendre le script exécutable
Une fois que vous avez cloné le dépôt, rendez le script exécutable :
```bash
chmod +x grep_super.sh

````
### 3.Installer le script globalement (optionnel):
Pour installer le script globalement sur votre système et pouvoir l'utiliser depuis n'importe quel répertoire :
```bash
sudo mv grep_super.sh /usr/local/bin/grep_super
```
### 4.Utilisation:
Recherche dans un répertoire spécifique :
```bash
grep_super "mot_recherche" /chemin/vers/repertoire
```

