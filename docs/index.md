# Samichlaus-Tool

Dokumentation des Samichlaus-Tool.

- [Einrichtung](./setup/index.md) – neues Jahr
- [Administration Termine](./termine/index.md) – während Aktion
- [Diverses](./div/index.md)
- [Technisches](./tech/index.md) – Architektur etc.

## Todos

- Mailster & AWS Alternative
- Terminplanung Wochenende
  - Konflikt Familienbesuche 16:40 mit Grossfeiern
  - Alterszentrum Grampen etc. immer 6. Dez, kann WE sein
    - Soligänter immer Mittwoch; Bergli individuell
    - Grampen etc. (alle anderen) immer 6. - adde Doku
    - Siehe Dropbox für Zeiten 2024/25
  - Dokumentieren!
- Sonstiges
  - Doku: [MkDocs](https://www.mkdocs.org/) ausprobieren, vielleicht [mike](https://github.com/jimporter/mike)

## Bugs & Features

### Kundenseitig

- Änderungen Buchung
  - Feature: Anzahl Kinder bei Buchung - Subtext für Erklärung Anzahl Steckbrief
  - Feature: Alternativer Termin - gleiches Datum ermöglichen?
  - Feature: Aussenstandorte ohne Feieradresse analog "Waldhüsli" von Zürich
  - Feature: Validierung während Termineingabe
    - Bessere Texte, z.B. wenn keine Nummer (Anzahl Kinder & Erwachsene)
    - Felder mit Fehlern hervorheben?
- Feature: Popup Werbung Neumitglieder und Spenden (oder Status Buchungen etc.) auf Startseite
- Feature: neue Seite FAQ (inkl. Top Menu)
- Bug: Kunde erhält bis zu 3 gleiche Mails, wenn Termin storniert wird - gemeldet
- Bug: Termine ab 5 Kindern (Ab 100.-) bei Buchung 0.- (war 100.-, auch nicht optimal)
- Webseite Allgemein
  - Texte zu Chlaussäckli von Eltern fehlen
  - Höhe Spenden beschreiben?

### Vereinsmitglieder & Touren

- Änderungen Touren-PDF
  - Feature: Subtitel auf PDF für zusätzliche Informationen (Notfall-Nr)?
  - Feature: Feld für Eingang Geld/Spenden pro Termin?
  - Feature: Feld für effektive Startzeit für Retro?

### Einsatzzentrale

- Änderungen Chlauschef-Tools
  - Anzeige Chlauschef-Tools ➔ Tourenliste
    - Anzeige von Anzahl Kindern und Erwachsenen (z.B. rechts oben)
    - Details auch "in Bearbeitung" etc. anzeigen
      - statt Stern andere Symbole? Sanduhr (in Bearbeitung), Kreuz (storniert), ...
      - angepasste Hintergrundfarbe? grau (in Bearbeitung), rot (storniert), ...
    - Paging: Mehr Touren auf einer Seite anzeigen
  - Anzeige Chlauschef-Tools ➔ Buchungsliste
    - Trennung von Anzahl Teilnehmer in Kinder und Erwachsene
- WP Admin - WooCommerce
  - Bug: löscht manchmal "Besuchszeit von" bei Bearbeitung von Terminen - gemeldet
- Mailbenachrichtigungen
  - Mails an `info@` unnötig

### Vorstand

- Feature: Mailboxen für Kassier etc.?
- Diskussion: gewisse Gemeinden streichen?
- Diskussion: Vorschlag Spende pro Kind auf Webseite?
