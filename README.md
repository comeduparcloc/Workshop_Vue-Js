# Initiation au dévellopement web avec Vuetify Js

Ce workshop est conçu pour vous initier au développement web en utilisant le langage Vue Js avec son framework Vuetify. Vous allez apprendre comment créer un site Web de manière efficace et rapide en utilisant ce nouveau language.

Voici un lien de la documentation de [Vuetify.js](https://vuetifyjs.com/en/getting-started/installation/) qui sera très utile pour tous les exercices.

## Prérequis

Avant de commencer ce workshop, assurez-vous d'avoir npm ou yarn d'installé.

## Exercices

### Exercice 1: Configuration initiale

1. Cloner le repository.
2. Exécuter la commande suivante dans le terminal :
   ```bash
   sudo yarn create vuetify
   sudo npm create vuetify
   ```
3. Choisissez le nom de votre projet.
4. Selectionnez "Base".
5. N'utilisez pas Typescript.
6. Choississez yarn ou npm
6. Votre projet sera ensuite créé dans un dossier.
7. Pour lancer le site web en localhost, allez dans le dossier puis :
    ```bash
    yarn/npm install && yarn/npm dev
    ```

Vous devriez arriver sur cette page :
![alt text](https://cours.brosseau.ovh/assets/vuetify-projet.D-aXqQn_.jpg)

Cette page est automatiquement ajouté lors de la création d'un nouveau projet.

### Exercice 2: Ajout de notre premier component

Sur la page de base il y a un bouton components, je vous invite à cliquer dessus.

Cela va vous rediriger sur un site qui va vous montrer tous les components et objets que vuetify peut vous fournir.

Pour le début, nous allons coder dans le fichier index.vue qui se situe dans /src/pages/

"HelloWorld" est le seul composant de la page index (première page).
Premierement, supprimez le composant "HelloWorld" dans le fichier index.

Pour ce premier exercice, allez chercher l'objet "Color Picker" ou "Palette de couleur" sur le site de vuetify. Ajoutez le composant dans le fichier index.vue. Modifiez ensuite le code du fichier pour que le background ou un objet possède la couleur choisie.

Résultat attendu :

![img1](https://github.com/comeduparcloc/Workshop_Vue-Js/assets/114906835/facaf685-1831-4aa9-9879-0a06e6502386)

### Exercice 3: Barre de Navigation

Si vous avez reussit l'exercice précédant, c'est que vous avez compris comment faire pour ajouter des objets, modifier leurs attributs et appréhender le language Vue Js.

Maintenant, nous allons nous intéresser à la navigation sur notre site web.

Ajoutez une barre de navigation en haut ou sur le côté (components vuetify). Mettez dans cette barre des boutons permettant d'accéder à différentes routes sur le site.

La route de base "/" correspond à la page donnant sur le color picker et la route "/exercice 4" redirigera sur une page blanche que l'on remplira au prochain exercice.

Résultat attendu :

![img4](https://github.com/comeduparcloc/Workshop_Vue-Js/assets/114906835/7ed24dbe-d6f7-43c6-b42e-090564e51ec5)

![img3](https://github.com/comeduparcloc/Workshop_Vue-Js/assets/114906835/2718995a-2ac6-4f26-abfb-d6678d0f3859)

A noter que la barre de navigation peut être un composant porpre à chaque page ou un composant général à implémenter dans le fichier App.vue pour qu'il soit présent sur toutes les pages

### Exercice 4: Créer un Sondage

Pour créer un sondage il est recommandé d'utiliser une class qui encadre votre sondage. Trouvez le composant form et ajoutez plusieurs champs à compléter tels que :
    - Nom
    - Age
    - Question à réponse fermée
    - Question à réponse ouverte

N'oubliez pas d'implémenter le bouton de soumission du formulaire.

![img5](https://github.com/comeduparcloc/Workshop_Vue-Js/assets/114906835/45855cc4-6b3a-44d2-a08e-475f09cc6507)

### Exercice 5: Relier à une Api

Pour ce dernier exercice, nous allons voir comment faire pour utiliser une api sur notre site. Créez une nouvelle route "/exercice 5" ne contenant rien pour l'instant.

Sur ce site [ici](https://www.geeksforgeeks.org/free-apis-list/) vous avez une liste d'api. Prennez en une et utilisez ses fonctionnalitées sur votre site. Pour appeler l'api, cherchez "axios Vue.js" sur google.

## Conclusion

Félicitations ! Vous avez complété avec succès ce workshop d'initiation au développement d'un site web avec vuetify js. N'hésitez pas à explorer davantage les fonctionnalités de ce framework et à ajouter d'autre fonctionnalités sur votre site web. Amusez-vous bien !
