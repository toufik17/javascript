# javascript

## Écriture d'une fonction renvoyant une valeur

Appel à une fonction retournant une valeur</br>
1. Créez deux variables globales a et b, initialisées respectivement à 3 et à 2.
2. Créez une fonction multiplie prenant un argument x prenant comme valeur par défaut 8, et renvoyant le résultat de la multiplication de x par 3
3. Créez une fonction affiche, appelée au clic sur le bouton, qui affiche dans des boîtes d'alerte successivement le résultat de multiplie appliquée a, à b, puis sans aucun paramètre (en exécutant donc la fonction avec la valeur de x par défaut)


## Utilisation d'un tableau

Appel à une fonction retournant une valeur
1. Créez un tableau nommé tab dont le premier élément est -2, le deuxième 1 et le troisième 4
2. Créez une fonction additionne prenant un argument x et renvoyant le résultat de l'addition de x à 2
3. Créez une fonction affiche, appelée au clic sur le bouton, qui affiche dans des boîtes d'alerte successivement le résultat de additionne appliqué au premier élément, puis au dernier élément du tableau (en utilisant la propriété length).

## Utilisation de switch et de l'objet Date

Au click sur le bouton, lancer la fonction jourDeLaSemaine(). Cette fonction détermine le jour de la semaine et affiche selon le cas dimanche, lundi, mardi... etc. jusqu'à samedi.

## Changements de couleurs

__Introduction__
Les changements de couleurs d'une zone de texte font appel à onmouseover, onmouseout, onclick et ondblclick, ainsi qu'aux méthodes de contrôle du style par JavaScript appliquées à l'objet courant indiqué par this.


__Exercice__

Créer une page web comportant une phrase, dont un groupe de mots, de couleur noire au chargement, doit prendre la couleur :

1. rouge au passage de la souris ;
2. citron vert (lime) en réponse à un click ;
3. bleu marine (navy) en réponse à un double click.

## Changements de contenus

__Introduction__

Il est possible de changer le contenu d'un tag. On peut réaliser un rollover, qui consiste à changer une image au passage de la souris, ce qui sert parfois lorsqu'il s'agit de matérialiser l'activation possible d'un bouton par exemple. Mais il est également envisageable de modifier le contenu de l'élément lui-même, comme par exemple le texte inséré entre deux tags <b> et </b>. On utilise pour ce faire la propriété this.innerHTML.

__Exercices__

1. Trouver deux images si possible de tailles différentes sur le PC ; les insérer dans une page web élémentaire en rollover. Tenir compte des effets de hauteur et de largeur de telle manière qu'aucune image ne soit déformée.

2. A l'aide de la propriété this.innerHTML que l'on expérimentera, reproduire l'exemple suivant :
Un petit texte avec un texte en italique au milieu
