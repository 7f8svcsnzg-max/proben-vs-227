PLANPROBEN – Premium Dark Hochkant-Update

Enthalten: index.html, manifest.webmanifest, sw.js, README.txt und App-Symbole.

Änderungen:
- Smartphone-Hochkantansicht optimiert; kein Drehen erforderlich.
- Kopfbereich, „Neue Probe hinzufügen“, Excel-Import und Filterleiste bleiben beim Scrollen oben sichtbar.
- Mengenangabe als freies Textfeld; längere Angaben umbrechen und werden vollständig angezeigt.
- Excel-Import gemäß der tatsächlich bereitgestellten Datei: Spalte A = Produkt, Spalte B = Mengenangabe, Spalte C = Monatszahlen 1–12.
- Pro Produkt wird je zugeordnetem Monat ein eigener offener Eintrag angelegt; Monats- und Quartalszuordnung bleiben erhalten.
- Löschsymbol ist ein Papierkorb.
- Verschieben, Duplizieren, Bearbeiten, Abschließen und JSON-Sicherung bleiben enthalten.
- Kein Kalender-/Einzeldatum; Planung erfolgt weiterhin über Monate und Quartale.

Wichtig:
- Der lokale Speicher-Schlüssel proben-vs-227-v2 und die bestehende App-Adresse werden nicht verändert.
- Bestehende Datensätze bleiben im lokalen Browser-Speicher; vor dem Upload trotzdem eine JSON-Sicherung exportieren.
- Excel-Lesehilfe wird beim Import über CDN geladen; Internetverbindung erforderlich.

Update:
Alle sechs Dateien im Hauptverzeichnis des bestehenden GitHub-Repositories hochladen/ersetzen und auf main committen. Netlify veröffentlicht danach automatisch.
