# App-gestion-de-produits-php
Application de Gestion de Produits en PHP
Ce projet PHP vise à créer une application simple de gestion de produits. Trois pages distinctes sont nécessaires pour réaliser cette tâche : index.php, traitement.php, et recap.php.

Pages Principales
Page index.php
Cette page présentera un formulaire permettant à l'utilisateur de renseigner :

Le nom du produit
Son prix unitaire
La quantité désirée
Page traitement.php
Cette page traitera la requête provenant de index.php (après soumission du formulaire). Elle ajoutera le produit avec son nom, son prix, sa quantité et le total calculé (prix × quantité) en session.

Page recap.php
Cette page affichera tous les produits en session avec des détails et présentera le total général de tous les produits ajoutés.

Fonctionnalités
Enregistrement en Session : Les produits renseignés seront enregistrés en session pour une consultation ultérieure.

Calcul Automatique du Total : Le total pour chaque produit (prix × quantité) sera calculé automatiquement.

Affichage des Produits et du Total Général : La page recap.php affichera tous les produits en session avec des détails et présentera le total général de tous les produits ajoutés.
