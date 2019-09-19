# Hauteur des eucalyptus

Cet exercice utilise le jeu de données employé dans le **chapitre 1 : la régression linéaire simple** au sein du livre "Régression avec R" de Pierre-André Cornillon & Eric Matzner-Lober paru chez Springer (Paris). Une version pdf de ce chapitre est mis à votre disposition au sein de ce dépôt.

## Information sur les données

Lorsque le forestier évalue la vigueur d’une forêt, il considère souvent la hauteur des arbres qui la compose. Plus les arbres sont hauts, plus la forêt ou la plantation produit. Si l’on cherche à quantifier la production par le volume de bois, il est nécessaire d’avoir la hauteur de l’arbre pour calculer le volume de bois grâce à une formule du type « tronc de cône ». Cependant, mesurer la hauteur d’un arbre d’une vingtaine de mètres n’est pas aisé et demande un dendromètre. Ce type d’appareil mesure un angle entre le sol et le sommet de l’arbre. Il nécessite donc une vision claire de la cime de l’arbre et un recul assez grand afin d’avoir une mesure précise de l’angle et donc de la hauteur. Dans certains cas, il est impossible de mesurer la hauteur, car ces deux conditions ne sont pas réunies, ou la mesure demande quelquefois trop de temps ou encore le forestier n’a pas de dendromètre. Il est alors nécessaire d’estimer la hauteur grâce à une mesure simple, la mesure de la circonférence à 1 mètre 30 du sol.
Nous possédons des mesures sur des eucalyptus dans une parcelle plantée et nous souhaitons à partir de ces mesures élaborer un modèle de prévision de la hauteur. Les eucalyptus étant plantés pour servir de matière première dans la pâte à papier, ils sont vendus au volume de bois. Il est donc important de connaître le volume et par là même la hauteur, afin d’évaluer la réserve en matière première dans la plantation (ou volume sur pied total). Les surfaces plantées sont énormes, il n’est pas question de prendre trop de temps pour la mesure et prévoir la hauteur par la circonférence est une méthode permettant la prévision du volume sur pied. La parcelle d’intérêt est constituée d’eucalyptus de 6 ans, âge de « maturité » des eucalyptus, c’est-à-dire l’âge en fin de rotation avant la coupe. Dans cette par- celle, nous avons alors mesuré n = 1429 couples circonférence-hauteur.

## Objectif de ce travail

Nous attendons un rapport individuel sous le format d'un notebook d'analyse. Il ne s'agit pas d'un rapport scientifique conventionnel qui comprend les parties que vous connaissez bien (introduction, matériels & méthodes, but, ....). 

Votre rapport doit respecter la logique suivante : 

- but : Quelle est la question que vous vous posez ? cette information se trouve dans la section ci-dessus. 

- introduction : une introduction axée sur la biologie et l'écologie de l'arbre que vous étudiez (ajouter une photo de cette espèce est un plus). 

- analyse : Cette section doit montrer l'évoluton de votre analyse des données. (par exemple, visualisation des données par nuage de points, puis réalisation du modèle, analyse du tableau des résultats, puis analyse des résidus via les différents tableaux,...). Chaque graphiqe doit être commenté dans le texte en dessous de ce dernier.

Durant les prochains cours, vous serez amené à réaliser plusieurs modèles sur ces données, il vous suffira de faire une nouvelle partie dans votre analyse afin d'y répeter la même stratégie d'analyse. 

Le notebook d'analyse à la particularité de ne rien cacher à l'inverse d'un rapport scientifique où l'on ne va garder que la meilleure analyse. 


Les données sont mises à votre disposition au sein du dépôt dans le dossier `data`
