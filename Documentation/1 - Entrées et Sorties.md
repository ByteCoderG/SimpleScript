# Doc - Entrée/Sortie

### Afficher du texte simple

Pour cela, on utilise la commande `afficher`, suivie du texte ou de la variable à afficher :

```
afficher "Bonjour"
```

### Récupérer une entrée utilisateur

Pour cela, on utilise la commande `demander`, suivie du nom de la variable dans laquelle sera stockée l'entrée :

```
demander exemple
```

### Programme exemple

Voici un programme qui demande le prénom puis qui l'affiche :

```
afficher "Quel est votre prénom ?"
demander prenom
afficher "Vous vous appelez" + prenom
```

### Arrêter le code/Mettre une pause dans le code

Pour mettre en pause le code, on utilise la commande `pause`. Pour arrêter le code, on utilise la commande `quitter` :&#x20;

```
// Mon code
pause
```

[Page suivante (Variables)](<2 - Variables.md>)
