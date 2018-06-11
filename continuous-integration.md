# Continuous Integration and Delivery

Das Projekt verwendet mehrere Tools für das Sicherstellen der Qualität.

## Travis CI

Mit Hilfe von Travis CI, werden die Tests der Software automatisiert durchgeführt. Die Tests sind in zwei Projekte aufgeteilt und werden zur Zeit getrennt voneinander durchgeführt.

* [Travis CI Umgebung](https://travis-ci.org/Flux-Coordinator)

## Heroku

Um möglichst immer eine Instanz zum Demonstrieren und Testen zur Verfügung zu haben, werden die Systeme automatisch auf Heroku bereitgestellt. Es gibt hierbei mehrere Instanzen, welche sich bezüglich Stabilität unterscheiden. Productive Instanzen entsprechen den ```master``` Branches auf GitHub. Staging Instanzen entsprechen den ```develop``` Branches auf GitHub und entsprechen deshalb einer aktuelleren (aber auch instabileren) Version. Unten sind die entsprechenden Links zu den Produktiven und Staging Instanzen aufgelistet:

* [Application Server (Productive)](https://flux-server-prod.herokuapp.com)
* [Application Server (Staging)](https://flux-server-staging.herokuapp.com)
* [Frontend (Productive)](https://flux-coordinator.herokuapp.com)
* [Frontend (Staging)](https://flux-coordinator-staging.herokuapp.com)

Es kann sein, dass der Request beim ersten Aufrufen der Links etwas länger dauert. Dies tritt auf, wenn sich der Server längere Zeit inaktiv verhält und deshalb in den Schlafmodus übergeht. Nach dem Aufwachen des Servers, steht dieser wieder normal zur Verfügung.