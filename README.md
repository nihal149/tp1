Projet : Gestion de Sites avec JDBC et MySQL


Ce projet est une application Java qui permet de gérer des sites en interagissant avec une base de données MySQL à l'aide de JDBC. L'application permet d'insérer des données dans une table et de récupérer ces données pour les afficher.

Fonctionnalités principales :
Insertion de données : L'application permet d'ajouter de nouveaux sites dans la base de données, chaque site étant caractérisé par un nom.

Affichage des données : Les sites déjà enregistrés dans la base de données sont récupérés et affichés dans la console.

Description des classes :

Classe Site : Représente un site avec deux attributs principaux : un identifiant unique et un nom. Elle fournit des méthodes pour définir et accéder à ces attributs.

Classe Test : Contient deux méthodes principales :

save() : Enregistre un site dans la base de données.

load() : Charge et affiche les sites enregistrés.

Pré-requis :
Un serveur MySQL avec une base de données et une table configurée pour stocker les informations sur les sites.
Une installation de Java pour exécuter le programme.

Exécution :
L'application insère plusieurs sites dans la base de données, puis affiche la liste complète des sites insérés dans la console.
