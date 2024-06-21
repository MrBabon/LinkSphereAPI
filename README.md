# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

## Ce qu'il faut faire lors du clonage du template.
* cliquer sur le btn 'Use this template' en haut à droite sur la page github et 'Create a new repository'
* Dans 'Owner' prendre sont compte github et ensuite ajouter un nom de projet et cliquer sur 'create repository'
* cliquer sur '<> Code' et prendre le SSH.

* Aller dans le terminal et faire
  ```Terminal
  git clone git@github.com:MrBabon/test.git
  ```
* Faire
``` Terminal
bundle
```
* Aller sur la loupe de VSCODE et rechercher linksphereapi dans la premiere barre de recherche et dans la deuxieme "Remplace" mettre le nom du nouveau projet "test" dans cette exemple
## ATTENTION
* si le nouveau projet ce nomme par exemple "rails-new-test" dans remplace mettre "rails_new_test" !
* Cela ouvrira un popup disant qu'il va avoir 8 occurences qui vont changer et faire changer

* Une fois cela fait dans le terminal mettre ceci
```Terminal
EDITOR="code --wait" rails credentials:edit
```
* Il va y avoir un popup cliquer sur 'Ouvrir'
* Fermer la page qui étais ouverte et ajouter ceci dans le terminal
``` Terminal
rails db:create db:migrate
rails s
```
## POSTMAN

* Aller sur postman et tester si tout fonctionne en commançant par signup
* login et copier le token "commence par Bearer ....."
* current_user et ajouter le token dans le header dans la colonne Authorization

## Fini 

* Une fois que tout fonctionne "response 200 partout" push sur github
  
