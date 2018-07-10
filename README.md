# Task Manager

### Sommaire

Il s’agit ici de concevoir/designer (Sketch ou Figma) puis développer un outil simple (type Trello) qui permettra à l’utilisateur de gérer ses projets et la liste des tâches relatives à ces projets.

### User stories

* Je dois pouvoir sign-in/sign-up avec un email/mot de passe ou via Facebook ;
* Je dois pouvoir create des projets ;
* Je dois pouvoir ajouter des tâches à un projet ;
* Je dois pouvoir donner un ordre de priorité à des tâches au sein d’un projet ;
* Je dois pouvoir attribuer une deadline à une tâche ;
* Je dois pouvoir marquer une tâche comme “réalisée” ;

### Pré-requis techniques

* Les maquettes sont à réaliser sur Sketch ou Figma
* Il doit s’agir d’une application web :
  * Côté client: Pas de contraintes particulières, Rails Asset Pipeline ou Webpack ;
  * Côté serveur: Ruby on Rails, Postgresql ;
* Les validations doivent se faire aussi bien côté client que côté serveur ;
* L’application doit fonctionner entièrement en mode “single page” avec des requêtes AJAX (sans rechargement de la page) ;
* L’utilisation de gems (notamment [Devise](https://github.com/plataformatec/devise) est recommandée.

### Workflow

Le test est volontairement assez dense, on en a conscience ! A toi de faire un certain nombre d'arbitrages.

Néanmoins, organise bien ton temps entre la conception/design et la partie dev et essaie de coller aux user stories. On préfère un rendu qui couvre assez bien l'ensemble des user stories avec du code soigné et une UX efficace qu'un rendu avec juste un sign-up incroyable 😉

* Réalise tes maquettes/wireframes sur Sketch ou Figma
* Clone ce repo (tu y trouveras un template minimal d'app Rails : Rails 5.1.0 / Ruby 2.4.2 / Postgresql / Simple Form / des gems de debug.)
* Commit et push le plus régulièrement possible.
* Idéalement, pense à mettre en production sur Heroku ou autre Hosting Service de ton choix
* Tu as 96h pour réaliser ce test(conception/design + dev backend et frontend). Si tu n'as pas terminé, ce n'est pas grave du tout 😉 L'idée est juste d'évaluer la façon dont tu travailles et tu t'organises.
* Bon courage 🚀
