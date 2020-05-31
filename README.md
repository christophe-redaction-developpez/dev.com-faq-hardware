# dev.com-faq-hardware

Bienvenue sur le projet communautaire de FAQ Hardware !

Cette FAQ est publiée sur [Developpez.com](https://hardware.developpez.com/faq/), tout en restant disponible sur GitHub. Toute contribution est bienvenue !

## Contribuer

L'édition est possible en forkant le projet et en effectuant une pull request ou simplement en utilisant l'interface Web de GitHub.
> La FAQ s'écrit au [format MarkDown](https://www.markdownguide.org/basic-syntax).

### Modifier une question/réponse

La modification d'une question/réponse est simple. Il suffit d'éditer le fichier correspondant à la question/réponse, que vous pouvez facilement retrouver dans le [sommaire](faq-content/SUMMARY.md).

### Ajouter une question/réponse

L'ajout d'une question/réponse se fait en créant un nouveau fichier nommé `XXX.qYYY.md` (où `XXX` renseigne le numéro de section et `YYY` le numéro de la question/réponse (c'est-à-dire, sa place dans la section)).
Le fichier de question/réponse doit contenir les méta données suivantes :
```
---
createDate: 2007-09-28
lastUpdateDate: 2007-09-28
author: Nom-ou-pseudo
keywords: série, de, mot, clés
---

# FAQ Hardware pour developpez.com

## Titre de votre question/réponse
```

Ensuite, il n'y a plus qu'à écrire la question/réponse au format MarkDown.

### Ajouter une section

L'ajout d'une section s'effectue en ajoutant un nouveau dossier nommée `section-XXX` dans le dossier ./faq-content/. Pour les sous-sections, il faut nommer le dossier `section-XXX-YYY` où `XXX` indique le numéro de la section parent.
Ensuite, le dossier de la section doit **obligatoirement** contenir un fichier `000.title.md` contenant le titre de la section :
```
# Titre de la section
```
