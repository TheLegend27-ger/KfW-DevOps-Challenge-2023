# KfW DevOps Challenge

## Challenge 14 - Datenbank Backup

[Home](../../README.md) - [Back >](../challenge13/README.md)

### Intro

In Challenge 8 habt ihr die Datenbank in eine "Azure Cosmos DB API for MongoDB" überführt. Diese bietet eine automatische BackUp Funktion, beispielsweise um jeden Stand in den letzten 7 Tagen wiederherzustellen zu können oder andere Zeitintervalle. Ihr könnt euch gerne unter den Reiter "Backup Policy" die zur Verfügung stehenden Optionen näher anschauen und diese testen.
Für die nachfolgende Challenge wollen wir uns allerdings auf den Fall vorbereiten, dass etwas mit dem Azure BackUp System kaputt gegangen ist. Um uns für diesen Fall abzusichern wollen wir ein manuelles Backup der Datenbank, zum Beispiel mit dem Tool mongodump, in regelmäßigen Abständen in ein Azure Blob Storage speichern.

### Tasks

1. Erstellen eines Backups der Datenbank
   
   - _Hinweis_: Ihr könnt diesen Prozess zum testen manuell und gegebenenfalls lokal durchführen, allerdings soll dieser Prozess später vollständig in der Cloud stattfinden. Entweder ihr entwickelt eine eigene Lösung oder findet fertige kostenfreie und OpenSource Lösungen im Internet.

2. Speichern des Backups in Azure Blob Storage

3. Einrichten eines Mechanismus um den Prozess in regelmäßigen Abständen auszuführen (zum Beispiel jeden Tag um 23:30)

4. Führt nun mindestens einmal einen Wiederherstellungsprozess mithilfe eines zuvor erstellen Backups durch

5. _Bonus_: Prüft ob man mithilfe von Berechtigungskonfigurationen den Zugriff auf die Backup Dateien weiter einschränken kann, da nicht jeder an die gegebenenfalls sensiblen Daten gelangen soll

6. _Bonus_: Erweitert den Mechanismus, dass ab einer bestimmten Anzahl an Backup Dateien (zum Beispiel ab 7 Dateien - 1 Woche) die älteste gelöscht wird um die Speicherkosten zu begrenzen

### Checklist

- [ ] Ihr habt erfolgreich mindestens ein Backup erzeugt
- [ ] Ihr habt erfolgreich mindestens einmal ein erzeugtes Backup zwischengespeichert (Azure Blob Storage)
- [ ] Ihr habt erfolgreich einen Prozess implementiert um diesen Vorgang in regelmäßigen Abständen durchzuführen
- [ ] Ihr habt erfolgreich einen älteren Stand der Datenbank wiederhergestellt

### Outro

Herzlichen Glückwunsch zur erfolgreichen Absolvierung der Challenge 14 - Datenbank Backup! Durch die Durchführung dieser Aufgabe habt ihr wichtige Sicherheitsmaßnahmen implementiert, um eure Datenbank vor möglichen Ausfällen des Azure Backup-Systems zu schützen. Das erstellen der Backups mithilfe von mongodump und deren Speicherung im Azure Blob Storage gewährleistet, dass ihr stets auf unabhängige Kopien eurer Daten zugreifen könnt. Zudem habt ihr einen Mechanismus eingerichtet, um diese Backups regelmäßig auszuführen und somit einen kontinuierlichen Schutz eurer Daten sicherzustellen. Abschließend habt ihr eure Fähigkeiten unter Beweis gestellt, indem ihr erfolgreich einen älteren Stand der Datenbank mithilfe der zuvor erstellten Backups wiederhergestellt habt. Durch diese Challenge seid ihr bestens gerüstet, um eure Datenbank vor unvorhergesehenen Ereignissen zu schützen und einen reibungslosen Betrieb aufrechtzuerhalten. Großartige Arbeit!

[Home](../../README.md) - [Next >](../challenge15/README.md)
