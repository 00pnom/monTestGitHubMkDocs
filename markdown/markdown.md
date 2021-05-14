
### Code :
#### Elément de code en ligne :
=== "Code"

    ```
    Texte avec un `élément de code`.
    ```

=== "Rendu"

    Texte avec un `élément de code`.

#### Bloc de code :
=== "Code"

    ```
    ```python
    import toto

    def foo() :
        bar = 1
        return bar
```

    ```

=== "Rendu"

    ```python
    import toto

    def foo() :
        bar = 1
        return bar
```



### Titres :

| Code                    | Rendu                   |
|-------------------------|-------------------------|
| `# Titre niveau 1`      | <h1>Titre niveau 1</h1> |
| `## Titre niveau 2`     | <h2>Titre niveau 2</h2> |
| `### Titre niveau 3`    | <h3>Titre niveau 3</h3> |
| `#### Titre niveau 4`   | <h4>Titre niveau 4</h4> |
| `##### Titre niveau 5`  | <h5>Titre niveau 5</h5> |
| `###### Titre niveau 6` | <h6>Titre niveau 6</h6> |


### Retour à la ligne et paragraphe :

Insérer deux espaces à la fin d'une phrase pour forcer le retour à la ligne et insérer une ligne vide pour former des paragraphes.

=== "Code"

    ```
    Ma première phrase sans deux espaces après le point.
    Ma seconde phrase sans retour à la ligne.

    Ma troisième phrase avec deux espaces après le point.  
    Ma quatrième phrase avec retour à la ligne.
    ```

=== "Rendu"

    Ma première phrase sans deux espaces après le point.
    Ma seconde phrase sans retour à la ligne.

    Ma troisième phrase avec deux espaces après le point.  
    Ma quatrième phrase avec retour à la ligne.


### Emphase :

=== "Code"

    ```
    _Texte_ avec *emphase* en Italique

    __Texte__ plus **important** en Gras

    ***Texte*** ou ___Texte___ ou encore **_Texte_** à la fois en **gras** et en *italique*

    Texte barré ~~à supprimer~~
    ```

=== "Rendu"

    _Texte_ avec *emphase* en Italique

    __Texte__ plus **important** en Gras

    ***Texte*** ou ___Texte___ ou encore **_Texte_** à la fois en **gras** et en *italique*

    Texte barré ~~à supprimer~~

code `du code`

```python
import toto

def foo() :
    bar = 1
    return bar
```

## Des liens :

- `[mkdocs.org](https://www.mkdocs.org)` => [mkdocs.org](https://www.mkdocs.org)

- `[mkdocs.org](https://www.mkdocs.org){.md-button}` => [mkdocs.org](https://www.mkdocs.org){.md-button}

- [monScript.py](python_script.py){.md-button}

- [monNotebook.ipynb](Introduction-Le_BN_pour_explorer.ipynb){.md-button}


## Listes :

```mardown
* a
* b
- c
1. d
1. e
```

* a
* b
- c
1. d
1. e


## Annotations, citations

>  simple

!!! info

!!! done

!!! abstract

!!! tip

!!! check

!!! alert

## Intégrations :
```html
<figure>
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/EErFdkrwdyI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<figcaption>Impression 3D de deux supports de visière de protection</figcaption>
</figure>
```
<figure>
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/EErFdkrwdyI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<figcaption>Impression 3D de deux supports de visière de protection</figcaption>
</figure>

```html
<iframe   width="100%"
height="642" name="embedded_python_anywhere" src="https://www.pythonanywhere.com/embedded3/"></iframe>
```
<iframe   width="100%"
height="642" name="embedded_python_anywhere" src="https://www.pythonanywhere.com/embedded3/"></iframe>
