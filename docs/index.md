Mon memo pour l'utilisation de [MkDocs](https://www.mkdocs.org/), avec le theme 
[Material pour MkDocs](https://squidfunk.github.io/mkdocs-material/) et l'environnement [Mkdocs-et](http://pageperso.lif.univ-mrs.fr/~edouard.thiel/mkdocs-et/) d'[Edouard THIEL](http://pageperso.lif.univ-mrs.fr/~edouard.thiel/)

## Commandes `mkdocs` :

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

## Commandes `mkdocs-et` :

- `~$ cd mkdocs-et-1.2/` - Accéder au répertoire `mkdocs-et`.
- `~/mkdocs-et-1.2$ ./mkdocs-et.sh serve --all -p 8001`- Démarrer le serveur embarqué sur un port différent que 8000.
- `~/mkdocs-et-1.2$ ./mkdocs-et.sh serve --lec 2 --prw 3`- Démarrer le serveur embarqué sur le port 8000 avec filtration des pages publiées.