


![screenshot](asset/Capture.png)

[Lien vers le portfolio](https://reynaud2000.github.io/Portfolio/index.html "Lien vers le portfolio")

## Code HTML

<br>

```
<nav>
        <ul>
            <li><a href="#etude" tabindex="0">Etudes</a></li>
            <li><a href="#expertises" >Expertises</a></li>
            <li><a href="#competence">Compétences / Atouts</a></li>
            <li><a href="#loisir">Loisirs</a></li>
          </ul> 
    </nav>
```

```

        <fieldset>
            <legend>Remplir le formulaire</legend>
            <form action="mailto: morgane.reynaud2000@gmail.com" method="post">
                <label for="nom">Nom</label>
                <input type="text" id="nom" name = "nom" placeholder="Nom" aria-required="true">

                <label for="nom">Prénom</label>
                <input type="text" id="prénom" name = "prenom" placeholder="Prénom" aria-required="true"><br>

               <label><br>Votez<br></label>
                <input type="radio" name="size" value="1" /> 1 
                <input type="radio" name="size" value="2" /> 2 
                <input type="radio" name="size" value="3" /> 3 
                <input type="radio" name="size" value="4" /> 4 
                <input type="radio" name="size" value="5" /> 5 

                <input type="submit" value="Envoyer">
            </form>
        </fieldset>
```

## Code CSS

<br>

```
/*fonction*/

:root{
    --background:#292F33;
    --fond3: #B0C4DE;
    --soustitre:#CCD6DD;
    --fond6:#ffffff;
    --fond7:#4682B4;
}

/* class */

.profil{
    width: 15rem;
    height: 12rem;
    border-radius: 50%;
    float: left;
}


.Langage{
    width: 10rem;
    height: 10rem;
    border: 0.1rem #23282d solid;
    border-radius: 50%;
}
.box{
    margin-top: 2rem;
    float: left;
    max-width: 50%;
    text-align: center;

}
```

```
@media screen and (max-width: 80.00rem){

    nav ul {
        list-style-type: none;
        margin: 0;
        padding: 0;
        background-color: var(--background);
        
    }
      
    nav li {
        display: block;
        min-width: 100%;
      }
    
    nav ul li a{
        color: white;
        text-decoration: none;
      }


    nav li a:hover { /* Change the link color on hover */
        background-color: var(--fond7);
        color: white;
    }

        
    }

    
  
}
```

## Donner votre Avis
<br>
En bas de la page vous pouvez cliquer sur "donner un avis" pour pouvoir remplir le formulaire. <br>
! Cela ne fonctionne que si vous avez synchronisé votre boite mail avec votre téléphone ou ordinateur!
