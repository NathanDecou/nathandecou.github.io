---
title: Commandes utiles
---

Un ensemble de commandes qu'il peut être bon de se rappeler.

## Système de fichiers

| But                                                    | Commande                                      | Commentaire                        |
| :----------------------------------------------------- | :-------------------------------------------- | :--------------------------------- |
| Afficher la taille d'un dossier                        | `du -sh <dirpath>`                            |                                    |
| Trouver les fichiers les plus volumineux               | `find . -type f -printf '%s %p\n' \| sort -n` |                                    |
| Outil de visualisation de la taille                    | `ncdu`                                        | [lien](https://dev.yorhel.nl/ncdu) |
| Analyser uniquement les fichiers sur la même partition | `du -x <dirpath>`                             |                                    |
| Espace occupé par les systèmes de fichiers             | `df -h`                                       |                                    |
| Lister les fichiers ouverts mais supprimés             | `lsof -nP \| grep '(deleted)'`                |                                    |
