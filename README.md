# Projet de Blog

## Fonctionalités

Sur la page principale, on peux voir les différents articles :
    - Titre
    - Auteur
    - Les 500 premiers caractères du post, si le post est trop long " ... lire la suite" s'affichera à la fin du post.

Il est possible de cliquer sur les articles pour pouvoir les lire dans leur entierté. (même si leur taille est inférieur à 500 caractères) A la fin de l'article, un bouton de retour peut être trouvé.

### Visite anonyme

Le site est accessible en anonyme. Dans ce cas, le visiteur peux voir les articles mais ne peux pas en créer de nouveau.
Dans ce cas, un message indiquant au visiteur qu'il n'est pas connecté s'affichera, un lien y est aussi disponible pour la connexion.

### Connexion & Inscription

Sur la page de la connexion, les champs nom d'utilisateur et mot de passe sont requis pour la connexion. En bas de la page, un lien est disponible pour la création du compte.
Lors de l'inscription, il faut renseigner un nom d'utilisateur, un mot de passe et la confirmation du mot de passe. Les noms d'utilisateurs doivent être unique, le mot de passe doit contenir au minimum 6 caractères.

### Rédaction, Modification et Suppression d'articles

Un fois l'utilisateur connecté, deux nouvelles options seront disponibles sur la page principale. A gauche, l'icône de crayon peut rédiger un article. A droite l'icône de déconnexion permet de se déconnecter.

#### Rédaction

Si l'utilisateur choisit de rédiger un article, il sera diriger vers la page de rédaction. Il y est demandé de saisir un titre pour l'article ansi que son contenu. Il suffit ensuite de cliquer sur le bouton "Enregistrer" pour envoyer le post.

#### Modification & Suppresion

Seul l'auteur de l'article est capable de modifier ou de supprimer l'article en question. Si l'utilisateur connecté est l'auteur du post, à la fin de l'article -sur la page qui affiche l'article complet- une option de supression et une option d'édition du post.
La page d'édition est la pratiquement la même que la page de [rédaction](#rédaction).

## Technologies

Version de php : PHP 7.4.13

J'ai utilisé quelques morceau de CSS du template que j'ai utilisé pour le TP1 (CV) ansi que *Font Awesome* pour les icônes.
