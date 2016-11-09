# Présentation générale

En France, près de la moitié des femmes se concentrent dans une dizaine de métiers sur 86, contre 30% pour les hommes.

12% des Français.e.s travaillent actuellement dans une filière mixte, c’est-à-dire un secteur comportant au moins 40% de professionnels femmes et hommes.

92% de femmes dans les métiers de secrétariat-bureautique
97,7% des assistantes maternelles
85,2% d’hommes en tant que techniciens et agents de maitrise
90% d’hommes, conducteurs de véhicule.
etc...

Face à celà, nous avons décidé de mener une action liée à la mixité. Un évènement aura lieu du 5 au 9 Décembre afin de promouvoir la mixité.

Dans le cadre de ce dispositif, nous aimerions pouvoir mettre en place un site internet, facile d'utilisation, pouvant être diffusé sur tous les réseaux sociaux, afin de mettre en avant l'action menée auprès de divers publics. Nous avons du mal à ce jour à cibler les publics jeunes. 

Cette application, aura pour interêt de mettre en avant des images, des textes ou encore des vidéos ciblées sur la thématique de la mixité. Ainsi que de mettre en lumière les actions que nous aurons mises en place. Nous avons pensé à une application semblable à pinterest, permettant d'avoir une rapide visibilité de l'ensemble des médias disponibles. 


# Environnement (positionnement du domaine, échanges, flux et interfaces).

Cette application web sera utilisée ponctuellement dans le cadre de l'évènement de la mixité. Mais nous souhaiterions avoir un outil de travail utilisable et reutilisable par les differents entreprenants de missions à thématiques fortes telles que celle-ci.

Cette application se devra d'être dynamique, autonome et n'a pas pour but de se connecter à de tierces applications. 

Un administrateur, ou une équipe d'administrateurs aura pour charge de maintenir le site ainsi que son contenu. 


# Description des données

L'administrateur aura pour mission d'y intégrer divers types de contenus. Chaque contenu que ce soit une vidéo, un texte, une image ou un son devra contenir : 

 * Un titre
 * Une date de création
 * Un champ de saisie pour le(s) media(s)
 * Un champ description


Chaque contenu sera séparé, ainsi ils seront tous affichés séparément sur la page d'accueil du site. 

A l'exception des images qui pourront contenir un son également. Le son associé à l'image ne saura nullement obligatoire. 

# Volumétrie

Nous ne connaissons pas à l'heure actuelle, l'impact qu'aura cette application. Mais nous aurons une équipe sujette à promouvoir ce site sur divers réseaux sociaux. 

Votre application devra donc être robuste face à des fortes sollicitations à des instants précis.

La volumétrie de données n'excèdera pas les 1000 médias pour un évènement donné.

# Fonctionnalités attendues

Cette application de type Single Page Application (SPA) contiendra un grand dashboard, dans lequel, les utilisateurs connectés (modérateurs ou administrateurs) pourront rajouter du contenu à leur guise. Les contenus seront représentés sous forme de blocs, et seront facilement reconnaissable grâce à une vignette. Chaque bloc sera modifiable en largeur et longueur afin de pouvoir personnaliser la page du dashboard.

La plupart des visiteurs ne seront pas connectés.

Si un utilisateur connecté ou non connecté clique sur un bloc, celui-ci s'agrandit afin de prendre toute la taille de la page et afficher les médias.

Attention, si un son ou une vidée est incorporée dans le bloc, le media devra se lancer automatiquement lors de l'ouverture du bloc. Une interface de contrôles du média sera affichée.

Une connection utilisateur sera requise afin qu'uniquement les organisateurs des évènements, ou l'équipe mandatée puisse rajouter du contenu. La partie d'administration doit être très intuitive. Afin d'avoir un meilleur impact sur les jeunes, nous aimerions que l'application ait un effet "gaming" dans le design.

Chaque membre disposant d'un compte sur l'application aura un rôle attitré. 
Etant donné que cette application pourra être utilisée dans plusieurs évènements par la suite, nous ne souhaiterions pas avoir des rôles définis en "dur". Mais les rôles configurables devront pouvoir permettre de gérer des droits pour : 

*  Changer le thème de l'application
*  Administrer du contenu
*  Administrer les comptes utilisateurs


## Configuration d'un thème
Certains rôles d'utilisateurs doivent permettre de configurer le thème de l'application. Ces réglages doivent être les suivants : 

* Fond de la page web : Fond Noir, Fond Blanc, Fond avec une image de son choix
* Reglage de l'effet de transparence du fond
* Format des blocs possibles à créer

## Administration du contenu
Certains rôles d'utilisateurs doivent permettre d'administrer le contenu de l'application. Nommons un contenu un "Bloc". Ce dernier doit pouvoir contenir : 

 * Un titre
 * Un permalien généré automatiquement
 * Une description
 * Une date de création
 * Un ou deux médias

Si une vidéo est définie comme média, nul autre média ne doit pouvoir être rajouté
Si une image est définir comme média, il doit être possible de rajouter un fond sonore. Et inversement.

##  Administration des utilisateurs
Certains rôles d'utilisateurs doivent permettre d'administrer les comptes utilisateurs. 
Un utilisateur doit contenir : 

* Un pseudo
* Une adresse mail
* Un mot de passe
* Un rôle
    

# Architecture technique - Rappels et précisions sur les choix techniques


// A confirmer

Cette application devant être dynamique, l'état dispose de serveurs sur lesquels nous pourront déployer la solution. 
Nous disposons de serveurs Apache 2.4.7
Nous disposons d'un PHP 5.5.9
Nous disposons d'une base de données mysql 5.5.52

Votre application se devra d'être compatible avec les versions technologiques sus-mentionnées.


# Exigences vis à vis du développement

Nous souhaitons avoir une application supportant tout type de visionneuse. Qu'il s'agisse d'une smartphone, d'une tablette ou d'un écran d'ordinateur. 
Le livrable se devra d'être léger et indépendant ainsi que facilement installable. 

# Prestations et livrables annexes

Nous savons que la code académie ne peut pouvoir de prestation de service après vente.
Nous souhaitons avoir en documentation annexe : 

* Une notice d'installation
* Une spécification fonctionnelle
* Une spécification technique

