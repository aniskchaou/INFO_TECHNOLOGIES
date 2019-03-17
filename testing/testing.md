

# Testing Logiciel

un test désigne une procédure de vérification partielle d'un système. Son objectif principal est d'identifier un nombre maximum de  problématiques du logiciel afin d'en augmenter la qualité (si les problèmes identifiés lors des tests sont corrigés).

Un test vise à mettre en évidence des défauts de l'objet testé. Cependant, il n'a pas pour finalité :
•	d'identifier la cause des erreurs,
•	de les rectifier,
•	de prouver la correction de l'objet testé.

L'activité de test d'un logiciel utilise différents types et techniques de tests pour vérifier que le logiciel est conforme à son cahier des charges (vérification du produit) et aux attentes du client (validation du produit). Elle est un des processus du développement de logiciels.

## Qualité et Test

Les phases de test dans le cycle de développement d'un produit logiciel permettent d'assurer un niveau de qualité défini en accord avec le client.

Il est alors important que ces différentes phases soient bien intégrées dans le cycle de développement sur la base de bonnes pratiques et de la rationalisation du processus

## Classification des tests

Classification selon le niveau

1-Composant
2-Intégration

3-Test système

4-Test d'acceptation 



## Classification selon le niveau d'accessibilité

Technique de conception de test de structure(boîte blanche,white box): 
technique de conception de test, en général fonctionnel, fondée sur l'analyse de la structure interne du composant ou du système.

par exemple l'exécution des branches des instructions conditionnelles. Les tests unitaires sont souvent spécifiés à l'aide de telles techniques.

•	Technique de conception de test de type boîte noire (black box) :
technique de conception de test, fonctionnel ou non, qui n'est pas fondée sur l'analyse de la structure interne du composant ou du système.

Dans les tests résultant d'une technique de conception de test de type boîte noire, les données en entrée et le résultat attendu sont sélectionnés non pas en fonction de la structure interne mais de la définition de l'objet.


## Classification selon la caractéristique

On ne peut pas être exhaustif, on se contentera de quelques exemples :
•	tests de performance: valider que les performances annoncées dans la spécification sont bien atteintes.
•	test fonctionnel: vérifier que les fonctionnalités demandées sont bien supportées.
•	test de robustesse: valider la stabilité et la fiabilité du logiciel dans le temps. Le test exploratoireest une forme de test fonctionnel.
•	test de vulnérabilité: vérification de sécurité du logiciel.
•	test de charge
•	test utilisateur
•	automatisation de test

## Activités de test

**Conception**
Cette activité consiste en la rédaction des tests qui seront joués. Elle définit pour chaque test à exécuter quels seront :
1- les pré-requis à posséder pour effectuer le test
2- les actions qu'il faudra mener
3- les résultats auxquels on s'attend.

**Exécution**
Cette activité est le test à proprement parler du logiciel. Dans le cas où un comportement inhabituel est détecté lors de cette phase, celui-ci est alors le plus souvent décrit dans une fiche d'anomalie

**Clôture ou Bilan**
 Cette activité permet de synthétiser la phase de test lorsque celle-ci est terminée.

## Documents

Le plan de tests et d'évaluation
est le document regroupant tous les tests et décrit la stratégie de test en décrivant les tests dans leur globalité: place dans le processus produit, environnement de test, types de tests, etc.

## les fiches de test

sont des documents rattachés au plan de test
Une fiche de test décrit généralement, étape par étape, les démarches à suivre pour dérouler le test, et les résultats : comportement ou réaction attendu du système à chacune de ces étapes.

## Le dossier de test

désigne un ensemble de documents regroupant les différents plans de tests avec leurs fiches, mais aussi les résultats des tests passés sur la base de ces fiches.

## Qualité logicielle

En informatique et en particulier en génie logiciel, la qualité logicielle est une appréciation globale d'un logiciel, basée sur de nombreux indicateurs.
La complétude des fonctionnalités, la précision des résultats, la fiabilité, la tolérance de pannes, la facilité et la flexibilité de son utilisation, la simplicité, l'extensibilité, la compatibilité et la portabilité, la facilité de correction et de transformation, la performance, la cohérence et l'intégrité des informations qu'il contient sont tous des facteurs de qualité

