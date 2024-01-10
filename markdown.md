# Cour Markdown 


<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

- [Cour Markdown](#cour-markdown)
  - [Formatage de texte](#formatage-de-texte)
    - [Mise en forme](#mise-en-forme)
    - [Les puces](#les-puces)
      - [Liste ordonnée](#liste-ordonnée)
      - [Liste non ordonnée](#liste-non-ordonnée)
  - [Les liens](#les-liens)
  - [Les images](#les-images)
  - [Gestion du code](#gestion-du-code)
  - [Les tableaux](#les-tableaux)

<!-- /code_chunk_output -->


## Formatage de texte

### Mise en forme

Texte au kilomètre.
Mise **en gras**, *en italique* ou ~~barré~~.

Pas de souligné natif, mais <span style="color: red;text-decoration:underline;">on peut le faire en HTML</span>.

Deuxième contenu.

> Ceci est une citation
> Deuxième contenu
>
> Avec saut de ligne

### Les puces

#### Liste ordonnée
1. Créer un répertoire
   1. Sous élement
   2. Encore un 
2. Rentrer dedans
3. ...

#### Liste non ordonnée

- Item 1
- Item 2
  - Sous item
  - ...

## Les liens

- [Github](https://github.com)
- [Mise en forme](#mise-en-forme)
- [Fichier 2](AH.md)


## Les images

![Texte alt](./Yuji2.png)


## Gestion du code

```
<html>
<head>
</head>
<body>
<h1>Coucou</h1>
</body>
</html>
```

La commande `git init` permet d'initialiser un dépot Git.

## Les tableaux

| Commande | Description |
| --- | --- |
|`git init` | Initialise un dépot Git |
| `git add` | Ajoute des fichiers |