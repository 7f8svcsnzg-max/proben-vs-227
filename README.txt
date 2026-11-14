PLANPROBEN – Excel-Import-Update

Enthalten: index.html, manifest.webmanifest, sw.js und App-Symbole.

Neu:
- Kleine, dezente Schaltfläche „Excel importieren“ unter „Neue Probe hinzufügen“.
- Import von .xlsx, .xls und .csv.
- Erwartetes Tabellenformat: Spalte A = Produktname, Spalte B = Anzahl, Spalte C = Monatszahlen 1 bis 12.
- Pro angegebener Anzahl wird je ausgewähltem Monat ein eigener offener Probeneintrag erstellt.
- Monat und Kalenderquartal werden automatisch zugeordnet.
- Vor dem Import erscheint eine Zusammenfassung. Bereits vorhandene gleiche Produkt-/Monats-Einträge werden übersprungen.
- Bestehende manuelle Eingabe, Sortierung, Kopieren, Bearbeiten, Löschen und JSON-Sicherung bleiben erhalten.

Hinweise:
- Die Excel-Lesehilfe wird beim Import aus einem CDN geladen; dafür ist eine Internetverbindung nötig.
- Die Daten bleiben lokal im Browser. Der Speicher-Schlüssel proben-vs-227-v2 wurde beibehalten.
- Vor dem Update bitte eine JSON-Sicherung exportieren.
- Die Excel-Datei muss Produkt, Anzahl und Monatszahlen in den ersten drei Spalten enthalten.

Update:
Die sechs Dateien im Hauptverzeichnis des bestehenden GitHub-Repositories hochladen/ersetzen und auf main committen. Netlify veröffentlicht danach automatisch.
