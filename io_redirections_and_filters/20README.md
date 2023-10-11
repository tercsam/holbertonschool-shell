#!/bin/bash: Cette première ligne est le shebang, indiquant que le script doit être interprété par le shell Bash.

tr -d "cC" : Cette ligne contient la commande tr avec l'option -d. La commande tr signifie "translate" (traduire) et est utilisée pour la translation de caractères, tandis que l'option -d signifie "delete" (supprimer).

"cC" est l'ensemble de caractères à supprimer. Dans ce cas, les caractères 'c' et 'C' sont spécifiés. Tous les 'c' et 'C' dans l'entrée seront supprimés.
Ainsi, lorsque vous exécutez ce script avec une entrée, il supprimera tous les 'c' et 'C' de l'entrée. Par exemple, si l'entrée est "Computer Science", la sortie sera "omputer Sien".
