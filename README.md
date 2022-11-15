Equipe back-end :
Faites votre 
```
git init
git remote add dyna3i https://github.com/KnightOfGall/dyna3i.git
git pull dyna3i master
```
Sur sa distribution linux, chacun doit exécuter la commande dans le bon répertoire xxx/dyna3i
```
docker run --rm --interactive --tty \
  --volume $PWD:/app \
  composer install
  ```
Equipe back-office :
Roy Nathan, Dudognon François, Bellemare Maxime

Equipe front-end :
Emonet Julian, Saguez Arthur

Chef de projet : 
Couillebault Gatien

```
git clone https://github.com/KnightOfGall/dyna3i.git
git remote add dyna3i https://github.com/KnightOfGall/dyna3i.git
```
Créé un fichier .env et mettre tout ce qui est dans le .env.example dedans.
Sur sa distribution linux, chacun doit exécuter la commande dans le bon répertoire xxx/dyna3i.

Pour l'équipe back-end :
```
docker run --rm --interactive --tty \
  --volume $PWD:/app \
  composer install
  ```
Démarrer le docker avec  ``` ./vendor/bin/sail up ```
Une fois démarré il faut faire 
```./vendor/bin/sail php artisan make:model Tasks -mc```
```./vendor/bin/sail php artisan make:model Comment -mc ```
```./vendor/bin/sail php artisan make:model Reply -mc```

Pour l'équipe front-end et la back-end, il faut merge sa branche en étant dans la branche master pour fusionner ces deux branches quand les modifications de son équipe a été modifié.

Différentes étapes :
Le chef de projet initialise le dossier avec le curl et le git init et donne accès aux deux équipes.
Quand les deux équipes ont le prit le projet sur Git et 
que le Laravel est installé sur leur poste, elles se lancent sur leur partie respective.

Problèmes rencontrés :
Le chef de projet a mal effectué le ```git init``` et le ```curl -s https://laravel.build/example-app | bash```
car il a mal ordonné ces deux dossiers qui étaient dans l'un dans l'autre au lieu d'être au même endroit.

Pour sail ```php artisan make:model Post -mc``` il fallut plusieurs réinstallations pour modifier post en task comment reply.
Différentes étapes :
Le chef de projet initialise tout pour donner accès aux deux équipes.
Quand les deux équipes ont le prit le projet sur Git et 
que le Laravel est installé sur leurs postes, elles se lancent sur leur partie respective.

Problèmes rencontrés :
Le chef de projet a mal effectué le ```git init``` et le ```curl -s https://laravel.build/example-app | bash``` car il a mal ordonné ces deux dossiers qui étaient dans l'un dans l'autre au lieu d'être au même endroit.
