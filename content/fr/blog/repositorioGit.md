---
author: "Daniel Caballo"
title: "Git"
date: 2022-10-21
description: "Git"
tags: ["shortcodes", "privacy"]
thumbnail: https://media.giphy.com/media/XDsQPj2Q8rtQG4BQ7b/giphy.gif
---
# référentiel Github
## Créez un nouveau dépôt et liez-le au dépôt local
1. Nous accédons à github avec notre nom d'utilisateur et notre mot de passe
2. Dans notre compte, nous créons un référentiel
3. À ce moment, la page nous montrera une série de commandes qui doivent être exécutées localement. Les gestes sont :
4. Nous allons en local dans le répertoire où se trouve notre projet
5. Nous exécutons
``` bash
    git init # cette commande initialise notre répertoire en tant que projet git. Vous aurez créé un répertoire appelé .git
 
    
    git add . # avec cette commande on ajoute les fichiers de mon répertoire (tous à préciser) au repository
   
   
    git commit -m "checkpoint message" # avec cette commande nous spécifions un message pour les changements actuels
   
    git branch -M main # crée une branche ou un répertoire de travail associé au référentiel local
   
   git add remote origin https://github.com/DanielCaballo/ # relie le dépôt local au dépôt distant
    
   git push origin main # pousser les fichiers ajoutés à distance
   ```
   

### Copier un projet vers une autre destination
1. J'accède à github et copie l'url du dépôt
2. J'écris
git clone "the url" # créera un répertoire avec le nom du projet et tout le contenu

3. travail normal et à la fin je fais un push
git ajouter *
git cpmmit -m "nouveaux changements"
git push origin main "the url" # cela mettra à jour le projet sur github avec les dernières modifications

### Mise à jour d'un projet modifié
* Je mets à jour le projet en local avec la télécommande
git tirer

<br>

---