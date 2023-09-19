## Partie 1 : Création d'une Calculatrice en JavaScript

[Calculatrice simple](./index.html)

### Mise en place de l'atelier

- Créez un dossier "simple-calculator" et un fichier "index.html" vide à l'intérieur.
- Ajoutez la structure HTML5 à "index.html".
- Utilisez une balise `<script>` pour écrire du code JavaScript.
- Ouvrez le fichier dans un navigateur pour vérifier que tout fonctionne.

### Ce que vous obtenez

La structure de base d'une page HTML5 avec un script JavaScript.

### Les premières instructions

- Créez des variables pour stocker les valeurs et l'opérateur.
- Utilisez des `console.log` pour afficher les valeurs.
- Utilisez la fonction `prompt` pour permettre à l'utilisateur de saisir des valeurs.
- Utilisez `console.log` pour afficher la somme des valeurs.

### On agit sur l'opérateur

- Ajoutez une condition basée sur l'opérateur.
- Si l'opérateur est "+", effectuez une addition ; sinon, effectuez une soustraction.

### Dernières instructions

- Ajoutez des conditions pour les opérateurs "-", "*", et "/" en utilisant "else if".
- Affichez le résultat de chaque opération avec `console.log`.
- Ajoutez une clause "else" pour gérer les opérateurs non valides.

N'oubliez pas de rendre le code réutilisable en encapsulant le tout dans une fonction (bonus). Cet atelier vous aidera à comprendre les concepts de base de JavaScript en construisant une calculatrice simple.

## Partie 2: Création d'un Jeu en JavaScript

[Le juste prix](./justePrix.html)

Si vous souhaitez créer un petit jeu, suivez ces étapes similaires à la partie "Mise en place de l'atelier", en modifiant simplement le nom du dossier.

1. Demandez le nom du joueur ou de la joueuse.

2. Stockez un nombre aléatoire entre 1 et 100 (le prix à trouver) dans une variable. Par exemple : `const rightPrice = Math.ceil(Math.random() * 100);`

3. Demandez un nombre au joueur ou à la joueuse (entre 1 et 100).

4. Si le nombre est supérieur au juste prix, affichez "C’est moins".

5. Si le nombre est inférieur au juste prix, affichez "C’est plus".

6. Si le nombre est égal au juste prix, affichez "Bravo <nom> tu as gagné !" avec `<nom>` qui est remplacé par le nom saisi au début du jeu.

Le jeu s'arrête lorsque le joueur gagne. C'est une façon amusante d'implémenter un petit jeu en JavaScript où le joueur doit deviner un nombre aléatoire.