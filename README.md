# emchateau.github.io

Page personnelle d’Emmanuel Château-Dutier

## Cloner le projet

Ce projet contient des sous-modules git

Cloner le répertoire

```bash
git clone --recursive https://github.com/publicarchi/ledoux-architecture.git
```

Mettre à jour le répertoire et ses sous-modules

```bash
git pull --recurse-submodules
```

## Déployer

Le site se déploie en utilisant une XSLT version 3.

- Exécuter `xsl/main.xsl` avec Saxon sur une branche gh-pages.
- Pousser sur la branche distante
