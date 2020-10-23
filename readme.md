# ![microjam](https://goessner.github.io/microjam//img/icon128.png) &mu;Jam

[![marketplace](https://vsmarketplacebadge.apphb.com/version/goessner.microjam.svg)](https://marketplace.visualstudio.com/items?itemName=goessner.microjam)
[![marketplace](https://vsmarketplacebadge.apphb.com/installs-short/goessner.microjam.svg)](https://marketplace.visualstudio.com/items?itemName=goessner.microjam)
[![npm](https://img.shields.io/npm/v/microjam.svg)](https://www.npmjs.com/package/microjam)
![Dependencies](https://goessner.github.io/microjam//img/dependencies-badge.png)
[![License](https://img.shields.io/github/license/goessner/mdmath.svg)](https://github.com/goessner/microjam/blob/master/LICENSE.txt)

## Qu'est-ce que c'est ?

**&mu;Jam** permet d'utiliser *Visual Studio Code* comme un outil de création et de publication léger pour les sites web de petite et moyenne taille.

La lettre grecque " μ " se prononce " my " comme dans " micro ", " mu " comme dans " musique " ou " mee " selon le [grec moderne](https://www.thoughtco.com/the-greek-alphabet-1705558). Dans ce contexte, cela signifie simplement *tiny* ou *minimaliste*.

Ce "Jam" dans &mu;Jam vient de "Jamstack" et signifie la collection des trois attributs

* **J** avaScript
* **A** PI
* **M** arkup

Il s'agit principalement de la création de pages web statiques ou de sites web *sans serveur* et vous voudrez peut-être [en savoir plus](https://jamstack.org/) sur cette façon moderne de construire des pages web légères [ici](https://jamstack.wtf/) et [là](https://jamstack.email/).

## Que puis-je en faire ?

Si vous voulez 
* créer un site web de petite ou moyenne taille
* notez le contenu de vos pages web dans un langage facile à apprendre et à utiliser [Markdown language] (https://commonmark.org/help/)
* publier vos pages web dans votre dépôt GitHub et [pages GitHub] (https://pages.github.com/)
* faire tout cela de l'intérieur éditeur gratuit [*Visual Studio Code*](https://code.visualstudio.com/) (`vscode`)

alors l'approche minimaliste et puissante de &mu;Jam pourrait vous convaincre.

<img src="https://github.com/goessner/microjam/raw/master/img/browser-view2.png">
<br><br>
<img src="https://github.com/goessner/microjam/raw/master/img/vscode-view2.png">

## Exemples ?

Quelques modèles sont ici ...

* [microjam-simple](https://github.com/goessner/microjam-simple) &ndash ; Un modèle de site web simple pour μJam
* [microjam-tufte](https://github.com/goessner/microjam-tufte) &ndash ; A Tufte Style Template for μJam
* [microjam-docs](https://github.com/goessner/microjam-docs) &ndash ; Un thème de documentation pour μjam avec sidebar
* [microjam-g2](https://github.com/goessner/microjam-docs) &ndash ; Un thème pour μjam + g2

## Pourquoi une nouvelle approche Jamstack ?

**&mu;Jam** est un outil de création et de publication web [low code](https://en.wikipedia.org/wiki/Low-code_development_platform) destiné aux scientifiques, ingénieurs et étudiants, qui ...

> * est facile à apprendre et à utiliser.
> * ne nécessite pas de compétences en programmation web.
> * peut gérer des expressions mathématiques LaTeX en natif.
> * intègre des graphiques vectoriels statiques ou dynamiques.
> * intègre des capacités de scripting.
> * offre une prévisualisation Html confortable.
> * prend en charge différents modèles et styles.
> Permet de produire des documents de recherche de haute qualité au format pdf.
> * fait tout cela à l'intérieur d'une application professionnelle de création de notes.

Mais comme vous pouvez facilement laisser de côté les notions de *math*, *graphiques vectoriels* et *papier de recherche*, cela peut également servir vos souhaits de publication non universitaire.

Intéressé(e) ... ?  Alors [lisez la suite](https://goessner.github.io/microjam/index.html) ...

## [FAQ](https://goessner.github.io/microjam/faq.html)


## Notes de mise à jour

### [0.3.8] le 21 juin 2020
* L'organisation des fichiers de démarque dans les sous-répertoires `docs/*.md` ayant l'extension `md` sous `docs` est possible. 
* L'utilisation des sous-répertoires `docs/*.md` nécessite l'existence d'un seul élément Html `<base>` dans la section d'en-tête du modèle.
* **Breaking Change** : L'entrée `"use"` dans les sections frontmatter est renommée en `"uses"`.

### [0.3.7] le 17 juin 2020
* L'expression TeX en ligne `$$..$$` entraînera une présentation mathématique de l'affichage maintenant.
* Les éléments HTML personnalisés "g-2" et "mec-2" sont pris en charge. 