Sur iPad :

- Installer iSH Shell [https://apps.apple.com/us/app/ish-shell/id1436902243](https://apps.apple.com/us/app/ish-shell/id1436902243)
Rendre visible iSH dans fichier
- iSH utilise Alpine Package Manager, `apk`
 - `apk update`, mettre à jour
 - `apk search nom_du_paquet`, rechercher un paquet
 - `apk add nom_du_paquet`, installer un paquet

- `apk add python3` installer python 3 ;
- `apk add py3-pip` installer pip (pour gérer l'installation de module Python) ;
- `apk add bash` installer bash (pour exécuter des scripts .sh)
- `apk add py3-virtualenv` installer virtualenv (pour créer des environnements virtuels spécifiques et éviter les conflits avec d'autres installations de python)
- `apk add py3-regex`
- `apk add vim`

mkdocs et material :

- `pip install mkdocs-material`

## Un site avec Material pour Mkdocs éditer et hébergé depuis un iPad (ou un iPhone) :

J'ai testé et ... **ça marche !**

### La démarche :

1. Installer iSH Shell [https://apps.apple.com/us/app/ish-shell/id1436902243](https://apps.apple.com/us/app/ish-shell/id1436902243)
> - l'application [iSH Shell](https://github.com/ish-app/ish) est un terminal Linux pour iOS ;
> - les dossiers créés par iSH peuvent être rendus visibles depuis l'application [Fichiers] ;(https://support.apple.com/fr-fr/guide/ipad/ipad49b77901/ipados)
> - iSH utilise Alpine Package Manager : `apk update` pour mettre à jour, `apk search nom_du_paquet`, pour rechercher un paquet, `apk add nom_du_paquet`, pour installer un paquet ;

2. Installer les paquets utiles depuis le terminal iSH :
 ```bash
apk add python3
apk add py3-pip
apk add py3-regex
apk add git
apk add vim
```
> `emacs` est aussi disponible 😉

3. Installer mkdocs et material :

`pip install mkdocs-material`