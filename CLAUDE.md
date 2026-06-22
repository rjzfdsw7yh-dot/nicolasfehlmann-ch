# Projekt: Persönliche Webseite Nicolas Fehlmann (Kanuslalom)

Statische Einseiten-Webseite (One-Pager) für den Schweizer Kanuslalom-Athleten
Nicolas Fehlmann. Keine Build-Tools, kein Framework – reines HTML/CSS in einer
einzigen Datei. Ziel: einfach pflegbar, schnell ladend, später auf GitHub Pages
mit eigener Domain gehostet.

## Dateien
- `index.html` – die komplette Seite (HTML + CSS im <style>-Block, kein externes CSS)
- `images/` – alle Fotos, fürs Web optimiert (object-fit: cover wird genutzt)

## Aufbau der Seite (Abschnitte / "Tore")
1. Hero – Name, zwei Weltranglisten (K1 + Kajak-Cross), Stats, Action-Foto
2. Über mich (#about) – Bio in Ich-Perspektive + Stammdaten + Porträt
3. Vollbild-Band – Ender-Foto mit Motto "Trust the Process."
4. Erfolge (#achievements) – Resultattabelle + Podestfoto
5. News (#news) – aktuell 2 Einträge (teils Platzhalter)
6. Kontakt (#contact) – Instagram-Link, E-Mail (Platzhalter), Infokarte

## Design-System (CSS-Variablen in :root)
- Basis: tiefes Petrol-Blau (--deep #06222B, --deep2, --deep3)
- Akzent: Schweizer Rot (--swiss-red #D52B1E)
- Hell: --foam (#EEF6F5)
- Slalom-Tore: grün (--gate-green, "up"/Upstream) und rot (--gate-red, "down"/Downstream)
- Schriften: "Archivo Expanded" (Headlines), "Archivo" (Text) via Google Fonts
- Stil: dynamisch/sportlich, quadratische Slalom-Tornummern als Abschnitts-Marker

## Noch offen / Platzhalter
- News-Einträge enthalten teils Platzhaltertext
- Kontakt-E-Mail ist Platzhalter (platzhalter@email.ch)

## Konventionen
- Texte auf Deutsch, Schweizer Rechtschreibung (ss statt ß)
- Bio in Ich-Perspektive
- Beim Hinzufügen von Fotos: in `images/` ablegen, vorher fürs Web verkleinern
  (max ~1600px Breite, JPEG-Qualität ~85) und per <img> mit object-fit:cover einbinden
- Weltranglisten-Zahlen sind manuell gepflegt (Stand-Vermerk im Hero aktualisieren)
