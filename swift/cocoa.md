## Cocoa

Cocoa est une API native d'Apple pour le développement orienté objet sur son système d'exploitation Mac OS X. C'est l'une des cinq API majeures disponibles pour Mac OS X

Les applications Cocoa sont typiquement construites en utilisant les outils de développement fournis par Apple, Xcode (anciennement Project Builder) et Interface Builder, en utilisant les langages de programmation Objective-C et Swift. 

De plus, l'environnement de programmation Cocoa peut être accessible en utilisant d'autres outils, comme Ruby (via MacRuby (en) et RubyMotion (en)) et C# (via Xamarin).

Au fil des versions de Mac OS X, on assiste à un rapprochement progressif de Cocoa et de Carbon, construits de plus en plus à partir de la même base (Core Foundation ).

## Framework principal
Cocoa est principalement constitué de deux bibliothèques Objective-C appelées frameworks.

**Foundation Kit** , ou plus simplement Foundation est apparu pour la première fois dans OpenStep. Sur Mac OS X, il est basé sur Core Foundation . Foundation est une bibliothèque orientée objet générique, fournissant des outils de manipulations de chaîne de caractères, de valeurs numériques ou encore diverses structures de données. Des outils pour le calcul distribué et les boucles événementielles ainsi que des fonctionnalités indirectement liées à l'interface graphique utilisateur sont aussi proposée par Foundation.

**Application Kit**  ou AppKit est directement hérité de l'original NeXTSTEP Application Kit. Il contient du code permettant de créer et d'interagir avec les interfaces graphiques utilisateurs. AppKit est construit comme une sur-couche de Foundation et utilise par conséquent le même préfixe « NS ».

**Core Data**  ou frameworks de persistance, il facilite l'enregistrement des objets dans un fichier, et par la suite leur chargement en mémoire