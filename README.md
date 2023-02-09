# Projet 2: Booki
Deuxième projet du parcours "Développeur web" chez OpenClassroom. L'objectif est de transformer une maquette en site web avec HTML5 & CSS3.

<img src="https://user-images.githubusercontent.com/98737248/217825346-0de37e2b-cc12-47e5-9576-6e692255e834.svg" style="height:35px;"> [![forthebadge](https://forthebadge.com/images/badges/powered-by-coffee.svg)](https://forthebadge.com)

#### Visualiser le site ici [https://alyciabedel.github.io/Booki/]

![bannière booki](https://user-images.githubusercontent.com/98737248/217827698-1734f038-3bc9-4cbc-bb21-09cdf6acf8f1.png)


## Qui est Booki ?
Booki est une entreprise qui souhaite développer un site internet qui permette aux usagers de trouver des hébergements et des activités dans la ville de leur choix.

## Objectifs
1. Développer un site responsive à partir d'une maquette en HTML5 & CSS3.
2. Validation du code W3C.

## Technologies
- Utilisation de HTML5 et CSS3. 
- Interdiction d'utiliser un framework CSS (type BootStrap ou Tailwind CSS) ou préprocesseur CSS (type Sass ou Less).

## Compatibilité
Le site sera responsive pour les ordinateurs, tablettes et mobiles. La maquette est compatible avec les dernières versions de Google Chrome et de Mozilla Firefox.

## Spécifications fonctionnelles
- Les usagers pourront rechercher des hébergements dans la ville de leur choix. Le champ de recherche est un champ de saisie, le texte doit pouvoir être édité par l’utilisateur. On englobe ce champ dans un formulaire pour que ce dernier soit valide auprès du W3C. La partie recherche n'est pas fonctionnelle.
- Chaque carte d’hébergement ou d’activité est cliquable dans son intégralité (pas uniquement le titre). Pour l’instant, les liens sont vides. On utilise un attribut `href=”#”` pour simuler la présence d’un lien.
- Les filtres changent d’apparence au survol. Par contre, ils ne sont pas fonctionnels.
- Les textes “Hébergements” et “Activités”, situés dans l’en-tête, sont des liens. Ils menent respectivement vers la section “Hébergements à Marseille” et “Activités à Marseille”.

## Spécifications techniques
- Deux maquettes ont été réalisées : l’une desktop et l’autre mobile. 
- Les breakpoints : 992 px pour les écrans d’ordinateurs et 768 px pour les tablettes, et tout ce qui est en dessous de 768 pour les mobiles.
- Réalisation en premier de l’intégration pour les ordinateurs (desktop first), avec l’utilisation des Media Queries.
- Choix du format d'image le plus adapté par rapport à la résolution et au temps de chargement.
- Utiisation des pixels et des pourcentages plutôt que les REM et les EM.
- Utilisation de Flexbox plutôt que Grid car c’est la technologie que l’équipe maîtrise le mieux.
- Utilisation des balises sémantiques (type `main`, `header`, `nav`, etc.).
- Le code doit être valide aux validateurs W3C HTML et CSS.
- Il n’est pas nécessaire de versionner le code.

## Identité graphique
### Polices
- Texte: Raleway [https://fonts.google.com/specimen/Raleway]

### Icônes
- Font Awesome [https://fontawesome.com/]

### Couleurs
- Bleu #0065FC 
- Bleu claire #DEEBFF 
- Gris #F2F2F2
