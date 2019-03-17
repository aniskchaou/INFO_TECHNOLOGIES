# POO

## Objet
**Un objet est une instance d'une classe.** On peut assimiler une classe à un type, et un objet à une variable.
Créer un objet à partir d'une classe est une opération appelée "instanciation".

## Classe

Une classe encapsule, **c'est-à-dire regroupe des propriétés et des comportements.** Par exemple, la classe Humain définit des propriétés ( deux bras, deux jambes...) et des comportements ( marcher, parler, voir...).

En OO, **les comportements sont appelés _méthodes_ et les propriétés variables d'instance.**
 Notons que les propriétés des classes peuvent elles-même être des objets. Par exemple, la propriété _bras_ de notre exemple peut être un objet de type _'Bras'._

## Notion de références

Dans les programmes, **un objet est une zone mémoire qui est pointée par une ou plusieurs références.**
 Une fois l'objet instancié, il correspond en réalité à une zone mémoire donnée. Cette zone mémoire, pour être utilisée doit être référencée.

## classe abstraite
Une classe abstraite **est une classe possédant des méthodes abstraites.**
 ***Il n'est pas possible de créer et d'utiliser une instance directe d'une classe abstraite.*** 
 Il faut utiliser une sous-classe qui implémente toutes les méthodes abstraites.

## interface

Une interface **ne contient que des méthodes abstraites.** 
Comme une classe abstraite, il n'est pas possible de créer et d'utiliser une instance directe d'une interface.

## différence

   Dans une classe abstraite, **il est possible d'avoir des méthodes concrètes qui implémentent des fonctionnalités générales ou communes**,
-   Dans certains langages de programmation où le nombre de classes mères d'une sous-classe est limité (Java, par exemple, n'autorise qu'une seule classe mère), l'implémentation d'une classe abstraite impose d'hériter de cette classe, alors qu'il est généralement possible d'implémenter plusieurs interfaces dans une classe.
- 
## instanciation
L'instanciation d'une classe c'est créer un objet ayant pour modèle la classe concernée.

Il est également possible d'allouer un objet **dynamiquement en utilisant explicitement une instruction d'allocation (généralement un opérateur nommé new)**. 
L'objet doit être libéré explicitement (C++), ou il peut être **libéré automatiquement par un ramasse-miettes** (Java, C#).

Une fois l'espace mémoire alloué à un objet, les champs de celui-ci sont initialisés par le constructeur invoqué lors de l'instanciation.

## Les trois fondamentaux de la POO

## Encapsulation
Ce principe est souvent accompagné du masquage de ces données brutes afin de s’assurer que l’utilisateur ne contourne pas l’interface qui lui est destinée. **L’ensemble se considère alors comme une boîte noire ayant un comportement et des propriétés spécifiés.**

## Héritage
 **Le terme est faire dériver la classe en une classe fille.**

_Remarque:_ Les méthodes et propriétés peuvent être héritées à un niveau n, c'est-à-dire qu'un objet peut utiliser une méthode de la mère de sa mère et ainsi de suite. 

### Les deux types de transtypages

Il existe deux types de transtypage:

-   **Le transtypage ascendant :** Ce transtypage est fait de façon implicite et n'est nécessaire que dans le cas où la classe courante possède une propriété ayant le même nom que sa classe mère et que l'on cherche à accéder à la propriété mère. 
-   Le transtypage descendant - le plus courant - qui sert à forcer une classe de type mère à être vue comme un type fille. 


## Polymorphisme
Le terme polymorphisme est également souvent associé par abus de langage au concept de polymorphisme paramétrique: **un objet peut comporter plusieurs méthodes de même nom et possédant des arguments différents.**

L’on distingue 2 types de polymorphisme, la surcharge et la redéfinition.

**la surcharge**
La surcharge est une possibilité offerte par certains langages de programmation qui permet de choisir entre **différentes implémentations d'une même fonction ou méthode** selon le nombre et le type des arguments fournis.

**la redéfinition**
La notion de polymorphie est très liée à celle d’héritage. **Grâce à la redéfinition, il est possible de redéfinir une méthode dans des classes héritant d’une classe de base.**

# Différents types de méthodes

### Constructeurs
Un constructeur est, en programmation orientée objet, **une fonction particulière appelée lors de l'instanciation.** Elle permet d'allouer la mémoire nécessaire à l'objet et d'initialiser ses attributs.

Dans de nombreux langages, on distingue certains constructeurs en particulier:
 - le constructeur par défaut n'a aucun argument ; 
 - le constructeur par   recopie a un unique argument du même type que l'objet à créer (généralement sous forme de référence constante) et il recopie les   attributs depuis l'objet passé en argument sur l'objet à créer.

### Destructeurs
En programmation orientée objet, **le destructeur d'une classe est une méthode spéciale lancée lors de la destruction d'un objet afin de récupérer les ressources (principalement la mémoire vive)** réservée dynamiquement lors de l'instanciation de l'objet. Alors qu'il peut exister plusieurs constructeurs, il ne peut exister qu'un seul destructeur.

# Visibilité

## Champs et méthodes publics
Comme leur nom l'indique, les champs et méthodes dits publics sont accessibles **depuis tous les descendants et dans tous les modules** : programme, unité...
On peut considérer que les éléments publics n'ont pas de restriction particulière.

## Champs et méthodes privés
La visibilité privée **restreint** la portée d'un champ ou d'une méthode au module **où il ou elle est déclaré(e).** 

## Champs et méthodes protégés
La visibilité **protégé** correspond à la visibilité **privé** excepté que tout champ ou méthode protégé(e) **est accessible dans tous les descendants,** quel que soit le module où ils se situent.