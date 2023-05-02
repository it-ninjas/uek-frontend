# Projekt

Nach der Theorie und den Übungen könnt ihr euer Wissen nun in einem eigenen, kleinen Projekt anwenden und vertiefen:

## Departure

Departure - dein Dashboard für den öffentlichen Verkehr.

Mit departure können Benutzer die persönlichen öV-Verbindungen verwalten und deren Status live anzeigen lassen.

### Funktionale Anforderungen

* Benutzer kann eigene Verbindungen mit von/zu-Haltestelle verwalten (CRUD ohne Update).
* Um Verbindungen zu verwalten, muss sich der Benutzer erst mit seiner E-Mail und einem Passwort anmelden.
* Auf der Hauptseite wird eine Liste aller gespeicherten Verbindungen angezeigt.
* Beim Klick auf eine Verbindung werden die nächsten 5 Verbindungen angezeigt:
  * Abfahrt in: x h, min
  * Verspätung in Minuten
  * Status: ...
  * Optional: weitere nützliche Infos
* Ist die Verbindungsseite geöffnet, werden die Daten im Minutentakt aktualisiert
* Ist am aktuellen Tag keine Verbindung mehr vorhanden, werden die Verbindungen des nächsten Tages angezeigt. In diesem Fall soll ein entsprechender Hinweis angezeigt werden. 

### Nicht funktionale Anforderungen

* Als Backend wird folgendes Projekt verwendet: https://github.com/it-ninjas/fuek-departure-api
* Source Code in JavaScript, kein Typescript
* Verwendung einer i18n Library (z.B. i18next), alle Texte sind übersetzt und nicht hardcoded im Code. UI Sprache ist vorerst nur Deutsch.
* Design ist mit Twitter Bootstrap implementiert (react-bootstrap wird empfohlen)
* Es gibt eigene CSS-Regeln, die mit SCSS implementiert worden sind. Bootstrap soll mit einigen Custom-Rules angepasst werden. (z.B. Farbe, Schrift)
* Es wurde `momentjs` oder eine ähnliche Library verwendet, um Datum/Zeit zu formatieren oder Berechnungen damit durchzuführen.
* Es ist ein Testframework in das Projekt integriert worden und mind. eine Komponente wird automatisiert getestet. Es existieren insgesamt mind. 3 Unit-Tests.
* Für das Routing wird React Router verwendet
* Source Code in einem öffentlichen Github Repo
* Die öV-Verbindungsdaten werden via https://transport.opendata.ch/ abgerufen
* README.md vorhanden:
  * Beschreibt die Ordnerstruktur (was ist wo?)
  * Setupanleitung vorhanden

### Vorgehen

* Suche einen Partner-Ninja und trage dich in der Liste ein
* Erstelle zuerst eine Skizze von deiner Lösung (Mockups oder auf Papier)
* Erstellt ein neues React-Projekt und arbeitet euch durch Thinking-React (https://react.dev/learn/thinking-in-react)
* Erstellt ein öffentliches Github-Repo und tragt den Link in die Liste ein
* Macht euch Gedanken über eine sinnvolle Ordner-Struktur und dokumentiert diese kurz und bündig
* Bringe das Backend lokal zum Laufen und stelle sicher, dass die Unit Tests laufen (gem. Backend-README).
* Versuche z.B. mit PostMan, dich einzuloggen und mache dich mit der REST API vertraut.
* Identifiziert eure Aufgaben und teilt diese sinnvoll auf. Happy Coding :)

### Abgabe Fük 2023

Termin: Montag, 8.5.2023, 20:00

* Erstellt einen Branch **abgabe** für euer Projekt
* Jedes Team-Mitglied schreibt eine E-Mail mit dem Titel 'Abgabe Projekt Frontend-ÜK', mit dem Link zum Projekt/Branch Abgabe an eure Coaches
* Verspätete Abgabe gibt mind. 0.5 Noten Abzug
