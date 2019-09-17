
# Webpack StarterKit

### Description 🧐

Voici le StarterKit webpack que j'utilise pour mes projets. Celui-ci utilise les fonctionnalités suivantes :

 - Le support SASS via [sass-loader](https://github.com/jtangelder/sass-loader)
 - Un Dashboard stylisé via [webpack-dashboard](https://github.com/FormidableLabs/webpack-dashboard)

 
### Installation de Webpack et des fonctionnalités 🚀 

Pour installer Webpack ainsi que toutes les fonctionnalités pour faire fonctionner le StarterKit, rendez-vous dans le répertoire de votre application web et il faut taper la commande suivante dans le terminal :

        npm install

Pendant l'installation, un dossier `node-modules` est créé, on y retrouvera toutes les dépendances téléchargées nécessaires au fonctionnement de ce StarterKit. Un fichier `package-lock.json` est aussi créé dans le répertoire, celui-ci est généré automatiquement pour toutes les opérations où npm modifie l'arborescence. 

### Démarrer le serveur de développement Webpack 🔷

Pour démarrer le serveur de développement Webpack, il faut taper la commande suivante dans le terminal tout en restant toujours dans le répertoire de l'application web :

        npm start

Une fois le serveur démarrer, l'application web est accessible depuis votre hôte sur l’adresse [http://localhost:8081/](http://localhost:8081/)
  

### Pour exporter la version de production ⚙️
Afin d'exporter la version de production de l'application web, il faut taper la commande suivante dans le terminal tout en restant toujours dans le répertoire de l'application web :

        npm run build

Quand `npm run build` est lancé, la fonctionnalité [mini-css-extract-plugin](https://github.com/webpack-contrib/mini-css-extract-plugin) permet de regrouper le css dans un fichier séparé. Celui-ci sera inclus dans la balise `<head>` qui contient tous les éléments de l’en-tête de votre document du fichier `index.html`.

