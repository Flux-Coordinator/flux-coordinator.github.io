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
| 3 | Messung anzeigen | Als Benutzer möchte ich eine bereits im System verfügbare Messung anzeigen, damit ich die gesammelten Daten nochmals betrachten kann. | Benutzer |
| 4 | Messung exportieren | Als Benutzer möchte ich im System vorhandene Messungen in einem textbasierten Format exportieren können, um sie extern zu sichern oder in ein anderes System importieren zu können. | Benutzer |
| 5 | Messung importieren | Als Benutzer möchte ich eine im System nicht verfügbare Messung importieren, damit ich sie später wieder anzeigen kann. | Benutzer |
| 6 | ~~Pozyx pairen~~ | Als Messer möchte ich mein Pozyx über die Benutzerschnittstelle mit dem System verbinden können, damit diese dort erkannt werden. | Messer |
| 7 | Antennen kalibrieren | Als Messer möchte ich mein Pozyx über die Benutzerschnittstelle kalibrieren können, um meinen Einarbeitungsaufwand in die Anwendung zu reduzieren. | Messer |
| 8 | ~~Lichtsensor pairen~~ | Als Messer möchte ich meinen Lichtsensor über die Benutzerschnittstelle des Systems mit dem System verbinden, um manuelle Eingaben zu vermeiden. | Messer |
| 9 | Lichtsensor kalibrieren | Als Messer möchte ich den Lichtsensor über die Benutzerschnittstelle kalibrieren können, um ungenaue Messungen zu vermeiden und korrekturen vorzunehmen. | Messer |
| 10 | (Instrumente testen) | Als Messer möchte ich meine mit der Anwendung verbundenen Instrumente testen können, bevor ich die Messung starte. Live-Vorschau? | Messer |
| 11 | Messung starten | Als Messer möchte ich eine Messung über die Benutzerschnittstelle des Systems starten, damit die Sensordaten aufgezeichnet werden. | Messer |
| 12 | Messung fertigstellen | Als Messer möchte ich eine gestartete Messung über die Benutzerschnittstelle des Systems fertigstellen, damit die Messung als abgeschlossen gekennzeichnet wird (**?**). | Messer |
| 13 | Messung fortfahren | Als Messer möchte ich bereits angefangene Messungen ergänzen, indem ich bereits gestoppte Messungen erneut state, damit ich die Messung verbessern kann. | Messer |

<div class="datatable-end"></div>