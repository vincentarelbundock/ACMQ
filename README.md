# Analyse Causale et Méthodes Quantitatives

### Vincent Arel-Bundock

Cette librairie `R` et page Github accompagnent le livre "Analyse Causale et Méthodes Quantitatives." Ce livre est [disponible gratuitement en version électronique](http://arelbundock.com/acmq.html) et à prix raisonnable [en format papier](https://www.renaud-bray.com/Livres_Produit.aspx?id=3319599&def=M%c3%a9thodes+quantitatives+et+analyse+causale%2cAREL-BUNDOCK%2c+VINCENT%2c9782760643215) (les redevances seront versées à une [OSBL](http://www.nwsm.info/)).

Ressources:

* [Table des matières et description du livre](http://arelbundock.com/acmq.html)
* [Diapos](https://github.com/vincentarelbundock/ACMQ/tree/master/diapos)
* [Exercices](https://github.com/vincentarelbundock/ACMQ/tree/master/exercices)
* [Capsules vidéos sur Youtube (13 heures)](https://youtube.com/playlist?list=PLwV5Cyu4EJ1BviLt-nWJFSTjW30Tawv2R)

Les Presses de l'Université de Montréal décrivent le livre ainsi:

> Ce livre offre une introduction intégrée à la théorie de l’analyse causale et aux méthodes quantitatives qui permettent d’évaluer les relations de cause à effet en sciences sociales. Il présente les outils classiques de l’analyse descriptive (visualisation, probabilités, statistiques descriptives, inférence statistique et régression linéaire), les cadres théoriques qui facilitent le saut entre description et causalité (modèle Neyman-Rubin et graphes orientés acycliques), les défis de l’inférence causale (biais par variable omise, de sélection, de mesure et de simultanéité) ainsi que les stratégies pour les déjouer. Les exemples tirés de plusieurs disciplines en sciences sociales sont accompagnés de syntaxes informatiques com-plètes pour R, Stata et SPSS, et des annexes de mathématiques et de statistiques viennent ici soutenir les explications données.

![](https://github.com/vincentarelbundock/ACMQ/blob/master/diapos/acmq_couverture.png)

Le reste de cette page explique comment utiliser le tutoriel interactif qui accompagne le livre.
 
# Tutoriel interactif sur le logiciel `R`

Ce tutoriel pour le logiciel `R` accompagne le livre *Analyse Causale et Méthodes Quantitatives* de Vincent Arel-Bundock. Pour commencer le tutoriel, il devez:

1. Installer les logiciels `R`, `RTools` (pour Windows), et `RStudio`.
2. Installer la librairie `acmq`.
3. Exécuter le tutoriel.

Ces trois étapes sont décrites plus bas.

## Installation: `R`, `RTools`, et `RStudio`

Sur un ordinateur Mac, Windows, ou Linux, il faut installer les deux logiciels gratuits `R` et `RStudio`:

* https://cran.r-project.org/
* https://rstudio.com/products/rstudio/download/

Sur un ordinateur Windows, il faut installer un troisième logiciel gratuit nommé `RTools`:

* https://cran.r-project.org/bin/windows/Rtools/

## Installation: librairie `acmq`

Pour installer la librairie `acmq`, il faut exécuter les commandes suivantes:

```r
install.packages('remotes')
remotes::install_github('vincentarelbundock/acmq')
```

## Exécuter le tutoriel

Quand toutes les librairies sont installées, ouvrez le logiciel `RStudio`, tapez la commande suivante dans la "Console", et exécutez la commande en appuyant sur la touche "Entrée" de votre clavier:

```r
learnr::run_tutorial('R', package = 'acmq')
```

<img width="881" alt="console" src="https://user-images.githubusercontent.com/987057/90315253-edffd700-dee7-11ea-859f-767a94e6ded6.png">

Si tout va bien, un navigateur web devrait s'ouvrir avec un tutoriel pour apprendre comment `R` fonctionne.
