# Continuous Integration and Delivery

Das Projekt verwendet mehrere Tools für das Sicherstellen der Qualität.

## Sonar

Auf Sonarcloud finden sich verschiedene Codemetriken, mit welchen Missstände im Code aufgedeckt werden können.

* [SonarCloud Metriken](https://sonarcloud.io/organizations/flux-coordinator/projects)

## Travis CI

Mit Hilfe von Travis CI, werden die Tests der Software automatisiert durchgeführt. Die Tests sind in zwei Projekte aufgeteilt und werden zur Zeit getrennt voneinander durchgeführt.

* [Travis CI Umgebung](https://travis-ci.org/Flux-Coordinator)

## Heroku

Um möglichst immer eine Instanz zum Demonstrieren und Testen zur Verfügung zu haben, werden die Systeme automatisch auf Heroku bereitgestellt. Es gibt hierbei mehrere Instanzen, welche sich bezüglich Stabilität unterscheiden. Unten sind die stabilsten Bereitstellungen zu finden. Diese entsprechen dem Stand des ```master``` Branches auf GitHub.

* [Application Server (Productive)](https://flux-server-prod.herokuapp.com)
* [Frontend (Productive)](https://flux-coordinator.herokuapp.com/)

Es kann sein, dass der Request beim ersten Aufrufen der Links etwas länger dauert. Dies tritt auf, wenn sich der Server längere Zeit inaktiv verhält und deshalb in den Schlafmodus übergeht. Nach dem Aufwachen des Servers, steht dieser wieder normal zur Verfügung.