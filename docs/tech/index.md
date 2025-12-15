# Technisches

## Architektur

- Santa: Selbst programmiert, es dient dazu alle folgenden Tools miteinander zu verknüpfen und die individuellen Funktionalitäten zu gewährleisten.
- WooCommerce: Open Source Shop-System für WP, alles was mit Bestellungen und Kunden zu tun hat, inklusive Kunden-Dashboard. Die letzte Seite bei der Buchung vom Samichlaus gehören zu WooCommerce.
- JetAppointments: Komplettes Terminbuchungssystem, welches dazu dient den Samichlaus zu buchen.
- JetEngine: Custom Post Types Erstellung und Custom Fields 5th Generation Programming Tool. Zur Definition eigener Entitäten, Feldern und Abfragen (Queries).
- JetFormBuilder: Komplexe und dynamische Formulare (alle Frontend-Formulare sind mit diesem Tool erstellt worden).
  - Diese sind komplex und sollten, wenn immer möglich, nicht angepasst oder verändert werden. Sie sind vor allem zusammen mit Custom Code von Santa am Funktionieren.
- JetFilter: Alle möglichen Filter auf der App sind von diesem Tool.

## Änderungen

- Santa: Anpassungen an den Tools haben unweigerlich Konsequenzen auf das Plugin und in dem Fall auch auf wichtige Funktionen der Applikation. Vorsicht ist also geboten.
  - Elementor Templates: Dort sind individuelle Programme enthalten (ShortCodes und Custom Fields), welche selbst programmiert wurden und bei einer Änderung oder Löschung nicht mehr so funktionieren wie sie sollten.
- Bei Third-Party-Plugins wie Elementor, WooCommerce und Crocoblock (Jet... Plugins) kann nicht eingegriffen werden.
  - Bei WooCommerce sind kleine Anpassungen möglich, aber auch dort sollte man keine Änderungen machen, da man sonst das Plugin nicht mehr updates kann.

## Daten

- Doppelte Felder: Viele Seiten und Funktionen übernehmen o.g. Tools. Deswegen kommen Datum, Telefon-Nr. und andere Felder mehrmals vor.
