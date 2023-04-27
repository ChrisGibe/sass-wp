# Install

En premier il faut installer [Nodejs](hhttps://nodejs.org/en). Télécharger la version "LTS".

Ensuite ouvrer un terminal puis regarder si Nodejs est correctement installé en tapant "node -v".
Si vous avez quelque chose du genre : v18.13.0 c'est que Nodejs est bien installé sur votre machine.

Toujours dans le terminal, nous allons installer SASS de manière globale dans votre machine.
Lancer la comande npm install -g sass.

Puis comme pour Nodejs nous allons voir si SASS est bien installé avec la commande "sass --version".
Une fois encore si vous aves quelque chose comme 1.57.1 c'est que tout est ok.

## Mettre le package dans Wordpress

Dans votre éditeur de code contenant votre site Wordpress.
Déplacer ce dossier à l'endroit où se trouve le styles.css de votre Wordpress.
Faite un clic droit est cliqué sur "Open in integrated Terminal".

Votre terminal va s'ouvrir à l'emplacement de votre dossier "scss".
Dans votre terminal lancer la commande "sass scss/styles.scss:../style-sass.css -w --style compressed".

Votre fichier scss: "styles.scss", va alors compiler votre scss en css à l'extérieur de votre dossier "scss".




