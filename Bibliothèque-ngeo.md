[Source](http://www.camptocamp.com/actualite/ngeo-une-bibliotheque-combinant-angularjs-et-openlayers-3/)
---
- [Voir le code source ngeo](https://github.com/camptocamp/ngeo)
- [Voir les exemples](http://camptocamp.github.io/ngeo/master/)

Avec ngeo, l’objectif de Camptocamp est de faciliter et rendre efficace le développement d’applications fondées sur AngularJS et OpenLayers 3. Nous développons une bibliothèque riche et flexible, adaptée à un maximum de cas d’utilisation.

ngeo fournit un ensemble de « directives » et de « services » AngularJS. Notre objectif, dans un premier temps, n’est pas de fournir des composants haut niveau, « clé en main », mais de fournir une collection de composants élémentaires, pouvant être combinés ensemble de différentes manières, selon les besoins spécifiques de l’application.

Le code source de ngeo est disponible sur GitHub. Des exemples d’utilisation sont également disponibles sur l’espace github.io de Camptocamp.

D’autres bibliothèques Open Source combinant AngularJS et OpenLayers 3 sont disponibles, la plus actuelle et conséquente étant certainement « angular-openlayers-directive ».

L’approche prise par ngeo est très différente d’angular-openlayers-directive. En effet, cette dernière offre une API déclarative pour créer des cartes OpenLayers 3 et interagir avec ces cartes ; notamment, avec angular-openlayers-directive, la carte OpenLayers 3 n’est pas créée par le code de l’application mais par la directive « openlayers » (fournie par angular-openlayers-directive), selon les valeurs d’attribut spécifiées dans le code HTML de l’application. angular-openlayers-directive fournit donc une sur-couche déclarative à OpenLayers 3.

Contrairement à angular-openlayers-directive, ngeo ne vise pas à fournir une sur-couche à OpenLayers 3. Avec ngeo, l’application est responsable de créer la carte OpenLayers 3 ; celle-ci est créée de manière impérative, dans un « contrôleur » de l’application. Le but de ngeo n’est pas de définir une autre façon d’utiliser OpenLayers 3 ; il est de fournir les briques nécessaires au développement d’applications cartographiques riches, ainsi qu’une manière d’utiliser conjointement OpenLayers 3 et AngularJS dans une application.

Comme OpenLayers 3, le code de ngeo utilise Closure Library et est compilé avec Closure Compiler. ngeo est développé pour que les applications elles-mêmes puissent bénéficier de Closure Compiler et Closure Library. Closure Compiler permet de vérifier « statiquement » le code JavaScript et de compresser le code avec des taux de compression très importants par rapport aux outils concurrents. Notre expérience nous montre que c’est un outil précieux pour le développement d’applications d’envergure et ayant des contraintes fortes en terme de performance.

Avec ngeo, Camptocamp cible donc une bibliothèque très souple, très riche fonctionnellement, et de haute qualité. Nous espérons que cet article vous a donné envie d’en savoir plus sur cette bibliothèque. N’hésitez pas à poster vos questions ou commentaires sur la mailing list ngeo-discuss.
