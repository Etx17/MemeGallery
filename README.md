# MemeGallery
A participative gallery of memes, and nothing else.

## Specs & guidelines

  0. AUTHENTIFICATION
- L’utilisateur doit pouvoir s’authentifier et se déconnecter s’il veut liker et ajouter un contenu
- Il doit avoir un message d’erreur s’il est mal authentifié
- Le form doit avoir de la validation de format.
- Crypter les données abec bcrypt?
- Utiliser une confirmation de création de compte avec le mailer.

1. BASE DE DONNEE:
- Dessiner la table
- Seeder des users et des contenus
- Qu’il y ait une ou plusieurs catégories par même
- Qu’il y ait des commentaires
- Qu’on puisse voir quel utilisateur ait lié quel post, et quels commentaires il a. Donc stocker.

2. PAGES :
- Une seule page Home, scrollable ( mais ne pas charger tout, la charger que quand on scroll si possible)
- Sign in par dessus la page qui l’assombrit derriere, avec option continuer sans s’identifier.
- Navbar pour l’utilisateur et le call to action: ajouter un meme. Cette navra doit être en haut et permettre à l’utilisateur de se déconnecter. Elle doit être sticky au fur et a mesure que l’utilisateur scroll.

3. CARD MÊME:
- Doit pouvoir être soit crée, soit supprimée, mais pas éditée. Crée, c'est crée.
- Catégorie obligatoire
- Photo obligatoire
- Title obligatoire
- Likes, comments
- Si clique ou commente, le rediriger vers le sign in.
 - doit centrer l’image si jamais on nous donne un truc carré ou pas bien formaté.

3. STYLES :
- Doit être compatible juste avec téléphone et laptop.
- Display grid sur laptops, column sur telephone.
-


Coding plan :
 // Tests
1. Dessiner la base de données avec toutes les relations nécessaires
2. Créer le projet sur GitHub, le cloner localement.
3. Créer le projet rails en question
3.5 Créer les modeles
4. Créer les migrations
5. Seeder la base de données
6. Faire le form de création de card
7. Coder juste rapides un squelette css pour avoir une navbar, une grid avec quelques cards juste pour voir.
