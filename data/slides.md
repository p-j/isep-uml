![git](images/UML_logo.gif "Unified Modeling Language")
# Les bases du Use Case



## À quoi ça sert ?
- Identifier et illustrer les différents acteurs
- Identifier et illustrer les fonctionalités d'un système
- Identifier les liens de dépendences entre les fonctionnalités
- Délimiter le système



## Les Acteurs
![acteur](images/acteur.png "Représentation d'un acteur")

Représente un élément externe : 

- Utilisateur
- Systèmes tiers (autre ordinateur, autre programme).

Note:
L'acteur représente un élément externe qui interagit avec le système. Cet élément peut être un utilisateur ou un système tiers (autre ordinateur, autre programme).

Tous les éléments extérieurs qui stimulent le système et tous les éléments extérieurs qui sont utilisés par le système sont représentés par des acteurs.



## Les cas d'utilisations
![use-case](images/use_case.png "Représentation d'un Use Case")

- Représente une fonctionnalité du système
  - Action déclenchante
  - Déroulement(s)
  - Fin
- Se représente par une ellipse contenant un verbe à l'infinitif et éventuellement un [stéréotype](http://www.visual-paradigm.com/product/vpuml/tutorials/extendusecasediagrambystereotype.jsp).
  - Décrit la fonctionnalité
  - Exprime des contraintes

Note:
- Un cas d'utilisation représente une fonctionnalité du système.
- Cette fonctionnalité est définie par une action déclenchante, un ou plusieurs déroulements possibles et éventuellement une fin.
- Les différents déroulements aussi appelés scénarii seront modéliser par des diagrammes de séquence, d'activité ou d'état.
- Le cas d'utilisation se représente par une ellipse contenant un nom décrivant la fonctionnalité et éventuellement un [stéréotype](http://www.visual-paradigm.com/product/vpuml/tutorials/extendusecasediagrambystereotype.jsp).
- **Remarque :** Le nom du use case doit se composer d'un verbe à l'infinitif qui décrit une action. Pour que l'ensemble du modèle soit cohérent il faut choisir tous les verbes soit du point de vue du système soit du point de vue de l'utilisateur (ce qui est généralement préférable).



## Relations entre acteurs
![relations-acteurs](images/relations_acteurs.png "Représentation d'une relation entre acteurs")

- Possible de définir une relation d'héritage entre acteurs
- L'héritage transmet toutes les associations



## Exemple
![exemple](images/exemple.png "Exemple")