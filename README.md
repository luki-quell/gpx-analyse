# GPX-Analyse

Wandertouren und GPX-Tracks analysieren – 100 % lokal im Browser. Kein Backend, keine Uploads, kein Tracking.

## Funktionen

- GPX-Dateien per Drag & Drop analysieren: Distanz, Auf-/Abstieg, Tempo, Dauer, Bewegungszeit
- Wanderzeit nach Schweizer Formel (4,2 km/h · 400 m/h Aufstieg · 800 m/h Abstieg)
- Interaktives Höhenprofil mit Live-Tooltip (km, Höhe, Steigung, Uhrzeit)
- Echte Karte, umschaltbar zwischen OpenTopoMap, OpenStreetMap und swisstopo
- Hover im Höhenprofil zeigt die Position live auf der Karte
- Klick in die Karte: WGS84- und LV95-Koordinaten (Schweizer Landeskoordinaten)
- Abschnitts-Tabelle bei Mehrfach-Segmenten, Wegpunkt-Übersicht
- CSV-Export aller Trackpunkte
- Beispiel-Tour zum sofortigen Ausprobieren ohne eigene Datei

## GitHub Pages aktivieren

1. Repo öffnen: Settings → Pages
2. Source: Deploy from a branch
3. Branch: main, Ordner: / (root) → Save

Danach ist die App unter https://luki-quell.github.io/gpx-analyse/ erreichbar.

## Datenschutz

Alle Daten bleiben im Browser. Die einzige Netzwerkverbindung ist das Laden der Kartenkacheln vom gewählten Anbieter – die GPX-Datei verlässt das Gerät nie.
