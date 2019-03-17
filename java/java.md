# Java

Java est un langage de programmation orienté objet créé par James Gosling et Patrick Naughton, employés de Sun Microsystems, avec le soutien de Bill Joy (cofondateur de Sun Microsystems en 1982), présenté officiellement le 23 mai 1995 au SunWorld.

La société Sun a été ensuite rachetée en 2009 par la société Oracle qui détient et maintient désormais Java.

La particularité et l'objectif central de Java est que les logiciels écrits dans ce langage doivent être très facilement portables sur plusieurs systèmes d’exploitation tels que Unix, Windows, Mac OS ou GNU/Linux, avec peu ou pas de modifications, mais qui ont l'inconvénient d'être plus lourd à l'exécution (en mémoire et en temps processeur) à cause de sa machine virtuelle. Pour cela, divers plateformes et frameworks associés visent à guider, sinon garantir, cette portabilité des applications développées en Java.

## Frameworks et API

Sun fournit un grand nombre de frameworks et d’API afin de permettre l’utilisation de Java pour des usages très diversifiés.

On distingue essentiellement quatre grands frameworks :

-   Java SE (anciennement J2SE) : Ce framework est destiné aux applications pour poste de travail ;
    
-   Java EE (anciennement J2EE) : Ce framework est spécialisé dans les applications serveurs. Il contient pour ce faire un grand nombre d’API et d’extensions ;
    
-   Java ME (anciennement J2ME) : Ce framework est spécialisé dans les applications mobiles ;
    

-   Java FX (à ne pas confondre avec JavaFX) : Ce framework est spécialisé dans les applications liées aux cartes à puces et autres SmartCards. Il recouvre notamment l'ancien Java Card.
    

La persistance est fondée sur les standards :

-   JDBC (Java DataBase Connectivity) ;
    
-   JDO (Java Data Objects) ;
    
-   EJB (Enterprise Java Beans).
    

On trouve toutefois de nombreuses autres technologies, API et extensions optionnelles pour Java :

-   Java Media Framework (en) : framework multimédia, contenant notamment les API Java2D, Java 3D, JavaSound, Java advanced Imaging ;
    
-   Java Telephony API (en) ;
    
-   Java TV (en) ;
    
-   JXTA : Système de peer-to-peer reposant sur Java ;
    

-   Jini ;
    
-   JAIN ;
    
-   Java Dynamic Management Kit (en) (JMDK) ;
    
-   JavaSpeech ;
    
-   JMI ;
    

-   JavaSpaces.
    

## Automatisation

Un programme Java peut être produit avec des outils qui automatisent le processus de construction (c'est-à-dire l'automatisation de certaines tâches faisant appel à un nombre potentiellement grand de dépendances comme l'utilisation de bibliothèques, la compilation, la génération d'archives, de documentation, le déploiement, etc.). Les plus utilisés sont :

-   Apache Ant (génération portable, décrite en XML) ;
    
-   Apache Maven (génération portable, décrite en XML) ;
    

-   Gradle (génération portable, en utilisant le langage Groovy) ;
    
-   SCons (génération portable, en utilisant le langage Python).
    

Le nom « Java » n'est pas un acronyme, il a été choisi lors d'un brainstorming3 en remplacement du nom d'origine « Oak », à cause d'un conflit avec une marque existante, parce que le café (« java » en argot américain)4 est la boisson favorite de nombreux programmeurs5. Le logo choisi par Sun est d'ailleurs une tasse de café fumant.

# informations

   Date de première version, 23 mai 1995
    
-   Paradigme, Orienté objet, structuré, impératif, fonctionnel
    

-   Auteur, Sun Microsystems
    
-   Développeurs, Oracle Corporation
    
-   Dernière version, 11.0.2 (15 janvier 2019)
    
-   Typage, Statique, fort, sûr, nominatif
    
-   Influencé par, Objective-C, C++, Smalltalk, Eiffel1, Ada 83, Mesa, Modula-3, Oberon, UCSD Pascal
    

-   A influencé, C#, J#, Ada 2005, Gambas, BeanShell, Clojure, ECMAScript, Groovy, JavaScript, PHP, Kotlin, Python2, Scala, Seed7, Vala, Processing
    
-   Implémentations, Liste de JVM
    
-   Système d'exploitation, Multiplateformes
    
-   Licence, GNU GPL
    
-   Site web, www.java.com [archive]
    

-   Extensions de fichiers, .class, .jar, .jad, .java, .jmod
    

## Spécifications

## Java SE

Java, édition standard, est une plateforme normalisée, destinée au développement de logiciels pour des ordinateurs personnels ainsi que des serveurs. La plateforme comporte une suite d'interfaces de programmation, qui permettent notamment de créer des interfaces graphiques, de manipuler des bases de données, des fichiers, d'utiliser le réseau, ainsi que les annuaires.

Java Platform, Standard Edition, ou Java SE (anciennement Java 2 Platform, Standard Edition, ou J2SE), est une spécification de la plate-forme Java d'Oracle, destinée typiquement aux applications pour poste de travail1.

La plate-forme est composée, outre les API de base :

-   des API spécialisées dans le poste client (JFC et donc Swing, AWT et Java2D) ;
    
-   des API d'usage général comme JAXP (pour le parsing XML) ;
    
-   de JDBC (pour la gestion des bases de données).
    

À chaque version de Java SE correspond notamment, comme toutes les éditions Java :

-   les Java Specification  Requests (JSR), constituant les spécifications de la version considérée ;
    

Java Specification  Requests (JSR) est un système normalisé ayant pour but de faire évoluer la plate-forme Java.

-   un Java Development Kit (JDK), contenant les bibliothèques logicielles ;
    
-   un Java Runtime Environment (JRE), contenant le seul environnement d'exécution (compris de base dans le JDK).
    

## JDK

Le Java Development Kit (JDK) désigne un ensemble de bibliothèques logicielles de base du langage de programmation Java, ainsi que les outils avec lesquels le code Java peut être compilé, transformé en bytecode destiné à la machine virtuelle Java.

## JRE

-JRE : environement qui permet d'exécuter vos applications java (c'est pourquoi il y a le mot RUNtime, run veut dire exécuter, et la lettre E pour environnement dans le mot JRE), mais ne contient pas le kit d'outils pour développer des applications java.  
Donc avec JRE, vous ne pouvez pas créer des applications java, mais juste exécuter des applications java.

## La machine virtuelle

La machine virtuelle Java (abr. JVM pour Java Virtual Machine) est une simulation logicielle d'une véritable machine7. La principale tâche de la machine virtuelle est de charger en mémoire les fichiers exécutables et d'exécuter le bytecode — les instructions machine de la machine virtuelle. Il existe plusieurs modes d'exécution du bytecode
