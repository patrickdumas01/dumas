# Modèle de configuration de Webpack pour WordPress

## reutilisation

1 cloner le repo 
2 renommer le dossier
3 se rendre dans le dossier ->cd xxxx
4 supprime le dossier .git afin de repartir d'un repo neuf -> sudo rm -R .git
5 ilitialisation d'un git neuf -> git init
6 PREMEIR VERSIONNING
git add .
git commit -m "xxx"
git remote add origin 
git push -u origin master

## Installation

1. Exécuter dans le répertoire la commande `npm install` qui va installer toute les dépendances Node.js nécessaire au bon fonctionnement de l'application.
2. Exécuter une des commandes ci-dessous.

## Commandes disponibles

- `npm run start` : Démarre le serveur de développement en utilisant [Browsersync](https://www.browsersync.io/)
- `npm run build:dev` : Génère les ressources front sans compression en vue d'une utilisation dans un environnement de développemnt
- `npm run build:prod` : Génère les ressources front avec compression (minify, uglify) en vue d'une utilisation dans un environnement de production
- `npm run clean` : Supprime les fichiers générés par Webpack
- `npm run clean:all` : Supprime les fichiers générés par Webpack ainsi que le répertoire des dépendances installées avec NPM (`node_modules`)
