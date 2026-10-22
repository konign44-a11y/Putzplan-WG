# Putzplan-WG

Wöchentlicher Putzplan für unsere WG in Innsbruck (Nico, Bruno, Kiki) als einzelne Webseite. Läuft auf dem Handy und lässt sich als Lesezeichen auf den iPhone-Home-Bildschirm legen.

## Funktionen

- Drei Reiter: **Küche**, **Bad**, **Müll & Gang**
- Wöchentlicher Wechsel der Zuständigkeit, automatisch aus der Kalenderwoche berechnet (Wechsel jeden Montag)
- Infobox pro Bereich mit den wichtigsten Regeln (Spüle, Ablauf in der Dusche, Mülltrennung)
- Checkliste pro Woche und Bereich, Haken werden nur auf dem jeweiligen Gerät gespeichert
- Rotationsübersicht für die nächsten Wochen
- „Ich bin“-Auswahl markiert den eigenen Reiter
- Heller und dunkler Modus je nach Geräteeinstellung

## Dateien

| Datei | Inhalt |
| --- | --- |
| `index.html` | Die komplette Seite (HTML, CSS und JavaScript in einer Datei) |
| `apple-touch-icon.png` | Icon für den iPhone-Home-Bildschirm |
| `README.md` | Diese Beschreibung |

## Online

Die Seite wird über GitHub Pages ausgeliefert (Branch `main`, Ordner `/ (root)`).

Adresse: `https://konign44-a11y.github.io/Putzplan-WG/`

## Aufs iPhone legen

1. Link in Safari öffnen.
2. Teilen-Symbol antippen (Quadrat mit Pfeil nach oben).
3. „Zum Home-Bildschirm“ wählen und bestätigen.

## Rotation

Die Startwoche ist KW 43 / 2026 (Montag, 19.10.2026):

| Woche | Küche | Bad | Müll & Gang |
| --- | --- | --- | --- |
| KW 43 | Nico | Bruno | Kiki |
| KW 44 | Bruno | Kiki | Nico |
| KW 45 | Kiki | Nico | Bruno |

Danach wiederholt sich der Dreierzyklus.

## Anpassen

Alle Einstellungen stehen im JavaScript am Ende von `index.html`:

- **Namen und Reihenfolge:** Liste `PEOPLE`
- **Startwoche:** Konstante `ANCHOR` (Montag der Startwoche, Monate beginnen bei 0)
- **Aufgaben und Infotexte:** Liste `AREAS` (pro Bereich `info` und `tasks`)

## Aktualisieren

1. Geänderte `index.html` im Repo hochladen (**Add file → Upload files**). Der Dateiname muss gleich bleiben.
2. **Commit changes** klicken.
3. Nach etwa 1 bis 2 Minuten ist die neue Version online.

## Hinweise

- Das Repo ist öffentlich, die Seite ist für jeden mit dem Link sichtbar. Sie enthält nur Vornamen und Putzaufgaben.
- Die Schriften kommen von Google Fonts. Ohne Internet greift die Seite auf Systemschriften zurück.

## Stand

- v1 ist online.
- Nächster Schritt: Aufgaben und Infotexte mit Bruno und Kiki abstimmen.
