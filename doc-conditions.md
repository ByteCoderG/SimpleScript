# Doc - Conditions

### Faire une condition simple

Pour cela, on utilise la commande `si` avec les options `plus grand que`, `plus petit que` ou `est égal à`. On ajoute `fin si` pour signifier la fin de la condition :&#x20;

<pre><code>si 5 <a data-footnote-ref href="#user-content-fn-1">est plus grand que</a> 1 alors:
// Code de la condition
fin si
</code></pre>

### Ajouter un sinon

Le sinon se fait avec la commande `autrement:`. Lorsque la condition sera fausse, la commande s'exécutera. Cette commande est facultative. On l'utilise comme ceci :&#x20;

```
si 5 est plus petit que 1 alors:
// Code de la condition
autrement:
// Code du autrement
fin si
```

[^1]: Vous pouvez mettre : est plus petit que/est égal à
