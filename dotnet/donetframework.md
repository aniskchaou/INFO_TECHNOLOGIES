
# .NET Framework

Le framework .Net comprend tout ce qu'il faut pour développer, déployer, exécuter des Web Services, des applications Web et des applications Windows. 
On peut voir le framework comme une application 3-tiers :

-   Technologies pour développer des applications
-   Bibliothèque de classes du framework .Net
-   Common language runtime (CLR)

Le CLR est le moteur d'exécution du noyau .Net pour exécuter des applications. Il apporte des services tels que la sécurité d'accès de code, la gestion de la vie d'un objet, la gestion des ressources, la sûreté des types, etc

**Informations**
Développé par	Microsoft
Dernière version	4.7.1 (17 octobre 2017)1
Environnement	Windows NT 4.0, Windows 98 et supérieurs
Type	Plate-forme
Licence	MS-EULA, BCL sous licence shared Source
Site web	www.microsoft.com/net
.
## Common Language Infrastructure

Le code répondant aux spécifications CLI est dit « managed code » en anglais, littéralement « code géré », ce qui est parfois traduit abusivement par « code managé ».

L'implémentation de la CLI inclut des fonctions pour gérer les erreurs, le ramasse-miettes, la sécurité et l'interopérabilité avec le système d'exploitation (les objets COM pour Microsoft Windows, gtk pour Mono de Novell)

## Common Language Runtime
Common Language Runtime (CLR) est le nom choisi par Microsoft pour le composant de machine virtuelle du framework .NET. 
 Le CLR fait tourner une sorte de bytecode nommé Common Intermediate Language (CIL). Le compilateur à la volée transforme le code CIL en code natif spécifique au système d'exploitation. Le CLR fonctionne sur des systèmes d'exploitation Microsoft Windows.

Le CLR est composé des quatre parties suivantes :

 - Common Type System (CTS) ; 
 - Common Language Specification (CLS) ;
   Metadata ; 
   Virtual Execution System (VES).
   

## Common Intermediate Language

Dans l'environnement de programmation Microsoft, le Common Intermediate Language (CIL) est le langage de programmation de plus bas niveau qui peut être lu par un humain. Le code de plus haut niveau dans l'environnement .NET est compilé en code CIL qui est assemblé dans un code dit bytecode. CIL est un code assembleur orienté objet et pile. Il est exécuté par une machine virtuelle.
**MSIL**
C'est un jeu d'instruction indépendant du CPU généré par les compilateurs .NET, à partir de langages comme le J#, C# ou Visual Basic. Le langage MSIL est compilé avant ou pendant l'exécution du programme par le VES (Virtual Execution System), qui fait partie intégrante du CLR.


## Compilateur JIT/NGEN
Durant la compilation .NET, le code source est transformé en un code CIL portable, indépendant de la plateforme et du processeur, et appelé bytecode.
