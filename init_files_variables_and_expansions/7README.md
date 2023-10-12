#!/bin/bash: Cette ligne est le shebang, et elle indique que le script doit être exécuté avec l'interpréteur Bash.

export BEST=School: Cette ligne définit une variable d'environnement appelée BEST avec la valeur "School" et l'exporte dans l'environnement. Cela signifie que la variable BEST sera disponible non seulement dans ce script mais aussi pour tous les processus fils et les futurs scripts ou programmes exécutés dans le même environnement.

L'utilisation de la commande export est courante pour définir des variables d'environnement. Cela garantit que la variable est accessible de manière globale par d'autres programmes exécutés dans le même environnement. Une fois que vous exécutez ce script, la variable BEST est définie avec la valeur "School" et peut être utilisée dans ce script ou par d'autres scripts ou programmes lancés ultérieurement dans le même environnement en utilisant $BEST.

L'exportation de variables est utile lorsque vous avez besoin de partager des valeurs entre plusieurs processus ou scripts en cours d'exécution dans une session shell.
