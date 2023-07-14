# KfW DevOps Challenge

## Challenge 7 - IaC Pipeline Integration

[Home](../../README.md) - [Back >](../challenge06/README.md)

### Intro

Nun wollen wir die bestehende GitHub Actions-Pipeline nutzen um die Terraform-Infrastruktur zu integrieren. Infrastructure-as-Code (IaC) ist ein Ansatz zur Automatisierung und Verwaltung der Infrastruktur in der Cloud. Mit Azure können Entwickler die Infrastruktur in einem deklarativen Code definieren und bereitstellen. Dies ermöglicht eine effiziente und konsistente Verwaltung der Ressourcen und fördert die Wartbarkeit und Versionierung von Infrastruktur.


### Tasks

1. Euer Ziel ist es, Terraform-Code in die bestehende GitHub Actions-Pipeline zu integrieren, um die Bereitstellung und Verwaltung der Infrastruktur zu automatisieren. Ändert die YAML-Datei des Workflows, um die notwendigen Schritte für Terraform aufzunehmen.

2. Fügt innerhalb der Pipeline einen Job hinzu, der die Azure Infrastruktur aufbaut. Überprüft dabei, dass die notwendigen Secrets sicher an Terraform zur Authentifizierung und Konfiguration übergeben werden.

3. Checkt, ob eure Infrastrukutur in Azure zur Verfügung steht und funktioniert.

4. Dokumeniert euer Vorgehen.

### Checklist

- [ ] Die Workflow-YAML-Datei sollte den Terraform-Job in der Pipeline beinhalten.
- [ ] Die notwendigen Secrets werden an Terraform sicher übermittelt.
- [ ] Die Pipeline läuft fehlerfrei durch, anschließend ist die Infrastruktur auf Azure verfügbar.

### Lernmaterial

- [Terraform Documentation](https://www.terraform.io/docs/index.html)
- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [GitHub Actions Workflow Syntax](https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions)
- [GitHub Actions Marketplace](https://github.com/marketplace?type=actions)
- [Terraform GitHub Actions](https://github.com/marketplace?category=terraform)


[Home](../../README.md) - [Next >](../challenge08/README.md)
