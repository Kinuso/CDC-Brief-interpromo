# Cahier des charges Brief Inter Promo

## Contexte

Vous êtes missionné pour créer un site de blog amateur concernant les jeux olympiques.

Il y aura une partie admin qui pourra gérer les utilisateurs et différents articles, une partie rédacteurs, qui pourront gérer et modifier leur compte ainsi que leurs articles, tout en pouvant accéder aux articles des autres rédacteurs (sans pouvoir les modifier)

Les utilisateurs devront arriver sur une page d’accueil.

Le lien [Figma](https://www.figma.com/design/cLwKW2Py9YAZyoOJ9661lI/L'odyssé-Olympique?node-id=0-1&t=oGHRkFJ5U1xlUKJV-0) pour les maquettes 
## Liste des droits 

![image](https://github.com/user-attachments/assets/5cbe8692-73c5-4bf0-906c-74ea92ae5860)


## Attentes techniques 


Lors de l’inscription, on voudra retrouver :  
&emsp;&emsp;__L’adresse mail__   
&emsp;&emsp;__Mot de passe__   
&emsp;&emsp;__Nom__   
&emsp;&emsp;__Prénom__


Pour la connexion :   
&emsp;&emsp;__Adresse mail__   
&emsp;&emsp;__Mot de passe__   
      
Option :  
    ajouter un bouton “mot de passe oublié” avec l’emailing ainsi qu’utilisation de token dans l’url pour la sécurité  


Le compte de l’utilisateur devra lui permettre : 
    Tout le CRUD concernant son compte  
    Option : 
        Supprimer ses commentaires des posts, puis de pouvoir retrouver dans son profil tous les posts qu’il a commenté  
        Retrouver dans son profil tout les post qu’il a aimé  



Pour les articles il faut :   
&emsp;&emsp; __Titre__   
&emsp;&emsp; __Image__ (Un URL sera suffisant, si vous souhaitez aller plus loin, l’ajout d’une image téléchargé depuis son ordinateur par l’utilisateur)   
&emsp;&emsp; __Description__ (max 1000 caractères)   
&emsp;&emsp; __Nom__, __prénom__   
&emsp;&emsp; __Date__   
&emsp;&emsp; __Commentaires__   
&emsp;&emsp; __Like__ , en affichant le nombre  
  

Sur la page d'accueil, seuls les 6 premier articles seront affichés, si la description dépasse les 50 caractères, on cachera le reste pour garder une taille fixe.  


Les commentaires des articles seront affichés uniquement quand on sera sur la page affichant l’article en entier, seuls les 5 premiers devront apparaître pour une lecture de page plus claire, un bouton “afficher plus” permettra d’en afficher 5 de plus etc…  


Vous aurez 5 catégories d' articles à réaliser :  
&emsp;&emsp;  __actualités__   
&emsp;&emsp;  __épreuves__   
&emsp;&emsp;  __conseils__   
&emsp;&emsp;  __médailles__   
&emsp;&emsp; __interviews__ 
      
## Les différents page   

Utilisateurs :   
&emsp;&emsp;Page d’accueil   
&emsp;&emsp;Page avec tous les articles par catégorie (option : mettre une barre de recherche pour retrouver les articles)   
&emsp;&emsp;Une page par article  
&emsp;&emsp;Page pour voir son compte  
&emsp;&emsp;Page pour modifier son compte  
&emsp;&emsp;Page d’inscription   
&emsp;&emsp;Page de connexion  

Rédacteur :   
&emsp;&emsp;Page avec tous les articles (pour chacun de __SES__ articles accès à la page de l'article à la modification et la suppression + accès création)  
&emsp;&emsp;(option : mettre une barre de recherche pour retrouver les articles)  
&emsp;&emsp;Une page par articles (accès à tous les commentaires avec possibilité de les supprimer)  
&emsp;&emsp;Page de création d’article  
&emsp;&emsp;Page de modification de ses articles  
&emsp;&emsp;Page pour voir son compte  
&emsp;&emsp;Page pour modifier son compte  

Admin :   
&emsp;&emsp;Page avec tous les articles (pour __TOUS__ les articles accès à la page de l'article à la modification et la suppression + accès création)  
&emsp;&emsp;(option : mettre une barre de recherche pour retrouver les articles)  
&emsp;&emsp;Une page par articles (accès à tous les commentaires avec possibilité de les supprimer)  
&emsp;&emsp;Page de création d’article  
&emsp;&emsp;Page de modification d’article  
&emsp;&emsp;Page pour voir son compte  
&emsp;&emsp;Page pour modifier son compte  
&emsp;&emsp;Page avec tous les utilisateurs (pour chaque utilisateur accès à la modification et la suppression)  
&emsp;&emsp;Page modification utilisateur  
