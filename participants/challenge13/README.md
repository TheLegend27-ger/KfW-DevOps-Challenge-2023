# KfW DevOps Challenge

## Challenge 13 - Code Quality & Code Security

[Home](../../README.md) - [Back >](../challenge12/README.md)

### Intro

In der nachfolgenden Challenge wollen wir nicht nur das Tool Snyk einrichten und verwenden, sondern auch Tools wie ESLint und Prettier integrieren, um die Sicherheit und Codequalität unserer Software zu verbessern. Snyk bietet eine Vielzahl von Vorteilen, darunter Schwachstellenanalyse, Patch-Management und Lizenzüberprüfung, um Sicherheitslücken und potenzielle Lizenzkonflikte zu erkennen. Darüber hinaus sind Tools wie ESLint und Prettier wichtige Ergänzungen, um die Codequalität und Lesbarkeit zu verbessern. ESLint ermöglicht eine statische Code-Analyse, um potenzielle Fehler, unerwünschte Muster und Best Practices zu identifizieren. Prettier sorgt für eine konsistente Codeformatierung und erleichtert die Zusammenarbeit im Team. Durch die Integration von Snyk, ESLint und Prettier können wir nicht nur die Sicherheit, sondern auch die Qualität unseres Codes optimieren. _(Ähnliche Tools, die wir in Betracht ziehen könnten, sind CodeClimate oder beispielsweise SonarCloud die ebenfalls statische Code-Analyse und Sicherheitsüberprüfungen bieten.)_

### Tasks

1. Richtet euch auf [Snyk](https://app.snyk.io/login) ein kostenloses Konto ein

2. Richtet nun lokal die Synk CLI oder optional ein Plugin/Extension für eure Entwicklungsumgebung ein

3. Scannt das lokale Projekt und lasst dieses mittels Snyk überprüfen

4. Geht nun wieder auf die Webseite von [Snyk](https://app.snyk.io/login) und bindet euer zuvor angelegtes Projekt ein (hierbei ist es ausreichend wenn das jeweils ein Teilnehmer pro Team macht und ggf den anderen Access gewährt)

5. Prüft ob die Einstellungen von eurem Snyk so gewählt sind, dass bei jedem neuen Pull Request Snyk die Changes scannt

   - _Hinweis_: Snyk kann auch so eingerichtet werden, dass es für bekannte Schwachstellen oder ähnliches, automatische Pull Requests erzeugt - für unser Beispiel können wir diese Einstellung wahrscheinlich deaktivieren, da es ggf schnell unübersichtlich wird

6. _Bonus_: Richtet ESlint und Prettier für das Projekt ein

   - (Nutzt hier auch gerne die Visual Studio Code Extensions)

7. _Bonus_: Richtet euch einen Precommit Hook ein, damit eure festgesetzten Regeln vor jedem Commit geprüft werden

### Checklist

- [ ] Ihr habt erfolgreich ein kostenloses Konto auf Snyk erstellt um eure Projekte zu verwalten
- [ ] Ihr habt erfolgreich eine lokale Variante von Snyk eingrichtet und ausgeführt
- [ ] Bei jedem neuen Pull Request wird nun ein neuer Snyk Scan durchgeführt und ihr habt die wichtigsten Daten auf einem Blick im Snyk Dashboard

### Outro

Herzlichen Glückwunsch! In der abgeschlossenen Challenge habt ihr erfolgreich das Tool Snyk eingerichtet und verwendet, um die Sicherheit eurer Software und die Verwaltung von Abhängigkeiten zu gewährleisten. Durch die Integration von Snyk in euren Entwicklungsprozess könnt ihr potenzielle Schwachstellen in verwendeten Bibliotheken identifizieren und beheben, Patches verwalten und Lizenzkonflikte erkennen.
Zusätzlich habt ihr auch die Bonusaufgabe gemeistert, indem ihr ESLint und Prettier für das Projekt eingerichtet habt. Diese Tools ermöglichen eine statische Code-Analyse und automatische Codeformatierung, um die Code-Qualität und Lesbarkeit zu verbessern. Durch die Kombination von Snyk, ESLint und Prettier könnt ihr die Codequalität steigern und die Sicherheit eurer Softwareprojekte kontinuierlich gewährleisten. Großartige Arbeit!

### Lernmaterial

- [Snyk CLI](https://docs.snyk.io/snyk-cli/install-the-snyk-cli)
- [Prettier Precommit Hook](https://prettier.io/docs/en/precommit.html)

[Home](../../README.md) - [Next >](../challenge14/README.md)
