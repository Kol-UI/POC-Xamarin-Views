

# Heading h :
# Heading level 1
`<h1>Heading level 1</h1>

## Heading level 2
`<h2>Heading level 2</h2>`

### Heading level 3
`<h3>Heading level 3</h3>`

#### Heading level 4
`<h4>Heading level 4</h4>`

##### Heading level 5
`<h5>Heading level 5</h5>`

###### Heading level 6
`<h6>Heading level 6</h6>`


# Paragraph p :
`<p>I really like using HTML.</p>
I really like using HTML.

❗️Attention les espaces et sauts de ligne sont ignorés
Exemple
```
<p>In HTML, spaces and new lines are ignored:</p>

<p>

  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.
  
  Oh, bring back my Bonnie to me.

</p>
```
<p>In HTML, spaces and new lines are ignored:</p>
<p>

  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.
  
  Oh, bring back my Bonnie to me.

</p>
Pour résoudre ce problème soit utiliser balise **br** soit balise **pre**

# Line Breaks br :
`<p>This is the first line.<br>  
`And this is the second line.</p>`

Line Breaks br n'a pas besoin de /br pour se clore❗️


# Pre Element pre :
```
<p>The pre tag preserves both spaces and line breaks:</p>

<pre>
   My Bonnie lies over the ocean.

   My Bonnie lies over the sea.

   My Bonnie lies over the ocean.
   
   Oh, bring back my Bonnie to me.
</pre>
```
<p>The pre tag preserves both spaces and line breaks:</p>

<pre>
   My Bonnie lies over the ocean.

   My Bonnie lies over the sea.

   My Bonnie lies over the ocean.
   
   Oh, bring back my Bonnie to me.
</pre>


# Bold Text strong :
`I just love <strong>bold text</strong>.`
I just love **bold text**.


# Italic Text em :
`Italicized text is the <em>cat's meow</em>.`
Italicized text is the *cat's meow*.


# Bold & Italic Text strong em :
`This text is <em><strong>really important</strong></em>.`
This text is ***really important***.


# Formating List & Example :
-   `<b>` - Bold text <p><b>bold</b></p>
-   `<strong>` - Important text
<p><strong>Important</strong></p>
-   `<i>` - Italic text
<p><i>Italic</i></p>
-   `<em>` - Emphasized text
<p><em>Emphasized</em></p>
-   `<mark>` - Marked text
<p><mark>Marked</mark></p>
-   `<small>` - Smaller text
<p><small>Smaller</strong></p>
-   `<del>` - Deleted text
<p><del>Deleted</del></p>
-   `<ins>` - Inserted text
<p><ins>Inserted</ins></p>
-   `<sub>` - Subscript text
<p><sub>Subscript</sub></p>
-   `<sup>` - Superscript text 
<p><sup>Superscript</sup></p>


# Blockquote :
`<blockquote cite="https://www.huxley.net/bnw/four.html">`
`        <p>Words can be like X-rays, if you use them properly—they’ll go through anything. You read and you’re pierced.</p>
 `</blockquote>`

> Words can be like X-rays, if you use them properly—they’ll go through anything. You read and you’re pierced.


# Short Quote q :
```
<p>Browsers usually insert quotation marks around the q element.</p>

<p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>
```
<p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>

# Abbreviation abrr :
```
<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>

<p>Marking up abbreviations can give useful information to browsers, translation systems and search-engines.</p>
```

<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>


# Contact Info address :
```
<p>The HTML address element defines contact information (author/owner) of a document or article.</p>

<address>
Written by John Doe.<br> 
Visit us at:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
</address>
```
<address>
Written by John Doe.<br> 
Visit us at:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
</address>


# Work Title cite:
(Sous une oeuvre d'art par exemple)

```
<p>The HTML cite element defines the title of a work.</p>
<p>Browsers usually display cite elements in italic.</p>

<img src="img_the_scream.jpg" width="220" height="277" alt="The Scream">
<p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>
```

<p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>


# Ordered List ol - li :
Exemple 1
```
<ol>  
  <li>First item</li>  
  <li>Second item</li>  
  <li>Third item</li>  
  <li>Fourth item</li>  
