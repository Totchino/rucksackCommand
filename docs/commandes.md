# Listes des commandes


## GIT

* `git checkout "n°commit"` - Reviens à la version du commit
* `git checkout -b old-state "n°commit" ` - Crée une branche à partir du commit renseigné
* Pour revenir à la version actuelle, il faut refaire un git checkout
* `git stash` - Sauvegarde les modifs
* `git reset --hard "n°commit"` - Remet à zéro le répertoire de travail par rapport à la version du commit
* `git stash pop` - Applique les modif sauvegardées


## Symfony

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        commandes.md  # Les commandes listés.
        about.md  # à Propos
        ...       # Other markdown pages, images and other files.
