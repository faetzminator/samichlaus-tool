# Samichlaus-Tool

Dokumentation des Samichlaus-Tool.

- [Einrichtung](./setup/index.md) – neues Jahr
- [Administration Termine](./termine/index.md) – während Aktion
- [Diverses](./div/index.md)
- [Technisches](./tech/index.md) – Architektur etc.

## WIP

### Todos

- Nach Go-live
  - WP Plugin: Mailster
  - Mailboxen
    - Accounts für Kassier etc.?
    - Generierte Mails
      - Mails an `info@` unnötig?
- Terminplanung Wochenende
  - WE ab 16:40 statt 17:00 i.O.? Alterszentrum Grampen etc. immer 6. Dez, kann WE sein
    - Soligänter immer Mittwoch; Bergli individuell
    - Grampen etc. (alle anderen) immer 6. - adde Doku
    - Siehe Dropbox für Zeiten 2024
  - Dokumentieren!
- Sonstiges
  - Doku: [MkDocs](https://www.mkdocs.org/) ausprobieren, vielleicht [mike](https://github.com/jimporter/mike)

### Bugs & Features

- Touren-PDF
  - Feature: Subtitel auf PDF für zusätzliche Informationen (Notfall-Nr)?
  - Feature: Feld für Eingang Geld/Spenden pro Termin?
  - Feature: Feld für effektive Startzeit für Retro?
- Feature: Anzahl Kinder & Erwachsene
  - Chlauschef-Tools ➔ Buchungsliste: Total sichtbar - trennen?
  - Chlauschef-Tools ➔ Tourenliste: Anzeigen?
    - auch bei "in Bearbeitung" anzeigen
    - JetAppointment Nummer könnte weichen
- Feature: Anzahl Kinder bei Buchung - Subtext für Erklärung Anzahl Steckbrief?
- Feature: Alternativer Termin - gleiches Datum ermöglichen?
- Feature: Popup Werbung Neumitglieder (oder Status Buchungen etc.) auf Startseite
- Feature: Aussenstandorte ohne Feieradresse analog "Waldhüsli" von Zürich
- Feature: neue Seite FAQ
- Feature: Status von Touren
  - Storniert: farblich hinterlegt (grau), nicht Teil vom PDF
  - Ausgebucht: farblich hinterlegt (gelb)
- Improvement: Validierung während Termineingabe
  - Bessere Texte, z.B. wenn keine Nummer (Anzahl Kinder & Erwachsene)
  - Felder mit Fehlern hervorheben?
- SEO: gemäss Mail Beni / Zentrale / Peter
- Bug: WP Admin - WooCommerce - löscht manchmal "Besuchszeit von" bei Bearbeitung von Terminen - gemeldet
- Bug: Kunde erhält bis zu 3 gleiche Mails, wenn Termin storniert wird - gemeldet
- Bug: Testing mit Handy - Kunde hat nur einen Slot gesehen?
- Bug: Termine ab 5 Kindern (Ab 100.-) bei Buchung 0.- (war 100.-, auch nicht optimal)
- Bug: PDF-Download Tourenplan funktioniert nicht auf allen Clients (falscher Content-Type?) - gemeldet

- Steckbrief
  - Bug: Mailadresse bei Button falsch
  - Feature: "Name", "Vorname", "Strasse / Nr.", "PLZ", "Ort", "Tel." - Feieradresse vs. Rechnungsadresse
  - Feature: Kommentar digital ausfüllen / Adobe Reader o.ä.

- Webseite
  - Texte zu Chlaussäckli von Eltern fehlen
  - Höhe Spenden beschreiben?