</ol>
```
1. First item  
2. Second item  
3. Third item  
4. Fourth item

---
Exemple 2
```
<ol>  
  <li>First item</li>  
  <li>Second item</li>  
  <li>Third item  
    <ol>  
      <li>Indented item</li>  
      <li>Indented item</li>  
    </ol>  
  </li>  
  <li>Fourth item</li>  
</ol>
```
1. First item  
2. Second item  
3. Third item  
    1. Indented item  
    2. Indented item  
4. Fourth item

# Unordered Lists ul - li :
```
<ul>  
  <li>First item</li>  
  <li>Second item</li>  
  <li>Third item</li>  
  <li>Fourth item</li>  
</ul>
```
- First item  
- Second item  
- Third item  
- Fourth item

# Ordered & Unordered Lists ul - li - ol - li :

```
<ul>  
  <li>First item</li>  
  <li>Second item</li>
  <li>Third item</li>  
  <li>Fourth item 
    <ol>  
      <li>First Indented item</li>  
      <li>Second Indented item</li>  
    </ol>  
  </li>  
  <li>Fifth item</li>  
</ul>
```
<ul>  
  <li>First item</li>  
  <li>Second item</li>
  <li>Third item</li>  
  <li>Fourth item 
    <ol>  
      <li>First Indented item</li>  
      <li>Second Indented item</li>  
    </ol>  
  </li>  
  <li>Fifth item</li>  
</ul>

# Image img src alt:
````
<img class="fit-picture"
     src="https://mdg.imgix.net/assets/images/tux.png?auto=format&fit=clip&q=40&w=100"
     alt="LinuxLogo">
 ````

<img class="fit-picture"
     src="https://mdg.imgix.net/assets/images/tux.png?auto=format&fit=clip&q=40&w=100"
     alt="LinuxLogo">






# Code code :
<p>The <code>push()</code> method adds one or more elements to the end of an array and returns the new length of the array.</p>

```
<p>The <code>push()</code> method adds one or more elements to the end of an array and returns the new length of the array.</p>
```

# Link a :
<a href="https://www.markdownguide.org">Link</a>
```
<a href="https://www.markdownguide.org">Link</a>
```


# Link Image a href - img src :
```
<a href="link address"><img src="image destination"></a>
```
Exemple :
```
<h2>Image as a Link</h2> <a href="https://www.tutorialspoint.com"><img src="https://www.tutorialspoint.com/assets/questions/media/426142-1668760765.png" alt="Tutorialspoint" style="width:50px;height:60px;"></a>
```
<h2>Image as a Link</h2> <a href="https://www.tutorialspoint.com"><img src="https://www.tutorialspoint.com/assets/questions/media/426142-1668760765.png" alt="Tutorialspoint" style="width:50px;height:60px;"></a>

# Center Elements center :
Exemple precedent + center :
```
<center> <h2>Image as a Link</h2> <a href="https://www.tutorialspoint.com"><img src="https://www.tutorialspoint.com/assets/questions/media/426142-1668760765.png" alt="Tutorialspoint" style="width:50px;height:60px;"></a> </center>
```
<center> <h2>Image as a Link</h2> <a href="https://www.tutorialspoint.com"><img src="https://www.tutorialspoint.com/assets/questions/media/426142-1668760765.png" alt="Tutorialspoint" style="width:50px;height:60px;"></a> </center>




# HTML Page Structure :
<html>

<head>

<title>Page title</title>

</head>

<body>

<h1>This is a heading</h1>

<p>This is a paragraph.</p>

<p>This is another paragraph.</p>

</body>

</html>
```
<html>

<head>

	<title>Page title</title>

</head>

<body>

	<h1>This is a heading</h1>
	
	<p>This is a paragraph.</p>
	
	<p>This is another paragraph.</p>

</body>

</html>
```


# Separator hr :
```
<h1>This is heading 1</h1>
<p>This is some text.</p>
<hr>

