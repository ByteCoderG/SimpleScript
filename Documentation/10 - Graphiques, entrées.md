# Doc - Graphiques, entrées

### Demander du texte à l'utilisateur

Pour cela, on utilise la commande `f.demander` comme `demander` ici le texte sera enregistré dans texte :&#x20;

```
fenêtre:
f.demander texte
fin fenêtre
```

### Demander du texte à l'utilisateur personnalisé

Pour cela, on ajoute des paramètres à la commande `f.demander`, ce sont les mêmes que pour `f.afficher` à l'exeption que l'on ne choisi pas la hauteur :&#x20;

```
fenêtre:
f.demander texte, red blue 5
fin fenêtre
```
