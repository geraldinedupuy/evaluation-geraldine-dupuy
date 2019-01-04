# Évaluation individuelle

## Programmation - Coaching

```
Nom : Dupuy
Prénom : Géraldine
URL de votre compte Github : https://github.com/geraldinedupuy
```

## Déroulé et fonctionnement. 

L'évaluation est à faire sur [Typora](https://typora.io/). Les réponses sont à écrire dans les blocks de code. 
Pour la partie Ruby, testez votre code sur [repl.it](https://repl.it/) et copiez le dans les blocks de code prévu à cet effet. 
Une fois fini, pushez votre feuille sur Github, dans un nouveau repository que vous appelerez "evaluation-inseec".
L'évaluation est individuelle et durera 1h30. Elle intègre des notions d'HTML, CSS, Ruby et computer science. 

![alt](https://media.giphy.com/media/26xBBfd0ii1khakpy/giphy.gif)

## Quelques mises en garde.

Je connais très bien ce merveilleux site qu'est Wikipédia. Je vous saurais gré de ne pas me remplir certaines questions avec les définitions de Wikipédia. Accessoirement, je sais aussi faire une recherche Google. Si j'ai un doute, je n'hésiterais pas rechercher "Qu'est-ce qu'une API" et comparer les définitions en tête de recherche avec les votre. Si je trouve une similarité trop grande et que je doute de votre bonne foi, je n'hésiterais pas à mettre 0 à la question. 
Pareil pour la copie sur les voisins. Si c'est trop gros et que j'ai un doute trop prononcé... 🔫

![alt](https://media.giphy.com/media/BtedgmzGNCiuk/giphy.gif)



------

### 1. Avec vos mots, expliquez l'interaction client-serveur

```t
l'interaction client-serveur repose sur une communication d’égal à égal entre les applications
```



 ### 2. HTML est un langage côté... 	

```
Client
```



### 3. Donnez-moi la structure de base d'une feuille HTML

```html
<!DOCTYPE html>
<!-- Completez après cette ligne -->
<html>
 
  <head>
  </head>
 
  <body>
  </body>
 
</html>
```



### 4. Changez la couleur du texte "J'adore la programmation" en vert en utilisant du CSS.

```html
<div>
   <p>J'adore la programmation</p>
</div>
```

```css
/* Ecrire le code CSS sous cette ligne */
.texte1 {
    color:green
}
```



### 5. Qu'est-ce que Bootstrap ?

```
Bootstrap est une boîte à outils open source pour le développement avec HTML, CSS et JS.
```



### 6. Reprenez votre code de la question 3 et ajoutez Bootstrap à votre feuille HTML, au bon endroit.

```html
<!DOCTYPE html>
<html>
 
  <head>
      <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
  </head>
 
  <body>
  </body>
 
</html>
```



### 7. Mettez ces trois divs sur le même plan horizontal avec trois colonnes de même taille.

```html
<div class="container">
  <div class="row">
    <div class="col-sm">
     Google
    </div>
    <div class="col-sm">
       Microsoft
    </div>
    <div class="col-sm">
       Apple
    </div>
  </div>
</div>
```



### 8. Avec le même code, changez le texte par le logo de la marque en question

```html
<div class="container">
  <div class="row">
    <div class="col-sm">
     <img src="img/logo_google.png" alt="logo">
    </div>
    <div class="col-sm">
       <img src="img/logo_microsoft.png" alt="logo">
    </div>
    <div class="col-sm">
       <img src="img/logo_apple.png" alt="logo">
    </div>
  </div>
</div>
```

 

### 9. Toujours sur le même bout de code, rendez les logos cliquables. Quand on clique sur le logo, on doit arriver sur le site officiel de la marque.

```html
<div>
<div class="container">
  <div class="row">
    <div class="col-sm">
      <a href="ton_lien.html"><img src="img/logo_google.png" alt="logo"></a>
    </div>
    <div class="col-sm">
      <a href="ton_lien.html"><img src="img/logo_microsoft.png" alt="logo"></a>
    </div>
    <div class="col-sm">
       <a href="ton_lien.html"><img src="img/logo_apple.png" alt="logo"></a>
    </div>
  </div>
</div>
```

![Mon gars sûr !](https://media.giphy.com/media/l0K4mbH4lKBhAPFU4/giphy.gif)

### 10. Parlons Ruby. Ruby est un langage côté...

```
serveur
```



### 11. Listez-moi tous les types de données que vous connaissez en donnant le nom et la syntaxe.

```
string = "Je suis Géraldine" # Ceci est une chaine de caractère

boolean = true # Ceci est une réponse vraie
booleann = false # Ceci est une réponse fausse

integer = 261869 # Ceci est un chiffre entier

float = 15,6 # ceci est un chiffre à virgule


```



### 12. Assignez à des variables votre prénom, nom et le lien de votre compte Github puis affichez chacune des variables. En 6 lignes.

```ruby
my_first_name = "Géraldine"
my_last_name = "Dupuy"
my_link = "https://github.com/geraldinedupuy"
puts my_first_name
puts my_last_name
puts my_link

```



### 13. Assignez 674 et 311 à des variables `a` et `b` et stockez le résultat `a` modulo `b` dans une variable `c` et affichez la. 

```ruby
  a = 674

  b = 311
  result = a % b
puts result
# Le résultat attendu est 52. 
```



### 14. Qu'est-ce qu'une gem ? 

```texte
C'est une librairie externe pour ruby
```



### 15. Qu'est-ce qu'une API et qu'est-ce qui nous permet de nous y connecter ?

```
Une API est une interface de programmetion, elle s'oppose au interface graphique. Ce qui nous permet de nous connecter est appelé une clé d'API. 
```



### 16. On va créer un script pour dire bonjour ou bonsoir, en fonction de l'heure de la journée. Votre script doit demander à l'utilisateur de rentrer son prénom. Si `hour` est inférieur à 12, lui dire `Bonjour Anthony` sinon `Bonsoir Anthony` (évidemment, le prénom doit être celui renseigné par l'utilisateur).

```Ruby
# <- Demander le prénom de l'utilisateur
print "What's your first name? "
first_name = gets.chomp
first_name.capitalize!
hour = 15
if hour < 12
    puts "Bonjour #{first_name}"

else
    puts "Bonsoir #{first_name}"
end

```



### 17. Itérer sur l'array contenant des noms de twitos un peu famous et follow chacun d'eux grâce à une méthode trouvée dans la [doc de la gem twitter](https://github.com/sferik/twitter). Pas besoin de lancer le code et de faire la partie authentification. Juste le bloc d'itération suffira. 

```ruby
handles = ["@richardbranson", "@jeffweiner", "@LinkedInQueen", "@ericschmidt", "@elonmusk", "@petecashmore", "@SteveForbesCEO", "@mtbarra"]

client.follow("gem")


```



### 18. Félicitations, vous êtes arrivé·e à la fin, pushez cette feuille sur votre Github dans un repo appelé `evaluation-inseec`. N'oubliez pas de remplir le premier block avec votre identité tout en haut ! 

![alt](https://media.giphy.com/media/l0MYJnJQ4EiYLxvQ4/giphy.gif)