<h2>This is heading 2</h2>
<p>This is some other text.</p>
<hr>

<h2>This is heading 2</h2>
<p>This is some other text.</p>
```
<h1>This is heading 1</h1>
<p>This is some text.</p>
<hr>

<h2>This is heading 2</h2>
<p>This is some other text.</p>
<hr>

<h2>This is heading 2</h2>
<p>This is some other text.</p>


# Bi-Directional Override :
(Jamais utilisé)
```
<p>If your browser supports bi-directional override (bdo), the next line will be written from right to left (rtl):</p>

<bdo dir="rtl">This line will be written from right to left</bdo>
```

<bdo dir="rtl">This line will be written from right to left</bdo>


# Comments:
Utilisé pour travail d'équipe ou se repérer dans le code

<!-- Write your comments here -->

Exemple habituel :
```
<!-- couleur de fond bleu -->
<body style="background-color:powderblue;">  
```

---
Exemple autour d'une balise (la balise ne sera pas affichée, voir résultat):
```
<p>This is a paragraph.</p>  
  
<!-- <p>This is another paragraph </p> -->  
  
<p>This is a paragraph too.</p>
```
<p>This is a paragraph.</p>  
  
<!-- <p>This is another paragraph </p> -->  
  
<p>This is a paragraph too.</p>

---
Exemple plusieurs balises :
```
<p>This is a paragraph.</p>  
<!--  
<p>Look at this cool image:</p>  
<img border="0" src="pic_trulli.jpg" alt="Trulli">  
-->  
<p>This is a paragraph too.</p>
```
<p>This is a paragraph.</p>  
<p>This is a paragraph too.</p>

---
Exemple dans texte :
`<p>This <!-- great text --> is a paragraph.</p>`
<p>This <!-- great text --> is a paragraph.</p>


# Attribute :
`<img src="img_girl.jpg" width="500" height="600">`

❗️"src" "width" et "height" sont des attributs

- src = source d'une image ou d'un lien (Absolute URL ou Relative URL)
- width = largeur d'un element
- height = hauteur d'un element
- alt = text si l'img charge pas ou  si l'utilisateur utilise un screen reader (Ex:`<img src="img_typo.jpg" alt="Girl with a jacket"> `)
- style = pour mettre du css directement dans l'element (Ex: `<p style="color:red;">This is a red paragraph.</p>`)
- lang = OBLIGATOIRE, pour la langue de la page web, se trouve dans la balise html `<html lang="en">`

❗️Les attributs doivent toujours être entourés par des ""
Exemple width="500"

❗️Pour utiliser des "" ou '' il suffit d'inverser
Exemple
`<p title='John "ShotGun" Nelson'>`
`<p title="John 'ShotGun' Nelson">`
Premier titre =  John "ShotGun" Nelson
Deuxième titre = John 'ShotGun' Nelson


# Commentaires CSS :
```
/* Commentaire sur une ligne */

/*
Commentaire
sur plusieurs
lignes
*/


/* Le commentaire qui suit permet
   de désactiver une règle */
/*
p {
  color: blue;
  font-size: 1.5em;
}
*/
```


# Les Couleurs :
Elles peuvent être RGB - HEX - HSL - Named
```
<h1 style="background-color:rgb(255, 99, 71);">...</h1>  
<h1 style="background-color:#ff6347;">...</h1>  
<h1 style="background-color:hsl(9, 100%, 64%);">...</h1>  
  
<h1 style="background-color:rgba(255, 99, 71, 0.5);">...</h1>  
<h1 style="background-color:hsla(9, 100%, 64%, 0.5);">...</h1>
```
Le 0.5 à la fin sur rgba et hsla donne une opacité de 0.5 (0.5 = 50% transparent).
- Plus c'est proche de 0 moins la couleur sera visible.
- Plus c'est proche de 1 plus la couleur sera visible.


# Utilisation du CSS :
CSS can be added to HTML documents in 3 ways:

-   **Inline** - by using the `style` attribute inside HTML elements
-   **Internal** - by using a `<style>` element in the `<head>` section
-   **External** - by using a `<link>` element to link to an external CSS file

### Inline CSS :
```
<h1 style="color:blue;">A Blue Heading</h1>  
  
