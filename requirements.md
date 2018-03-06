---
datatable: true
---
# Anforderungen (Draft)

## Rollen

Folgende Rollen wurden identifiziert:

* **Benutzer**: Greift auf die Anwendung zu, um bereits erstellte Aufzeichnungen anzuzeigen.
* **Messer**: Führt die Messungen durch und überwacht diese während der Durchführung. *Der Messer ist ein Benutzer mit erweiterter Rolle*

## Funktionale Anforderungen

Die Funktionen, die die Anwendung unterstützen soll:

<div class="datatable-begin"></div>

| # | Anforderung | Beschreibung | Rolle |
|---|-------------|--------------|-------|
| 1 | Login | Als Benutzer möchte ich mich einloggen können, um auf die Daten meiner Installationen zugreifen zu können. | Benutzer |
| 2 | Logout | Als Benutzer möchte ich mich nach dem Login ausloggen können, um die Daten meiner Installationen für unbefugte unzugänglich zu machen. | Benutzer |
| 3 | Messung anzeigen | Als Benutzer möchte ich die Daten einer Messung als Visualisierung anzeigen, damit ich die gesammelten Daten verstehen kann. | Benutzer |
| 4 | Messung speichern | Als Benutzer möchte ich eine Messung speichern, damit ich die gesammelten Daten zu einem späteren Zeitpunkt betrachten kann. | Benutzer |
| 5 | Messung exportieren | Als Benutzer möchte ich im System vorhandene Messungen in einem textbasierten Format exportieren können, um sie extern zu sichern oder in ein anderes System importieren zu können. | Benutzer |
| 6 | Messung importieren | Als Benutzer möchte ich eine im System nicht verfügbare Messung importieren, damit ich sie später wieder anzeigen kann. | Benutzer |
| 7 | Messwerte filtern | Als Benutzer möchte ich einen Filter setzen, um die Werte nach ihren Messabständen zu gruppieren. | Benutzer |
| 8 | ~~Positionierungssystem pairen~~ | Als Messer möchte ich mein Positionierungssystem über die Benutzerschnittstelle mit dem System verbinden können, damit diese dort erkannt werden. | Messer |
| 9 | Antennen kalibrieren | Als Messer möchte ich mein Positionierungssystem über die Benutzerschnittstelle kalibrieren können, damit ich die Messung schneller konfigurieren kann. | Messer |
| 10 | ~~Lichtsensor pairen~~ | Als Messer möchte ich meinen Lichtsensor über die Benutzerschnittstelle des Systems mit dem System verbinden, um manuelle Eingaben zu vermeiden. | Messer |
| 11 | Lichtsensor kalibrieren | Als Messer möchte ich den Lichtsensor über die Benutzerschnittstelle kalibrieren können, um ungenaue Messungen zu vermeiden und korrekturen vorzunehmen. | Messer |
| 12 | (Instrumente testen) | Als Messer möchte ich meine mit der Anwendung verbundenen Instrumente testen können, bevor ich die Messung starte. Live-Vorschau? | Messer |
| 13 | Messung starten | Als Messer möchte ich eine Messung über die Benutzerschnittstelle des Systems starten, damit die Sensordaten aufgezeichnet werden. | Messer |
| 14 | Messung fertigstellen | Als Messer möchte ich eine gestartete Messung über die Benutzerschnittstelle des Systems fertigstellen, damit die Messung als abgeschlossen gekennzeichnet wird. | Messer |
| 15 | Messung fortfahren | Als Messer möchte ich bereits angefangene Messungen ergänzen, indem ich gestoppte Messungen erneut starte, um sie zu verbessern. | Messer |

<div class="datatable-end"></div>

## Nichtfunktionale Anforderungen

| # | Anforderung | Beschreibung | Kategorie |
| - | ----------- | ------------ | --------- |
| 1 |  | | |
| 2 | | | |