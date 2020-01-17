<a href="www.keepizi.com"><img src="https://www.keepizi.com/wp-content/uploads/2018/08/Logo-Keepizi_violet_mobile.png" title="keepizi" alt="keepizi"></a>

*** Exercice de mise en ligne d'un projet ajax via Git ***

# AJOUT D'ARTICLES FAVORIS
> Des articles apparaissent pour l'utilisateur.
Au clic, l'article est ajouté aux favoris via la SESSION. Lors du déclic, l'icône favoris disparaît et l'article est enlevé de la SESSION.

> Tech: AJAX, Javascript, PHP

** N'oubliez pas de ... **
- Si vous souhaitez lier à une base de données,
creez votre fichier d'initialisation dans le dossier inc.
Les articles apparaissent en "dur" dans notre index, veuillez les remplacer par les vôtres.

> Ajout de notre GIF [![LES FAVORIS SELON LES GOONIES](https://media.giphy.com/media/GHcm2aWIczatG/giphy.gif)]()

## Table des matières

- [Explication](#explication)
- [Remerciments](#remerciements)

---
## Explication
---
> Ajout d'une portion de code dans le README

```PHP
 if(isset($_POST["a"]) && $_POST["a"] == "remove"){

    foreach ($_SESSION['favorites'] as $key => $value){

        if($id == $value){

            unset($_SESSION['favorites'][$key]);

        }
    }
}
```

- Pour retirer les favoris de ma SESSION, je regarde bien que l'action demandé est un "remove";
-Je fais concorder le $id envoyé en POST avec les valeurs enregistré en SESSION.

---
## Remerciements
---
A tous les étudiants !

[![Veuillez cisiter notre site]()](https://www.keepizi.com)