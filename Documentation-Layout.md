# Documentation mise en page

Informations pour le développement.

## Largeur du site

Selon la maquette originale 2025-26, la largeur maximum du site est définie à *1728px*. Cette valeur est définie de la façon suivante:  
Dans le **Gestionnaire de styles > Styles de thème > Eléments > Container** : **Largeur** est défini à 1728.

<img width="444" height="54" alt="image" src="https://github.com/user-attachments/assets/0cfb9be2-3d52-42ca-a30e-6b140cfa77a7" />

Etant donné que le **Container** fonctionne en Flexbox, cette largeur est une "largeur maximum" et pas une largeur fixe.

## Principes importants

* On donne aux éléments **Section** un réglage de "Padding" à gauche et à droite, avec la variable var(--space-L). Cela assure que le contenu ne touche pas le bord.
* Les **Container** n'ont pas de marge ou padding, mais leur largeur maximale est définie (voir ci-dessus).
