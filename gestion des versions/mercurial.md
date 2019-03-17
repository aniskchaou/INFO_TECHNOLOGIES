
# Git

Git est un logiciel de gestion de versions décentralisé. C'est un logiciel libre créé par Linus Torvalds, auteur du noyau Linux, et distribué selon les termes de la licence publique générale GNU version 2. En 2016, il s’agit du logiciel de gestion de versionsle plus populaire qui est utilisé par plus de douze millions de personnes

Similaire en cela à BitKeeper, Git ne repose pas sur un serveur centralisé, mais il utilise un système de connexion pair à pair. Le code informatique développé est stocké non seulement sur l’ordinateur de chaque contributeur du projet, mais il peut également l'être sur un serveur dédié.

-   git init crée un nouveau dépôt ;
    

-   git clone clone un dépôt distant ;
    
-   git  add ajoute de nouveaux objets blobs dans la base des objets pour chaque fichier modifié depuis le dernier commit. Les objets précédents restent inchangés ;
    
-   git commit intègre la somme de contrôle [SHA-1](https://fr.wikipedia.org/wiki/SHA-1) d'un objet tree et les sommes de contrôle des objets commits parents pour créer un nouvel objet commit ;
    
-   git  branch liste les branches ;
    
-   git merge fusionne une branche dans une autre ;
    

-   git rebase déplace les commits de la branche courante devant les nouveaux commits d’une autre branche ;
    
-   git log affiche la liste des commits effectués sur une branche ;
    
-   git push publie les nouvelles révisions sur le remote. (La commande prend différents paramètres) ;
    
-   git pull récupère les dernières modifications distantes du projet (depuis le Remote) et les fusionner dans la branche courante ;
    
-   git  stash stocke de côté un état non commité afin d’effectuer d’autres tâches.
    

## Sites d’hébérgement

Il existe différents sites (également appelées forges) généralistes d'hébergement, ainsi que des sites dédiés à des développements en particulier, acceptant des projets liés d'utilisateur, comme l'instance cgit de Kernel.org (noyau Linux) ou les instances Gitlab de Freedesktop.org, Gnome, KDE ou Freedesktop.org, ou encore de Blender.

-   Framagit, site communautaire associatif libre de Framasoft, basé sur Gitlab.
    
-   GitHub est un service web d'hébergement et de gestion de développement de logiciels développé en Ruby on Rails et Erlang, qui appartient à Microsoft depuis juin 2018 ;
    

-   GitLab.com équivalent à GitHub et développé en Ruby, évolution du code du service Gitorious, racheté en mars 2015, le code source est disponible et utilisé par différentes autres forges ;
    
-   GNU Savannah, permettant également l'utilisation de Mercurial, dépôt officiel de la Free Software Foundation ;
    
-   SourceForge.net, probablement le plus ancien, ouvert en 1999, il utilisait CVS à ses débuts, avant de passer à Subversion (SVN), puis récemment à git également. Il utilise aujourd'hui Apache Allura
    

## Informations

-   Développé par, Software Freedom Conservancy (en)
    

-   Première version, 7 avril 20051
    
-   Dernière version, 2.21.0 (24 février 2019)2
    
-   Dépôt, git.kernel.org/pub/scm/git/git.git
    
-   Écrit en, C, Shell Unix, Perl, Tcl, Python et C++
    
-   Système d'exploitation, Multiplateforme
    
-   Langues, Anglais
    
-   Type, Gestionnaire de code source décentralisé (en)
    
-   Licence, GPLv2
    
-   Site web, git-scm.com
    

Un changelog (anglicisme), ou journal des modifications, est une liste des modifications, généralement présentées par ordre décroissant de commit, et groupées par version.