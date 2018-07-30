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

## Premiers pas dans le DOM

Manipulation des méthodes d'accès aux éléments

__Introduction__

L'exemple du cours vous a montré comment utiliser les méthodes getElementById, getElementsByName et getElementsByTagName, ainsi que leurs limitations.

Dans l'exercice suivant, vous allez apprendre à les utiliser, ainsi qu'une autre méthode.

__Exercice méthodes getElementById, getElementsByName et getElementsByTagName__

1. Créer une page HTML vide dans laquelle vous aurez à insérer votre code JavaScript. Notez en passant l'utilisation des attributs title pour informer sur les éléments de titre et paragraphe (pour les tester, laisser la souris au-dessus de l'élément).
2. Créer une fonction modif_paragraphe, appelée en cliquant sur le titre. Cette fonction sélectionne le paragraphe en utilisant son identifiant, puis le modifie avec la propriété innerHTML, en remplaçant le mot original en caractères droit par le mot corrigé, en italique.
3. Créer une fonction centrage_h1, appelée en cliquant sur le paragraphe. Cette fonction détecte d'abord les éléments portant le nom de balise h1. Elle sélectionne ensuite le premier d'entre eux (ça tombe bien, il n'y en a qu'un seul sur la page !), et modifie son attribut align, en lui affectant la valeur "center", à l'aide de la méthode setAttribute... dont vous testerez le fonctionnement.

## Accès relatif aux noeuds

1. Télécharger le fichier /exoEnfant/exoEnfantvide.html.
2. La fonction change_enfants() sélectionne le paragraphe à l'aide de son identifiant.
3. Combien d'enfants le paragraphe a-t'il ? Pourquoi ?
4. Changer la valeur du premier enfant de l'élément paragraphe en "On change le texte plein d'enfants ".
5. Diviser par deux les hauteur et largeur de l'image (le dernier enfant).
6. Changer le code HTML du deuxième enfant en "<font color='blue'>en bleu</font>"
7. Changer la propriété display de style du quatrième enfant en "block".
