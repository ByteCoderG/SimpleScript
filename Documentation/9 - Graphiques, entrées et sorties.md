# Doc - Graphiques, entrées/sorties

Tout comme pour la version ligne de commande, la version graphique propose des entrées et sorties :&#x20;

### Afficher du texte simple sur la fenêtre

Pour cela, on utilise la commande `f.afficher` :&#x20;

```
fenêtre:
f.afficher "Bonjour"
fin fenêtre
```

### Afficher du texte personnalisé

Pour cela, on ajoute une virgule puis les paramètres suivant à la commande `f.afficher` : (dans l'ordre) 'couleurdutexte' 'couleurdufond' 'taille'x'taille' :&#x20;

```
fenêtre:
f.afficher "Bonjour", red blue 5x5
fin fenêtre
```

{% hint style="warning" %}
Les couleurs doivent être données en anglais uniquement...
{% endhint %}

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
