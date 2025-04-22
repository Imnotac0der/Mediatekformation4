Mediatekformation partie Admin
Présentation
Ce site, développé avec Symfony 5.4, permet d'accéder à la modifications des formations , playlists et catégories.

Les différentes pages
Voici les 4 pages correspondant aux différents cas d’utilisation.

Page 1 : la Connexion
Lorsque l'on tente d'acceder à la partie admin, une page de connexion s'ouvre nous demandant d'entrer un login et un mot de passe.


Page 2 : Admin Formation
Page accessible dans le menu en cliquant sur le nom "Admin Formations"

Possibilité de tri croissant et decroissant des formations

Filtre de recherche de formations

Possibilité de tri croissant et decroissant des playlists liées aux formations

Filtre de recherche de playlists liées aux formations

Possibilité des tris par catégories

Possibilité de tri croissant/décroissant par date de création

Fonctionnialité ajout de formation

Bouton Edition qui mène au formulaire d'édition de la formation

Bouton de suppression

Liste de toutes les formations , avec leur playlists associés, catégories associées , date de parutions, miniature vidéos


Page 3 : Admin Playlists
Page accessible dans le menu en cliquant sur le nom "Admin Playlists"

Possibilité de tri croissant et decroissant des playlists

Filtre de recherche de playlists

Possibilité de tri croissant et decroissant des playlists en fonction du nombre de formations dans la playlist

Ajout de Playlists

Bouton Edition qui mème au formulaire d'édition de la playlist

Bouton de suppression

Liste de toutes les playlists , avec leur catégories associés, nombre de formations dans la playlist

Page 4 : Admin Catégorie
Page accessible dans le menu en cliquant sur le nom "Admin Catégories"

Ajout de catégories Noms des catégories placées en liste avec la possibilité de les supprimer grâce au bouton "supprimer" placés à coté de chaque catégorie.

Le lien de déconnexion est présent sur toutes les pages.

La base de données
La base de données exploitée par le site est au format MySQL.

Installation de l'application
Vérifier que Composer, Git et Wamserver (ou équivalent) sont installés sur l'ordinateur.
Télécharger le code et le dézipper dans www de Wampserver (ou dossier équivalent) puis renommer le dossier en "mediatekformation".
Ouvrir une fenêtre de commandes en mode admin, se positionner dans le dossier du projet et taper "composer install" pour reconstituer le dossier vendor.
Récupérer le fichier mediatekformation.sql en racine du projet et l'utiliser pour créer la BDD MySQL "mediatekformation" en root sans pwd (si vous voulez mettre un login/pwd d'accès, il faut le préciser dans le fichier ".env" en racine du projet).
De préférence, ouvrir l'application dans un IDE professionnel. 

TABLEAU DE COMPETENCES

Bloc 1 - Support et mise à disposition de services informatiques

 

B1.1 : Gérer le patrimoine informatique

 

Exploiter des référentiels, normes et standards adoptés par le prestataire informatique

Mettre en place et vérifier les niveaux d’habilitation associés à un service

Gérer des sauvegardes

Vérifier le respect des règles d’utilisation des ressources numériques

B1.2 : Répondre aux incidents et aux demandes d’assistance et d’évolution

Collecter, suivre et orienter des demandes

Traiter des demandes concernant les applications

B1.3 : Développer la présence en ligne de l’organisation

Participer à la valorisation de l’image de l’organisation sur les médias numériques en tenant compte du cadre juridique et des enjeux économiques

Référencer les services en ligne de l’organisation et mesurer leur visibilité.

Participer à l’évolution d’un site Web exploitant les données de l’organisation

B1.4 : Travailler en mode projet

Analyser les objectifs et les modalités d’organisation d’un projet

Planifier les activités

Évaluer les indicateurs de suivi d’un projet et analyser les écarts

B1.5 : Mettre à disposition des utilisateurs un service informatique

Réaliser les tests d’intégration et d’acceptation d’un service

Déployer un service

Accompagner les utilisateurs dans la mise en place d’un service
