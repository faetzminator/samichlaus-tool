# Einrichtung Anbieter

## Neu erfassen

1. Besuche WordPress Admin
2. Anbieter &rarr; Neuen Beitrag erstellen
3. Fülle Formular aus - s.u.
4. \[Veröffentlichen\]

## Anbieter

Wir erfassen die Anbieter so, dass möglichst viele Einstellungen in den Feierarten übernommen werden können.

- Aussenstandorte
- Samichlaus Bülach
- Samichlaus in umliegenden Gemeinden
- Samichlaus in Aussengemeinden

## Daten

### Familienbesuche

Titel: Samichlaus `<Ort>`, z.B. "Samichlaus Bülach" - s.o.

Text

> Je nachdem, ob Samichlaus und Schmutzli eine Familie, eine Firma oder einen Kindergarten besuchen, läuft die Feier anders ab. Bei Feiern für Spielgruppen, Kindergärten und Schulen sowie bei Grossfeiern für Erwachsene ruft Samichlaus im Vorfeld an, um den Ablauf zu besprechen. Bei Familienfeiern nicht.
>
> Bei einer Familienfeier zaubern Samichlaus und Schmutzli vorweihnachtliche Stimmung ins Wohnzimmer. Schmutzli «beobachtet» das Jahr hindurch die Kinder. Er notiert, was sie sehr gut machen und was noch verbesserungswürdig ist. Diese Rückmeldungen werden von den Eltern aufgeschrieben und für Samichlaus und Schmutzli auf dem «Steckbrief» notiert.
>
> Aktuell können in unserem neuen Buchungssystem ausschliesslich Termine für Familienfeiern gebucht werden. Für alle anderen Feierarten wenden Sie sich bitte weiterhin via Mail an unser Präsidium (`info@s...h.ch`).

#### Einstellungen

- [x] Inherit Service Price
- [ ] Benutzerdefinierten Zeitplan verwenden

Da unsere Touren meist unterschiedliche Zeitpläne definieren (z.B. nach Ortschaft), können wir auf Stufe Anbieter
**keine** benutzerdefinierten Zeitpläne verwenden. S.u.

### Aussenstandorte

Titel: Aussenstandorte

Text

> Bei einer Familienfeier zaubern Samichlaus und Schmutzli vorweihnachtliche Stimmung ins Wohnzimmer. Schmutzli «beobachtet» das Jahr hindurch die Kinder. Er notiert, was sie sehr gut machen und was noch verbesserungswürdig ist. Diese Rückmeldungen werden von den Eltern aufgeschrieben und für Samichlaus und Schmutzli auf dem «Steckbrief» notiert.
>
> Nebst den Besuchen zu Hause kann man Samichlaus und Schmutzli seit einigen Jahren an Aussenstandorten treffen. Aktuell empfangen wir Familien am Rütihof Bülach hinter der Kantonsschule.
>
> Bei Besuchen am Aussenstandort wird – im Unterschied zu den Hausbesuchen – Samichlaus für jedes Kind ein Chlaussäckli bereitstellen. Darum müssen wir **pro Kind 25.-** verrechnen.

#### Einstellungen

- [x] Inherit Service Price
- [x] Benutzerdefinierten Zeitplan verwenden
- Dauer: `02:00`
- Arbeitstage: `<Von>` - `<Bis>` (Sa & So)
- Arbeitsstunden:
  - `16:00` - `18:00`
  - `18:20` - `20:20`

## Benutzerdefinierter Zeitplan

Falls die Arbeitsstunden oder die Arbeitstage eines Anbieters (z.B. Aussengemeinden, Aussenstandorte) von den
[Standards](./crocoblock.md) abweichen, muss ein benutzerdefinierter Zeitplan verwendet werden.

Der benutzerdefinierte Zeitplan kann nur verwendet werden, wenn **keine** darunterliegenden Feierarten weitere
Einschränkungen benötigen. Es ist **nicht möglich**, die angebotenen Arbeitsstunden oder Arbeitstage (auch mit
arbeitsfreien Tagen) weiter einzuschränken (Stand 2025). Dementsprechend ungeeignet für unterschiedliche Touren in
Aussengemeinden.

**Alle Einstellungen** müssen entsprechend überschrieben werden. Leer erfasste Arbeitstage oder Arbeitsstunden werden
beim *benutzerdefinierten Zeitplan* **nicht** vom Standard übernommen.

- [x] Benutzerdefinierten Zeitplan verwenden
- Dauer: *gemäss Anbieter*
- Arbeitstage: *gemäss Anbieter*
- Arbeitsstunden: *gemäss Anbieter*
