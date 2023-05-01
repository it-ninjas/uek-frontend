# Projekt

Nach der Theorie und den Übungen könnt ihr euer Wissen nun in einem eigenen, kleinen Projekt anwenden und vertiefen:

## Departure

Departure - dein Dashboard für den öffentlichen Verkehr.

Mit departure können Benutzer die persönlichen öV-Verbindungen verwalten und deren Status live anzeigen lassen.

### Funktionale Anforderungen

* Benutzer kann eigene Verbindungen mit von/zu-Haltestelle verwalten (CRUD ohne Update).
* Um Verbindungen zu verwalten, muss sich der Benutzer erst mit seiner E-Mail und einem Passwort anmelden (keine Registration erforderlich, Anmeldedaten sind im Backend hartcodiert).
* Auf der Hauptseite wird eine Liste aller gespeicherten Verbindungen angezeigt.
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
* Es gibt eigene CSS-Regeln, die mit SCSS implementiert worden sind.
* Es wurde `momentjs` oder eine ähnliche Library verwendet, um Datum/Zeit zu formatieren oder Berechnungen damit durchzuführen.
* Es ist ein Testframework in das Projekt integriert worden und mind. eine Komponente wird automatisiert getestet. Es existieren insgesamt mind. 3 Unit-Tests.
* Für das Routing wird React Router verwendet
* Source Code in einem öffentlichen Github Repo
* Die öV-Verbindungsdaten werden via https://transport.opendata.ch/ abgerufen
* README.md vorhanden:
  * Beschreibt die Ordnerstruktur (was ist wo?)
  * Setupanleitung vorhanden

### Vorgehen

* Erstelle zuerst eine Skizze von deiner Lösung (Mockups oder auf Papier)
* Erstelle ein neues React-Projekt.
* Lade dieses auf GitHub hoch und teile den entsprechenden Link (inkl. Berechtigungen) mit den Coaches.
* Mache dir Gedanken über eine sinnvolle Ordner-Struktur und setze diese um (Tipp: berücksichtige funktionalen sowie nicht-funktionalen Anforderungen).
* Bringe das Backend lokal zum Laufen und stelle sicher, dass die Unit Tests laufen (gem. Backend-README).
* Versuche z.B. mit PostMan, dich einzuloggen und mache dich mit der REST API vertraut.
* Nun kannst du mit dem Projekt beginnen. Happy Coding :)