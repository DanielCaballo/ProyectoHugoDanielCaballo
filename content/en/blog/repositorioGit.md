---
author: "Daniel Caballo"
title: "Git"
date: 2022-10-21
description: "Git"
tags: ["shortcodes", "privacy"]
thumbnail: https://media.giphy.com/media/XDsQPj2Q8rtQG4BQ7b/giphy.gif
---
# github repository
## Create a new repository and link it to the local one
1. We access github with our username and password
2. In our account we create a repository
3. At this time, the page will show us a series of commands that must be executed locally. The actions are:
4. We go to local to the directory where our project is
5. We execute
``` bash
    git init # this command initializes our directory as a git project. You will have created a directory called .git
 
    
    git add . # with this command we add the files in my directory (all to be specified) to the repository
   
   
    git commit -m "checkpoint message" # with this command we specify a message for the current changes
   
    git branch -M main # create a branch or working directory associated with the local repository
   
   git add remote origin https://github.com/DanielCaballo/ # link the local repository to the remote repository
    
   git push origin main # push added files to remote
   ```
   

### Copy a project to another destination
1. I access github and copy the repository url
2. I write
git clone "the url" # will create a directory with the project name and all content

3. normal work and at the end I do a push
git add *
git cpmmit -m "new changes"
git push origin main "the url" # this will update the project on github with the latest changes

### Updating a modified project
* I update the project locally with the remote
git pull

<br>

---