ort: La commande sort est utilisée pour trier les lignes d'entrée. Par défaut, elle trie les lignes en ordre alphabétique. Si vous ne spécifiez pas de fichier ou d'entrée, il attendra des données à partir de l'entrée standard (clavier ou sortie d'une autre commande).

|: C'est un tuyau (pipe) qui redirige la sortie de la commande précédente (sort) vers l'entrée de la commande suivante (uniq).

uniq -u: La commande uniq est utilisée pour filtrer les lignes en supprimant les doublons adjacents. L'option -u (ou --unique) indique à uniq de ne montrer que les lignes qui n'ont pas de doublons. Cela signifie que seules les lignes uniques seront affichées, et les lignes qui apparaissent plus d'une fois consécutivement seront supprimées.

En résumé, ce script prend une liste de lignes en entrée, les trie par ordre alphabétique (ou numérique, selon le contenu) à l'aide de sort, puis supprime toutes les lignes en double pour ne conserver que les lignes uniques consécutives en utilisant uniq -u. Cela peut être utile pour trouver des éléments uniques dans une liste de données, en éliminant les doublons.
