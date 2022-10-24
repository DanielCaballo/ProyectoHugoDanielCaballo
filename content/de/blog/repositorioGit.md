---
author: "Daniel Caballo"
title: "Git"
date: 2022-10-21
description: "Git"
tags: ["shortcodes", "privacy"]
thumbnail: https://media.giphy.com/media/XDsQPj2Q8rtQG4BQ7b/giphy.gif
---

# Github-Repository
## Erstellen Sie ein neues Repository und verknüpfen Sie es mit dem lokalen
1. Wir greifen mit unserem Benutzernamen und Passwort auf github zu
2. In unserem Konto erstellen wir ein Repository
3. Zu diesem Zeitpunkt zeigt uns die Seite eine Reihe von Befehlen, die lokal ausgeführt werden müssen. Die Aktionen sind:
4. Wir gehen zu local in das Verzeichnis, in dem sich unser Projekt befindet
5. Wir führen aus
``` versuchen
    git init # Dieser Befehl initialisiert unser Verzeichnis als Git-Projekt. Sie haben ein Verzeichnis namens .git erstellt
 
    
    git hinzufügen. # Mit diesem Befehl fügen wir die Dateien in meinem Verzeichnis (alle anzugeben) zum Repository hinzu
   
   
    git commit -m "checkpoint message" # mit diesem Befehl geben wir eine Nachricht für die aktuellen Änderungen an
   
    git branch -M main # erstellt einen Zweig oder ein Arbeitsverzeichnis, das dem lokalen Repository zugeordnet ist
   
   git add remote origin https://github.com/DanielCaballo/ # Verknüpfe das lokale Repository mit dem Remote-Repository
    
   git push origin main # hinzugefügte Dateien auf Remote schieben
   ```
   

### Kopieren Sie ein Projekt an ein anderes Ziel
1. Ich greife auf github zu und kopiere die Repository-URL
2. Ich schreibe
git clone "the url" # erstellt ein Verzeichnis mit dem Projektnamen und allen Inhalten

3. normale Arbeit und am Ende mache ich einen Push
git hinzufügen *
git cpmmit -m "neue Änderungen"
git push origin main "the url" # Dadurch wird das Projekt auf github mit den neuesten Änderungen aktualisiert

### Aktualisieren eines geänderten Projekts
* Ich aktualisiere das Projekt lokal mit der Fernbedienung
git ziehen

<br>

---