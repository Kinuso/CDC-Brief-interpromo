# Cahier des charges Brief Inter Promo

## Contexte

Vous êtes missionné pour créer un site de blog amateur concernant les jeux olympiques.

Il y aura une partie admin qui pourra gérer les utilisateurs et différents articles, une partie rédacteurs, qui pourront gérer et modifier leur compte ainsi que leurs articles, tout en pouvant accéder aux articles des autres rédacteurs (sans pouvoir modifier)

Les utilisateurs devront arriver sur une page d’accueil.


## Liste des droits 

![image](https://github.com/user-attachments/assets/fb380a19-0984-4871-91f9-92a79ebb33f6)

## Attentes techniques 


Lors de l’inscription, on voudra retrouver : 
    +L’adresse mail
    +Mot de passe
    +Nom
    +Prénom


Pour la connexion : 
    +Adresse mail
    +Mot de passe

    Option : 
        ajouter un bouton “mot de passe oublié” avec l’emailing ainsi qu’utilisation de token dans l’url pour la sécurité 


Le compte de l’utilisateur devra lui permettre : 
    +Tout le CRUD concernant son compte+
    Option : 
        Supprimer ses commentaires des posts, puis de pouvoir retrouver dans son profil tous les posts qu’il a commenté
        Retrouver dans son profil tout les post qu’il a aimé



Pour les articles il faut : 
    +Titre
    +Image (Un URL sera suffisant, si vous souhaitez aller plus loin, l’ajout d’une image téléchargé depuis son ordinateur par l’utilisateur)
    +Description (max 1000 caractères)
    +Nom, +prénom
    +Date
    +Commentaires
    +Like , en affichant le nombre


Sur la page d'accueil, seuls les 6 premier articles seront affichés, si la description dépasse les 50 caractères, on cachera le reste pour garder une taille fixe.


Les commentaires des articles seront affichés uniquement quand on sera sur la page affichant l’article en entier, seuls les 5 premiers devront apparaître pour une lecture de page plus claire, un bouton “afficher plus” permettra d’en afficher 5 de plus etc….



Vous aurez 5 catégories d' articles à réaliser : 
    +actualités
    +épreuves
    +conseils
    +médailles
    +interviews


    Les différents page : 
        Utilisateurs : 
            Page d’accueil
            Page avec tous les articles par catégorie (option : mettre une barre de recherche pour retrouver les articles)
            Une page par article
            Page pour voir son compte
            Page pour modifier son compte
            Page d’inscription 
            Page de connexion
            Rédacteur : 
            Page avec tous les articles (pour chacun de _**SES**_ articles accès à la page de l'article à la modification et la suppression + accès création) (option : mettre une barre de recherche pour retrouver les articles)
            Une page par articles (accès à tous les commentaires avec possibilité de les supprimer)
            Page de création d’article
            Page de modification de ses articles
            Page pour voir son compte
            Page pour modifier son compte
            Admin : 
            Page avec tous les articles (pour _**TOUS**_ les articles accès à la page de l'article à la modification et la suppression + accès création) (option : mettre une barre de recherche pour retrouver les articles)
            Une page par articles (accès à tous les commentaires avec possibilité de les supprimer)
            Page de création d’article
            Page de modification d’article
            Page pour voir son compte
            Page pour modifier son compte
            Page avec tous les utilisateurs (pour chaque utilisateur accès à la modification et la suppression)
            Page modification utilisateur
