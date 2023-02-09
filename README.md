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
La cible étant les personnes connectées et pressées, le site sera développé en utilisant l’approche mobile-first. Sur tablette et desktop, le site devra s’adapter.

## Spécifications fonctionnelles
- Les usagers pourront rechercher des hébergements dans la ville de leur choix. Le champ de recherche est un champ de saisie, le texte doit donc pouvoir être édité par l’utilisateur. Il faut englober ce champ dans un formulaire pour que ce dernier soit valide auprès du W3C. La partie recherche ne doit pas être fonctionnelle.
- Chaque carte d’hébergement ou d’activité devra être cliquable dans son intégralité (pas uniquement le titre). Pour l’instant, les liens sont vides. On peut utiliser un attribut `href=”#”` pour simuler la présence d’un lien.
- Les filtres doivent changer d’apparence au survol. Je te laisse décider de l’effet approprié, je n’ai pas encore eu le temps de me pencher dessus. Par contre, ils ne doivent pas être fonctionnels.
- Les textes “Hébergements” et “Activités”, situés dans l’en-tête, sont des liens. Ils doivent mener respectivement vers la section “Hébergements à Marseille” et “Activités à Marseille”.

## Spécifications techniques
- Deux maquettes ont été réalisées : l’une desktop et l’autre mobile. Le site devra être également adapté aux formats tablette. Pour les tablettes, nous sommes libres de faire les adaptations nécessaires. Il est important qu’aucun élément ne soit coupé, et que le texte ait une taille suffisante.
- Concernant les breakpoints, nous avons convenu avec le designer UI d’utiliser 992 px et 768 px. 992 px pour les écrans d’ordinateurs et 768 px pour les tablettes, et tout ce qui est en dessous de 768 pour les téléphones portables.
- Il faut d’abord réaliser l’intégration pour les ordinateurs (autrement dit, en desktop first), puis les tablettes et enfin les téléphones. L’utilisation des Media Queries nous permettra de réaliser l’intégration pour les différents supports.
- Plusieurs formats et tailles d’images ont été exportés. Il faudra choisir le format le plus adapté par rapport à la résolution et au temps de chargement.
- Il est important d’utiliser les pixels et les pourcentages plutôt que les REM et les EM.
- Il est important d’utiliser Flexbox plutôt que Grid car c’est la techno que l’équipe maîtrise le mieux.
- Il est important d’utiliser des balises sémantiques (type `main`, `header`, `nav`, etc.).
- Le code doit être valide aux validateurs W3C HTML et CSS.
- La maquette doit être compatible avec les dernières versions de Google Chrome et de Mozilla Firefox. Il faudra tester le prototype sur ces deux navigateurs.
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