## Test d'intégration

Dans le monde du développement informatique, le test d'intégration est une phase dans les tests, qui est précédée des tests unitaires et est généralement suivi par les tests de validation

Dans le test unitaire, on vérifie le bon fonctionnement d'une partie précise d'un logiciel ou d'une portion d'un programme (appelée « unité » ou « module »), dans le test d’intégration chacun des modules indépendants du logiciel sont assemblés et testés dans l’ensemble

## Intégration continue

L'intégration continue est un ensemble de pratiques utilisées en génie logicielconsistant à vérifier à chaque modification de code source que le résultat des modifications ne produit pas de régression dans l'application développée.

Le principal but de cette pratique est de détecter les problèmes d'intégration au plus tôt lors du développement.

Pour appliquer cette technique, il faut d'abord que :
•	1-le code source soit partagé (en utilisant des logiciels de gestion de versionstels que CVS, Subversion, git, Mercurial, etc)
•	
•	les développeurs intègrent (commit) quotidiennement (au moins) leurs modifications
•	des tests d'intégration sont développés pour valider l'application (avec JUnit par exemple)


Un outil d'intégration continue est ensuite nécessaire, tel que TeamCity,CruiseControl ou Jenkins (fork de Hudson) pour le langage Java par exemple. D'autres outils, comme SonarQube ou Jacoco,

## Méthode d’approche de l’intégration

Il existe plusieurs méthodes pour les tests d’intégration dont voici les plus courants :Top-down, Bottom-up, Sandwich et Big-bang

**Top-down**
On teste les modules les plus hauts puis ceux en dessous .
On obtient donc les tests de :
•	première étape
•	1
•	seconde étape
•	1, 2 et 3
•	troisième étape
•	1, 2, 3, 4, 5 et 6
•	quatrième étape
•	1, 2, 3, 4, 5, 6, 7, 8 et 9

**Bottom-up**
On teste les modules du plus bas niveau puis ceux plus hauts qui les appellent. On obtient donc :
•	première étape
•	7
•	8
•	9
•	seconde étape
•	4
•	5, 7 et 8
•	9 et 6
•	troisième étape
•	2, 4, 5, 7 et 8
•	3, 6 et 9
•	quatrième étape
•	1, 2, 3, 4, 5, 6, 7, 8 et 9

**Big-bang**
Il s’agit d'une intégration non-incrémental . On intègre tous les modules d'un coup juste après les tests unitaires.

## Outils utilisés

Pour les applications utilisant les nouvelles technologies et donc des ateliers de génie logiciel (Eclipse - Visual Studio - JBuilder - JDeveloper...), les tests d’intégration ont évolué vers de l’intégration continue.
L’intégration continue est la fusion des tests unitaires et des tests d’intégration, car le programmeur détient toute l’application sur son poste et peut donc faire de l’intégration tout au long de son développement.

## Test unitaire

 le test unitaire (ou « T.U. », ou « U.T. » en anglais) est une procédure permettant de vérifier le bon fonctionnement d'une partie précise d'un logiciel ou d'une portion d'un programme (appelée « unité » ou « module »).
 Cependant, les méthodes Extreme programming (XP) ou Test Driven Development (TDD) ont remis les tests unitaires, appelés « tests du programmeur », au centre de l'activité de programmation.


## Extreme programming

La méthode XP préconise d'écrire les tests en même temps, ou même avant la fonction à tester (Test Driven Development).

 Ceci permet de définir précisément l'interface du module à développer. Les tests sont exécutés durant tout le développement, permettant de visualiser si le code fraîchement écrit correspond au besoin.

## Utiliser des mocks

