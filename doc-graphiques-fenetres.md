# Doc - Graphiques, fenêtres

Le SimpleScript possède aussi une version logicielle graphique !

### Créer une fenêtre simple

Pour cela, on utilise la commande `fenêtre:` et `fin fenêtre` :&#x20;

```
fenêtre:
// Code de la fenêtre
fin fenêtre
```

### Modifier les paramètres de la fenêtre

Pour changer le titre de la fenêtre, on utilise la commande f.titre :&#x20;

```
fenêtre:
f.titre "Titre de ma fenêtre"
fin fenêtre
```

Pour changer la taille de la fenêtre, on utilise la commande `f.taille` on entre ensuite la taille au format XxY, la taille est en pixels :&#x20;

```
fenêtre:
f.titre "Titre de ma fenêtre"
f.taille 500x500
fin fenêtre
```

{% hint style="info" %}
Toutes les commandes spécifiques au graphique commencent par `f.` qui signifie fenêtre.
{% endhint %}
