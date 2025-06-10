# 21:9 Bildzuschnitt Tool

Dieses Repository enthält eine einzelne HTML-Datei (`zuschnitt-openai.html`), die ein simples Werkzeug zum Zuschneiden von Bildern im 21:9-Format bereitstellt. Das Tool läuft komplett im Browser und benötigt keine zusätzlichen Abhängigkeiten.

## Funktionen

- **Bild laden:** Über die Schaltfläche „Bild laden“ können lokale Dateien ausgewählt werden. Alternativ lassen sich Bilder auch per Drag & Drop oder aus der Zwischenablage einfügen.
- **Positionieren & Zoomen:** Nach dem Laden kann das Bild innerhalb des 21:9-Containers verschoben und gezoomt werden, um den gewünschten Ausschnitt festzulegen.
- **Speichern:** Der gewählte Ausschnitt wird als JPEG heruntergeladen.

## Verwendung

1. Klone dieses Repository oder lade die Datei `zuschnitt-openai.html` herunter.
2. Öffne die HTML-Datei in einem modernen Browser.
3. Klicke auf **Bild laden**, wähle ein Bild aus (oder ziehe es in den markierten Bereich).
4. Bewege das Bild mit der Maus und passe den Zoom an, bis der gewünschte 21:9-Ausschnitt korrekt sitzt.
5. Klicke auf **Speichern**, um das Ergebnis als JPEG zu speichern.

## Hinweise

- Das Tool arbeitet vollständig clientseitig. Es werden keine Daten an einen Server übertragen.
- Die minimal erforderliche Zoomstufe wird automatisch ermittelt, sodass das gesamte 21:9-Verhältnis ausgefüllt ist.

