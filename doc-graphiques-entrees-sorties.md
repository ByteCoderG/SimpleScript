# Doc - Graphiques, texte

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
