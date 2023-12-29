# Garry's Piece

- Visiter mon projet sur Vercel : https://ece-webtech-609.vercel.app
- URL Supabase : https://supabase.com/dashboard/project/szimsxzignpvhltdqkgk

## Authors

- Rany KARDOUS GR06

## Table des Matières
- [Accueil](#accueil)
- [Navigation](#navigation)
- [Login et Page de Profil](#login-et-page-de-profil)
- [Création et Affichage de Posts](#cr\u00E9ation-et-affichage-de-posts)
- [Création et Affichage de Commentaires](#cr\u00E9ation-et-affichage-de-commentaires)
- [Modification et Suppression de Posts](#modification-et-suppression-de-posts)
- [Recherche](#recherche)
- [Utilisation d'une API Externe](#utilisation-dune-api-externe)
- [Contrôle d'Accès aux Ressources](#contr\u00F4le-dacc\u00E8s-aux-ressources)
- [Paramètres du Compte](#param\u00E8tres-du-compte)
- [Intégration WYSIWYG](#int\u00E9gration-wysiwyg)
- [Intégration Gravatar](#int\u00E9gration-gravatar)
- [Mode Clair/Sombre](#mode-clairsombre)
- [Feedback](#feedback)

## Naming convention
**Points:** 2 (facile)
Les conventions de nommage ont été respectées.

## Project structure
**Points:** 2 (facile)
La structure du projet correpond à celle demandée pour le groupe 06.

## Git usage
**Points:** 2 (facile)
Les commits sont assez détaillés pour savoir quelles parties du projet ont été modifiées.

## Code Quality
**Points:** 3 ou 4 (moyen)
Les commentaires sont suffisants pour comprendre les blocs importants, cependant, certaines indentations ont été ignorées seulement au niveau du code des balises par soucis de rapidité et d'efficacité.

## Design, UX, and content
**Points:** 4 (moyen)
Un effort conséquent a été fourni afin de parvenir à un design moderne et optimal.

## Accueil
![Home Page](/images/Home.PNG)
**Points:** 2 (facile)
Création d'une page d'accueil conviviale, attrayante, informative avec un appel à l'action (CTA).

## Navigation
![Navigation Bar](/images/Nav.PNG)
**Points:** 2 (facile)
Implémentation d'une barre de navigation avec des liens vers plusieurs pages, 'Home' est liée à la page d'accueil, 'Unsplash' est lié à la présentation de l'API externe et 'Suggestions' est lié aux publications. Il est possible de se connecter via le bouton Login qui va rediriger vers la page de connexion. La barre de recherche est disponible pour rechercher des publications via leur contenu ou leur tag.

## Login et Page de Profil
![Login](/images/Login.PNG)
![Profile](/images/Profile.PNG.png)
**Points:** 4 (moyen)
Intégration d'un bouton de connexion/déconnexion dans l'en-tête et affichage des informations de l'utilisateur sur la page de profil.

## Création et Affichage de Posts
![Post Creation](/images/Create_Post.PNG)
![Post Display](/images/Display_Post.PNG)
![Oops](/images/Oops.PNG)
**Points:** 6 (difficile)
Permettre la création de posts par les utilisateurs authentifiés et afficher une liste de posts paginée et triée par date de création (La page de création de publications n'est pas accessible pour les utilisateurs déconnectés).

## Création et Affichage de Commentaires
![Comments](/images/Comments.PNG)
**Points:** 4 (moyen)
Affichage d'un formulaire en bas des pages de posts permettant aux utilisateurs de laisser des commentaires.

## Modification et Suppression de Posts
![Edit and Delete Posts](/images/Edit_Delete_Posts.PNG)
**Points:** 4 (moyen)
Permettre à l'auteur d'un post de voir le bouton "éditer" pour modifier ou supprimer son post.

## Recherche
![Search](/images/Search.PNG)
**Points:** 6 (difficile)
Création d'une barre de recherche pour trouver des posts, avec recherche effectuée côté serveur (La recherche supabase s'effectue sur deux colonnes; content et tags.).

## Utilisation d'une API Externe
![External API](/images/Unsplash.PNG)
**Points:** 2 (facile)
Intégration de l'API Unsplash pour enrichir le contenu de l'application avec des images thématiques.

## Contrôle d'Accès aux Ressources
![Resource Access Control](/images/RLS.PNG)
**Points:** 6 (difficile)
Sécurisation des données de l'application, utilisation de RLS de Supabase pour prévenir les accès et tentatives d'intrusion non autorisés.

## Paramètres du Compte
![Account Settings](/images/Profile.PNG)
**Points:** 4 (moyen)
Création d'un tableau de bord pour que l'utilisateur puisse modifier ses paramètres personnels (email, nom, langue, photo de profil...).

## Intégration WYSIWYG
![WYSIWYG](/images/WYSIWYG.PNG)
**Points:** 2 (facile)
Intégration d'une bibliothèque WYSIWYG pour l'édition du contenu des posts (react-quill).

## Intégration Gravatar
![Gravatar](/images/Comments.PNG)
**Points:** 2 (facile)
Affichage de l'icône utilisateur Gravatar à côté de ses commentaires, dans l'en-tête et sur la page de profil (Une image aléatoire est attribuée lorsqu'aucune URL d'image n'est reçue).

## Mode Clair/Sombre
![Light Mode](/images/Home.PNG)
![Dark Mode](/images/Dark.PNG)
**Points:** 2 (facile)
Implémentation du basculement entre les thèmes clair et sombre en utilisant Tailwind CSS.

## Feedback

J'ai trouvé ce cours extrêmement enrichissant. La structure était claire et les TPs ont vraiment aidé à consolider ma compréhension. J'ai particulièrement apprécié la section sur l'utilisation de supabase, qui a ajouté une dimension intéressante au projet. Une suggestion serait d'inclure plus de contenu sur les meilleures pratiques de sécurité pour les applications web modernes.


