# KfW DevOps Challenge

## Challenge 8 - Deployment nach Azure

[Home](../../README.md) - [Back >](../challenge07/README.md)

### Intro

Nun wollen wir unsere Anwendung auch anderen zur Verfügung stellen, und machen uns dafür die Azure Cloud zu nutze. 

### Tasks

In dieser Herausforderung werden wir uns Azure App Services mit Multicontainern zu nutze machen.
Obwohl sich dieses Feature im "Preview" Status befindet, ist dies für unsere Zwecke gut geeignet, da wir unser Wissen zu docker compose wieder verwenden können. Alternativ würden wir für jede Komponente einen Cloud Service hochfahren, und diese dann verknüpfen, würde aber an dieser Stelle den Rahmen sprengen, da dies auch ins Netzwerk Setup gehen würde.

1. Wir werden im folgenden mit dem docker-compose.webapp.yml arbeiten. Öffnet das File und ersetzt die Einträge mit `yourregistry.azurecr.io` mit eurer ACR URL.

2. Ladet als Vorbereitung das `mongo:5` Image in euren privaten ACR hoch. Es ist gebräuchlich öffentliche Assets in die eigene Infrastruktur zu duplizieren, weil man nicht abhängig von einer externen Quelle sein möchte, da es evtl. gelöscht oder manipuliert werden kann.

3. Folgt diesem [Tutorial](https://docs.microsoft.com/en-us/azure/app-service/quickstart-multi-container) um eure Applikation auf Azure App Service zu deployen, überspringt die ersten beide Schritte bzgl. Resourcen Gruppe und Beispiel runterladen, da wir das bereits gemacht haben. Verwendet beim App Service Plan "`--sku B2`". (Hinweis: Nicht vergessen das `docker-compose.webapp.yml` zu verwenden)
   - Am Ende des Tutorial nach dem "Create a Docker Compose app" Schritt, wird eure Applikation noch nicht aufrufbar sein, weil wir die Images aus unserem ACR beziehen
   - Um euer ACR zu konfigurieren für den App Service, geht im Azure Portal zu dem neu erstellten `App Service -> Deployment | Deployment Center` und richtet unter Einstellungen euer ACR für den App Service ein
   - Kopiert die `docker-compose.webapp.yml` nochmal um abspeichern zu können

4. Wartet bis eure Applikation erfolgreich startet (kann ein paar Minuten dauern) und greift auf die Applikation über die App Service URL zu. Ihr könnt unter `Euer App Service -> Deployment | Deployment Center | Logs` beobachten ob eure Applikation startet.

5. Dokumentiert die Schritte und Kommandos die ihr verwendet habt.

Bonus:

6. Entkoppelt die Datenbank von der Applikation, indem ihr euch in Azure eine "Azure Cosmos DB API for MongoDB" erstellt, und die entsprechende Anpassung im docker-compose.webapp.yml durchführt. Dokumentiert die notwendige Änderung!
   - Hinweis 1: Es müssen Änderungen im docker-compose, db-seed/Dockerfile und am App Service gemacht werden
   - Hinweis 2: Die Komponenten müssen auf die mongo uri der azure resource angepasst werden
   - Hinweis 3: In der URI Connection String könnt ihr direkt die collection angeben yourdb.mongo.cosmos.azure.com:10255/**dobook**

### Checklist

- [ ] Eure Applikation ist über eure App Service URL erreichbar

### Lernmaterial

- [ACI Multi Container Deployment](https://docs.microsoft.com/en-us/azure/container-instances/tutorial-docker-compose)
- [Docker running compose Applications on ACI](https://docs.docker.com/cloud/aci-integration/#running-compose-applications)
- 

[Home](../../README.md) - [Next >](../challenge09/README.md)