# Analyse de la Volatilité des Paires de Devises avec le FCFA

## Description

Ce projet analyse la volatilité des paires de devises impliquant le FCFA (Franc CFA) par rapport aux principales monnaies mondiales (Euro, Dollar, Yen, etc.). L'objectif est d'utiliser des modèles GARCH pour estimer la volatilité et déterminer les paires les plus volatiles et les plus stables. Ce projet vise à fournir des informations pratiques pour la conversion de monnaie et la gestion des risques.

## Objectif

- Analyser la volatilité des paires de devises FCFA/Euro, FCFA/Dollar, etc.
- Utiliser des modèles GARCH pour estimer la volatilité.
- Identifier les paires les plus volatiles et les plus stables.
- Fournir des stratégies adaptées à la gestion des risques pour les utilisateurs du FCFA.

## Méthodologie

1. **Collecte des données** : Les données de taux de change des paires FCFA/Euro, FCFA/Dollar, etc., sont extraites et préparées pour l'analyse.
2. **Modélisation GARCH** : Les modèles GARCH sont utilisés pour estimer la volatilité des paires de devises.
3. **Analyse des résultats** : Les paires les plus volatiles et les plus stables sont identifiées.

## Résultats Attendus

Les résultats devraient permettre de déterminer les paires de devises les plus volatiles et les plus stables, aidant ainsi à prendre des décisions éclairées concernant les conversions de devises et à proposer des stratégies de gestion des risques.

## Prérequis

- R (version 4.x ou supérieure)
- Packages R nécessaires :
  - rugarch
  - ggplot2
  - dplyr

## Installation

Clonez ce dépôt et installez les dépendances en exécutant le code suivant :

```bash
git@github.com:Naofal03/Analyse-Volatilite-FCFA-Devises.git
```

```R
install.packages(c("rugarch", "ggplot2", "dplyr", "readr", "car", "plm","gplots","corrplot","lmtest"))
```

## Comment Exécuter
1. Clonez le dépôt.
2. Exécutez le fichier sub_saharan_africa_esperance.rmd dans RStudio pour générer les résultats.
## Auteurs
- Naofal AKANHO
