# BLE GPS Provider – XC Tracer

Android-App aus einem HTL-Schulprojekt: Sie empfängt die GPS-Position eines **XC Tracer Mini IV GPS** per Bluetooth,
zeigt sie auf einer Karte mit Navigation und kann sie anderen Apps (z. B. Google Maps) als Standort bereitstellen.
Neu in 1.1: farbiges Gelände und Lufträume (Sperr-, Gefahren-, Kontrollzonen) mit Warnung bei Annäherung.
Ohne XC Tracer funktioniert die Karte mit dem GPS des Handys.

## Download

**[⬇ BLE-GPS-XC-Tracer.apk herunterladen](https://github.com/NickPD09/ble-gps-xc-tracer/releases/latest/download/BLE-GPS-XC-Tracer.apk)**
(Version 1.1, ca. 27 MB, Android 12 oder neuer)

## Installation

1. Den Link oben **am Handy** öffnen und die Datei herunterladen.
2. Die Datei antippen. Beim ersten Mal fragt Android, ob der Browser „unbekannte Apps installieren“ darf → **erlauben**.
3. Google Play Protect warnt eventuell, weil die App nicht aus dem Play Store kommt →
   „Weitere Details“ → **„Trotzdem installieren“**.
4. App öffnen. Ein Assistent führt durch Berechtigungen, Verbindung und GPS-Test.

Ein Update wird einfach über die alte Version installiert; die Einstellungen bleiben erhalten.

## Gut zu wissen

- **Testversion** eines Schulprojekts: im Android-Emulator (Android 15) geprüft, mit dem echten XC Tracer noch nicht.
- Die Navigation ist Straßen-, Rad- und Fußwegrouting auf Basis von OpenStreetMap. **Nicht für die Navigation in
  der Luft** (Gleitschirm, Segelflug) geeignet.
- **Lufträume nur zur Orientierung:** Daten von openAIP (CC BY-NC 4.0) ohne NOTAMs und Aktivierungszeiten – kein
  Ersatz für AIP, NOTAM oder ICAO-Karte. Lufträume und Warnungen funktionieren auch offline.
- Karte, Ortssuche und Routen brauchen Internet. Datenquellen: Karte © OpenFreeMap, © OpenMapTiles,
  © OpenStreetMap-Mitwirkende · Suche: Nominatim · Routen: OSRM-Server der FOSSGIS.
- Die App sammelt keine Daten und speichert keine Standortverläufe (außer man schaltet im Expertenbereich
  das Rohdaten-Log ein).
