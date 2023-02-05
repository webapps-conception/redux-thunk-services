# redux-thunk-services

Redux-Thunk est le middleware le plus populaire pour Redux. Il permet de simplifier la manipulation des actions asynchrones.

Chaque service permet de prendre en charge le fonctionnement de notre application :
- Posts s'occuera de la récupération des sujets du subreddit React.
- postDetails ira chercher les détails pour les sujets lors du clic par l'utilisateur; les clics suivants sur le même sujet ne généreront pas de traffic réseau du fait de la mise en mèmoire de chaque sujet ouvert...
- routing se chargera du cycle de vie de l'application, c'est-à-dire d'afficher un sujet spécifique dès qu'il est cliqué, et de réafficher la liste lorsque le bouton retour est cliqué.

# Installation
```
yarn
or
yarn install
```

# Execution d'un test en dev
```
yarn dev
```

# Auteur
* Exercice issu du livreReact Développez le Front End de vos applications web et mobiles avec JavaScript : https://github.com/scastiel
* Rudy TUANI : adaptation du Framework vitejs avec les dernières versions de librairies.
