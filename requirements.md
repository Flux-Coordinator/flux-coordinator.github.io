---
datatable: true
---
# Anforderungen (Draft)

## Rollen

Folgende Rollen wurden identifiziert:

* **Benutzer**: Greift auf die Anwendung zu, um bereits erstellte Aufzeichnungen anzuzeigen.
* **Vermesser**: Führt die Messungen durch und überwacht diese während der Durchführung. *Der Vermesser ist ein Benutzer mit erweiterten Anforderungen.*

## Funktionale Anforderungen

Die Funktionen, die die Anwendung unterstützen soll:

<div class="datatable-begin"></div>

| # | Anforderung | Beschreibung | Rolle |
|---|-------------|--------------|-------|
| 1 | Login | Als Benutzer möchte ich mich einloggen können, um auf die Daten meiner Installationen zugreifen zu können. | Benutzer |
| 2 | Logout | Als Benutzer möchte ich mich nach dem Login ausloggen können, um die Daten meiner Installationen für unbefugte unzugänglich zu machen. | Benutzer |
| 3 | Messung visualisieren | Als Benutzer möchte ich alle Messwerte einer Messung als Visualisierung anzeigen können, um deren Zusammenhänge zu verstehen. | Benutzer |
| 4 | Messung speichern | Als Benutzer möchte ich eine Messung speichern können, um die gesammelten Daten zu einem späteren Zeitpunkt zu betrachten. | Benutzer |
| 5 | Messung exportieren | Als Benutzer möchte ich im System vorhandene Messungen in einem textbasierten Format exportieren können, um sie extern zu sichern. | Benutzer |
| 6 | Messung importieren | Als Benutzer möchte ich eine nicht mehr im System vorhandene Messung importieren können, um sie wieder anzuzeigen. | Benutzer |
| 7 | Messwerte filtern | Als Benutzer möchte ich in der Visualisierung einen Filter setzen können, um die Messwerte nach ihren Abständen zu gruppieren. | Benutzer |
| 8 | Positionierungssystem konfigurieren | Als Vermesser möchte ich das Positionierungssystem über die Benutzerschnittstelle konfigurieren können, um die Messung schneller aufzusetzen. | Vermesser |
| 9 | Lichtsensor kalibrieren | Als Vermesser möchte ich den Lichtsensor über die Benutzerschnittstelle kalibrieren können, um ungenaue Messungen zu vermeiden und korrekturen vorzunehmen. | Vermesser |
| 10 | (Instrumente testen) | Als Vermesser möchte ich die Konfiguration und Kalibrierung der Sensoren vor Beginn der Messung testen können, um ungültige Messungen zu vermeiden. | Vermesser |
| 11 | Messung starten | Als Vermesser möchte ich eine Messung über die Benutzerschnittstelle starten können, damit die Messwerte aufgezeichnet werden. | Vermesser |
| 12 | Messung abschliessen | Als Vermesser möchte ich eine laufende Messung über die Benutzerschnittstelle des Systems abschliessen können, um die Aufzeichnung weiterer Messwerte zu beenden. | Vermesser |
| 13 | Messung fortfahren | Als Vermesser möchte ich eine bereits abgeschlossene Messung fortfahren können, um sie durch weitere Messwerte zu erweitern. | Vermesser |

<div class="datatable-end"></div>

Das Formulieren der CRUD-Methoden (Create, Read, Update, Delete) wurde der Einfachheit halber weggelassen. Diese werden bei Bedarf implementiert.

## Nichtfunktionale Anforderungen
Die folgenden nichtfunktionalen Anforderungen sind nach ISO 9126 gruppiert.

| # | Anforderung | Kategorie |
|---|-------------|-----------|
| 1 | Sensoren lassen sich austauschen, ohne die Serverkomponente anpassen zu müssen. | Maintainability |
| 2 | Ein Benutzer muss auf das User Interface zugreifen können, ohne zusätzliche Software installieren zu müssen. | Usability |
| 3 | Die Messwerte müssen in mindestens 90% der Anfragen in weniger als 1 Sekunde in der Visualisierung angezeigt werden. | Efficiency |
| 4 | Die Server-Komponente muss auf einer alternativen Platform, separiert von den Sensoren ausgeführt werden können. | Portability |
| 5 | Die gespeicherten Daten des Systems müssen vor unbefugtem Zugriff geschützt werden. | Security |
| 6 | Die aufgezeichneten Messwerte müssen unverändert persistiert werden. Eventuelle Faktoren oder Filter müssen zusätzlich zu den Rohdaten abgelegt werden. | Functionality |