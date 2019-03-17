# Les Bonnes pratiques en programmation

## Tester régulièrement son code:

tu devras, après chaque modification de ton code, tester (e.g. lancer le pro-﻿gramme) la nouvelle partie pour vérifier qu’elle fonctionnecomme envisagé. Il faudra également vérifier que lenouveau code ne modifie pas en mal le comportement du reste du programme.

## Compiler régulièrement son code:

tu devras recompiler ton projet à chaque ajout de fonctionsou de blocsd’instructions. Après chaque compilation, tu devras lire et comprendre les messages affichés par le compilateur.Le cas échéant, tu devras directement corriger les erreurs (erreurs de syntaxe, warnings, etc.) relevés par le com-pilateur.

## Découper son code en petites fonctions:

 tu devras agencer ton code en petites fonctions simples et bien spé-cifiques. Plus une fonction est conséquente, moins elle devient compréhensible. Ta fonction principale (main)devra se trouver au début du fichier principal de ton code.7.

## Découper son code en plusieurs fichiers:

tu devras découper ton code en plusieurs fichiers de manièreà ceque chacun d’eux regroupe les fonctions spécifiques à un thème. De plus, tu devras utiliser un fichier en-tête(généralement .h) qui comportera les différentsinclude, définition des structures et prototypes des fonctions.


## Déclarer correctement les variables:

tu devras déclarer tes variables au début de chaque fonction ou blocd’instructions. Ne déclare qu’une variable par ligne. Initialise chaque variable directement par la valeur adéquate(NULL dans le cas d’un pointeur). Jamais, au grand jamais tu n’utiliseras de variables globales.

Exemple de mauvaises déclarations de variables :﻿

int main(void){
int val, num1, wcount = 0;char*table,*printcolor;

Les mêmes variables déclarées correctement :
int main(void){
int val    = 0;
int num1   = 0;
int wcount = 0;
float result = 0;
char*table = NULL;
char*printcolor = NULL;




## Respecter une taille de ligne maximale:

tu devras t’assurer qu’aucune ligne de ton programme ne fasse pasplus de 80 caractères. Au delà de cette limite, tu poursuivras ton instruction sur la ligne suivante. 

Si nécessaire,tu appliqueras la coupure après un opérateur.

printf("Nombre d’années : %d%d, Nombre de mois : %d\n", years1, ...

deviendra (par ex.) :
printf("Nombre d’années : %d%d, "
"Nombre de mois : %d\n"
,﻿years1, years2, month);



## Placer correctement les accolades:

tu devras, à chaque nouveau bloc d’instructions (fonction, boucle, etc.),délimiter ce bloc par des accolades. Elles devront être placées sur une ligne seule et sur la même colonne. 

Tudevras utiliser des accolades même pour une unique instruction.Exemple d’un mauvais placement des accolades :

for(i=0; i<n, i++) 
{...}
for(j=1; j<k; j++)
printf("salut\n");
while(i>n)
{....}


Après correction :
for(i=0; i<n, i++){
...
}
for(j=1; j<k; j++){
   printf("salut\n");
}
while(i>n){
....
}

## Indenter son code:

tu devras, à chaque nouveau bloc d’instruction, introduire un retrait par rapport à la ligneprécédente. Les nouveaux blocs d’instructions débutent généralement à la suite d’une accolade ouvrante. Lataille du retrait sera toujours de 4 espaces.

Exemple : le code suivant n’est pas indenté

if (unlikely(prev->policy == SCHED_RR))
{
if (!prev->counter)
{
prev->counter = NICE_TO_TICKS(prev->nice);
move_last_runqueue(prev);
}
}


Après indentation, il deviendra :

if (unlikely(prev->policy == SCHED_RR))
{
	if (!prev->counter)
	{
	    prev->counter = NICE_TO_TICKS(prev->nice);
	    move_last_runqueue(prev);
	}
}

## Commenter son code:

 tu devras, avant même l’écriture d’une fonction ou d’un bloc d’instructions, détailler﻿l’utilité de la fonction (ou du bloc d’instructions). Dans le cas d’une fonction, l’ajout supplémentaire d’un des-criptif des paramètres ainsi que de la valeur de retour de la fonction paraît une bonne idée. Le formalisme àadopter est celui utilisé par l’outildoxygen1qui permet de générer automatiquement de la documentation àpartir d’un code source. De même, vous devrez ajouter un en-tête descriptif dans chaque fichier source. Astuce :privilégiez les commentaires en anglais

## Éviter les conditionnelles négatives

Les expressions négatives sont plus difficiles à comprendre que les expressions positives


## Nombre de méthodes

Une classe avec de trop nombreuses méthodes est une bonne cible de réusinage .
Cela permet de réduire sa complexité et d’avoir des objets d’une granularité plus fine.

## Éviter les affectations dans les conditions des structures de controles

Une règle simple, qui évite de nombreuses erreurs de programmation : éviter d’utiliser l’affectation
dans la condition d’une structure de controle

## Éviter les opérateurs ternaires

Les opérateurs ternaires sont jugés difficiles à lire par certains programmeurs. On préfère les éviter,
d’autant plus qu’ils sont imbricables les uns dans les autres.
