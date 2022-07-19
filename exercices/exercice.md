# Exercices UML

## Exercice cas d'utilisation

    1. Créer le diagramme des cas d'utilisation du blog fait en symfony pour les utilisateurs
        Ils peuvent: 
            - Lire les catégories
            - Lire les articles
            - Lire une catégorie
            - Lire un article
            - Laisser un commentaire sur un article (nécessite d'être connecté)
    2. Créer le diagramme des cas d'utilisation du blog pour les administrateurs
        Ils peuvent (en plus des actions des utilisateurs):
            - Ajouter une catégorie
            - Modifier une catégorie
            - Supprimer une catégorie
            - Ajouter un article
            - Modifier un article
            - Supprimer un article
            L'ensemble de ces actions nécessitent qu'ils soient connectés

## Exercice sequence

 1. Réaliser le diagramme en séquence du cas d'utilisation **Ajouter une catégorie** (Une fois que la catégorie est crée l'utilisateur arrive sur la page de la catégorie)
 2. Réaliser le diagramme en séquence du cas d'utilisation **Modifier une catégorie** (Avant de modifier la catégorie, il faut l'afficher)

 ## Exercice classe

 1. Réaliser le diagramme de classe pour l'exercice de sondage comprenant les classes Sondage, Question, Reponse
 2. Exercice RPG


 ### Exercice RPG

 Vous allez réaliser le diagramme de classe d'un jeu

 Dans ce jeu, l'utilisateur va incarner un personnage qui possède de la force(int), des points de vie(int), de la sagesse (int).
 Ce personnage peut être un elfe, ou un orc. 
 L'elfe possède de la dextérité (int) et les sorts déplacements rapide et invocation.
 L'orc possède une force multipliée par 2 (int) et de la défense (int). Il a les compétences tête dur et coup de boule.

 Chaque personnage va posséder des attaques. Ces attaques sont définies par des armes ou des sorts et on un nombre de dégâts (int) et un pourcentage de parade (int).
 Les attaques ont un tracé spécifique en fonction de si ce sont des armes ou des sorts.

 Le personnage va posséder des objets. Ces objets peuvent soigner, brûler, guérir, empoisonner, ...

 