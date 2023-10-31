# EXO_ALOGO
checkpoint_alogo

cet algo consistera à lire une phrase se terminant par un point, caractère par caractère, et de déterminer :
le nombre de caractères
Le nombre de mots dans la phrase  et 
Le nombre de voyelles dans la phrase

lp represente le nombre de caractère c'est la dire la longueur de la phrase ,
nb_mot represente le nombre de mots,
et  nb_voy represente le nombre de voyelle.

ces 3 variables sont de type entier.

Nous recuprerons les caratères avec la variable c de type  caractère;

Nous parcourons la phrase à l'aide d'une variable i de type entier qui permet de l'incrementataion 


1: pour compter le nombre de caratère nous parcourons la phrase à chaque caratère nous faisons l'incrementation jusqu'a ce que nous arrivons au point.


2: pour compter le nombre de voyelles nous parcourons la phrase caractère par caratère nous faisons l'incrementation à chaque fois que nous rencontrons un caratère qui est identique à l'un des caratères que nous avons indiqué (soit a ou i ou e ou u ou o ou y) comme reference  jusqu'a ce que nous arrivons au point.

3: pour compter le nombre de mots  nous utilisons une variable alpha de type booleen initialisé à l'état faux
nous parcourons la phrase caratère par caractère et quand nous rencontrons un caractère qui est une lettre de l'alphabet nous declarons le booleen vrai c'est à dire que nous commencons un mot  et nous conservons cet état vrai jusqu'a ce nous rencontrons un autre caractère qui n'est pas une lettre de l'alphabet soit une virgule ou un espace ou apostrophe. donc à chaque fois que passons de l'état faux à l'état vrai nous faisons l'incrementation et continuons le parcours  jusqu'a ce que nous arrivons au point.

a la fin nous faisons l'affichage de la valeur de chaque variable 








