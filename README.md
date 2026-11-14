# GPX-Analyse

Wandertouren und GPX-Tracks analysieren – 100 % lokal im Browser. Kein Backend, keine Uploads, kein Tracking.

## Funktionen

- GPX-Dateien per Drag & Drop analysieren: Distanz, Auf-/Abstieg, Tempo, Dauer, Bewegungszeit
- **Live-Tracking:** Tour per GPS direkt im Browser aufzeichnen – Live-Karte, Live-Profil, Live-Statistik, Pause-Funktion
- **Wetter entlang der Strecke:** Vorhersage für bis zu 8 Punkte der Route (Open-Meteo, ohne API-Key), Datum + Uhrzeit wählbar
- Wanderzeit nach Schweizer Formel (4,2 km/h · 400 m/h Aufstieg · 800 m/h Abstieg)
- Interaktives Höhenprofil mit Live-Tooltip (km, Höhe, Steigung, Uhrzeit)
- Echte Karte, umschaltbar zwischen OpenTopoMap, OpenStreetMap und swisstopo
- Hover im Höhenprofil zeigt die Position live auf der Karte
- Klick in die Karte: WGS84- und LV95-Koordinaten (Schweizer Landeskoordinaten)
- Export als GPX und CSV (auch aufgezeichnete Live-Touren)
- Abschnitts-Tabelle bei Mehrfach-Segmenten, Wegpunkt-Übersicht, Beispiel-Tour

## GitHub Pages aktivieren

1. Repo öffnen: Settings → Pages
2. Source: Deploy from a branch
3. Branch: main, Ordner: / (root) → Save

Danach ist die App unter https://luki-quell.github.io/gpx-analyse/ erreichbar.

## Datenschutz

Alle Daten bleiben im Browser. Netzwerkzugriffe sind minimal und transparent:
- Kartenkacheln vom gewählten Anbieter (OpenTopoMap/OSM/swisstopo)
- Wetterdaten von Open-Meteo.com beim Klick auf "Wetter abrufen" (nur Koordinaten, keine Track-Daten)

Die GPX-Datei und die GPS-Aufzeichnung verlassen das Gerät nie.
