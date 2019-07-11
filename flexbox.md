Justify-content aligne les éléments horizontalement:

flex-start : Les éléments s'alignent au côté gauche du conteneur.
flex-end : Les éléments s'alignent au côté droit du conteneur.
center : Les éléments s'alignent au centre du conteneur.
space-between : Les éléments s'affichent avec un espace égal entre eux.
space-around : Les éléments s'affichent avec un espacement égal sur leurs côtés.


Align-items aligne les éléments verticalement:

flex-start : Les éléments s'alignent au haut du conteneur.
flex-end : Les éléments s'alignent au bas du conteneur.
center : Les éléments s'alignent au centre vertical du conteneur.
baseline : Les éléments s'alignent à la ligne de base du conteneur.
stretch : Les éléments sont étirés pour s'adapter au conteneur.

Align-self accepte les mêmes valeurs que align-items, mais s'applique seulement à un élément ciblé.


Align-content défini l'espacement entre plusieurs lignes:

flex-start : Les lignes sont amassées dans le haut du conteneur.
flex-end: Les lignes sont amassées dans le bas du conteneur.
center : Les lignes sont amassées dans le centre vertical du conteneur.
space-between : Les lignes s'affichent avec un espace égal entre eux.
space-around : Les lignes s'affichent avec un espace égal autour d'eux.
stretch : Les lignes sont étirées pour s'adapter au conteneur.
Comparé à align-items, align-content ne fait effet que si il y a plusieurs lignes


Flex-direction définit la direction dans laquelle les éléments sont placés dans le conteneur:

row : Les éléments sont disposés dans la même direction que le texte (vers la droite).
row-reverse : Les éléments sont disposés dans la direction opposée au texte (vers la gauche).
column : Les éléments sont disposés de haut en bas.
column-reverse : Les éléments sont disposés de bas en haut.


Order permet de définir un ordre pour l'organisation à un élément:

ex: on veut réorganiser l'ordre de 3 éléments et on veut que le premier soit
à l'emplacement du dernier on va donc sélectionner ce dernier avec CSS et lui 
appliquer la propriété order: 3, il va donc passer de la 1ère position à la dernière.
Si on veut se déplacer vers la droite le nombre sera positif et négatif si c'est vers la gauche.


Flex-wrap accepte les valeurs suivantes :

nowrap : Tous les éléments sont tenus sur une seule ligne.
wrap : Les éléments s'enveloppent sur plusieurs lignes au besoin.
wrap-reverse : Les éléments s'enveloppent sur plusieurs lignes dans l'ordre inversé.

Flex-flow permet de combiner flex-direction et flex-wrap parce que ces deux propriétés 
sont utilisées tellement souvent ensembles:

ex: on veut aligner des éléments en colonnes (flex-direction) sur plusieurs lignes (flex-wrap),
on fera uniquement flex-flow: column wrap
