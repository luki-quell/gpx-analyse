# GPX-Analyse

Wandertouren und GPX-Tracks analysieren – 100 % lokal im Browser. Kein Backend, keine Uploads, kein Tracking.

## Funktionen

- GPX-Dateien per Drag & Drop analysieren: Distanz, Auf-/Abstieg, Tempo, Dauer, Bewegungszeit
- **Live-Tracking:** Tour per GPS direkt im Browser aufzeichnen – Live-Karte, Live-Profil, Live-Statistik, Pause-Funktion
- **Wetter interaktiv auf der Karte:** Vorhersage-Marker mit Temperatur, Wetter-Symbol und ungefährer Ankunftszeit an bis zu 8 Punkten der Route (Open-Meteo, ohne API-Key)
- Ankunftszeiten: aus den Track-Zeitstempeln oder simuliert ab wählbarer Startzeit (Schweizer Wanderformel: 4,2 km/h · 400 m/h Aufstieg · 800 m/h Abstieg)
- Echte Karte, umschaltbar zwischen OpenTopoMap, OpenStreetMap und swisstopo; Marker folgen beim Ziehen/Zoomen
- Klick in die Karte: WGS84- und LV95-Koordinaten (Schweizer Landeskoordinaten)
- Export als GPX und CSV (auch aufgezeichnete Live-Touren)
- Abschnitts-Tabelle, Wegpunkt-Übersicht, Beispiel-Tour

## GitHub Pages

Settings → Pages → Source: Deploy from a branch → main / (root) → Save.
Danach: https://luki-quell.github.io/gpx-analyse/

## Datenschutz

Alle Daten bleiben im Browser. Netzwerkzugriffe minimal und transparent:
- Kartenkacheln vom gewählten Anbieter (OpenTopoMap/OSM/swisstopo)
- Wetterdaten von Open-Meteo.com beim Klick auf "Wetter abrufen" (nur Koordinaten von bis zu 8 Punkten, keine Track-Daten)

Die GPX-Datei und die GPS-Aufzeichnung verlassen das Gerät nie.
