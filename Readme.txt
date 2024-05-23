# Détails du Projet

## Langages Utilisés
- HTML
- CSS
- JavaScript

## Auteur
Foufie4

## But du Projet
Ce projet vise à créer une interface Web pour rechercher des informations sur les films à partir de l'API OMDB. 
Il permet aux utilisateurs de rechercher des films par titre et d'afficher les détails de chaque film sélectionné.

## Explications des Fonctions

### Fonction `searchMovies(searchTerm)`
Cette fonction est déclenchée lorsqu'un utilisateur recherche un film. Elle utilise l'API OMDB pour rechercher des films correspondant au terme de recherche spécifié. Les résultats sont affichés dans la section dédiée sur la page.

### Fonction `displayResults(movies)`
Cette fonction prend en entrée un tableau d'objets représentant des films et affiche chaque film dans la section des résultats de recherche. Pour chaque film, elle crée un élément HTML contenant l'image, le titre, l'année et un lien vers les détails du film.

### Fonction `displayFilmDetails(film)`
Cette fonction est appelée lorsqu'un utilisateur clique sur un film pour afficher ses détails. Elle récupère les détails du film à partir de l'API OMDB en utilisant l'identifiant IMDB du film et affiche ces détails dans la section dédiée sur la page.

---

Vous pouvez trouver le projet complet [ici](https://github.com/foufie4/Looking4movie).
