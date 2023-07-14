# KfW DevOps Challenge

## Challenge 2 - Git

[Home](../../README.md) - [Back >](../challenge01/README.md)

### Intro

Historisch gesehen ist die Versionskontrolle die erste Komponente, die Teams zu Beginn eines Projekts implementieren. Sie ist eine der ältesten und am besten verstandenen Komponenten von DevOps. Versionskontrollsysteme ermöglichen es Entwicklern, zusammenzuarbeiten und gleichzeitig zur gleichen Codebasis beizutragen. Sie können Teams auch dabei helfen, Versionen zu verfolgen (so dass Code zurückgesetzt werden kann, wenn fehlerhafte Änderungen vorgenommen werden) und Fehler, Arbeit und Tests durch das Team zu verfolgen. Nehmt euch gerne einen Moment Zeit, um im [Git-Handbuch](https://git-scm.com/book/en/v2) die Grundlagen (Kapitel 1.1 - 1.3) der Versionskontrolle durchzulesen und zu verstehen. Die Technologie auf den wir den Fokus legen werden für verteilte Versionskontrolle nennt sich **Git**.

### Tasks

Nachdem wir nun ein grundlegendes Verständnis von Versionskontrolle und Git haben, können wir etwas Code in die Versionskontrolle einchecken. DevOps-Best-Practices können auf jede Programmiersprache angewendet werden, für heute haben wir euch eine einfache Node.js Webanwendung zur Verfügung gestellt.

1. Beginnt damit, das GitHub-Repository, das euer Team in der vorherigen Herausforderung erstellt hat, auf euren lokalen Computer zu klonen ([hint](https://help.github.com/en/articles/cloning-a-repository)).

2. Ladet als Nächstes [den Code herunter](https://github.com/openkfw/tumo-hackathon-app).

3. Übertragt (Pusht) schließlich die Dateien in euer GitHub-Repository mit eurem bevorzugten Git-Client.

In dieser Aufgabe haben wir erfolgreich Code zu unserem Repository hinzugefügt! Bei der Versionskontrolle geht es jedoch um mehr als nur darum, Code an einen zentralen Ort zu verschieben - sie ist entscheidend dafür, dass die Entwickler mit den Änderungen, die von anderen vorgenommen werden, auf dem Laufenden bleiben. Wir kümmern uns also nicht nur darum, Code in unser Repository hochzuladen, sondern auch darum, Änderungen aus dem Repository herunterzuladen.

4. Um dies zu üben, lasst ein anderes Teammitglied das Repository auf ihren/seinen lokalen Rechner klonen (oder zieht/pull die neuen Änderungen, falls bereits geklont). Lasst diese Person eine kleine eigene Änderung an einer der Dateien vornehmen (vielleicht einen Kommentar oder einen Zeilenumbruch hinzufügen). Dann schiebt die Änderung zurück auf GitHub. Der Rest des Teams sollte dann die Änderung ziehen, um sicherzustellen, dass sie auf ihren lokalen Rechnern zu sehen ist. (Siehe einige der unten genannten Links zum Hinzufügen von Dateien und Synchronisieren von Änderungen, falls ihr nicht weiterkommen).

5. (Optional) Experimentiert gerne noch mit Git und Github. Zum Beispiel:
   - Erstellt einen neuen Branch (`git checkout -b <name>`) und pusht diesen
   - Erstellt einen Push Request in Github, und schließt diesen ab

### Checklist
  
- [ ] Euer Repository ist auf euren lokalen Rechner geklont und mit GitHub synchronisiert
- [ ] Der "application" Ordner befinden sich im root verzeichnis eures Repositories

### Lernmaterial

- Klonen eines repository via der [command line](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) oder [GitHub Desktop](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/cloning-a-repository-from-github-to-github-desktop)
- Für GitHub Desktop Benutzer: [commiting](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/committing-and-reviewing-changes-to-your-project) und [pushing](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/pushing-changes-to-github) von Änderungen.
- Für Command Line Benutzer: [commiting](https://docs.github.com/en/github/committing-changes-to-your-project/creating-and-editing-commits) und [pushing](https://docs.github.com/en/github/using-git/pushing-commits-to-a-remote-repository) von Änderungen.
- Um Änderungen anderer Personen in das lokale Repository zu ziehen, zum synchron bleiben - siehe die Dokumentation zu [command line](https://docs.github.com/en/github/using-git/getting-changes-from-a-remote-repository) und [GitHub Desktop](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/keeping-your-local-repository-in-sync-with-github).
- Eine kurze Erläuterung zum Hinzufügen von Dateien zu einem Repository über die Befehlszeile finden ihr [hier](https://docs.github.com/en/github/managing-files-in-a-repository/adding-a-file-to-a-repository-using-the-command-line). 


[Home](../../README.md) - [Next >](../challenge03/README.md)