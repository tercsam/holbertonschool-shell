#!/bin/bash: La première ligne, appelée "shebang," indique que le script doit être exécuté avec l'interpréteur Bash.

printf: C'est une commande qui permet de formater la sortie en utilisant une chaîne de format spécifiée.

"%x\n": C'est la chaîne de format utilisée pour spécifier que vous souhaitez afficher la valeur de $DECIMAL en notation hexadécimale. Plus en détail, % indique le début de la spécification de format, x indique que vous souhaitez afficher la valeur en notation hexadécimale, et \n indique que vous souhaitez ajouter un saut de ligne à la fin de la sortie, de sorte que chaque valeur soit affichée sur une nouvelle ligne.

$DECIMAL: Il s'agit d'une variable qui doit être préalablement définie avec une valeur décimale (base 10). La valeur de cette variable sera affichée sous forme hexadécimale en utilisant la chaîne de format spécifiée.

En résumé, ce script utilise printf pour formater la valeur de la variable $DECIMAL en notation hexadécimale et affiche le résultat, suivi d'un saut de ligne. Assurez-vous que la variable $DECIMAL est correctement définie avec une valeur décimale avant d'exécuter le script.
