# KfW DevOps Challenge 

## Challenge 9 - Frontend Testing

[Home](../../README.md) - [Back >](../challenge08/README.md)

### Intro 

Um die funktionsfähigkeit einer App sicherzustellen werden Tests durchgeführt. Diese lassen sich mithilfe von Tools automatisieren. Das erlaubt nach einem initialen Implementierungsaufwand ein replizierbares, schnelles und weniger fehleranfälliges Testen.

### Tasks 

Für das automatisierte Testen von Web-App-Frontends bietet sich das Tool Cypress an, welches wir nun einsetzen werden. Dabei besteht die Aufgabe darin, einen End-to-End-Test (E2E-Test) zu schreiben, der die zentrale Funktionalität durch Abbilden des grundlegenden User-Workflows testet. 

1. Installiert das Tool "Cypress" in einen neuen Ordner "test". Befolgt dazu die Anleitung auf der [Cypress Doku-Seite](https://docs.cypress.io/guides/getting-started/installing-cypress). Welche Package Manager ihr dabei verwendet ist euch überlassen. Öffnet anschließend das Tool. 

1. Arbeitet das "Writing Your First E2E Test"-[Tutorial](https://docs.cypress.io/guides/end-to-end-testing/writing-your-first-end-to-end-test) durch. 

1. Es ist empfehlenswert die Tests zunächst lokal zu entwickeln. Startet dazu die App (falls sie nicht bereits läuft). Im Nachgang werdet ihr die in Azure deployte App testen können.

1. Schreibt einen E2E-Test, der die zentralen Funktionen der App abdeckt. Folgende Schritte sollten beinhaltet sein: 

    a. Validierung, dass die Seite aufrufbar ist
    
    b. Überprüfung, dass Bücher angezeigt werden (z.B. das Buch "Agile Software Development with Scrum")

    c. Hinzufügen eines neuen Buches (und Überprüfung, dass dieses Buch nach Erstellung auch tatsächlich sichtbar ist)

    d. Entleihen und zurückgeben eines Buches (und Validierung, das der Status des Buches entsprechend angezeigt wird)
    
    e. Löschen eines Buches (und Sicherstellung, dass das gelöschte Buch nicht mehr in der Liste auftaucht) 

1. Baut nun den Test als eigene Stage in die bereits erstellte Pipeline ein. Nun wird mit jedem Deployment ein Frontend-Test durchgeführt und somit die Qualität der App mit jedem Commit sichergestellt.

### Checklist:

- [ ] Es lässt sich mit dem Test überprüfen, dass die Web App aufrufbar ist und Bücher auf der Startseite sichtbar sind.
- [ ] Ein kompletter E2E Workflow ist abgebildet: Vom Hinzufügen eines Buches, über das Überprüfen der Ausleih-Funktionalität, bis hin zum Löschen eines Buches.
- [ ] Der Test ist in der CI/CD Pipeline eingebaut und wird erfolgreich ausgeführt.

### Lernmaterialien

- [Kurzer Artikel zur Testautomatisierung mit Cypress](https://t3n.de/news/cypress-beste-testing-framework-1203266/)
- [Übersicht zu Cypress](https://docs.cypress.io/guides/overview/why-cypress)

[Home](../../README.md) - [Next >](../challenge10/README.md)