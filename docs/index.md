Mon memo pour l'utilisation de [MkDocs](https://www.mkdocs.org/), avec le theme 
[Material pour MkDocs](https://squidfunk.github.io/mkdocs-material/) et l'environnement [Mkdocs-et](http://pageperso.lif.univ-mrs.fr/~edouard.thiel/mkdocs-et/) d'[Edouard THIEL](http://pageperso.lif.univ-mrs.fr/~edouard.thiel/)


## Exemples :
- Les exemples de Franck CHAMBON :
    - tutoriel pour MkDocs avec Material : [https://ens-fr.gitlab.io/mkdocs/](https://ens-fr.gitlab.io/mkdocs/)
    - présentation de Python facile pour les matheux : [https://ens-fr.gitlab.io/python_maths/](https://ens-fr.gitlab.io/python_maths/)
    - maths et algos un peu difficiles : [https://ens-fr.gitlab.io/enumeration](https://ens-fr.gitlab.io/enumeration)
    
- Nathalie WEIBEL :	[https://www.carnets.info/](https://www.carnets.info/)

- Frédéric JUNIER 	[https://parc-nsi.github.io/premiere/](https://parc-nsi.github.io/premiere/)

- Guillaume CONNAN : [https://giyom.gitlab.io/ecs1/1.2020_21/20.Espaces_probabilises_discrets/](https://giyom.gitlab.io/ecs1/1.2020_21/20.Espaces_probabilises_discrets/)


## Ressources :

- 
-
-

## Installations :

Sur iPad :

- Installer iSH Shell [https://apps.apple.com/us/app/ish-shell/id1436902243](https://apps.apple.com/us/app/ish-shell/id1436902243)
Rendre visible iSH dans fichier
- mettre à jour AKP
- installer python 3 :
- installer pip (permet de gérer l'installation de module Python) : Py3-pip


Sur PC Windows 10 :

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