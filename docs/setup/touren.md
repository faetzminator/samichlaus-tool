# Einrichtung Touren

## Neu erfassen

1. Besuche WordPress Admin
2. Touren &rarr; Neuen Beitrag erstellen
3. Fülle Formular aus - s.u.
4. \[Veröffentlichen\]

## Daten

- Titel: `<YY>-<DDNN> <Kurzname>`, z.B. 25-0601 Bülach Nord
- Einsatzdatum: `DD.MM.YYYY`, z.B. 06.12.2025

## Touren

| Nr     | Kurzname                      | Beschreibung                                                       | Gemeinden                                                                                                                                                      |
|--------|-------------------------------|--------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 01     | Bülach Nord                   | Bülach Nord                                                        | Bülach (Soli, Bergli)                                                                                                                                          |
| 02     | Bülach Ost                    | Bülach Ost                                                         | Bülach (Schleufenberg, Frohalden)                                                                                                                              |
| 03     | Bülach West                   | Bülach West                                                        | Bülach (Städtli, Kasernenstr., Hinterbirch)                                                                                                                    |
| 04     | Höri, Hochfelden              | Höri, Hochfelden & Neerach                                         | Höri, Hochfelden, Neerach\* (inkl. Riedt)<br>\* nur an Tagen mit 04 Tour (max. 3 Tage), ohne erster Zeitslot                                                   |
| 05     | Bachenbülach                  | Bachenbülach                                                       | Bachenbülach, **Alternative** Kapazität für Winkel/Rüti                                                                                                        |
| 06     | Winkel/Rüti                   | Winkel/Rüti, Lufingen/Augwil & Oberembrach                         | Winkel (inkl. Rüti, Seeb), Lufingen\* (inkl. Augwil), Oberembrach\*<br>\* nur an Tagen mit 06 Tour (max. 2 Tage), nur letzter Zeitslot                         |
| ~~07~~ | ~~Wehntal~~                   | ~~Wehntal~~                                                        | ~~Rümlang, Oberglatt, Niederhasli, Dielsdorf, gesamtes Wehntal~~                                                                                               |
| 08     | Glattfelden                   | Glattfelden, Stadel & Weiach                                       | Glattfelden (inkl. Siedlungen), Stadel b. N.\* (inkl. Raat, Schüpfheim, Windlach), Weiach\*<br>\* nur an Tagen mit 08 Tour (max. 3 Tage), ohne erster Zeitslot |
| 09     | Eglisau                       | Eglisau & Rafzerfeld                                               | Eglisau, Hüntwangen\*, Wasterkingen\*, Wil\*, Rafz\*<br>\* nur an Tagen mit 09 Tour (max. 3 Tage), ohne erster Zeitslot                                        |
| 10     | Embrach                       | Embrach, Rorbas & Freienstein-Teufen                               | Embrach, Rorbas\*, Freienstein-Teufen\*<br>\* nur an Tagen mit 10 Tour (max. 3 Tage), ohne erster Zeitslot                                                     |
|        |                               |                                                                    |
| 31     | Bülach Nord, Ost              | 01 Bülach Nord<br>02 Bülach Ost                                    | s.o.                                                                                                                                                           |
| 32     | Bachenbülach, Winkel/Rüti     | 05 Bachenbülach<br>06 Winkel/Rüti, Lufingen/Augwil & Oberembrach   | s.o.                                                                                                                                                           |
| 33     | Bülach West, Höri, Hochfelden | 03 Bülach West<br>04 Höri, Hochfelden & Neerach                    | s.o.                                                                                                                                                           |
| 34     | Eglisau, Embrach              | 09 Eglisau & Rafzerfeld<br>10 Embrach, Rorbas & Freienstein-Teufen | s.o.                                                                                                                                                           |
| 35     | Glattfelden, Eglisau          | 08 Glattfelden, Stadel & Weiach<br>09 Eglisau & Rafzerfeld         | s.o.                                                                                                                                                           |
|        |                               |                                                                    |
| 21     | Rütihof 1                     | Rütihof früh                                                       |                                                                                                                                                                |
| 22     | Rütihof 2                     | Rütihof spät                                                       |                                                                                                                                                                |

## Zeiten

| Tour            | Tage    | Zeit                                            | Kapazität*  |
|-----------------|---------|-------------------------------------------------|-------------|
| Familienbesuche | Mo - Fr | 18:00 - 19:00<br>19:20 - 20:20                  | 3<br>3      |
| Familienbesuche | Sa - So | 16:40 - 17:40<br>18:00 - 19:00<br>19:20 - 20:20 | 3<br>3<br>3 |
| Rütihof früh    | Sa & So | 16:00 - 18:00                                   | 6           |
| Rütihof spät    | Sa & So | 18:20 - 20:20                                   | 6           |

\* Kapazität Bülach höher wenn alle 3 Touren (01, 02, 03)

## Gestaffelte Freischaltung

**Folgende Idee wurde verworfen.**

Wir lassen zu Beginn die Randdaten weg.
Falls nötig, weitere Daten (früher oder später) pro Anbieter öffnen.

Beispiel 6. Dez Freitag: Öffnen der Buchungen vom Mittwoch bis Sonntag.

## Kombinierte Touren

Kombinierte Touren 31 bis 34 gestalten sich schwierig mit unserem Kapazität-Management.
Wir gehen aktuell davon aus, dass sich dies durch Angebot und Nachfrage regeln lässt.

Die kombinierten Touren müssen innerhalb eines [Anbieters](./anbieter.md) angelegt werden.

Wenn die einzelnen Ortschaften (innerhalb eines Anbieters) zu unterschiedlichen Daten freigeschaltet werden,
müssen die [Feierarten](./feierarten.md) dementsprechend *Arbeitstage* definieren.
