own -h vincent:staff _hello : Cette ligne de commande effectue les actions suivantes :

chown : Cette commande est utilisée pour changer le propriétaire et le groupe d'un fichier.

-h : Cette option signifie de ne pas suivre les liens symboliques. Cela garantit que les liens symboliques ne seront pas suivis, et que seuls les fichiers réels seront modifiés.

vincent:staff : C'est l'argument spécifiant le nouveau propriétaire ("vincent") et le nouveau groupe ("staff") auxquels vous souhaitez attribuer le fichier "_hello".

_hello : C'est l'argument spécifiant le fichier cible dont vous souhaitez changer le propriétaire et le groupe.

Après l'exécution de ce script, le fichier "_hello" aura été modifié pour appartenir à "vincent" en tant que propriétaire et "staff" en tant que groupe. Les autres permissions du fichier, telles que les droits de lecture, d'écriture et d'exécution, ne sont pas modifiées par cette commande, à moins que vous ne les modifiiez ultérieurement avec une autre commande comme chmod.
