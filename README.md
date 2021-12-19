# Nom du projet

DumontGontran_3_18112021

## Dépendances

Pour fonctionner ce projet a besoin de:

- **SASS**
- **Autoprefixer**
- VS code (optionnel)

## Installation

- **SASS**
1. Installer **NodeJS 16.13.1 LTS**: https://nodejs.org/dist/v16.13.1/node-v16.13.1-x64.msi
2. Une fois, sur l’invite de commandes, entrez la commande: **`node -v`** puis la commande: **`npm -v`** pour vérifier que **node** et **npm** soient bien **installés** et connaitre leur **version**.
3. Vous pouvez maintenant **installer** **Sass** avec la commande: **`npm -g install sass`**
4. Pour vérifier que **Sass** soit bien installé, entrez la commande: **`sass --version`**

- **Autoprefixer**
1. Pour installer **Autoprefixer**, entrez la commande:**`npm install autoprefixer postcss postcss-cli -g`**
2. Pour vérifier qu'**Autoprefixer** soit bien installé, entrez la commande: **`autoprefixer --version`**

## Utilisation

### Vous devez suivre entièrement ces étapes pour veiller au bon fonctionnement du projet. 

1. **SASS**
    - Pour **lancer Sass et faire une nouvelle compilation du fichier main.scss en mobile.css**, entrez la commande: **`npm run sass`**
    - Ceci est la première étape **obligatoire** à suivre pour le bon fonctionnement du projet.

2. **Autoprefixer**
    - Pour **lancer autoprefixer afin de rendre compatible avec tous les navigateurs votre fichier mobile.css en prefixed/mobile.css**, entrez la commande: **`npm run prefix`**
    - Ceci est la seconde étape **obligatoire** à suivre pour le bon fonctionnement du projet.

