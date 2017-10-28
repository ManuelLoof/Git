
# Git Cheat Sheet #

## Basics ##

Initialisiert ein neues Git Repository.

    git Init

Fügt Dateien dem Repository hinzu.

    git add name
    git add *

Check die Daten ein.

    git commit -m "Comment"

Farbige Konsolenausgabe.

    git config color.ui true

Holt sich ein Repository vom Server und legt eine lokale
Arbeitskopie an.

    git clone Verzeichnis

Logt sich auf GitHub ein und überträgt die Daten aus der Arbeitskopie auf den Server.

    git remote add origin https://github.com/ManuelLoof/BASTA_2016.git
    git push -u origin master

Gibt die alle commit messages für das Projekt aus.

    git log --pretty=format:"%h - %an, %ar : %s"
    
