### Une liste numérotée fonctionne de la manière suivante:

*Un ensemble d'item l'un après l'autre précédé de numéro montant dans l'ordre chronologique* 

1. Mon premier item
2. Mon second item
3. Mon troisième item 

### Pour insérer une image: 

Utilisez la syntaxe suivante en metant une description de l'image entre [] Ensuite l'url entre ()

![Deadpool](http://media.comicbook.com/2017/07/deadpool-2-movie-pansexual-deadpool-1012668.jpg)

## Liste imbriquée

Pour faire une liste à puce ou ordonné imbriquées, il faut reprendre la même procédure que pour les autres liste à la différence qu'il faut rajouter de la même manière sous une des puces :

1. Mon premier object
2. Mon deuième object
   * Mon deuxième object bis
   * Mon deuxième object trier
3. Mon troisième object
4. Mon quatrième object
   * Mon quatrième object bis
   * Mon quatrième object trier


### Les Headers


Pour mettre un titre, on rajoute :

Un # pour l'équivalent `<h1>` tag.
Deux # pour l'équivalent `<h2>` tag.
Ainsi de suite jusqu'à
Six # pour l'équivalent `<h6>` tag.


### Les liens


Il y a deux façons d’afficher un lien. De manière automatique en encadrant un lien par des chevrons. Il est alors cliquable et affiche l’url indiquée entre chevrons. 

"Code Markdown"

<http://www.becode.org>


"Code HTML"

<a href="http://becode.org">http://www.becode.org</a>

Ou en ajoutant des paramètres. Le texte à afficher est alors indiqué entre crochets suivit de l’adresse du lien entre parenthèses. Dans les parenthèses, à la suite du lien, on peut indiquer un titre entre guillemets. Ce titre sera affiché lors du survol du lien dans le navigateur. Il sera également lu par les navigateurs textuels pour les déficients visuels. Cette méthode est plus verbeuse lors de l’édition du document, mais plus élégante lors de sont export. Elle sera donc préférée à la première.

"Code Markdown"

[becode] (http://www.becode.org "link to becode")


"Code HTML"

<a href="http://www.becode.org" title="link to becode">becode</a>


[Qu'est ce que le Markdown](Markdown.md)
[Read me](README.md)


