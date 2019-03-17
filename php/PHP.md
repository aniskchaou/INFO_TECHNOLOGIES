## PHP

PHP:  Hypertext Preprocessor4, plus connu sous son sigle PHP (acronyme récursif), est un langage de programmation libre5, principalement utilisé pour produire des pages Web dynamiques via un serveur HTTP4, mais pouvant également fonctionner comme n'importe quel langage interprété de façon locale. PHP est un langage impératif orienté objet.

PHP a permis de créer un grand nombre de sites web célèbres, comme Facebook, Wikipédia, etc.6 Il est considéré comme une des bases de la création de sites web dits dynamiques mais également des applications web.

**Informations**

 - Date de première version, 1994
 - Paradigmes, Impératif, orienté objet, fonctionnel, procédural,
   réflexifet interprété
 - Auteur, Rasmus  Lerdorf
 - Développeurs, The PHP Group
 - Dernière version, 7.3.3 (7 mars 2019)
 - Typage, Dynamique, Faible
 - Influencé par, C/C++  Java  Perl 2
 - Écrit en, C
 - Système d'exploitation, Multi-plateforme
 - Licence, Licence libre :
 - Licence PHP3
 - Site web, https://secure.php.net [archive]
 - Extension de fichier, php, phtml, php4, php3, php5, phps et phar

La version actuelle est la version 7.2.9, sortie le 16 août 201816. Elle utilise Zend Engine 2 et introduit une modélisation objet plus performante, une gestion des erreurs fondée sur le modèle des exceptions, ainsi que des fonctionnalités de gestion pour les entreprises. PHP 5 apporte beaucoup de nouveautés, telles que le support de SQLite ainsi que des moyens de manipuler des fichiers et des structures XML basés sur libxml2 :

-   une API simple nommée SimpleXML ;
    
-   une API Document Object Model assez complète ;
    
-   une interface XPath utilisant les objets DOM et SimpleXML ;
    
-   intégration de libxslt pour les transformations XSLT via l'extension XSL ;
    
-   une bien meilleure gestion des objets par rapport à PHP 4, avec des possibilités qui tendent à se rapprocher de celles de Java.
    
## Utilisation

   Wiki (MediaWiki, DokuWiki...)
-   forum (phpBB, Vanilla, IPB, punBB...)
-   Systèmes de gestion de blog (Dotclear, WordPress...)
-   Systèmes de gestion de contenu (appelés aussi CMS) (SPIP, ExpressionEngine, Drupal, Xoops, Joomla, K-Box...)
-   Administration de bases de données (phpMyAdmin, phpPgAdmin, Adminer...)
-   Frameworks (Laravel, Symfony, Zend Framework, CodeIgniter, CakePHP, etc.)
    
-   Logiciel ECM (Dynacase Platform)
    
-   Logiciel BPM (Dynacase Platform)
    

-   E-commerce (PrestaShop, WooCommerce, Magento, osCommerce, etc.)
    

Dans le cas de PHP comme langage serveur, les combinaisons les plus courantes sont celles d'une plateforme LAMP (pour Linux Apache MySQL PHP) et WAMP (Windows Apache MySQL PHP). Une plate-forme WAMP s'installe généralement par le biais d'un seul logiciel qui intègre Apache, MySQL et PHP, par exemple EasyPHP, VertrigoServ, WampServer ou UwAmp. Il existe le même type de logiciels pour les plates-formes MAMP (Mac OS Apache MySQL PHP), à l'exemple du logiciel MAMP.

La réécriture du cœur de PHP, qui a abouti au Zend Engine pour PHP 4 puis au Zend Engine 2 pour PHP 5, est une optimisation. Le Zend Engine compile en interne le code PHP en bytecode exécuté par une machine virtuelle. Les projets open source APC et eAccelerator fonctionnent en mettant le bytecode produit par Zend Engine en cache afin d'éviter à PHP de charger et d'analyser les scripts à chaque requête. À partir de la version 5.5 de PHP, le langage dispose d'un cache d'opcode natif (appelé OpCache) rendant obsolète le module APC.

Il existe également des projets pour compiler du code PHP :

 - Roadsend et phc compilent du PHP en C,
 - Quercus compile du PHP en bytecode Java exécutable sur une machine
   virtuelle Java,
 - Phalanger compile du PHP en Common Intermediate  Language exécutable
   sur le Common Language Runtime du framework .NET.