<p style="color:red;">A red paragraph.</p>
```

### Internal CSS :
```
<!DOCTYPE html>  
<html>  
<head>  
<style>  
body {background-color: powderblue;}  
h1   {color: blue;}  
p   {
	color: red;
	font-family: verdana;  
	font-size: 300%;
	}  
</style>  
</head>  
<body>  
  
<h1>This is a heading</h1>  
<p>This is a paragraph.</p>  
  
</body>  
</html>
```
❗️Ici le style h1 sera appliqué à tous les h1, pareil pour p

### External CSS :
(Meilleure méthode)
.html
```
<!DOCTYPE html>  
<html>  
<head>  
  <link rel="stylesheet" href="styles.css">  
</head>  
<body>  
  
<h1>This is a heading</h1>  
<p>This is a paragraph.</p>  
  
</body>  
</html>
```
styles.css
```
body {  background-color: powderblue;}  
h1 {  color: blue;}  
p {  color: red;}
```
❗️On fait un ficher CSS a part pour pouvoir le re-utiliser sur d'autres .html si nécessaire.

- Pour lier vers css d'un autre site
`<link rel="stylesheet" href="https://www.w3schools.com/html/styles.css">`

- Pour lier vers d'autres page css d'un même site
`<link rel="stylesheet" href="/html/styles.css">`

- Pour lier vers un css qui est dans le même dossier
`<link rel="stylesheet" href="styles.css">`


# Quelques Notions CSS :
`style="property:value;"`
❗️"property" + ":" + "value" + ";"
Erreurs Communes = oublier ":" ou ";"

- **background-color** : donne une couleur de fond
```
<body style="background-color:powderblue;">  
<!-- couleur de fond bleu -->
  
<h1 style="background-color:green;">This is a heading</h1>  
<!-- couleur de fond du h1 vert -->

<p style="background-color:tomato;">This is a paragraph.</p> 
<!-- couleur de fond du paragraphe tomato -->
  
</body>
```

- **color** : applique une couleur au texte
```
<h1 style="color:blue;">This is a heading</h1> 
<!-- text bleu -->

<p style="color:red;">This is a paragraph.</p>
<!-- text rouge -->
```

- **font** : applique une police d'écriture
```
<h1 style="font-family:verdana;">This is a heading</h1>  
<p style="font-family:courier;">This is a paragraph.</p>
```

- **text-size** : applique une taille au texte
```
<h1 style="font-size:300%;">This is a heading</h1>  
<p style="font-size:160%;">This is a paragraph.</p>
```

- **text-align** : alignement du texte
```
<h1 style="text-align:center;">Centered Heading</h1>  
<p style="text-align:start;">Aligné à droite.</p>
<p style="text-align:end;">Aligné à gauche.</p>
<p style="text-align:justify;">Text Justifié.</p>
<p style="text-align:match-parent;">S'aligne comme son parent.</p>
```

- **border** : des bordures avec couleur
```
<!-- HTML -->
<h1 style="border:2px solid Tomato;">Hello World</h1>  
<h1 style="border:2px solid DodgerBlue;">Hello World</h1>  
<h1 style="border:2px solid Violet;">Hello World</h1>
```

<h1 style="border:2px solid Tomato;">Hello World</h1>  
<h1 style="border:2px solid DodgerBlue;">Hello World</h1>  
<h1 style="border:2px solid Violet;">Hello World</h1>
```
/* CSS */
p {  border: 2px solid powderblue;}
```

- **padding** : ajouter de l'espace à l'intérieur d'un élément (exemple aggrandir l'interieur d'une zone)
```
/* CSS */
p	{  
	border: 2px solid powderblue;  
	padding: 30px;
	}
  ```

- **margin** : ajouter de l'espace entre deux elements (exemple aggrandir l'écart entre deux zone)
```
/* CSS */
p   {
	border: 2px solid powderblue;  
	padding: 30px;
	}
```

