# Projet de tests fonctionnels - Produits_CRUDS

Ce projet vise à ajouter des tests fonctionnels aux applications Web [Products_CRUDS](https://mohamedmamdouh1999.github.io/Products_CRUDS/).

## Instructions de test
- Visitez [https://mohamedmamdouh1999.github.io/Products_CRUDS/](https://mohamedmamdouh1999.github.io/Products_CRUDS/) pour tester l'application.

## Les cas de tests

Cas usuel - ajout de produits premium
1. Description : L'utilisateur accède à la page d'accueil et ajoute des produits contenant des informations valides.
Action:
Ouvrez un navigateur et accédez à https://mohamedmamdouh1999.github.io/Products_CRUDS/.
Cliquez sur le champ Nom du produit et saisissez « Mi 9T ».
Cliquez dans le champ Prix du produit et saisissez « 1000 ».
Cliquez dans le champ Catégorie de produit et sélectionnez une catégorie (non spécifiée dans le script).
Cliquez sur le bouton Ajouter.
Vérifier:
Assurez-vous que le produit a été ajouté avec succès (vérifiez si le produit apparaît dans la liste des produits).


Cas extrême : tentative d'ajout d'un produit avec un nom incorrect
2. Description : L'utilisateur a tenté d'ajouter un produit avec un nom incorrect (les champs obligatoires sont manquants).
Action:
Ouvrez un navigateur et accédez à https://mohamedmamdouh1999.github.io/Products_CRUDS/.
Cliquez dans le champ Nom du produit sans rien saisir.
Cliquez dans le champ Prix du produit et entrez une valeur valide.
Cliquez sur le bouton Ajouter.
Vérifier:
Assurez-vous qu'une alerte s'affiche indiquant que le nom du produit est requis.


Cas d'erreur - Ajout d'un produit avec un prix incorrect
3. Description : L'utilisateur a tenté d'ajouter un produit avec un prix incorrect (double-clic sur le champ).
Action:
Ouvrez un navigateur et accédez à https://mohamedmamdouh1999.github.io/Products_CRUDS/.
Cliquez dans le champ Nom du produit et entrez un nom valide.
Cliquez dans le champ Prix du produit et entrez une valeur valide.
Double-cliquez sur le champ Prix du produit.
Cliquez dans le champ Catégorie de produit et sélectionnez une catégorie (non spécifiée dans le script).
Cliquez sur le bouton Ajouter.
Vérifier:
Assurez-vous qu'une alerte s'affiche indiquant que le prix du produit est incorrect.



## Crédits
Ce projet est basé sur les travaux de [MohamedMamdouh1999](https://github.com/MohamedMamdouh1999/Products_CRUDS).

## Membres du Groupe
- Adrien M
- Boris K
