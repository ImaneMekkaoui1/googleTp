# Reproduction de la Page d’Accueil Google en HTML/CSS
### Description
Bienvenue dans ce Tp académique consistant à reproduire l’interface principale de la page d’accueil de Google en utilisant uniquement HTML et CSS afin de comprendre les bases de la structuration d’une page web et de la mise en forme avec Flexbox.

### Objectif

L’objectif de ce TP est de :

Comprendre la structure d’une page HTML.

Manipuler les balises sémantiques (header, nav, div, section...).

Apprendre la mise en page avec Flexbox.

Appliquer du CSS moderne pour reproduire une interface réelle.

 ### Structure du Projet
Le projet est organisé de manière simple pour séparer la structure et le style

````Plaintext
.
├── index.html    # Structure HTML de la page
├── style.css     # Feuilles de style CSS
└── README.md     # Documentation du projet
`````

### Fichier HTML (index.html)

#### Le fichier HTML contient la structure principale de la page :

##### Header

. Barre de navigation en haut à droite :

  - Gmail

  - Images

  - Icône applications

  - Icône profil

###### Main

Contient deux sections principales :

Section Logo

Affichage du logo Google centré.

##### Section Recherche

- Barre de recherche

- Icônes (recherche + micro)

- Boutons :

    . Recherche Google

    . J’ai de la chance


### Fonctionnalités
Barre de navigation (Header) : Liens Gmail et Images avec effets au survol.

Section centrale (Main) : Logo Google officiel et barre de recherche interactive.

Barre de recherche : Design arrondi avec icônes de recherche et micro, incluant un effet d'ombre au survol (box-shadow).

Boutons d'action : Boutons "Recherche Google" et "J'ai de la chance" stylisés selon la charte graphique.

Design Responsive : Mise en page centrée verticalement et horizontalement.



### Fichier CSS (style.css)

Le fichier CSS gère toute la mise en forme visuelle.
````
Reset CSS
*{
 margin:0;
 padding:0;
 box-sizing:border-box;
}
````
Permet d’éviter les problèmes d’espacement par défaut des navigateurs.

Mise en page avec Flexbox

Utilisation de :

- display:flex

- justify-content

- align-items

pour :

- centrer le contenu

- aligner les éléments horizontalement

- créer une interface propre

- Effets visuels ajoutés

- Hover sur la barre de recherche

- Hover sur les boutons

- Bordures arrondies

- Ombres légères

#### Concepts Appris

Ce TP permet de comprendre :

. Structure HTML sémantique

. Séparation HTML / CSS

. Flexbox

. Organisation d’un mini projet Front-End

. Reproduction d’une interface existante (UI Practice)

. Stack Technique


#### Améliorations Possibles

Ajouter du JavaScript pour rendre la recherche fonctionnelle.

Rendre la page responsive avec Media Queries.

Ajouter un footer similaire à la vraie page.

Remplacer les icônes par une bibliothèque comme Font Awesome.

#### Résultat Attendu

Une interface visuellement proche de la page d’accueil Google avec :

Logo centré

Barre de recherche stylisée

Navigation en haut à droite

### Conclusion

Ce TP constitue une première étape importante pour maîtriser le développement Front-End.
Il permet de comprendre comment structurer une page web proprement et appliquer du style CSS pour reproduire une interface réelle.



