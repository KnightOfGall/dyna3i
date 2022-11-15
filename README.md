Equipe back-end : Roy Nathan, Dudognon François, Bellemare Maxime

Equipe front-end : Emonet Julian, Saguez Arthur

Chef de projet : Couillebault Gatien

<<<<<<< HEAD
git clone https://github.com/KnightOfGall/dyna3i.git
git remote add dyna3i https://github.com/KnightOfGall/dyna3i.git
=======
```git clone https://github.com/KnightOfGall/dyna3i.git
git remote add dyna3i https://github.com/KnightOfGall/dyna3i.git
```
>>>>>>> cd7d3e1d50bf21c10a225fce40abbf7589b418d1
Créé un fichier .env et mettre tout ce qui est dans le .env.example dedans. Sur sa distribution linux, chacun doit exécuter la commande dans le bon répertoire xxx/dyna3i.

Pour l'équipe back-end :

<<<<<<< HEAD
docker run --rm --interactive --tty \
  --volume $PWD:/app \
  composer install
Démarrer le docker avec ./vendor/bin/sail up Une fois démarré il faut faire ./vendor/bin/sail php artisan make:model Tasks -mc ./vendor/bin/sail php artisan make:model Comment -mc ./vendor/bin/sail php artisan make:model Reply -mc
=======
```
docker run --rm --interactive --tty \
  --volume $PWD:/app \
  composer install 
  ```
Démarrer le docker avec ```./vendor/bin/sail up``` Une fois démarré il faut faire ```./vendor/bin/sail php artisan make:model Tasks -mc ./vendor/bin/sail php artisan make:model Comment -mc ./vendor/bin/sail php artisan make:model Reply -mc```
>>>>>>> cd7d3e1d50bf21c10a225fce40abbf7589b418d1

Pour l'équipe front-end et la back-end, il faut merge sa branche en étant dans la branche master pour fusionner ces deux branches quand les modifications de son équipe a été modifié.

Différentes étapes : Le chef de projet initialise le dossier avec le curl et le git init et donne accès aux deux équipes. Quand les deux équipes ont le prit le projet sur Git et que le Laravel est installé sur leur poste, elles se lancent sur leur partie respective.

<<<<<<< HEAD
Problèmes rencontrés : Le chef de projet a mal effectué le git init et le curl -s https://laravel.build/example-app | bash car il a mal ordonné ces deux dossiers qui étaient dans l'un dans l'autre au lieu d'être au même endroit.

Pour sail php artisan make:model Post -mc il fallut plusieurs réinstallations pour modifier post en task comment reply.
=======
Problèmes rencontrés : Le chef de projet a mal effectué le ```git init``` et le ```curl -s https://laravel.build/example-app | bash ```car il a mal ordonné ces deux dossiers qui étaient dans l'un dans l'autre au lieu d'être au même endroit.

Pour ```sail php artisan make:model Post -mc``` il fallut plusieurs réinstallations pour modifier post en task comment reply.
>>>>>>> cd7d3e1d50bf21c10a225fce40abbf7589b418d1
