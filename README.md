# Frontend Mentor - Solution Grille Bento

Il s'agit d'une solution pour le [défi Grille Bento sur Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Les défis de Frontend Mentor vous aident à améliorer vos compétences en codage en construisant des projets réalistes.

## Table des matières

- [Frontend Mentor - Solution Grille Bento](#frontend-mentor---solution-grille-bento)
  - [Table des matières](#table-des-matières)
  - [Aperçu](#aperçu)
    - [Le défi](#le-défi)
    - [Capture d'écran](#capture-décran)
    - [Liens](#liens)
  - [Mon processus](#mon-processus)
    - [Technologies utilisées](#technologies-utilisées)
    - [Ce que j'ai appris](#ce-que-jai-appris)
    - [Développement continu](#développement-continu)
    - [Ressources utiles](#ressources-utiles)
  - [Auteur](#auteur)
  - [Remerciements](#remerciements)

## Aperçu

### Le défi

Les utilisateurs doivent être capables de :

- Voir la mise en page optimale de l'interface en fonction de la taille de l'écran de leur appareil.

### Capture d'écran

![](./assets/images/capture__ecran.png)


### Liens

- URL de la solution : [https://github.com/bouthilletteariane/tp2-bento.git]
- URL du site en direct : [http://127.0.0.1:5500/]

## Mon processus
J'ai commencé par construire la grille pour que les blocs soient prêts pour les ajouts Css. J'ai pris le temps d'ajouter les images directement dans le html. J'ai essayer d'ajouter les grandeurs directement dans le html, mais c'était plus simple de tout simplement garder la taille des images à 100%. 

Par la suite, j'ai pris le temps d'ajuster la taille des textes, les espaces et la hauteur et largeur des box. 

### Technologies utilisées

- Marquage HTML5 sémantique
- Propriétés CSS personnalisées
- Flexbox
- CSS Grid
- Workflow mobile-first 

### Ce que j'ai appris

J'ai appris à construire une grille avec "display:grid;" et "grid-template-areas". Je suis très fière de ce code puisque je me suis inspiré du dernier exercice et je l'ai adapté à cette nouvelle grille. 

Voici un exemple de la manière dont vous pouvez ajouter des extraits de code :

```css
@media (min-width: 600px) {
    .boite__media__sociaux {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 20px;
      grid-template-areas: 
     "boite__media__sociaux7 boite__media__sociaux1 boite__media__sociaux1 boite__media__sociaux4 "
     "boite__media__sociaux7 boite__media__sociaux2 boite__media__sociaux3 boite__media__sociaux4"
     "boite__media__sociaux7 boite__media__sociaux6 boite__media__sociaux5 boite__media__sociaux5"
  
      
    }
  }
```

### Développement continu

Dans mes futurs projets, j'aimerais me concentrer justement sur les grilles CSS je trouve que les possibilités sont infinies. J'ai commencé à me faire un portfolio en ligne et les grilles vont grandements me servir afin de rendre mon site plus beau et professionnel. 


### Ressources utiles

- [https://developer.mozilla.org/fr/docs/Web/CSS/CSS_flexible_box_layout/Basic_concepts_of_flexbox] - Cela m'a aider avec les flexbox.
- [https://cssgridgarden.com/#fr] - J'ai dû refaire l'exercice pour mieux comprendre 


## Auteur

- Site Web - Ariane Bouthillette
- Frontend Mentor - [@votrepseudo](https://www.frontendmentor.io/profile/votrepseudo) 



## Remerciements

J'aimerais remercier mes collègues de classe qui m'ont aider pour certains éléments CSS qui ne fonctionnait pas. Également merci à Ève Février, enseingante en Intégration II pour m'avoir rassuré lorsque j'avais des problèmes de html ou même de CSS. 
