#!/bin/bash: La première ligne, appelée "shebang," indique que le script doit être exécuté avec l'interpréteur Bash.

printf: C'est une commande qui permet de formater la sortie en utilisant une chaîne de format spécifiée.

%0.2f: C'est la chaîne de format utilisée pour spécifier la précision décimale de deux chiffres après la virgule. Plus en détail, % indique le début de la spécification de format, 0 signifie que vous voulez remplir l'espace vide avec des zéros, 2 spécifie la précision décimale de deux chiffres, et f indique que le format doit être en virgule flottante (nombre décimal).

'\n': Cela indique que vous souhaitez ajouter un saut de ligne à la fin de la sortie, de sorte que chaque nombre formaté soit affiché sur une nouvelle ligne.

$NUM: Il s'agit d'une variable qui doit être préalablement définie avec une valeur numérique. La valeur de cette variable sera formatée en utilisant la chaîne de format spécifiée.

En résumé, ce script utilise printf pour formater la valeur de la variable $NUM avec une précision décimale de deux chiffres après la virgule et affiche le résultat, suivi d'un saut de ligne. Assurez-vous que la variable $NUM est correctement définie avec une valeur numérique avant d'exécuter le script.
