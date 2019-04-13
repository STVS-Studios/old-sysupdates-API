![SysUpdate API](assets/sysupdatelogo.jpg)
Ein einfacher Dienst zur Erfassung von Update-Daten für viele Spielekonsolen



## Das wichtige zuerst
Dieser Dienst verwendet andere Server, um an die Informationen zu kommen. Diese sind:
- Nintendo's Support Seite (auf Japanisch)
- SONY's Offizielle Update-Server

Ich stehe in keinster Weise mit den Unternehmen im Zusammenhang, zumindest für dieses Projekt.
Wenn entweder SONY oder Nintendo die Schließung des Projekt fordern, gebt mir bitte bescheid (und beweist mir bitte, dass ihr dem Unternehmen wirklich angehört). 
Ich habe das Projekt überprüft und kann sagen, dass dieses keine URLS zu Update Dateien oder andere geheime Inhalte beinhaltet.
Nur die Update-Version und das Veröffentlichungsdatum des Updates werden mitgeteilt.

## Beschreibung
SysUpdate ist eine API, welche Update-Daten für viele Konsolen erfasst.
Es holt sich die Daten aus offiziellen Quellen und kodiert diese in JSON, um in anderen Services und Apps verwendet werden zu können.
Die erhaltenen Daten sind die Versionsnummer des Updates (wie 11.9.0-42) und das Veröffentlichungsdatum des Updates.

## Nutzung
Nutzt dieses URL Schema, um den Service zu benutzen:
https://sysupdate.stvs.me/v1/platform (ersetzt platform mit der benötigten Plattform)
Ihr könnt Daten zu folgenden Plattformen erhalten:
  - Nintendo Switch (switch)
  - Nintendo 3DS (3ds)
  - Playstation 4 (ps4)
  - Playstation VITA (psvita)
