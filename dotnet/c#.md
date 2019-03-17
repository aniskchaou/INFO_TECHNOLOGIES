## C sharp

C# est un langage de programmation orientée objet, commercialisé par Microsoft depuis 2002 et destiné à développer sur la plateforme Microsoft .NET.

Il est dérivé du C++ et très proche du Java dont il reprend la syntaxe générale ainsi que les concepts, **y ajoutant des notions telles que la surcharge des opérateurs, les indexeurs et les délégués.** Il est utilisé notamment pour développer des applications web sur la plateforme ASP.NET.


## Présentation
C# est un langage de programmation orientée objet, fortement typé, **dérivé de C et de C++**, ressemblant au langage **Java**. Il est utilisé pour développer des applications web, ainsi que des applications de bureau, des services web, des commandes, des widgets ou des bibliothèques de classes.

En C#, une application est un lot de classes où une des classes comporte une méthode Main, comme cela se fait en Java.

C# est destiné à développer sur la plateforme .NET, une pile technologique créée par Microsoft pour succéder à COM.

**Le Common Language Runtime (abr. CLR)** est le runtime utilisé par les langages de la plateforme .NET (C#, Visual Basic .NET, J#, etc.), les services fournis par la CLR sont le lancement et l'exécution de programmes, le ramasse-miettes et la gestion d'exceptions. 

Un programme pour la plateforme .NET est tout d'abord compilé en une forme intermédiaire, le MSIL, puis ce code MSIL est transformé en code machine qui sera exécuté par la CLR.

**Une bibliothèque de classes** qui permet de manipuler des fichiers, manipuler des tableaux ou des structures en arbres, accéder à Internet, créer des interfaces graphiques, accéder à des bases de données, accéder au registre Windows et beaucoup d'autres choses. La plupart des fonctionnalités sont offertes par des classes de l'espace de noms System


## Caractéristiques

C# est un langage dérivé du C++, il apporte un typage sûr, ainsi que les possibilités d'encapsulation, d'héritage et de polymorphisme des langages orientés objet. En C# tous les types sont des objets. Le langage comporte un ramasse-miettes et un système de gestion d'exceptions.

Beaucoup de possibilités de Java se retrouvent dans C# et il y a une forte ressemblance entre un code écrit en C# et le code équivalent en Java.

**En C# les variables peuvent être d'un type référence ou d'un type valeur. Les types valeur sont les types primitifs, les énumérations, les struct et les types nullable. Les types référence sont les classes, les interfaces, les tableaux et les delegate.**

**delegate**
Un delegate est une référence à une méthode qui comporte certains paramètres. Les delegates permettent d'assigner des méthodes à des variables et les passer en paramètre3.

**type nullable**
Les nullable sont des types primitifs qui peuvent en plus avoir la valeur null. Chaque type primitif T a un type nullable associé T?. Par exemple une variable de type int? peut contenir un int ou null

### Différences avec le Java
Bien que le C# soit similaire à Java, il existe des différences notables, par exemple :

 - Java n'autorise pas la surcharge des opérateurs ;
 - Java a des exceptions vérifiées, alors que les exceptions du C# ne
   sont pas vérifiées, comme en C++ ;
 - Java permet la génération automatique de la documentation HTML à
   partir des fichiers sources à l'aide des descriptions Javadoc-syntax,
   tandis que le C# utilise des descriptions basées sur le XML ;
 - Java n'a pas de langage préprocesseur ;
 - C# supporte les indexeurs, les méthodes déléguées, et les événements
   (là où Java se contente du patron de conception Observateur) ;
 - C# ne supporte pas les implémentations anonymes d'interfaces et de
   classes abstraites ;
 - C# ne supporte que les classes internes statiques ;
 - C# supporte les structures en plus des classes (les structures sont
   des types valeur : on stocke le contenu et non l'adresse) ;
 - C# utilise une syntaxe intégrée au langage (DllImport) et portable
   pour appeler une bibliothèque native, tandis que Java utilise Java
   Native Interface ;
 - C# supporte la généricité, et la machine .NET a été modifiée pour
   permettre cela (Java la supporte également, mais son implémentation a
   été réalisée dans le compilateur javac sans changer le bytecode
   Java). Plus de détails sur l'aspect théorique de cette réalisation
   peuvent être trouvés dans la référence6, diapositives 70 à 89.


**Informations**

 - Date de première version   2002
 - Paradigme   Structuré, impératif, orienté objet
 - Auteur   Microsoft
 - Dernière version  7.3 (16 avril 2018)
 - Typage   Statique, fort, nominatif
 - Dialectes   1.0, 1.1, 1.2, 2.0 (ECMA), 3.0, 3.5, 4.0, 5.0, 6.0, 7.0,
   7.1, 7.2, 7.3
 - Influencé par  C++, Java
 - A influencé Swift, Vala, F#, Kotlin, TypeScript
 - Implémentations   Microsoft .NET, Mono, DotGNU
 - Système d'exploitation  Multiplate-forme
 - Site web www.visualstudio.com [archive]
 - Extension de fichier