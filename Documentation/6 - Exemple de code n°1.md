# Doc - Code exemple n°1

### Créer un calculateur d'IMC

```
afficher "Bienvenue sur le calculateur d'IMC !"
afficher "Quel est votre poids ? (kg)"
demander poids
afficher "Quelle est votre taille ? (cm)"
demander taille
```

Ensuite, nous allons convertir les variables pour qu'elles soient ensuite considérées comme chiffres pour le calcul :&#x20;

```
afficher "Bienvenue sur le calculateur d'IMC !"
afficher "Quel est votre poids ? (kg)"
demander poids
afficher "Quelle est votre taille ? (cm)"
demander taille
convertir poids
convertir taille
```

Le calcul de l'IMC est : poids/taille\*taille. La taille doit être en mètres, on doit la convertir en mètres (on divise par 100) puis on calcule :

```
afficher "Bienvenue sur le calculateur d'IMC !"
afficher "Quel est votre poids ? (kg)"
demander poids
afficher "Quelle est votre taille ? (cm)"
demander taille
convertir poids
convertir taille
calculer taille taille / 100
calculer taille taille * taille
calculer imc poids / taille
```

On regarde si l'utilisateur est obèse ou non en utilisant la commande si. Le seuil d'obésité est de 30 :&#x20;

```
afficher "Bienvenue sur le calculateur d'IMC !"
afficher "Quel est votre poids ? (kg)"
demander poids
afficher "Quelle est votre taille ? (cm)"
demander taille
convertir poids
convertir taille
calculer taille taille / 100
calculer taille taille * taille
calculer imc poids / taille
si imc est plus grand que 30 alors:
afficher "Vous êtes obèse"
autrement:
afficher "Vous n'êtes pas obèse !"
fin si
```
