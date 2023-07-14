# KfW DevOps Challenge

## Challenge 4 - Package and Push to ACR

[Home](../../README.md) - [Back >](../challenge03/README.md)

### Intro

Jetzt haben wir die containerisierte Anwendung lokal laufen. Schicken wir nun die gepackte Anwendung (auch bekannt als containerisierte Anwendung) an ein Image-Repository. Es kann grundsätzlich jede Art von Image-Repository verwendet werden. In dieser Challenge verwenden wir jedoch die Azure Container Registry (kurz: ACR).

### Tasks

Dies ist eine Fortsetzung der vorherigen Aufgabe. In dieser Aufgabe werdet ihr eine Azure Container Registry (ACR) erstellen und Docker-Images in die ACR pushen.

1. Erstellt im Azure Portal eine Resourcen Gruppe und eine Azure Container Registry (ACR). Vergebt bei beidem  einen Namen mit dem Suffix / Bezeichnungsende "manual", da wir in der nächsten Aufgabe IaC verwenden werden. Ihr solltet euch dabei an den [gängigen Abkürzungen von Azure](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/resource-abbreviations) und [Namenkonventionen](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/resource-naming) orientieren. Beispiel: `team1-rg-manual`

2. Richtet die lokale Docker-Laufzeitumgebung so ein, dass sie auf die neu erstellte ACR verweist.

3. Pusht die containerisierte Anwendung in die ACR.

4. Bittet eure Team Mitglieder euer gepushtes Image zu ziehen (pullen).
   
5. Dokumentation ist ein wichtiger und essentieller Bestandteil für alle Teamarbeiten. Fügt Dokumentation in euer README.md hinzu für die Kommandos die ihr benutzt. 

### Checklist

- [ ] Containerisierte Anwendung auf ACR übertragen 
- [ ] Andere Teammitglieder sind in der Lage, das Image von ACR zu ziehen

### Lernmaterial

- [ACR Documentation](https://docs.microsoft.com/en-us/azure/container-registry/)


[Home](../../README.md) - [Next >](../challenge05/README.md)
