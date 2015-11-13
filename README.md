# gittest
Le projet présente une simple page html avec sa feuille de style.
La page Html final contient 2 paragraphes ayant un style différent.


Etape 1 :

index.htm
<p>Mon premier fichier HTML pour GIT</p>



Etape 2:

fichier index.htm
<link rel="stylesheet" type="text/css" href="styles.css">
<p>Mon premier fichier HTML pour GIT</p>

fichier styles.css
p{font-family: arial; color:red;}


Etape 3

fichier index.htm
<link rel="stylesheet" type="text/css" href="styles.css">
<p class="rouge">Mon premier fichier HTML pour GIT</p>
<p class="bleu"> Ceci est mon 2e paragraphe en bleu </p>

fichier styles.css
.rouge{font-family: arial; color:red;}
.bleu{font-family:verdana; color:blue}
