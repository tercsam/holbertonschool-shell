#!/bin/bash : Cette ligne de script indique que le script doit être interprété par le shell Bash.

chgrp school hello : Cette ligne de commande utilise la commande chgrp pour changer le groupe propriétaire du fichier "hello". En spécifiant "school" comme argument, vous indiquez que vous souhaitez que le groupe "school" devienne le nouveau groupe propriétaire du fichier "hello".

Après l'exécution de ce script, le fichier "hello" appartiendra au groupe "school". Cela signifie que les membres du groupe "school" auront les permissions définies pour le groupe sur ce fichier. Les autres permissions, telles que celles du propriétaire et des autres utilisateurs, ne sont pas affectées par cette commande, à moins que vous ne les modifiiez explicitement avec une commande supplémentaire comme chmod.
