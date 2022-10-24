---
author: "Daniel Caballo"
title: "Git"
date: 2022-10-21
description: "Git"
tags: ["shortcodes", "privacy"]
thumbnail: https://media.giphy.com/media/XDsQPj2Q8rtQG4BQ7b/giphy.gif
---

# Repositorio en github
## Crear un repositorio nuevo y ligarlo al local
1. Accedemos a github con nuestro usuario y password
2. En nuestra cuenta creamos un repositorio
3. En este momento nos mostrará la página una serie de comandos que hay que ejecutar en local. Las acciones son:
4. Vamos a local al directorio donde esta nuestro proyevto
5. Ejecutamos
``` bash
    git init # este comando inicializa nuestro directorio como proyecto de git . Habrá creado un directorio llamado .git
 
    
    git add * # con este comando añadimos los ficheros de mi directorio (todos por especificar) al repositorio
   
   
    git commit -m "mensaje de checkpoint" # con este comando especificamos un mensaje para los cambios actuales
   
    git branch -M main # creamos una rama o directorio de trabajo asociado al repositorio local
   
   git add remote origin https://github.com/DanielCaballo/ # ligamos el repositorio local al repositorio remoto
    
   git push origin main # sube los ficheros añadidos al remoto
   ```
   

### Copiar un proyecto en otro destino
1. Accedo a github y copio la url del repositorio
2. Escribo
git clone "la url" # creará un directorio con el nombre del proyecto y todo el contenido

3. trabajo normal y al final hago un push
git add *
git cpmmit -m "nuevos cambios"
git push origin main "la url" # con esto actualizaŕe el proyecto en github con los últimos cambios

### Actualizando un proyecto modificado
* Actualizo el proyecto en local con el remoto
git pull

<br>
<p> 
<span class="nowrap"><span class="emojify">🙊</span>
<span class="nowrap"><span class="emojify">🙊</span>
<span class="nowrap"><span class="emojify">🙊</span>
<span class="nowrap"><span class="emojify">🙊</span>
</p>
---