# Premiers programmes - Exercices
## Exercice 1 : Affichage

Ecris un programme qui affichera à l'utilisateur au moins trois lignes de
texte de ton choix.

@[Ta solution]({"stubs": ["echo.php"], "project":"echo", "command": "/bin/bash run.sh"})

## Exercice 2 : Variables 
Voici un programme, étudie-le et réponds aux questions.
```
<?php
$a = 1;
$b = 2;
$c = 3;
$b = $c;
$c = $a;
$a = $b;
```

?[Quelle est la valeur de la variable $a à la fin du programme ?]
-[] 1
-[] 2
-[X] 3

?[Quelle est la valeur de la variable $b à la fin du programme ?]
-[] 1
-[] 2
-[X] 3

?[Quelle est la valeur de la variable $c à la fin du programme ?]
-[X] 1
-[] 2
-[] 3

## Exercice 3 : Variables
Complète le programme de sorte à afficher à l'utisateur le texte suivant : **Tu es PRENOM, tu as AGE ans et tu es METIER.**, en remplaçant PRENOM, AGE et METIER par les valeurs contenues dans les variables correspondantes.

@[Ta solution]({"stubs": ["variables.php"], "project":"variables", "command": "/bin/bash run.sh"})

## Problème : Echange de Pokemon

### Situation 
Deux enfants ont chacun une carte Pokémon qu'ils souhaitent s'échanger.

Compléte le programme qui simule l'échange des cartes. La carte du 
premier enfant et celle du second enfant sont représentées respectivement par les variables `$carte1` et `$carte2`.
A la fin du programme, la variable `$carte1` doit avoir la valeur initiale de la variable `$carte2`, et la variable `$carte2` doit avoir la valeur initiale de la variable `$carte1`.

@[Ta solution]({"stubs": ["pokemon.php"], "project":"echangePokemon", "command": "/bin/bash run.sh"})