# Projekt

Nach der Theorie und den Übungen könnt ihr euer wissen nun in einem eigenen, kleinen Projekt anwenden und vertiefen:

## Departure

Departure - dein Dashboard für den öffentlichen Verkehr

Mit departure können Benutzer die persönlichen ÖV Verbindungen verwalten und deren Status live anzeigen lassen.

### Funktionale Anforderungen

* Benutzer kann eigene Verbindungen mit von/zu Haltestelle verwalten (CRUD ohne Update)
* Um Verbindungen zu verwalten muss sich der Benutzer erst mit seiner E-Mail und einem Passwort anmelden. 
* Auf der Hauptseite wird eine Liste aller gespeicherten Verbindungen angezeigt
* Beim Klick auf eine Verbindung werden die nächsten 5 Verbindungen angezeigt:
  * Abfahrt in: x h, min
  * Verspätung in Minuten
  * Status: ...
* Ist am aktuellen Tag keine Verbindung mehr vorhanden, werden die Verbindungen des nächsten Tages angezeigt. In diesem Fall soll ein entsprechender Hinweis angezeigt werden. 

### Nicht funktionale Anforderungen

* Als Backend wird folgendes Projekt verwendet: https://github.com/it-ninjas/fuek-departure-api
* Source Code in JavaScript, kein Typescript
* Verwendung einer i18n Library (z.B. i18next)
* Design ist mit Twitter Bootstrap implementiert
* Es gibt custom CSS Definitionen die mit SCSS implementiert sind
* momentjs oder ähnliche Library um Datum/Zeit zu formatieren oder Berechnungen zu machen
* Es ist ein Testframework in das Projekt integriert und mind. eine Komponente wird automatisiert getestet
* Für das Routing wird React Router verwendet
* Source Code in einem öffentlichen Github Repo
* Die öV-Verbindungsdaten werden via https://transport.opendata.ch/ abgerufen
* README.md vorhanden:
  * Beschreibt die Ordnerstruktur (was ist wo?)
  * Setupanleitung vorhanden

### Optionale Anforderungen
* 
