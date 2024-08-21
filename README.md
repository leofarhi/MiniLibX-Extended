# MiniLibX-Extended

MiniLibX-Extended est une extension de la bibliothèque MiniLibX, offrant des fonctionnalités supplémentaires qui permettent d'exploiter pleinement le potentiel de la bibliothèque d'origine sans la modifier. Cette surcouche est conçue pour faciliter le développement graphique en ajoutant de nouvelles fonctionnalités tout en simplifiant la gestion des ressources.

## Exemple d'utilisation

Voici un exemple d'application utilisant MiniLibX-Extended : [so_long](https://github.com/leofarhi/so_long42).

## Fonctionnalités

MiniLibX-Extended propose un ensemble étendu de fonctionnalités par rapport à la bibliothèque MiniLibX classique. Voici quelques-unes des capacités supplémentaires que cette extension apporte :

- **Dessin avancé** : possibilité de dessiner des pixels, des lignes, et des rectangles (remplis ou non).
- **Gestion des images** : importation et affichage d'images, y compris la possibilité d'afficher des sous-textures (fragments d'image) avec redimensionnement et application de teintes spécifiques. La gestion de l'alpha (transparence) est également supportée.
- **Affichage de texte** : affichage de texte avec des polices personnalisées (TTF, OTF) converties au préalable avec le script `ttf2xpm.py`.
- **Gestion des entrées** : nouvelle version de l'input permettant de vérifier l'état des touches (IsKeyDown, IsKeyPressed, IsKeyUp) directement dans la boucle principale, au lieu d'utiliser le système de callbacks traditionnel.

## Utilisation

Pour utiliser MiniLibX-Extended dans votre projet, suivez ces étapes :

1. **Ajoutez** les bibliothèques MiniLibX et MiniLibX-Extended à votre projet.
2. **Compilez** les deux bibliothèques.
3. **Utilisez exclusivement** MiniLibX-Extended dans votre code. Cette bibliothèque gère automatiquement de nombreuses fonctionnalités en arrière-plan, comme la libération de la mémoire grâce à un garbage collector intégré.
4. **Affichage optimisé** : MiniLibX-Extended utilise un buffer pour l'affichage, minimisant ainsi les clignotements à l'écran.
