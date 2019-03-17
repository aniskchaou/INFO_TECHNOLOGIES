Hibernate

Hibernate est un framework open source gérant la persistance des objets en base de données relationnelle.

Informations

Développé par	Red Hat
Première version	23 mai 2001
Dernière version	5.2.12 (19 octobre 2017)1
Dépôt	github.com/hibernate/hibernate-orm
Écrit en	Java
Environnement	Multiplate-forme (JVM)
Langues	anglais
Type	Mapping objet-relationnel
Licence	Licence publique générale limitée GNU
Site web	hibernate.org

Hibernate a été développé par un groupe de développeurs Java dirigés par Gavin King. L'entreprise JBoss (maintenant une division de Red Hat) a embauché les développeurs principaux d'Hibernate et a travaillé avec eux afin de maintenir et développer le produit.


Modules d'Hibernate
Hibernate se compose de plusieurs modules développés par des équipes différentes.

Core
Le module principal d'Hibernate contient les fonctionnalités clefs (principalement connues depuis la version 2 de la bibliothèque) telles que les sessions, les transactions, le cache d'objet ou le langage SQL.

Annotations
Apporte le support des annotations tel que décrit dans JSR 175. Cette approche permet d'éviter la description de la correspondance entre les champs d'une table et les champs du POJO en XML.

Entity manager
Permet le support de JSR 220 JPA par le module Core.

Shards
Ce module permet la partition horizontale du Core Hibernate.

Validator
Module de validation des contraintes d'entité de la base de données, implanté sous forme d'annotations telles que les plages de valeurs autorisées, les formats de chaine de caractères, la détection des valeurs nulles, etc.

Search
Le dernier module apporte une couche d'abstraction pour la recherche de Lucene appliquée sur les entités persistantes maintenues par Hibernate.


NHibernate : .NET et open source
NHibernate est un framework open source gérant la persistance des objets en base de données relationnelle. Il est l'implémentation .NET d'Hibernate qui a vu le jour en Java.

