# KfW DevOps Challenge

## Challenge 12 - AKS und Monitoring in Kubernetes

[Home](../../README.md) - [Back >](../challenge11/README.md)

### Intro

In dieser Hackathon-Herausforderung werden Sie sich mit den Kernaspekten von DevOps in Kubernetes befassen und sich dabei insbesondere auf eine effektive Überwachung und Protokollanalyse konzentrieren. Ihre Aufgabe ist es, einen Monitoring-Stack mit Prometheus, Grafana und Loki auf Azure Kubernetes Service (AKS) einzurichten. Sie werden Helm-Diagramme für die Bereitstellung nutzen und eine einfache React.js-Webanwendung als Demonstration der Überwachungsmöglichkeiten Ihres Setups überwachen.

### Tasks

Einrichten eines AKS-Clusters und Einsatz von Prometheus, Grafana und Loki unter Verwendung von Helm-Charts. Ziel ist es, eine bereitgestellte React.js-Webanwendung mit diesem Setup zu verbinden, um Metriken zu sammeln, Logs anzuzeigen und Daten auf einem Dashboard zu visualisieren.

1. Erstellen Sie einen Azure Kubernetes Service (AKS)-Cluster. Eine umfassende Anleitung zur Einrichtung von AKS finden Sie in der offiziellen [Azure-Dokumentation](https://docs.microsoft.com/en-us/azure/aks/).
2. Installieren Sie [Helm](https://helm.sh/docs/) auf Ihrem AKS-Cluster.
3. Verwenden Sie die Helm-Charts [kube-prometheus-stack](https://artifacthub.io/packages/helm/prometheus-community/kube-prometheus-stack) und [loki-stack](https://artifacthub.io/packages/helm/grafana/loki-stack), um Prometheus, Grafana und Loki auf dem Cluster zu installieren. Diese Diagramme sind im offiziellen Artifact Hub verfügbar und werden aktiv gepflegt.
4. Stellen Sie eine einfache, minimalistische React.js-Webanwendung bereit. Verwenden Sie für diese Aufgabe diese Beispielanwendung: [Real World React](https://github.com/gothinkster/react-redux-realworld-example-app). Diese Anwendung dient als gutes Beispiel für eine reale, in React.js geschriebene Frontend-Webanwendung.
5. Verbinden Sie die AKS- und React.js-Anwendung mit den bereitgestellten Prometheus-, Grafana- und Loki-Instanzen.
6. Prometheus sollte so konfiguriert werden, dass es Metriken aus dem AKS-Cluster abgreift. Loki sollte so eingerichtet werden, dass es die Logs der Anwendung anzeigt.
7. Einrichten eines Grafana-Dashboards zur Visualisierung der AKS-Metriken und Anwendungsprotokolle.

### Checklist

- [ ] Einen AKS-Cluster erstellen
- [ ] Installieren von Helm auf dem AKS-Cluster
- [ ] Installierte Prometheus, Grafana, Loki unter Verwendung von Helm Charts (kube-prometheus-stack und loki-stack)
- [ ] Bereitstellen der Real World React-Anwendung
- [ ] Verbinden der React.js-Anwendung mit Prometheus, Grafana und Loki
- [ ] Konfiguration von Prometheus zum Scrapen von Metriken aus dem AKS-Cluster
- [ ] Loki eingerichtet, um die Logs der Anwendung anzuzeigen
- [ ] Einrichten eines Grafana-Dashboards zur Visualisierung von Metriken und Logs der Anwendung

### Lernmaterial

1. [Azure AKS Dokumentation](https://docs.microsoft.com/en-us/azure/aks/)
2. [Helm-Dokumentation](https://helm.sh/docs/)
3. [kube-prometheus-stack Helm Chart](https://artifacthub.io/packages/helm/prometheus-community/kube-prometheus-stack)
4. [loki-stack Helm-Diagramm](https://artifacthub.io/packages/helm/grafana/loki-stack)
5. [Real World React App](https://github.com/gothinkster/react-redux-realworld-example-app)

[Home](../../README.md) - [Next >](../challenge13/README.md)
