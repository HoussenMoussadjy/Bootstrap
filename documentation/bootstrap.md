# Comment ça marche?

Bootstrap est un système de grille qui utilise une série de containers, de rows (rangées) et de columns  
pour disposer et aligner du contenu. 

Les *containers* permettent de centrer et de remplir horizontalement le contenu de votre site.  
On utilise des *.container* pour une disposition "responsive" ou le *.container-fluid* pour une largeur égale  
à 100% sur toutes tailles de fenêtres et d'appareils.

Les rows sont les contenants des columns. Chaque colonne est munie d'un remplissage horizontal  
pour contrôler l'espace entre elles.

Dans un agencement de grille, le contenu doit être placé à l'intérieur des colonnes et seules les colonnes  
sont les enfants directs des rows.  

Les colonnes de grille qui n'ont pas de largeur spécifié sont automatiquement réparties en largeurs égales.  
4 colonnes avec une largeur non-spécifiée sont automatiquement à 25% chacune.

Les grilles en Bootstrap sont réparties en 12 colonnes maximum. Pour répartir en parts égales 3 colonnes, on  
peut mettre un col-4 par colonne. 

Les largeurs de colonnes sont définies en pourcentage, elles prennent automatiquement la même largeur que  
leur élément parent.  

.no-gutters dans les rows nous permet d'enlever la marge naturelle entre les colonnes individuelles.

Pour avoir une une grille responsive, on a 5 breakpoints: un breakpoints par taille d'écran.  
On a les "très petits écrans" (.col-), les "petits écrans" (.col-sm-), les "écrans de taille moyenne" (.col-md-),  
les "écrans larges" (.col-lg-) et les "écrans très larges" (.col-xl-).

Quand on part d'un niveau de breakpoint, on prend ce dernier et + et ceux au-dessous ne sont
pas pris en compte. 
 

  