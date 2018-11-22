# laschekina221118
Dépot du 22 Novembre 11h 25

<h3>1. Récupération du code</h3>

- Via l'invite de commande git bash (nécessite d'installer git)
- Exécuter la commande <code>git clone</code> suivi de l'url du dépot.

<h3>2. Télécharger les vendors</h3>
Avec composer
<code>php composer.phar install</code>

<h3>3. Créer la base de données</h3>

- <code>php bin/console doctrine:database:create</code>

<h3>4. Importer les tables de la base existante dans votre base</h3>
