# Webseite Nicolas Fehlmann

Persönliche Webseite (Kanuslalom). Statischer One-Pager aus `index.html` + `images/`.

## Lokal ansehen
Doppelklick auf `index.html` öffnet die Seite im Browser. Für komfortables
Arbeiten in VS Code empfiehlt sich die Erweiterung **Live Server** (Live-Vorschau
mit automatischem Neuladen beim Speichern).

## In VS Code weiterbauen
1. VS Code installieren: https://code.visualstudio.com
2. Ordner öffnen: Datei → Ordner öffnen → diesen Projektordner wählen
3. Empfohlene Erweiterungen (Extensions, Strg/Cmd+Shift+X):
   - **Live Server** (Vorschau)
   - **Claude Code** (offizielle Anthropic-Erweiterung, für KI-Unterstützung)

## Mit Claude Code arbeiten
- Auf das Spark-Symbol in der Seitenleiste klicken, im Browser anmelden.
- Im Chat-Feld einfach in normaler Sprache beschreiben, was geändert werden soll,
  z.B.: "Füge im News-Bereich einen neuen Eintrag von heute hinzu" oder
  "Ändere meine Weltrangliste K1 auf 88 und den Stand auf Juli 2026".
- Tipp: "Plan-Modus" für Einsteiger – Claude zeigt erst einen Plan, du bestätigst.
- Dateien mit @ erwähnen, z.B. @index.html

Hinweis: Claude Code benötigt ein kostenpflichtiges Claude-Abo (Pro oder höher).
VS Code, Live Server und das Hosting (GitHub Pages) sind kostenlos.

## Später live schalten (GitHub Pages, kostenlos, eigene Domain)
Kurzfassung – Details macht Claude Code gern Schritt für Schritt mit dir:
1. Kostenloses Konto auf https://github.com anlegen
2. Neues Repository erstellen, die Projektdateien hochladen
3. Settings → Pages → Branch auf "main" stellen → Seite wird veröffentlicht
4. Eigene Domain unter Settings → Pages → "Custom domain" eintragen und beim
   Domain-Anbieter die DNS-Einträge setzen
