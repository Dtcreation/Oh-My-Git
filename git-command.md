---
title: Git config
category: Git
---

## Rappel

**Ne pas oublier : l'aide en ligne de commande.**

```shell
git help config
git help push
git help pull
git help branch
```

## Configuration

```shell
# Identity Name
git config --global user.name "SckyzO"

# Identity Email
git config --global user.email "mon_mail@mail.com"

# Editor Tool
git config --global core.editor subl

# Diff Tool
git config --global merge.tool filemerge
```

Liste des globals

```shell
git config --list
```