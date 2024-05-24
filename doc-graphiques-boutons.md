# Doc - Graphiques, boutons

Les boutons permettent d'effectuer des actions lorsque l'on clique dessus.

### Créer un bouton simple

Pour cela, on utilise la commande `f.bouton` suivie du texte affiché sur le bouton :&#x20;

```
fenêtre:
f.bouton "Cliquez"
fin fenêtre
```

### Ajouter une fonction à un bouton

Les boutons peuvent exécuter uniquement des fonctions (vu précédemment). Pour cela, on ajoute une virgule suivie du nom de la fonction :&#x20;

```
fenêtre:
def.fonction test
// Code de la fonction
fin fonction
f.bouton "Cliquez", test
fin fenêtre
```

### Personnaliser un bouton

Pour cela, on ajoute une seconde virgule suivie des paramètres, ce sont les mêmes que pour la fonction `f.afficher` ou `f.demander` ('couleurdutexte' 'couleurdufond' 'taille'x'taille') :&#x20;

```
fenêtre:
def.fonction test
// Code de la fonction
fin fonction
f.bouton "Cliquez", test, red blue 5x5
fin fenêtre
```
