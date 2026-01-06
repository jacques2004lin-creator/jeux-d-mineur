# jeux-d-mineur
portfolio

 Description

Ce projet est une implémentation complète du jeu du Démineur en langage C, jouable directement dans le terminal.
Il a été réalisé dans un but pédagogique afin de mettre en pratique les bases de la programmation procédurale : tableaux, fonctions, conditions, boucles, récursivité et gestion de la mémoire.

Le jeu propose un menu, des options configurables, ainsi qu’un système de victoire et de défaite fidèle au jeu original.

Structure du projet
 demineur/
 ├── main.c
 ├── inout.h
 ├── inout.c
 
 Fonctionnalités

Grille dynamique :
9x9 ou 16x16
Deux niveaux de difficulté :
Normal
Difficile
Placement aléatoire des mines
Sécurité du premier coup (aucune mine autour)
Propagation automatique des cases vides (récursivité)
Gestion des drapeaux 
Interface console claire et lisible
Menu principal et menu d’options

 Concepts abordés
 
Tableaux 2D
Passage de paramètres par référence
Constantes et macros
Fonctions utilitaires
Récursivité
Gestion des états (caché, ouvert, drapeau)
Génération aléatoire (rand, srand)
Logique de jeu (conditions de victoire/défaite)

 Commandes en jeu
 
1 : Ouvrir une case
2 : Placer / retirer un drapeau
0 : Quitter la partie
Les coordonnées commencent à 1 (ligne et colonne).

LIN jacques
Étudiant / Développeur débutant en C
Projet réalisé dans le cadre d’un apprentissage de la programmation