Les mocks sont des objets permettant de simuler un objet réel de façon contrôlée ; dans certains cas, l'utilisation de mock est primordial, pour un gain de temps de couverture de code, et de fiabilité des tests  :
•	Pour simuler une base de données, un service, un web-serveur, etc., les interactions entre l'application et ces outils prennent du temps, l'utilisation de mock pour simuler leurs fonctionnements peut être un gain de temps considérable ;

Sans l'utilisation de mock le test peut retourner une erreur ne provenant pas du code qui est testé (par exemple une base de donnée).


**Frameworks xUnit** 
Le terme générique « xUnit » désigne un outil permettant de réaliser des tests unitaires dans un langage donné (dont l'initiale remplace « x » le plus souvent).
•	
•	Junit pour Java ;
•	PHPUnit , pour PHP ;

**JUnit**
est un framework de test unitaire pour le langage de programmation Java.
JUnit définit deux types de fichiers de tests. Les TestCase sont des classes contenant un certain nombre de méthodes de tests. Un TestCase sert généralement à tester le bon fonctionnement d'une classe. Une TestSuite permet d'exécuter un certain nombre de TestCase déjà définis.

**PHPUnit**
PHPUnit est un framework open source de tests unitaires dédié au langage de programmation PHP .
Il permet l'implémentation destests de régression en vérifiant que les exécutions correspondent aux assertions prédéfinies.


## Test utilisateur

Un test utilisateur, ou test d’utilisabilité, est une méthode permettant d'évaluer un produit en le faisant tester par des utilisateurs . Le plus souvent, il s'agit de produits du domaine informatique (par exemple : un logiciel ou un site web) dans le cadre de l'intervention ergonomique. 

Elle est considérée comme une démarche indispensable dans la conception de produit, car la plus efficace pour évaluer l'ergonomie d'une application ou d'un site web


## Automatisation de test

L'automatisation de test permet de jouer à volonté des tests de non-régression à la suite de la livraison d'une nouvelle version d'une application.

L'automatisation d'un test n'a de sens que si le test répond à un certain nombre de critères :
•	le test est systématique il doit être exécuté à chaque nouvelle version de l'application.
•	le test est répétitif : il est présent dans de nombreux scénarios de test.
•	le test est automatisable : il est possible techniquement de faire jouer le test par un robot.

Plusieurs éditeurs proposent à ce jour des robots de tests, par exemple Smartbear (outil : TestComplete), Selenium.


## Test de validation

Le test de validation permet de vérifier si toutes les exigences client décrites dans le document de spécification d'un logiciel, écrit à partir de la spécification des besoins, sont respectées.

Les tests de validation se décomposent généralement en plusieurs phases:
Validation fonctionnelle Les tests fonctionnels vérifient que les différents modules ou composants implémentent correctement les exigences client.
Validation solution Les tests solutions vérifient les exigences client d'un point de vue cas d'utilisation (use cases). Généralement ces tests sont des tests en volume.
Validation performance, robustesse Les tests de performance vont vérifier la conformité de la solution par rapport à ses exigences de performance

## Test de performance

Un test de performance est un test dont l'objectif est de déterminer la performance d'un système informatique.
Cette définition est donc très proche de celle de test de charge où l'on mesure le comportement d'un système en fonction de la charge d'utilisateurs simultanés. Seuls les tests de charge permettent de valider correctement une application ou un système avant déploiement, tant en Qualité de Service qu'en consommation de ressources.


## Test driven development

Le test-driven development (TDD) ou en français développement piloté par les tests est une technique de développement de logiciel qui préconise d'écrire lestests unitaires avant d'écrire le code source d'un logiciel.


## Cycle de TDD

Le cycle préconisé par TDD comporte cinq étapes :

•	écrire un premier test ;
•	vérifier qu'il échoue (car le code qu'il teste n'existe pas), afin de vérifier que le test est valide ;
•	écrire juste le code suffisant pour passer le test ;
•	vérifier que le test passe ;
•	puis réusiner le code, c'est-à-dire l'améliorer tout en gardant les mêmes fonctionnalités.

## Analyse statique de programmes

En informatique, la notion d’analyse statique de programmes couvre une variété de méthodes utilisées pour obtenir des informations sur le comportement d'un programme lors de son exécution sans réellement l'exécuter.

C'est cette dernière restriction qui distingue l'analyse statique des analyses dynamiques (comme le débugage ou le profiling) qui s'attachent, elles, au suivi de l’exécution du programme.

L’analyse statique est utilisée pour repérer des erreurs formelles de programmation ou de conception, mais aussi pour déterminer la facilité ou la difficulté à maintenir le code.

Outils d'analyse statique
SonarQube ,Squale,FindBugs

## Relecture de code(code review)

Une autre méthode d'analyse statique, parmi les plus empiriques, consiste à faire lire le code source d'une application par une personne expérimentée mais extérieure à l’équipe de développement.

Si la revue de code est depuis longtemps reconnue comme un moyen performant d'améliorer la qualité du logiciel, les organisations qui ont mis en place une démarche systématique ont longtemps été minoritaires
Revue et tests
La revue est environ 2 à 4 fois plus rapide que le test1 et offre un meilleur taux de détection des défauts : tests unitaires 25 %, tests d'intégration 45 %, revue de conception 55 %, revue de code 60 

**outils**
gerrit,openstack

## Tests système

Les tests système de logiciel ou de matériel réfèrent à un processus de test d'un système intégré afin d'évaluer sa conformité aux exigences spécifiées. 

Les tests système appartiennent à la classe des tests de type boîte noire, et en tant que tels, ne devraient exiger aucune connaissance de la conception interne du code ou de la logique

**PMD**
PMD est un framework qui permet d'analyser le code source Java. Il contient un certain nombre de règles qui assurent la qualité de code : le code inutile, lesimbrications trop complexes... Il permet d'obtenir le résultat par le biais d'un rapport.

**Bugzilla**
Bugzilla est un logiciel libre desystème de suivi de problèmesavec interface web, développé et utilisé par l'organisation Mozilla. Il permet le suivi de bogues ou de« demande d'amélioration » (RFEen anglais) sous la forme de« tickets ». Logiciel de type serveur, architecture trois tiers, il est écrit en langage Perl. 

**FindBugs**
FindBugs est un logiciel libred'analyse statique de bytecode Java. Son but est de trouver desbugs dans les programmes Java en identifiant des patternsreconnus comme étant des bugs.

## Analyse dynamique de programmes

L'analyse dynamique de programmes est une analyse réalisée sur unprogramme informatique en l'exécutant sur un vrai processeur ou un processeur virtuel. 

 L'utilisation de techniques de test logiciel telles que la couverture de code aide à s'assurer qu'un ensemble adéquat des comportements possibles du programme a été observé.

Valgrind, détecte beaucoup d'erreurs dynamiquement: fuites de mémoire,dépassement de tampon, race conditions, etc.
•	Mpatrol
•	Purify, détecteur de fuites de mémoire
•	Electric Fence stoppe l'exécution d'un programme sur l'instruction exacte qui provoque un dépassement de tampon alloué dynamiquement avec la fonctionC malloc(). Il fonctionne avec GDB.


## Behavior driven development

Behavior driven development (ou BDD) est une méthode agile qui encourage la collaboration entre les développeurs, les responsables qualités, les intervenants non-techniques et les entreprises participant à un projet de logiciel.

## Test de régression

est de régression : tests d’un programme préalablement testé, après une modification, pour s’assurer que des défauts n’ont pas été introduits ou découverts dans des parties non modifiées du logiciel. 


Ces tests sont effectués quand le logiciel ou son environnement est modifié

1-ajout de nouvelles fonctionnalités,
 2-modification de fonctionnalités existantes 
 3-modification d'un composant externe au logiciel lui-même : 
nouvelle version du système, de l'interface graphique, d'un compilateur ou d'une bibliothèque tierce qui interviennent dans son fonctionnement.

'expression non-régression est parfois employée dans un sens différent pour les logiciels dont le mécanisme d'installation garantit que l'on n'écrasera pas involontairement une version plus récente déjà installée ; c'est le cas entre autres de Python, VLC et Java
