---
title: "Approches d'optimisation topologique avec surfaces de niveaux pour la conception de structures minces élastiques"
collection: talks
category: seminar
type: "Invited talk"
permalink: /talks/2024-01-30-seminaire_lma
excerpt: ' '
#venue: "Séminaire"
paperurl: https://laboratoire-mecanique-acoustique.fr/actualites/1182-approches-d-optimisation-topologique-avec-surfaces-de-niveaux-pour-...
date: 2024-01-30
location: "Laboratoire de Mécanique et d'Acoustique (LMA), Centrale Méditerranée, Marseille, France"
---

### Résumé

Les plaques et coques sont des éléments structurels tridimensionnels dont l'épaisseur est mince par rapport aux autres dimensions. Bien qu’on les retrouve dans de nombreuses domaines industriels, ces structures ont rarement fait l’objet d’études d’optimisation topologique. Le but de cette présentation est d’illustrer une adaptation des approches d'optimisation topologique pour deux types de problèmes de conception impliquant des plaques ou des coques visant à maximiser certaines propriétés.

La première partie est consacrée à la conception optimale de panneaux micro-architecturés périodiques aux propriétés élastiques adaptables. L'étude combine l'homogénéisation périodique, la dérivée de forme d’Hadamard et la méthode de surfaces de niveaux classique dans le contexte d'interface diffuse afin de décrire systématiquement la micro-architecture optimale au sein de la cellule unitaire. Le problème d’optimisation est adapté pour contrôler le comportement effectif d’une plaque de Kirchhoff–Love, en considérant simultanément la rigidité dans le plan, la rigidité hors plan et la réponse couplée. L'efficacité de la méthode est illustrée au travers d’exemples numériques réalisés à l'aide d'une programmation interne, où la forme conçue produit un couplage extension-flexion important. Après avoir obtenu les géométries, leur réponse est numériquement évaluée sous un chargement de traction, à la fois sur le panneau périodique complet et sur sa plaque équivalente homogénéisée. Dans le régime de petites déformations, une plaque plate peut être déformée en un dôme ou une forme de selle. Les cellules unitaires obtenues sont des blocs élémentaires permettant de créer des objets directement 3D imprimables avec des capacités de changement de forme.

La deuxième partie se concentre sur la conception de structures coque sous un ensemble spécifié de conditions de chargement et de contraintes. La distribution optimale du matériau est déterminée sur la surface médiane d'une structure coque d'arrière-plan, qui reste fixe tout au long du procédé. Le matériau est représenté à l'aide d'une fonction « level set » évoluant à l'aide de l'équation de réaction- diffusion, qui permet de réduire considérablement la sensibilité par rapport à la forme initiale. Le problème d'optimisation est régularisé en introduisant une énergie d'interface fictive, qui agit comme une contrainte de minimisation du périmètre. La taille des trous imposée par les contraintes de découpe est prise en compte en ajustant la valeur du coefficient de diffusion, qui contrôle le degré de complexité des structures optimales obtenues. Une analyse de sensibilité, obtenue à partir du gradient topologique, est réalisée afin de minimiser la souplesse et/ou les contraintes au sein des structures coque. L'algorithme permet de synthétiser plusieurs structures de types coques de complexité variable, allant des surfaces courbées jusqu'aux variétés et non-variétés comprenant des plis. Le projet vise la fabrication de tôles, mais sa formulation et sa portée sont généralistes, permettant des extensions à d'autres types de matériaux et géométries de parois minces.

### References

[1] F. Agnelli, G. Nika, A. Constantinescu. (2022). &quot;Design of thin micro-architectured panels with extension–bending coupling effects using topology optimization.&quot; <i>Comput. Meth. Appl. Mech. Eng.</i> 391, 114496.
[2] F. Agnelli, A.Butscher, D.Pasini. (2024). &quot;Sensitivity analysis for shape and topology optimization of elastic shell structures.&quot; <i>in preparation.</i>