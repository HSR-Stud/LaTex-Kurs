# LaTex-Kurs
---
## PreLab
## Installtion  
 Damit du möglichst viel vom LaTex Kurs profitierst, solltest du folgendes installieren:
 
 ### LaTeX Distribution
 Wir empfehlen TexLive. TexLive ist sowohl auf Linux wie auch auf Windows ausführbar.
 
- [TexLive](https://www.tug.org/texlive/acquire-netinstall.html)
	- [Direct Link für den Windows-Installer](http://mirror.ctan.org/systems/texlive/tlnet/install-tl-windows.exe)
	- [Direct Link für alles andere ausser Windows](http://mirror.ctan.org/systems/texlive/tlnet/install-tl-unx.tar.gz)
	- [Direct Link für wenn man sich nicht so ganz sicher ist, welches Betriebssystem man hat](http://mirror.ctan.org/systems/texlive/tlnet/install-tl.zip)

### Editor/IDE
LaTeX Code kann mit jedem beliebigen Editor geschrieben werden, auch mit Notepad++, Vim, Emacs oder ähnlichem.
Angenehmer ist es mit Texstudio.

- [Texstudio](https://www.texstudio.org)

Texstudio ist ein standalone IDEs, welches spezifisch für LaTeX entwickelt wurde.

### Git-Installation mit Sourcetree / GitHub
GitHub basiert auf der Software Git, welche zur Versionskontrolle & -verwaltung eingesetzt wird. Git kann von der Kommandozeile (Git CMD) aus genutzt werden. Dies ist jedoch sehr mühsam, weshalb wir die Nutzung des Git-Guis Github Desktop empfehlen. 

- [Github Desktop](https://desktop.github.com/)
  <!-- 1. [GitHub Account erstellen](https://www.github.com)
   Dabei solltest du unbedingt deine HSR-Emailadresse verwenden, denn dann hast du direkt Anspruch auf ein Github Student Developer Pack.    Dies erlaubt es dir unlimitierte private Repositories auf Github zu erstellen, Gratis Continuous Integration mit Travis-CI für private    Repositories sowie AWS und Digital Ocean Credits. 
   2. [Github Student Developer Pack beantragen](https://www.openhsr.ch/tipps/github-education-pack/)  
   3. [Sourcetree installieren für ein Git_GUI](https://www.sourcetreeapp.com/)  
   3.1 Atlassin Account erstellen (zwar ist sourcetree gratis, aber dennoch benötigst du eine Lizenz)  
   3.2 Mit GitHub-Account verknüpfen (am Besten bist du dann immernoch im Browser auf GitHub eingeloggt)  
   3.3 Es muss kein globales .gitignore File erstellt werden  
   3.4 Es muss kein SSH-Schlüssel erstellt werden  
   3.5 Sobald du beim Clonen eines Repos angelang bist, kann du den weiteren Setup übersprungen
--!>
   
---
## InLab 
### Herunterladen des Kurses
1. Lade diesen Kurs als Zip herunter.

### Clone die Vorlage
Für den Kurs brauchst du eine [LaTex Vorlage](https://github.com/HSR-Stud/Template-LaTex)
1. Öffne Sourcetree  
2. Klicke auf das + bei den Tabs  
3. Wähle clonen aus  
4. Setze den Cursor in das erste leere Feld unter dem Titel
4.1 Drücke Ctrl + V
4.2 Wähle aus, wo das Repo gespeichert werden soll. Achtung nicht in einer Cloud (Google Drive, Dropbox etc.).  
4.3 Gib an, wie die Kopie des Repos auf deinem Rechner heissen soll.  
4.3.1 (!) Wenn das Repo Submodule enthält, musst du unter Advanced Options die Checkbox "Recurse submodules" aktivieren.  
Falls du auf Probleme stösst findest du hier noch die offizielle [Sourcetree Anleitung zum Clonen eines Repos](https://confluence.atlassian.com/bitbucket/clone-a-repository-223217891.html). 

---
## PostLab
### Wichtige Infos zu HSR-Stud

Pflichtlektüre für alle die ein Repo wieder hochladen wollen oder ein Neues erstellen auf HSR-Stud.

[Willkommen](https://github.com/HSR-Stud/Willkommen#willkommen)

### Vorlage
!Achtung!: Die Untermodule müssen rekursiv eingebunden werden.

[Vorlage](https://github.com/HSR-Stud/VorlageZFLaTex)


### Header
Headerfiles für die Zusammenfassungen. (Sind auch rekursiv in der Vorlage eingebunden.)

[Header](https://github.com/HSR-Stud/header)
