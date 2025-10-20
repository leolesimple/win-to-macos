# Étape 1 — Installer les outils de développement

## 1. Installer Homebrew
[Site officiel Homebrew](https://brew.sh)
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
## 2. Installer les dépendances principales
```bash
brew install git node python php ffmpeg
```
## 3. Installer les outils de compilation
Télécharger Xcode Command Line Tools

Si nécessaire :

```bash
softwareupdate --install-rosetta
```
(Rosetta 2 permet d’exécuter des applications Intel sur puce Apple Silicon.)


---

[⬅️ Précédent](./00-intro.md) | [📋 Sommaire](./README.md) | [Suite ➡️](./02-apps.md)
