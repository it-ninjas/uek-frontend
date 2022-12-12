# Projekt

Nach der Theorie und den Übungen könnt ihr euer wissen nun in einem eigenen, kleinen Projekt anwenden und vertiefen:

## Departure

Departure - dein Dashboard für den öffentlichen Verkehr

Mit departure können Benutzer die persönlichen ÖV Verbindungen verwalten und deren Status live anzeigen lassen.

### Funktionale Anforderungen

* Benutzer kann eigene Verbindungen mit von/zu Haltestelle verwalten (CRUD)
* Um Verbindungen zu verwalten muss sich der Benutzer erst mit seiner E-Mail und einem Passwort anmelden. 
* Auf der Hauptseite wird eine Liste aller gespeicherten Verbindungen angezeigt
* Beim Klick auf eine Verbindung werden die nächsten 5 Verbindungen angezeigt:
  * Abfahrt in: x h, min
  * Verspätung in Minuten
  * Status: ...
* Ist am aktuellen Tag keine Verbindung mehr vorhanden, werden die Verbindungen des nächsten Tages angezeigt. In diesem Fall soll ein entsprechender Hinweis angezeigt werden. 
* Eine Verbindung kann via URL an einen anderen Benutzer gesendet werden. Für die Anzeige einer solchen Verbindung wird kein Login benötigt.


### Nicht funktionale Anforderungen
* Verwendung einer i18n Library (z.B. i18next)
* Source Code in einem öffentlichen Github Repo

### Optionale Anforderungen
* Registrierung neuer Benutzer
