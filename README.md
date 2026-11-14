# GPX-Analyse

Wandertouren und GPX-Tracks analysieren, planen und navigieren – 100 % lokal im Browser. Kein Backend, keine Uploads, kein Tracking.

## Funktionen

- GPX-Dateien per Drag & Drop analysieren: Distanz, Auf-/Abstieg, Tempo, Dauer, Bewegungszeit
- **Navigation:** Track-Führung per GPS – Live-Position auf der Karte, Richtungsansagen aus der Track-Geometrie (optional per Sprachausgabe), Abseits-der-Route-Warnung mit Rückführungs-Linie, Restdistanz/-höhenmeter und Ankunftszeit
- **Live-Tracking:** Tour per GPS direkt im Browser aufzeichnen – Live-Karte, Live-Profil, Live-Statistik, Pause-Funktion
- **Wetter interaktiv auf der Karte:** Vorhersage-Marker mit Temperatur, Wetter-Symbol und ungefährer Ankunftszeit (Open-Meteo, ohne API-Key)
- Wanderzeit nach Schweizer Formel (4,2 km/h · 400 m/h Aufstieg · 800 m/h Abstieg)
- Echte Karte, umschaltbar zwischen OpenTopoMap, OpenStreetMap und swisstopo
- Klick in die Karte: WGS84- und LV95-Koordinaten (Schweizer Landeskoordinaten)
- Export als GPX und CSV, Abschnitts-Tabelle, Wegpunkte, Beispiel-Tour
- Screen Wake Lock während der Navigation (Display bleibt an)

## GitHub Pages

Settings → Pages → Source: Deploy from a branch → main / (root) → Save.
Danach: https://luki-quell.github.io/gpx-analyse/

## Datenschutz

Alle Daten bleiben im Browser. Netzwerkzugriffe minimal und transparent:
- Kartenkacheln vom gewählten Anbieter (OpenTopoMap/OSM/swisstopo)
- Wetterdaten von Open-Meteo.com (nur Koordinaten von bis zu 8 Punkten, keine Track-Daten)

GPX-Dateien, GPS-Aufzeichnung und Navigation laufen ausschliesslich auf deinem Gerät.
