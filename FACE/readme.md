# Présentation générale

FACE Rennes (Fondation Agir Contre l'Exclusion) est une association spécialisée dans l'insertion professionnelle. Elle fait partie d'un réseau plus dense d'associations présentes sur tout le territoire.

Pour mener à bien sa mission d'insertion, FACE Rennes a recours à différentes méthodes et formations. L'une d'entres-elles est la réception de "flux". Un flux est une personne qui se rend physiquement aux locaux de FACE Rennes (avec ou sans rendez-vous) et qui souhaite recevoir l'expertise de l'association sur des sujets liés à l'insertion professionnelle : 

* Création d'une lettre de motivation
* Création/amélioration d'un CV
* Proposition d'offres.
* Préparation aux entretiens.
* Et bien d'autres ateliers encore.

Ces flux sont importants pour FACE et doit représenter une partie des missions de tous les salariés. Au vu des exemples d'ateliers cités précédemment, c'est une activité très chronophage et qui demande aussi une bonne gestion des informations. En effet, après un entretien à son premier passage, le flux sera assigné à un employé de FACE qui aura alors pour charge de le suivre dans son insertion profesionnelle et de faire des états de sa situation à 3, 6  et 9 mois après son insertion. Le "flux" devient alors un "suivi" et un ensemble d'entretiens entre l'employé de FACE et le "suivi" se feront jusqu'à ce que la situation professionnelle du "suivi" soit considérée comme stable ou que celui-ci n'est plus besoin des services de FACE.

FACE Rennes a 18 années d'ancienneté dans son domaine et 2 à 4 employés qui ont eux-même à charges plusieurs dizaines de flux. Ceci représente une quantité importante d'informations qui sont actuellement stockées sur un serveur peu organisé et aucune application de gestion n'y est liée, c'est aux employés de décider de son organisation. Ce manque de standard et d'interface d'application amène à des soucis quand il s'agit de retrouver des informations rapidement ou de les afficher de façon évidente, surtout quand on rajoute la liste des offres susceptibles de servir aux placements des flux.

FACE souhaite donc moderniser sa gestion des flux et demande la réalisation  d'une application "dashboard" pour un suivi efficace et facilité des flux et suivis. Cet application devra donc proposer:

* une fonction de recherche effiace et rapide qui permet de retrouver une page descriptive sur toutes les actions menées pour le flux et le suivi.
* Un agenda centralisé pour les employés de FACE (de façon que chacun connaisse les disponibilités de l'autres pour lui assigner un flux)
* Un suivi des actions menées par l'employé sur une période donnée
* Un système de mailing intégré avec envoi automatique aux dates de suivi.
* Un système de messagerie interne.
* Un système de reminder (notifications) pour les différents rendez-vous.
* Un système de gestion des fichiers et des offres d'emplois.

Les utilisateurs seront tous les employés de FACE Rennes dans un premier temps (4 employés actuellement) et on peut envisager une démocratisation de cet outil sur les autres FACE de France (64 clubs au total). Au sein des employés, il existe un corps de direction qui aura des droits supplémentaire avec une vision globale des flux par employés.

Le comité d'élaboration de cet application sera composé des employés de FACE qui exprimeront directement leurs besoins et qui seront receuillis et regroupés pour l'élaboration de ce dossier. Les développeurs en charge de ce projet seront présents dans les locaux de leurs clients, ils auront donc la possibilité d'échanger régulièrement.

Les décisions finales quant aux choix des fonctionnalités importantes de l'application seront à valider par Mustapha Laabid, directeur de FACE Rennes et devront être soumis à l'intégralité des employés de FACE Rennes.

# Exemple applicatif, cas classique : 

Afin d'éclaircir notre besoin applicatif. Vous trouverez ci-dessous trois exemples d'utilisations de l'application : 

* **Riverain Daïna** :

_Daïna a 1 an et demi d'ancienneté à FACE Rennes, elle a eu l'occaison de gérer plusieurs dizaines de suivis._

Ses premiers suivis sont terminés il a trois mois, mais elle en a encore 20 en cours et voit en moyenne deux à trois flux par semaines qui souhaite avoir des rendez-vous.

Elle a donc besoin d'avoir une visibilité sur son agenda pour leur organiser des rendez-vous et placer des rendez-vous à ses flux. Ces rendez-vous seront ensuite envoyés par mail. Si jamais elle est dans l'incapacité de s'occuper d'un flux car ses missions sont trop chargées, elle souhaite voir l'emploi du temps de ses collègues pour pouvoir les rediriger vers eux si ils ont des disponibilités... Avec leur accord!

Elle a donc besoin : 

    * D'un agenda personnel et un autre plus global.
    * Un système de mailling automatisé à la création d'un rendez-vous.
    * Une messagerie interne pour demander l'autorisation à ses collègues.

* **Sfia Agoujil**

_Sfia est en rendez-vous avec un de ses flux qu'elle n'a pas vu depuis longtemps_

Elle a besoin de connaitre les différents éléments liés à ce flux (documents et actions menées) et de rajouter de nouveaux éléments. Elle souhaite voir rapidement ces informations au cours des 5-10mns qui sépare son rendez-vous précédent et celui-ci.

Elle a donc besoin :

    * D'une fonction de recherche par nom du flux.
    * Une interface qui comprend : 
        * Un historique lié à ce flux (rendez-vous, fichiers, actions menées).
        * Une possibilité de consulter les fichiers liées à ce flux et d'en associer de nouveaux
        * Une photo du flux
        * Un résumé de sa situation (status, cours brief).

* **Mustapha Laabid**

_Mustapha est à la direction de FACE Rennes et prépare une réunion d'équipe_

En tant que membre de la direction, il souhaite consulter l'avancée des employés dans la gestion des flux (quantité, derniers rendez-vous, nombre de suivi par rapport au nombre de flux, temps). Mais il n'a que très peu de temps pour consulter ces informations.

Il a donc besoin : 

* D'une interface récapitulative des employés avec une présentation très visuelle des éléments cités plus haut.
* La possibilité de mettre des notes personnelles sur ses employés pour préparer la réunion d'équipe.
* La possibilité d'accéder à une interface plus détaillée des actions menées par l'employé.

# Environnement
 
Cette application sera utilisée quotidiennement. Et sera déployée sur un serveur local. Cette application devra être installée sur un nginx et devra respecter les normes de PHP 7.

# Charte graphique
FACE Rennes dispose d'une charte graphique, et cette application se devra de la respecter. Que ce soit les logos, couleurs ainsi que typographies.

# Exigences vis-à-vis du logiciel
Nous souhaitons avoir une application supportant tout type de visionneuse. Qu'il s'agisse d'une smartphone, d'une tablette ou d'un écran d'ordinateur. 

# Prestations et livrables annexes

Nous savons que la code académie ne peut pouvoir de prestation de service après vente.
Nous souhaitons avoir en documentation annexe : 

* Une notice d'installation
* Une spécification fonctionnelle
* Une spécification technique
* Un guide d'administration