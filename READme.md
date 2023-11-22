# Challenge #3

Nous voulons créer un site web avec nodejs et un template engine de votre choix (hbs, pug...)

Votre site web doit être constituté de plusieurs pages :

- une homepage qui affiche des températures selon une localité
- une page about qui en dira un peu plus sur votre métier de développeur (chargement de photo de profil, légère description de vous-même, votre lien vers github, affichage de quelque uns de vos repos...)
- une page contact qui contient une formulaire de contact

Le tout nicely formatted with CSS

## Features demandées

- Je dois pouvoir chercher la température d'une ville
- Historique des recherches disponible sur la homepage
- Je peux supprimer une recherche passée
- Je peux donner un label à un historique

### Architecture

- Express
- Template engines
- BDD via un fichier json au sein du serveur : chaque recherche doit comprendre
  -  un id
  -  date et heure de la requête
  -  la ville cherchée
  -  la température
- calcul geocode+temperature disponible sur un package public dans un package public npm
- déployer son application en production
