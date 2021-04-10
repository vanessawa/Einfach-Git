# Git-Basics
* Mit *"cd ORDNERNAME"* wird der gewünschte Ordner geöffnet worin sich die hochzuladenden Dateien befinden.
* Befindet man sich in dem Ordner wird mit *"git init"* ein neues Repository erstellt.
* Mit *"git add * "* werden alle Dateien in dem aktuellen Ordner ausgewählt. Über *"git add FILENAME"* kann man direk eine bestimmte Datei auswählen.
* Anschließend gibt man *"git commit -m "BEZEICHNUNG""* ein, womit die zuvor ausgewählten Dateien nach Änderungen durchsucht werden, und gleichzeitig die Bezeichnung für den nachfolgenden upload festgelegt wird. 
* Spätestens jetzt muss das Repository in github angelegt werden. Anschließend gibt man im Terminal *"git remote add origin github.com/USERNAME/REPOSITORY.git"* ein um das Remote anzulegen. (Das kann direkt aus der github-Seite kopiert werden, welche nach dem Erstellen des neuen Repository erscheint)
* Nun kann der Commit beendet werden indem *"git push -u origin main"* eingegeben wird. Damit werden die geänderten Dateien in github hochgeladen.
* **Jeder weitere push** zu dem bestehenden Repository kann nun mit dem Befehl *"git push"* eingegeben werden. Die zwei vorherigen Punkte sind lediglich beim ersten Upload des neuen Repository durchzuführen.  
