# Das Zuckerstück

Das ist ein Beispiel-Repository für unsere Zuckerstücke. Manchmal lernen wir sogar was!

## Git und GitHub

Git wurde ursprünglich von Linus Torvalds für die Entwicklung des Linux-Kernels initiiert und erfreut sich seitdem wachsender Beliebtheit. Als Vorteile werden das verteilte Prinzip und die starke Community genannt.

Ein Git-Server enthält dabei mehrere Repositorys ("Projekte"), auf die jeweils speziell zugelassene Nutzer Zugriff haben. Jeder dieser Nutzer hat das gesamte Repository als lokale Kopie auf dem eigenen Rechner. Auf den Rechner läuft auch der Git-Client, das Kommandozeilenprogramm git.

Im Prinzip geht es darum, das jeder Nutzer Änderungen an seiner lokalen Kopie des Projekts vornehmen kann. All diese Änderungen werden zum Git-Server geschickt und für jeden Nutzer wird versucht, eine Strategie zur Zusammenführung zu finden. Trivialerweise haben keine zwei Nutzer die gleiche Datei bearbeitet, dann nämlich geschieht das Zusammenführen automatisch. Ist es doch der Fall, hilft das Programm git dabei, den *Konflikt* zu lösen.

GitHub, Inc. betreibt github.com als eine SaaS (*Software as a Service*). GitHub versteht sich eher als Social Network, was seinen Usern Git-Server kostenlos zur Verfügung stellt und sie anhält, an den Projekten anderer mitzuwirken (*pill request*). Zusätzlich zu den Funktionen von Git gibt es dann noch Nutzerprofile, Statistiken, Issue Tracker, Wikis, Foren und einen Online-Repository-Browser (quasi eine Webseite, die wie ein Dateimanager auf die lokale Repository-Kopie des Git-Server zugreift). 

## Kommandos

`git add`

`git commit`

`git push`

`git pull`

`git stash` um einen Merge vorzubereiten, oder um versehentlich hinzugefügte Änderungen zu verwerfen (ohne sie endgültig zu löschen).

`git pop`

`.gitignore`

## Links

### Interaktives Tutorial mit Visualisierung
http://learngitbranching.js.org/

### Video-Einführung
https://www.youtube.com/watch?v=HVsySz-h9r4

### Superausführliches Tutorial
https://www.atlassian.com/git/tutorials/what-is-version-control
