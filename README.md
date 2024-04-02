<h1>Lara Immo</h1>

<h2>récup le dépot :</h2>

git clone https://github.com/DieuIramPS/github-cours-iramps.git


<h2>Installer le projet</h2>

composer update

npm install


<h2>Créer la db</h2>

Stocker les identifiants de la DB dans un bloc note


<h2>Renommer le env à la racine en .env</h2>

Et le modifier avec les informations de la db


<h2>Ensuite, garnir la db grâce aux migrations et seeder</h2>

php artisan migrate --seed


<h2>Pour finir, lancer le serveur</h2>

php artisan serv

npm run dev (lors du développement)

npm run build (une fois en production)
