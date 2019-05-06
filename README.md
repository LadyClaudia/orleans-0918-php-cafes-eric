# Les Cafés d'Éric

## Création du site web des "Cafés d'Éric", boutique à Orléans:

### Objectifs:
* Présentation de l'activité
* Présentation de l'équipe
* Formulaire de contact
* Console d'administration du contenu du site
* Le plus de contenu administrable possible

### Languages-Framework:
* PHP 7
* HTML 5
* SCSS
* Bootstrap 4
* Symfony 4

### Contributeurs:
- Candice Bourguignon - [Candicedb](https://github.com/Candicedb)
- Mélissa Viltet - [melissaviltet](https://github.com/melissaviltet)
- Amadou Kane - [amadrocky](https://github.com/amadrocky)
- Julien Delbez - [Hakha44](https://github.com/Hakha44)
- Jessica Viel - [LadyClaudia](https://github.com/LadyClaudia)

## Installation du projet "Les Cafés d'Éric" :

* Cloner "Les Cafés d'Éric" sur votre serveur : `https://github.com/WildCodeSchool/orleans-0918-php-cafes-eric`

* Créer un fichier .env.local à partir du fichier .env et renseigner les données suivantes :
   -utilisateur,
   -mot de passe,
   -nom de la base de donnée sous ce format:`DATABASE_URL=mysql://db_user:db_password@127.0.0.1:3306/db_name`

* Installer Composer, avec la commande :
`composer install`

* Initialiser et installer yarn en suivant ce lien :
`https://yarnpkg.com/lang/en/docs/install/#debian-stable`

* Créer une base de données, avec la commande :
`php bin/console doctrine:database:create`

* Mettre à jour la base de données, avec la commande :
`php bin/console doctrine:migration:migrate`

* Exécuter Webpack, avec la commande :
`yarn encore production`
