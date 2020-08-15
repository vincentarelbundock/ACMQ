# acmq: Analyse Causale et Méthodes Quantitatives

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
