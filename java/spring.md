# Spring

En informatique, Spring est un framework libre pour construire et définir l'infrastructure d'une application java, dont il facilite le développement et les tests.
Suite à la plainte des développeurs Spring d’un temps important passé à la configuration des beans Spring , l’équipe de Spring propose sa réponse : Spring boot.

Parmi les quatres fonctionnalités que nous allons présenter, les deux premières sont celles qui sont les plus utiles dans le quotidien du développeur.

Spring s’appuie principalement sur l’intégration de trois concepts clés :
 - l’inversion de contrôle est assurée de deux façons différentes : la
   recherche de dépendances et l'injection de dépendances
 - la programmation orientée aspect
 - une couche d’abstraction.

## la programmation orientée aspect

 
## L’inversion de contrôle :

 - La recherche de dépendance : consiste pour un objet à interroger le
   conteneur, afin de trouver ses dépendances avec les autres objets.
   C’est un cas de fonctionnement similaire aux EJBs.
 - L’injection de dépendances : cette injection peut être effectuée de
   trois manières possibles : L’injection de dépendance via le
   constructeur. L’injection de dépendance via les modificateurs
   (setters). L’injection de dépendance via une interface.

## couche d'abstraction

La couche d’abstraction permet d’intégrer d’autres frameworks et bibliothèques avec une plus grande facilité. Cela se fait par l’apport ou non de couches d’abstraction spécifiques à des frameworks particuliers. Il est ainsi possible d’intégrer un module d’envoi de mails plus facilement.

## Les modules

Spring Framework contient toutes les fonctionnalités de base pour développer des applications.

Le coeur de Spring Framework 3.0 est composé d'un ensemble d'une vingtaine de modules qui sont regroupés en plusieurs parties :

-   **Spring Core Container** : regroupe les modules de base pour mettre en oeuvre le conteneur
-   **AOP and Instrumentation** : permet de mettre en oeuvre l'AOP
-   **Data Acces/Integration** : regroupe les modules d'accès aux données
-   **Web** : regroupe les modules pour le développement d'applications web
-   **Test** : propose des fonctionnalités pour les tests automatisés avec Spring

## Spring Core

La partie Spring Core Container contient plusieurs modules :

-   Spring Core et Spring Beans : contiennent les fonctionnalités de base notamment le conteneur et des utilitaires
-   Spring Context : propose un support de la définition du context Spring (sa configuration) mais aussi des fonctionnalités de base comme le mail, l'internationalisation, JNDI, ...
-   Spring Expression Langage (SpEL) : propose un langage d'expressions pour interroger et manipuler les objets gérés par le conteneur

## AOP

La partie AOP and Instrumentation contient plusieurs parties :

-   Spring AOP : propose un support de l'AOP
-   AspectJ : propose une intégration d'AspectJ
-   Instrumentation : propose une instrumentation des classes et plusieurs implémentations de classloaders utilisés par certains serveurs d'applications

## Data Acces/Integration

La partie Data Acces/Integration contient plusieurs modules

-   Spring JDBC : propose une abstraction de l'utilisation de JDBC avec notamment une hiérarchie d'exceptions dédiées
-   Spring ORM : propose un support pour des outils de type ORM (JPA, JDO, Hibernate, iBatis)
-   Spring Transaction : propose un support déclaratif et par programmation de la gestion des transactions
-   Spring OXM : propose une abstraction pour le mapping objet/XML avec un support de JAXB, Castor, XMLBeans, JiBX et XStream
-   Spring JMS : propose des fonctionnalités pour faciliter la mise en oeuvre de JMS avec Spring

## La partie Web

La partie Web contient plusieurs modules :

-   Spring Web : propose des fonctionnalités de base pour les développements web (initialisation du conteneur, gestion des contextes, support multipart, extraction des paramètres d'une requête http, ...)
-   Spring Web-Servlet : framework pour le développement d'applications qui met en oeuvre le motif de conception MVC. Ceci permet entre autres de choisir la technologie utilisée pour la vue (JSP, Velocity, Tiles, iText, ...)
-   Spring Web-Struts : propose un support de Struts
-   Spring Web-Portlet : propose un support pour les portlets

## La partie Test

La partie Test contient un seul module :

-   Spring Test : propose un support pour les tests automatisés avec un support de JUnit et TestNG

Ces modules sont utilisés comme base pour le développement d'applications.


Spring ne respecte pas les spécifications de Java EE mais il intègre et utilise de nombreuses API de Java EE (Servlet, JMS, ...). Spring propose aussi une intégration avec certains composants de Java EE notamment les EJB.

## Fonctionnalité clé N°1 : notion de ‘Starter dependencies’

Vous dites à Spring Boot quelle fonctionnalité vous souhaitez pour votre application, et il s’assurer que les dépendances nécessaires pour cette fonctionnalité sont présentes lors de la compilation.

La dépendance maven suivante représente un ‘starter web’ :

org.springframework.boot:spring-boot-starter-web

Elle équivaut à la déclaration de l’ensemble des dépendances suivantes :

 org.springframework:spring-core

 org.springframework:spring-web

 org.springframework:spring-webmvc

 com.fasterxml.jackson.core:jackson-databind

 org.hibernate:hibernate-validator

 org.apache.tomcat.embed:tomcat-embed-core

 org.apache.tomcat.embed:tomcat-embed-el

 org.apache.tomcat.embed:tomcat-embed-logging-juli

## Fonctionnalité N°2 : configuration automatique
## Fonctionnalité N°3 : Interface ligne de commande (CLI)

## Fonctionnalité N°4 : l’Actuator

L’outil Spring Boot Actuator permet de voir et modifier les metriques d’une application Spring Boot.
Plusieurs canaux permettent d’accéder à ces métriques : REST (plus complet), JMX et shell.

## versions

Version	Date	
0.9	2002	
1.0	2003	
2.0	2006	
3.0	2009	
4.0	2013	
5.0	2017

## Informations

Développé par	Pivotal Software (en)
Première version	25 juin 20031
Dernière version	5.1.0 (8 mai 2018)2
4.3.17 (8 mai 2018)3
Dépôt	github.com/spring-projects/spring-framework
Écrit en	Java, Kotlin et Groovy
Environnement	Multiplate-forme
Type	Framework web (en)
Framework
Bibliothèque Java (d)
Licence	Licence Apache
Site web	projects.spring.io/spring-framework