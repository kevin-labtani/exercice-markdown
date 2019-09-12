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

**Bold**   ** bold1 ** , un blod d** an **s un mot  
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
2.  Recherchez le bloc de code suivant à la ligne 21:

        <html>
          <head>
            <title>Test</title>
          </head>         

3.  Mettez à jour le titre pour correspondre au nom de votre site Web.

Le rendu ressemble à ceci:

    Ouvrir le fichier.

    Recherchez le bloc de code suivant à la ligne 21:

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


### Liens de style référence

Les liens de style référence sont un type de lien spécial qui facilite l'affichage et la lecture des URL dans Markdown. Les liens de style référence sont construits en deux parties: la partie que vous maintenez alignée avec votre texte et la partie que vous stockez ailleurs dans le fichier pour que le texte reste facile à lire.


### Formater la première partie du lien

La première partie d'un lien de style de référence est formatée avec deux ensembles de crochets. Le premier ensemble de crochets entoure le texte qui doit apparaître lié. Le deuxième ensemble de crochets affiche une étiquette utilisée pour pointer vers le lien que vous stockez ailleurs dans votre document.

Bien que cela ne soit pas obligatoire, vous pouvez inclure un espace entre le premier et le deuxième ensemble de crochets. De plus, l’étiquette du deuxième ensemble de crochets ne fait pas la différence entre les majuscules et les minuscules et peut inclure des lettres, des chiffres, des espaces ou des signes de ponctuation.

Cela signifie que les exemples de formats suivants sont tous à peu près équivalents pour la première partie du lien:

* [hobbit-hole][1]
* [hobbit-hole][1]
* [hobbit-hole][a]
* [hobbit-hole][A]


