## Création du projet: 

- invite de commande : mkdir cine_avis 
- Github new repo
- invite de commande : 
symfony new . --webapp
git remote add origin https://github.com/Mline340/Cine_avis.git
git remote -v
git init
git add .
git commit -m "init : installation Symfony"
git push -u origin master
code . (ouverture de vscode)
- Terminal Vs code
composer require symfony/security-bundle
composer require symfony/form
composer require symfony/validator
création du fichier .env.local 
paramétrage de la variable DATABASE_URL : ........
php bin/console doctrine:database:create
ajout d'adminer.php + adminer.css dans le fichier public 

