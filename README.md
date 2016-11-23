# jiji.cat

Voici un template Jekyll, utilisé pour ma soutenance de thèse : [http://jiji.cat](http://jiji.cat).

# Installation

Il faut avoir installé `jekyll` et `sass`, par exemple :

    gem install jekyll
    gem install sass

De façon facultative, vous pouvez également installer le package [`bourbon`](https://github.com/thoughtbot/bourbon) pour mettre à jour les fichiers SASS :

    gem install bourbon
    cd _sass
    bourbon install

La commande suivante permet de lancer Jekyll (sur le port 4000 par défaut) et Sass :

    rake

Avant déploiement, vous pouvez faire `rake generate` pour générer un site sans commentaires SCSS.

## Mettre à jour Bourbon

Pour mettre à jour les fichiers SASS de Bourbon :

    cd _sass/
    bourbon update
