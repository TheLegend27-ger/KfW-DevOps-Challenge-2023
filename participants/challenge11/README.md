# KfW DevOps Challenge

## Challenge 11 - Azure Policy

[Home](../../README.md) - [Back >](../challenge10/README.md)

### Intro

Bisher haben wir die Azure Cloud uns zu Nutze gemacht, um uns Rechenleistung wie wir sie benötigen nach Bedarf zu beschaffen. Zu unseren Aufgaben gehört es aber auch unsere Cloud Umgebung zu managen, und ein Management Bereich davon nennt sich Governance.

Governance stellt Mechanismen und Prozesse bereit, um die **Kontrolle** über Anwendungen und Ressourcen in Azure zu behalten. Governance in Azure wird hauptsächlich mit zwei Diensten implementiert. Mit Azure Policy können wir Richtliniendefinitionen erstellen, zuweisen und verwalten, um Regeln für die Ressourcen durchzusetzen. Das ermöglicht uns die Cloud Ressourcen in Übereinstimmung mit unseren Unternehmensstandards zu halten. Der andere Aspekt in Governance ist Kostenmanagement. Hier werden wir uns Azure Policy genauer anschauen.

### Tasks

In dieser Herausforderung werden wir eine Azure Policy erstellen, um nicht konforme Ressourcen zu identifizieren.

1. Erstellt einen Storage Account in der location North Europe.
   
2. Erstellt eine Azure policy um die locations von Ressourcen auf "West Europe" zu beschränken. 

3. Prüft auf der "Policy" Seite im Azure Portal die Übersicht, was seht ihr?

4. Updated eure policy, sodass "North Europe" ebenfalls erlaubt ist, und schaltet die Policy auf "Enforcement".

5. Dokumentiert eure Schritte.

### Checklist

- [ ] Eine Azure Policy ist aktiv um die eingesetzten Locations zu überwachen
- [ ] Eure Ressourcen in Azure sind konform
- [ ] Ihr könnt keine neuen Ressourcen außerhalb von West oder North Europe erstellen

### Lernmaterial

- [Azure Policies](https://docs.microsoft.com/en-us/azure/governance/policy/overview)


[Home](../../README.md) - [Next >](../challenge12/README.md)