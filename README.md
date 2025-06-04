# Geschichtenklang Weberstein

Dieses Repository enthaelt den statischen Quellcode fuer die Kurzgeschichten-Sammlung **„Forschergeister“**.

Oeffne `index.html` in einem modernen Browser, um die Uebersicht der Geschichten als Kacheln zu sehen. Jede Kachel fuehrt zu `stories.html` mit der jeweiligen Geschichte. Dort findest du auch den Admin‑Bereich. Klicke auf **Nicht druecken** und gib das Passwort `geheim` ein.

Im Dashboard kannst du:

- Seitentitel, Haupt- und Unterueberschrift anpassen
- Fuer jede Geschichte Text und Sichtbarkeit aendern
- Reihenfolge, Textausrichtung und Bildposition bestimmen
- Ein Bild hochladen (wird lokal als Data-URL gespeichert)
- Beim Hochladen wird die Bildausrichtung erkannt und automatisch gesetzt
- Texte lassen sich im CMS fett, kursiv oder unterstrichen formatieren
- Die komplette Konfiguration als `json` exportieren

- Uebersichtsseite zeigt alle Geschichten in Kacheln
- Pro Kachel lassen sich Titel und Kurzbeschreibung bearbeiten und formatieren
- Ein "Zurueck zur Uebersicht"-Button fuehrt von jeder Geschichte zum Grid
- Zeilenumbrueche in den Kacheltexten bleiben erhalten
- Aktuell hochgeladene Bilder werden im CMS angezeigt und lassen sich skalieren
- Bilder behalten ihr Seitenverhaeltnis

Saemtliche Aenderungen werden im `localStorage` deines Browsers gesichert.
