# HTML
<p align="center">
  <img width="350" height="197" src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/langfr-1024px-HTML5_logo_and_wordmark.svg.png">
</p>
## Table des matières

- [1. Formatage texte1](#1)
- [2. Formatage texte2](#2)
- [3. Formatage technique](#3)
- [4. Liste](#4)
- [5. Tableaux](#5)
- [6. Formulaires1](#6)
- [7. Formulaires1](#7)
- [8. Structurer page Web](#8)
- [F10. Audio Védio](#9)
<a name="1"></a>
## 1. formatage texte1
``` 
HTML
<!-- commentaire-->
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>Ma première web !</title>
</head>
<body>
    <h1>Mon premier titre</h1>
    <p>Bonjour! <em>Monseur</em></p>
    <p>ça va? <strong>Qannaf</strong> <q> double cotte</q>  <cite>nom de livre filme ect</cite></p>
    <hr>
    <p>Bonjour!<br>ça va?</p>

    <hr>
    <h2>Mon premier titre</h2>
    <p>  Il y a <del> 800 </del> <ins>1 200</ins> habitant dans <mark>village</mark><b>desconsiellé </b> <i>Pas forcement</i><s>incorrecte</s> </p>

    <details>voir la détails</details>
        <summary>clicker pour les détails</summary>

    <p> voila mon lien, <a href="https//google.com"title="mon site"> le lien </a></p> 
    <p> voila mon lien, <a href="https//google.com"target="mon site"> le lien </a></p> 
</html>
  ```
  ### Output
 
![alt text](images/1.PNG?raw=true "sortie de code")

<a name="2"></a>
## 2. formatage texte2
``` HTML
<!-- 2éme cours-->
<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <title>Ma deusième page web !</title>
</head>

<body>
    <p>Bonjour! Monseur <abbr title="Hypertext Markup Language">voir</abbr></p>
</body>


<!------------------------------------------------->
<hr>
<body>
    <address>
        Qannaf AL-SAHMI<br>
        12 Rue de l'écharpe<br>
        <a href="émail : q.alsahmi@gmail.com">Envoyer un émail</a>

    </address>
</body>


<!------------------------------------------------->
<hr>
<body>
    <p> Salut :<bdi> مرحبا</bdi></p>
    <p> Salut :<bdi dir="auto"> مرحبا</bdi></p>
    <p> <bdo>ابحرم </bdo></p>
</body>


<!------------------------------------------------->
<hr>
<body>
    <p><dfn>HTML</dfn>   est un langage informatique pour créer une page web  </p>
    <p><dfn>CSS</dfn>   est un langage informatique pour mettre en forme des pages web    </p>
    <dl>
        <dt>HTML</dt>
        <dd>est un langage informatique pour créer une page web</dd>
        <dt>CSS</dt>
        <dd>est un langage informatique pour mettre en forme des pages web</dd>

    </dl>
</body>


<!------------------------------------------------->
<hr>
<body>
    Etat du projrt : <progress value="100" max=100></progress>
    <p>l'oxigine est : O<sub>2</sub>
    <p>X carré est : X<sup>2<sup></p>
    <p>hhhhhhhhhhhhhhhhhhhhhH<wbr>hhhhhhhhhhhhhhhhhhhhhhhhhhhhhH<wbr>hhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhh</p>
</body>


</html>
```

  ### Output
 
![alt text](images/2.PNG?raw=true "sortie de code")


<a name="3"></a>
## 3. formatage technique
```HTML

<!-- 2éme cours-->
<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <title>Ma 3 éme page web !</title>
</head>

<body>
    <p>Bonjour!<code>print("Hello world")</code></p>
    <p>Bonjour!<kdb>Ctrl+s</kdb></p>
    <p>Valeur en pourcentage: <meter value="0.25">25%</p>
    <p>T° corps : <meter value="37" optimum="37.4">37 dégré</p>
    <p>2+4= <output>6</output></p>
    <pre>        bonjours tout le monde
    ceci           est un            nouvelle phrase</pre>

    <code>if(age>18) {printf("Tu est majeur\n")}</code>
    <br>
    <ruby>
        ش<rt>cho</rt>       
        ك<rt>ka</rt>   
        ر<rt>Ra</rt>   
        ا<rt>Nn</rt>   
    </ruby>
    <p>Début du concours le <time  datetime="2020-04-08 13:25:54">08 Janvier 2020 </time></p>
    <p>Informatique: <var>x</var>  = <var> 14 </var></p>
    <p>Mathimatique: <var>x<sup>2</sup></var>  </p>
</body>


<!------------------------------------------------->

```

  ### Output
 
![alt text](images/3.PNG?raw=true "sortie de code")


<a name="4"></a>
## 4. Liste
```HTML

<!-- les  listes-->
<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <title>Ma page web pour les listes</title>
</head>

<body>
    <ul>
        <li>Un premier élément</li>
        <li>Deuxiéme élement</li>
        <li>Et encore un autre</li>
    </ul>

    <ol>
        <li>Un premier élément</li>
        <li>Deuxiéme élement</li>
        <li>Et encore un autre</li>
    </ol>

    <ol reversed>
        <li>Un premier élément</li>
        <li>Deuxiéme élement</li>
        <li>Et encore un autre</li>
    </ol>

    <ol start ="10">
        <li>Un premier élément</li>
        <li>Deuxiéme élement</li>
        <li>Et encore un autre</li>
    </ol>

    <ol type="a">
        <li>Un premier élément</li>
        <li>Deuxiéme élement</li>
        <li>Et encore un autre</li>
    </ol>

    <ul>
        <li>Un premier élément</li>
        <li>Deuxiéme élement</li>
        <ol type="a">
            <li>etape premier</li>
            <li>etape Deuxiéme</li>
            <li>etape troisiéme</li>
        </ol>
        <li>Et encore un autre</li>
    </ul>
    
</body>


<!------------------------------------------------->

```
  ### Output
 
![alt text](images/4.PNG?raw=true "sortie de code")

<a name="5"></a>
## 5. Tableaux
```HTML

<!-- les  Tableux 
        <thead></thead>
        <tbody></tbody>
        <tfoot></tfoot>        ---->
<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <title>Ma page web pour les Tableux</title>
</head>


<body>
    <table>
        <caption>Liste de jeux vidéos</caption>

        <thead>
            <tr>
                <th> /</th>
                <th> Name</th>
                <th> Age</th>
                <th> Email</th>
            </tr>
        </thead>

        <tbody>
            <tr>
                <th> Friste</th>
                <td> Qannaf</td>
                <td> 27 ans</td>
                <td rowspan= "2">q.alsahmi@gmail.com</td>
            </tr>
            <tr>
                <th> Seconde</th>
                <td> Qannaf</td>
                <td> 27 ans</td>
                <td> q.alsahmi@gmail.com</td>
        </tbody>
          
        
    </table>
    
</body>


<!------------------------------------------------->
<hr>
<body>
    <table>
        <caption>Liste 2</caption>
        <thead>
            <tr>
                <th id="Id"> Id</th>
                <th id="nom"> Name</th>
                <th id="age"> Age</th>
                <th id="mail"> Email</th>
            </tr>
        </thead>

        <tbody>
            <tr>
                <td headers="Id"> Friste</td>
                <td headers="nom">  Qannaf</td>
                <td headers="age"> 27 ans</td>
                <td headers="mail">q.alsahmi@gmail.com</td>
            </tr>
            <tr>
                <td> Seconde</td>
                <td> Qannaf</td>
                <td> 27 ans</td>
                <td> q.alsahmi@gmail.com</td>
        </tbody>
          
        
    </table>
    
</body>

```
  ### Output
 
![alt text](images/5.PNG?raw=true "sortie de code")


<a name="6"></a>
## 6. Formulaires1
```HTML

<!-- les formulaires        ---->
<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <title>Ma page web pour les formulaires</title>
</head>


<body>
    <form method="post" action="" > 
       <p><label for="prenom">Nom</label>: <input  id="prenom" name="username" placeholder="Entrez votre nom"> </p>
       <p> Password: <input type="password" name="password" placeholder="entrez votre MDP">
       <hr>

        <input type="text" name="Champformulaire"> <br>
        Publier le nom :<input type="checkbox" name="Champformulaire">
        Publier le nom :<input type="radio" name="Champformulaire"> <br>
        Votre choix : <input type="radio" name="choisir"> oui <input type="radio" name="choisir">non <br>
        coleur : <input type="color" name="coleur" >  <br>
        date : <input type="date" name="temps" >  <br>
        email: <input type="email" name="email"> <br>
        semain : <input type="week" name="semaine" >  <br>
        mois : <input type="month" name="mois" >  <br>
        recherche : <input type="search" name="recherche" >  <br>
        balier : <input type="range" name="balier" value="80" min="0" max="100" step="5"> <br>
        numéro : <input type="number" name="numéro"> <br>
        Nom : <input type="text" name="user" required>  <br>
              <input type="submit" value="effacer">
              <input type="reset" value="se connecter">
    </form>


</body>
</html>
    
```
  ### Output
 
![alt text](images/6.PNG?raw=true "sortie de code")


<a name="7"></a>
## 7. Formulaires2
```HTML
```
  ### Output
 
![alt text](images/7.PNG?raw=true "sortie de code")


<a name="8"></a>
## 8. Structurer page Web
```HTML
<!-- Structure page web
    Rigle d'or
    1) header et footer tete et pies pour une partie (body sectionarticle)
    2) Article a header et footer
    3) aside pour tout les page           -->

<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <title>Ma page web pour l'audio & Vidéo'</title>
</head>

<body>
    <main>
        <h1>Titre 1</h1>
    </main>
    <div>
        <p>.................<span>...................</span>
            ........................................................
        </p>
        <p>...........................................................................
            ......................................
        </p> 
    </div>
        
    <div>
        <p>...............................................
            ........................................
        </p>  
    </div>  

    <section>
        <h1>Mon titre de section</h1>
        <div>
            <p>.................<span>...................</span>
                ........................................................
            </p>
            <p>...........................................................................
                ......................................
            </p> 
        </div>
    </section>

    <article>
        <header>
            <h1>titre d'article ou de page</h1>
        </header>
        __________________________________bla bla bla____________________________________
        <footer>
            <p>Copyright &copy;2020</p>
            <p>cette document est rédiger par<address> Qannaf AL-SAHMI</address> </p>
        </footer>
    </article>



<hr>
<!------------------------------------------------------------------------------------->
    <nav>
        <h1>Mon site</h1>
        <ul>
            <li> <a href="#" Machine Learning >Machine Learning </a> </li>
            <li> <a href="#" Deep Learning >Deep Learning</a> </li>
            <li> <a href="#" IA>IA</a> </li>
        </ul>
    </nav>

    <aside>phrase fix pour toutes les pages</aside>




</body>
</html>
```
  ### Output
 
![alt text](images/8.PNG?raw=true "sortie de code")
<a name="9"></a>
## 9. Image
```HTML

<!-- les  listes-->
<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <title>Ma page web pour les listes</title>
</head>

<body>
    <h1>Image et figure</h1>

    <img src="1.jpg" alt="Texte alternatif à l'image" width="200" height="auto" >
    <br>

    <figure>
        <img src="1.jpg" alt="" width="200" height="auto">
        <figcaption>mon certificat source: <a href="#">lien</a></figcaption>
    </figure>
    
    <!---
        shape = rect   -> x1,y1,x2,y2
                circle -> x,y,r
                poly   -> x1,y1,x2,y2, ... ,x10,y10
    -->

    <img usemap="#certificat" src="1.jpg" alt="mon certificat image" width="200" height="auto">
    <map name="certificat">
        <area href="2.png" shape="rect" coords="0,0,50,50">
    </map>

    <picture>
        <source srcset="2.png" media="min-width: 600px">
        <img src="3.jpg" alt="" >
    </picture>

</body>


<!------------------------------------------------->
</html>
```
  ### Output
 
![alt text](images/9.PNG?raw=true "sortie de code")


<a name="10"></a>
## 10. Audio Vidéo
```HTML
<!-- l'udio vidéo
        Audio : mp3  (compatible avec tout)
                wav  (sauf IE)
                ogg  (sauf IE et safari)
        Audio : mp4  (compatible avec tout)
                webm (sauf IE)
                ogg  (sauf IE et safari)
                -->

<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <title>Ma page web pour l'audio & Vidéo'</title>
</head>

<body>
    <h1>Sons </h1>
    <audio src="50.MP3" controls preload="metadata">
        votre navigateur ne supporte pas l'audio 
    </audio>
<hr>
    <h1>vidéos</h1>
    <video src="PDV.mp4" controls preload="metadata" width="260" height="auto" poster="1.jpg"
        votre navigateur ne supporte pas l'audio 
    </video>


</body>


<!------------------------------------------------->
</html>
```
  ### Output
 
![alt text](images/10.PNG?raw=true "sortie de code")
