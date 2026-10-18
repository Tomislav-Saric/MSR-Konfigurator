# MSR Konfigurator – Web-App v0.1

Erster funktionsfähiger React/Vite-Prototyp für die Konfiguration von RLT-Anlagen.

## Start

```bash
npm install
npm run dev
```

## Veröffentlichung über GitHub Pages

1. Dateien in ein neues GitHub-Repository hochladen.
2. `npm install` und `npm run build` ausführen.
3. Für GitHub Pages unter einem Repository-Unterpfad die Vite-Option `base` passend konfigurieren (z. B. `/msr-konfigurator/`).
4. Den Inhalt von `dist/` per GitHub Actions oder anderem Pages-Deployment veröffentlichen.

## Enthalten
- Projekt- und Anlagenkennzeichen
- Geführte Ja/Nein-Auswahl von RLT-Baugruppen
- Beispielhafte Datenpunktgenerierung (DI/DO/AI/AO)
- Statuspflege je Datenpunkt
- CSV-Export (in Excel importierbar)
- Lokale Speicherung im Browser

## Noch nicht implementiert
Herstellerdatenbank, Plausibilitätsregeln, LV-Excel-Import, Aufmaß, Fotos, Historie, PDF-Export, Benutzerverwaltung und echte Offline-Synchronisierung.

**Hinweis:** Datenpunkte sind illustrative Standardvorschläge und müssen vor einer technischen Nutzung projektspezifisch geprüft werden. Browserdaten sind kein Ersatz für eine zentrale Datenbank oder Sicherung.
