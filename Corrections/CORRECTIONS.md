# Élements de corrections

## Séance 2.

### Questions

- **Question 6.** Vous ne pouvez utiliser un histogramme pour visualiser des variables qualitatives. Elles ne peuvent être représentées que par des diagrammes en bâtons. L'histogramme ne concerne que les variables quantitatives.

### Code

- Point de détail ! J'ai dû remplacer `dept= contenu.loc[i, "Libellé du département"]` par `dep = contenu.loc[i, "Code du département"]` pour faire fonctionner votre code.

- **Question 13.** Vous ne répondez pas à la question.

## Séance 3.

### Questions

- **Question 1.** Les variables qualitatives sont les plus générales, car vous pouvez convertir des variables quantitatives en variables qualitatives, mais l'inverse est faux.

- **Question 6.** Il manque les déciles.

### Code

- Excellent !

## Séance 4

### Questions

- Il manque quelques éléments.

### Code

- **Question 2.** non répondue

## Séance 5

### Questions

- **Question 5.** Une statistique travaillant sur la population totale est une statistique exhaustive. Une enquête exhaustive correspond à la méthode de collecte.

- **Question 8.** Vous ne faites pas une liste des tests.

### Code

- Où est la réponse à la question posée dans votre rapport ? Vous ne répondez qu'à la dernière question.

## Séance 6

### Questions

- Il manque quelques éléments.

### Code

- Où est la réponse à la question posée dans votre rapport ?

- Le graphique log-log est faux, mais je ne comprends pas pourquoi.

- Les tests sont faux. Vous avez écrit :

```
    spearman_2007 = spearmanr(r_pop2007, r_den2007)
    kendall_2007 = kendalltau(r_pop2007, r_den2007)

    spearman_2025 = spearmanr(r_pop2025, r_den2025)
    kendall_2025 = kendalltau(r_pop2025, r_den2025)
```

Il aurait fallu écrire quelque chose du type :

```
    spearman_pop = spearmanr(r_pop_2007, r_pop_2025)
    kendall_pop = kendalltau(r_pop_2007, r_pop_2025)

    spearman_dens = spearmanr(r_dens_2007, r_den_2025)
    kendall_dens = kendalltau(r_dens_2007, r_den_2025)
```

## Humanités numériques

- Analyse intéressante et bien argumentée.

## Remarques générales

- Aucun dépôt régulier sur `GitHub`.

- Attention ! Vous copiez-collez des équations en `LaTeX` dans un fichier de traitement texte.

- Attention ! Vous devez appeler votre fichier de code `main.py`. Vous comprendrez si vous faites un jour du `Python` avancé.

- Attention ! Tous les `import` se place au début du fichier, et qu'une seule fois.
