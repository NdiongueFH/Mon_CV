# Projet de Groupe CV en Ligne

## Description
Ce projet consiste à développer un CV en ligne pour chacun des membres de notre groupe. Le site web présentera des informations professionnelles telles que l'éducation, l'expérience, les compétences, etc., de chaque membre, utilisant HTML, CSS, et des images optimisées.

## Structure du Projet
Le projet est structuré comme suit:
- `index.html` - Le fichier HTML principal du site.
- `style.css` - Le fichier CSS pour styliser la page.
- `images/` - Un dossier contenant les images utilisées, y compris `imageProfil.png` pour les photos de profil.

## Début du Projet
1. **Création du Projet**: Le projet a été initialisé avec les fichiers `index.html` et `style.css`, ainsi qu'un dossier `images` pour les ressources visuelles.
2. **Clonage sur la Machine du Mainteneur**: Le projet a été cloné sur la machine du mainteneur pour centraliser le développement et la gestion du projet.

## Développement HTML
- Mise en place de la structure de base du HTML.
- Définition des `id` et des `class` pour les éléments HTML afin de faciliter le stylisme CSS.

## Choix des Couleurs
- Les codes couleurs et polices ont été choisis pour maintenir une cohérence visuelle à travers le site. Les nuances de vert-de-gris sont employées comme thème principal.
-    :root {
    /* Définition des couleurs de base */
    --teal-1: #265C4B; /* Teal foncé */
    --teal-2: #146551; /* Teal moyen foncé */
    --teal-3: #007566; /* Teal vif */
    --teal-4: #589A8D; /* Teal clair */
    --teal-5: #8FC1B5; /* Teal très clair */
    --Noir-6: #000000; /*Noir*/
    --Blanc-7: #fffffff; /*Blanc*/

    /* Utilisation des couleurs pour différents éléments */

    --color-title: var(--teal-1); /* Couleur pour les titres */
    --color-subtitle: var(--teal-3); /* Couleur pour les sous-titres */
    --color-paragraph: var(--teal-4); /* Couleur pour les paragraphes */
    --color-border: var(--teal-2); /* Couleur pour les bordures */
    --color-background: var(--teal-5); /* Couleur de fond général */
    --color-text: var(--Noir-6); /*Couleur pour le texte de fond*/
    --color-text: var(--Blanc-7); /*Couleur blanche pour les texte de fon d'une balise"*/
}
/*Intégration de nos polices d'écritures générales pour notre texte, titre et les sous-titres*/
:root {
    /* Polices */
    --font-title: 'Montserrat', sans-serif;
    --font-text: 'Open Sans', sans-serif;
    --font-subtitle: 'Roboto', sans-serif;

    /* Taille de police standard et poids */
    --font-size-normal: 16px; /* Taille de police standard pour le texte */
    --font-size-title: 28px; /* Taille de police pour les grands titres */
    --font-size-subtitle: 20px; /* Taille de police pour les sous-titres */
    --font-weight-normal: 400; /* Poids normal de la police */
    --font-weight-bold: 700; /* Poids en gras */
}

## Organisation des Tâches
- **Choix des Tâches**: Chaque développeur a reçu des tâches spécifiques pour progresser de manière efficace.
- **Noms des Branches Git**:
  - `ndiawarDev` - Branche pour le développement principal par Ndiawar.
  - `hawa_experience` - Branche dédiée aux sections d'expérience gérée par Hawa.
  - `dieng_noir` - Branche pour les ajustements de style et la mise en page par Dieng.
  - `antaeducation` - Branche pour la section éducation dirigée par Anta.

## Instructions pour les Développeurs
Pour cloner le projet:
git clone <https://github.com/NdiongueFH/Mon_CV.git


Pour basculer entre les branches:
git checkout <nom_de_la_branche>

Assurez-vous de mettre à jour votre branche locale régulièrement:
git pull origin main


## Contribution
Les membres sont encouragés à soumettre des Pull Requests pour révision avant de fusionner leurs modifications avec la branche principale (mainteneur). Veillez à suivre les pratiques de nommage et de codage standard pour maintenir la qualité du code.

## Contact
Pour toute question ou suggestion, veuillez contacter le mainteneur du projet à `Fatoumata Hawa Ndiongue hawa.ndiongue@gmail.com`.
