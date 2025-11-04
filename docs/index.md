# Samichlaus-Tool

Dokumentation des Samichlaus-Tool.

- [Einrichtung](./setup/index.md) – neues Jahr
- [Administration Termine](./termine/index.md) – während Aktion
- [Diverses](./div/index.md)
- [Technisches](./tech/index.md) – Architektur etc.

## WIP

### Todos

- Testen Änderungen JetTermine (Slots in Kalender; Status bereits gebucht; Bestätigungsmail(s); ...)
- Nach Go-live
  - WP Plugin: Mailster
  - Mailboxen
    - Generierte Mails
      - Mails an `info@` unnötig?
- Sonstiges
  - Doku: [MkDocs](https://www.mkdocs.org/) ausprobieren, vielleicht [mike](https://github.com/jimporter/mike)

### Fragen

- Div
  - WE ab 16:40 statt 17:00 i.O.? Alterszentrum Grampen etc. immer 6. Dez, kann WE sein
    - Soligänter immer Mittwoch; Bergli individuell
    - Grampen etc. (alle anderen) immer 6. - adde Doku
    - Siehe Dropbox für Zeiten 2024

### Bugs & Features

- Feature: Anzahl Kinder & Erwachsene
  - Chlauschef-Tools ➔ Buchungsliste: Total sichtbar - trennen?
  - Chlauschef-Tools ➔ Tourenliste: Anzeigen?
- Bug: "Password setzen" Link in Mails für neue Benutzer (während Buchung) führt ins Nirvana
- Bug: WP Admin - WooCommerce - löscht manchmal "Besuchszeit von" bei Bearbeitung von Terminen
- Bug: Kunde erhält 3 gleiche Mails, wenn Termin storniert wird
- Improvement: Validierung während Termineingabe
  - Bessere Texte, z.B. wenn keine Nummer (Anzahl Kinder & Erwachsene)
  - Felder mit Fehlern hervorheben?
- Bug: Testing mit Handy - Kunde hat nur einen Slot gesehen?
- Feature: Alternativer Termin - gleiches Datum ermöglichen?
