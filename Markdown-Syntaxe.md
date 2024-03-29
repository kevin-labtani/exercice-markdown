# Menu
1. [Read Me](https://github.com/kevin-labtani/exercice-markdown)
1. Markdown
    1. [Présentation](https://github.com/kevin-labtani/exercice-markdown/blob/master/Markdown.md)
    1. [Syntaxe](https://github.com/kevin-labtani/exercice-markdown/blob/master/Markdown-Syntaxe.md)
1. [Environnement Optimisé pour l'Apprentissage](https://github.com/kevin-labtani/exercice-markdown/blob/master/EOA.md)


# La syntaxe Markdown


### Headings

# Heading lvl1 
"#" + texte

## Heading lvl2
"##" + texte

### Heading lvl3
"###" + texte

#### Heading lvl4
"####" + texte

##### Heading lvl5
"#####" + texte

###### Heading lvl6
"######" + texte


### Les paragraphes

*Ceci est un paragraphe*

*Ceci est un second paragraphe*


### Les retours à la ligne

Voici la première ligne.
Voici la deuxième ligne.


### Bold ou Italic

Pour mettre l'accent sur certains éléments d'un texte, on peut les mettre en "bold" ou en "Italic"

**Bold**   ** bold1 ** , un bold d** an **s un mot  
*Italic*   * italic * , _ italic2 _ , un italic d* an * s un mot


### Bold et Italic

C'est ***très*** important  ***

C'est __*vraiment*__ important    __ * * __

C'est **_vraiment_** important   ** _ **


### Les Blockquotes

*Ajouter un > devant un paragraphe pour faire un blockquote*

> Voici un blockquote

*Un blockquote peut aussi contenir plusieur paragraphes en ajoutant un > sur l'espace blanc entre deux paragraphes*

> Voici un paragraphe
>
> Voici un second paragraphe

*Les blockquotes peuvent être imbriqués. Il suffit d'ajouter >> devant le paragraphe que l'on veut imbriquer*

> Voici un paragraphe
>
>> Voici un paragraphe imbriqué

*Les blockquotes peuvent aussi contenir plusieurs autres éléments Markdown. Toutefois, tous les éléments ne peuvent pas utiliser - , à vous de voir lesquels fonctionnent* 

> #### Voici un head
>
> - Voici une ligne
> - Voici une autre ligne
>
>  *Voici* un autre **paragraphe**.


### Les listes

**On peut organiser notre travail en faisant des listes**

*Les listes numérotées:*

1. Premier objet
2. Deuxième objet
3. Troisième objet
4. Quatrième objet

Quel que soit l'ordre des chiffres que l'on met, le résultat sera toujours 1,2,3,4,...

*Les listes non numérotées:*

* Premier objet
* Deuxième objet
* Troisième objet
* Quatrième objet 

On utilise * , + ou -

**Ajouter un élément à une liste sans modifier la continuité de cette dernière**

*Avec les paragraphes:*

* Premier objet
* Deuxième objet

  J'ai besoin d'intégrer un paragraphe dans ma liste (espace ou tab ou se mettre au même niveau)

* Troisième objet

*Avec les blockquotes:*

* Premier objet
* Deuxième objet

  >Voici un blockquote

* Troisième objet


### Les blocks de code

Les blocs de code sont normalement en retrait de quatre espaces ou d'un seul onglet. Quand ils sont dans une liste, indentez-les huit espaces ou deux onglets.

1.  Ouvrir le fichier.
2.  Par exemple:

        <html>
          <head>
            <title>Test</title>
          </head>         

3.  Mettez à jour le titre pour correspondre au nom de votre site Web.

Le rendu ressemble à ceci:

    Ouvrir le fichier.

    Par exemple:

```html
        <html>
          <head>
            <title>Test</title>
          </head>
```         

    Mettez à jour le titre pour correspondre au nom de votre site Web.


### Images

![nom de l'image](lien de limage)


### Liens et adresses mail

< https://www.markdownguide.org >
< fake@example.com >

<https://www.markdownguide.org>
<fake@example.com>


### Les liens formatés

I love supporting the ** [EFF ] (https://eff.org)**.
This is the * [Markdown Guide] (https://www.markdownguide.org)*.

I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*.


## Source 

* [MarkDown Guide](https://www.markdownguide.org/basic-syntax/)