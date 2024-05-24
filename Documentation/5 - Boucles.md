# Doc - Boucles

### Créer une boucle simple

Une boucle est un bout de code qui se répète. Pour faire cela, on utilise la commande `répéter:` et la commande `fin si` :&#x20;

```
répéter:
// Code à répéter
fin répéter
```

### Quitter une boucle

Pour cela, on utilise la commande `stop` :&#x20;

```
répéter:
// Code à répéter
fin répéter
stop
```

### Code exemple

```
afficher "Bienvenue sur le logiciel perroquet !"
afficher "Tapez stop pour arreter !"
répéter:
demander texte
afficher texte
si texte est égal à "stop" alors:
stop
fin si
fin répéter
```
[Page 6 - Code exemple n°1](6%20-%20Exemple%20de%20code%20n°1.md)
