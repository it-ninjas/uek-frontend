# Bewertung des Kleinprojekts
Hier ist eine Kurzfassung, anhand welcher Kriterien das Kleinprojekt beurteilt wird.

Die Endnote wird mit folgender Formel bestimmt:
Note = $\frac{Erreichte Punktzahl}{Maximale Punktzahl} * 5 + 1$

## Struktur, Naming (6 Punkte)
* Die Struktur ist dokumentiert (kurz, bündig) (1 Punkt)
* Code ist in sinnvolle Ordnern abgelegt (1 Punkt)
* Ein `README.md` oder `.txt` ist vorhanden und beschreibt
    * wie man das Projekt für den lokalen Gebrauch/Entwicklung konfiguriert (1 Punkt)
    * Setup kann von uns interpretiert werden und ist erfolgreich wenn wir es anwenden (3 Punkt)

## Coderichtlinien eingehalten (4 Punkte)
Einhaltung von Coderichtlinien, wie z.B.
  * keine Magic Numbers
  * keine ungebrauchten Variablen und Parameter
  * kein auskommentierter Code
  * kein unerreichbarer Code

## Funktionsumfang / Funktionsfähigkeit (12 Punkte)
* Kommunikation mit dem Backend (3 Punkte)
* React Router (3 Punkte)
  * Bestimmte Seiten sind nur nach Authentifizierung erreichbar.
* Validierung (2 Punkte)
    * Verhindern, dass ungültige Daten an das Backend verschickt werden
    * Anzeigen der Validierungsnachricht neben/unterhalb des Input-Elements
* Authentifizierung (4 Punkte)
    * Token wird nicht bei jedem Backend Aufruf neu generiert.
    * Ist der Token invalid, erfolgt ein Redirect auf die Loginseite.

## Design und Usability (6 Punkte)
* Navigation (1 Punkt)
    * Die Navigation zwischen den einzelnen Seiten ist selbsterklärend und sinnvoll gestaltet.
* Usability (1 Punkt)
    * die häufigsten Aufgaben sind einfach und schnell zu erledigen.
* Interaktivität (1 Punkt)
    * Die Seite arbeitet interaktiv und responsive: Während dem Laden ist die Seite nicht blockiert bzw. ein Ladebalken wird angezeigt.
* Design (3 Punkte)
    * Das Design und die Funktionalitäten sind einheitlich.
        * bei Buttons wird zwischen primary und secondary unterschieden (und entsprechend gestylt)
        * Einheitliche Schriftarten und -grössen.
        * Validierungsnachrichten (für Fehler) sind als Fehler erkennbar und einheitlich gestylt.

## Testing (4 Punkte)

- Es sind min. 3 sinnvolle Unit-Tests vorhanden. (3 Punkt)
- Eine Anleitung beschreibt, wie man Unit Tests ausführt. (1 Punkt)
