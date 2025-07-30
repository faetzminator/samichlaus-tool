# Einrichtung Touren

## Neu erfassen

1. Besuche WordPress Admin
2. Touren &rarr; Neuen Beitrag erstellen
3. Fülle Formular aus - s.u.
4. \[Veröffentlichen\]

## Daten

| Titel                  | Einsatzdatum |
|------------------------|--------------|
| `<YY>-<DDNN> - <Name>` | `DD.MM.YYYY` |
| 25-0622 - Rütihof spät | 06.12.2025   |
| 26-0701 - Bülach Nord  | 07.12.2026   |

## Touren

| Nr     | Beschreibung                                                       | Gemeinden                                                                                                                                                    |
|--------|--------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 01     | Bülach Nord                                                        | Bülach (Soli, Bergli)                                                                                                                                        |
| 02     | Bülach Ost                                                         | Bülach (Schleufenberg, Frohalden)                                                                                                                            |
| 03     | Bülach West                                                        | Bülach (Städtli, Kasernenstr., Hinterbirch)                                                                                                                  |
| 04     | Höri, Hochfelden & Neerach                                         | Höri, Hochfelden, Neerach* (inkl. Riedt)<br>\* nur an Tagen mit 04 Tour (max. 3 Tage), ohne erster Zeitslot                                                  |
| 05     | Bachenbülach                                                       | Bachenbülach, **Alt.** für Winkel (zweite Hälfte?)                                                                                                           |
| 06     | Winkel, Lufingen & Oberembrach                                     | Winkel (inkl. Rüti, Seeb), Lufingen* (inkl. Augwil), Oberembrach*<br>\* nur an Tagen mit 06 Tour (max. 2 Tage), nur letzter Zeitslot                         |
| ~~07~~ | ~~Wehntal~~                                                        | ~~Rümlang, Oberglatt, Niederhasli, Dielsdorf, gesamtes Wehntal~~                                                                                             |
| 08     | Glattfelden, Stadel & Weiach                                       | Glattfelden (inkl. Siedlungen), Stadel b. N.* (inkl. Raat, Schüpfheim, Windlach), Weiach*<br>\* nur an Tagen mit 08 Tour (max. 3 Tage), ohne erster Zeitslot |
| 09     | Eglisau & Rafzerfeld                                               | Eglisau, Hüntwangen*, Wasterkingen*, Wil*, Rafz*<br>\* nur an Tagen mit 09 Tour (max. 3 Tage), ohne erster Zeitslot                                          |
| 10     | Embrach, Rorbas & Freienstein-Teufen                               | Embrach, Rorbas*, Freienstein-Teufen*<br>\* nur an Tagen mit 10 Tour (max. 3 Tage), ohne erster Zeitslot                                                     |
|        |                                                                    |                                                                                                                                                              |
| 31     | 01 Bülach Nord<br>02 Bülach Ost                                    | s.o.                                                                                                                                                         |
| 32     | 05 Bachenbülach<br>06 Winkel, Lufingen & Oberembrach               | s.o.                                                                                                                                                         |
| 33     | 03 Bülach West<br>04 Höri, Hochfelden & Neerach                    | s.o.                                                                                                                                                         |
| 34     | 09 Eglisau & Rafzerfeld<br>10 Embrach, Rorbas & Freienstein-Teufen | s.o.                                                                                                                                                         |
| 35     | 08 Glattfelden, Stadel & Weiach<br>09 Eglisau & Rafzerfeld         | s.o.                                                                                                                                                         |
|        |                                                                    |                                                                                                                                                              |
| 21     | Rütihof früh                                                       |                                                                                                                                                              |
| 22     | Rütihof spät                                                       |                                                                                                                                                              |

## Zeiten

| Tour            | Tage        | Zeit                                            | Kapazität*  |
|-----------------|-------------|-------------------------------------------------|-------------|
| Familienbesuche | Mo - Fr     | 18:00 - 19:00<br>19:20 - 20:20                  | 3<br>3      |
| Familienbesuche | Sa - So     | 16:40 - 17:40<br>18:00 - 19:00<br>19:20 - 20:20 | 3<br>3<br>3 |
| Rütihof früh    | Sa &amp; So | 16:00 - 18:00                                   | 6           |
| Rütihof spät    | Sa &amp; So | 18:20 - 20:20                                   | 6           |

&ast; Kapazität Bülach natürlich höher wenn 3 Touren (01, 02, 03)

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
