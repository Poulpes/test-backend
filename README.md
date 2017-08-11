# Task Manager

### Sommaire

Il s’agit ici de développer un outil simple (type Trello) qui permettra à l’utilisateur de gérer ses projets et la liste des tâches relatives à ces projets.

#### User stories à implémenter

* Je dois pouvoir sign-in/sign-up avec un email/mot de passe ou via Facebook ;
* Je dois pouvoir create/update/delete des projets ;
* Je dois pouvoir ajouter des tâches à un projet ;
* Je dois pouvoir update/delete des tâches ;
* Je dois pouvoir donner un ordre de priorité à des tâches au sein d’un projet ;
* Je dois pouvoir attribuer une deadline à une tâche ;
* Je dois pouvoir marquer une tâche comme “réalisée” ;
* Je dois pouvoir ajouter des commentaires à une tâche ;
* Je dois pouvoir supprimer un commentaire ;
* Je dois pouvoir ajouter une pièce-jointe à un commentaire ;

### Pré-requis techniques

* Il doit s’agir d’une application web :
  * Côté client, utiliser HTML5, CSS3, Materialize, JavaScript et jQuery ;
  * Côté serveur, Ruby on Rails, Postgresql ;
* Les validations doivent se faire aussi bien côté client que côté serveur ;
* L’application doit fonctionner entièrement en mode “single page” avec des requêtes AJAX (sans rechargement de la page) ;
* Il est nécessaire de gérer à la fois l’authentication ET l’authorization : l’utilisateur ne doit pouvoir accéder qu’à ses propres projets.
* L’utilisation de gems (notamment [Devise](https://github.com/plataformatec/devise) et [Pundit](https://github.com/elabs/pundit)) est recommandée.
* Même s’il s’agit d’un test de backend, toute attention portée à l’UX de l’application sera appréciée.

### Workflow

* Clone ce repo
* Commit et push le plus régulièrement possible
* Tu as 96h pour réaliser ce test. Si tu n'as pas terminé, ce n'est pas grave du tout :) L'idée est juste d'évaluer la façon dont tu travailles et tu t'organises.


