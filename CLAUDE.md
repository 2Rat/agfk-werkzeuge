# Projektregeln: Werkzeuge Radverkehr Saarland (AGFK-SL)

## Kontext
- 2Rat-Arbeit (Selbständigkeit), entwickelt für die AGFK-SL.
- Keine Inhalte, Kontakte oder Dokumente aus dienstlichen Tätigkeiten verwenden oder vermischen.
- Schreibweise immer „2Rat", nie „2RAT".
- Dieses Repo ist **öffentlich** (GitHub Pages, Branch `main`): niemals API-Keys, Zugangsdaten, Zugangscodes im Klartext oder Kundendaten in Dateien oder Commits.

## Worum es geht
Vier Web-Tools für Mitarbeitende in Kommunen, die eine Radverkehrsmaßnahme umsetzen wollen:
- **Projekt-Check** (`projekt-check.html`): Wegweiser in drei Schritten (Vorhaben → Zusatzfaktoren → Ergebnis).
- **Zuständigkeiten** (`zustaendigkeiten.html`): Wer muss zustimmen oder anordnen (Straßenverkehrsbehörde, Gemeinde als Ortspolizeibehörde, Baulastträger, Land/LfS)? Abhängig von Straßenklasse, Ortslage und Maßnahme.
- **Fördermittel-Finder** (`foerdermittel-finder.html`): passende Förderung, Schwerpunkt saarländische Landesförderung (FRL-NMOB-Rad-Fuß). „Stadt und Land" läuft über NMOB, nicht als eigener Bundestopf.
- **Vergabe-Assistent** (`vergabe-assistent.html`): Unterstützung bei der Vergabe.

Zielgruppe sind Laien in der Verwaltung: einfache Sprache, klare Ergebnisse, Fachbegriffe erklären.

## Dateien in diesem Repo
`index.html`, die vier Tools oben, `so-gehts.html`, `hilfe/` (Screenshots), `impressum.html`, `datenschutz.html`, `rp-geo.js`, `rp-unfaelle.js`, `vendor/`, `agfk-logo.png`.

## Andere Repos
- `2Rat/2Rat.github.io/Werkzeuge/kunden/` enthält **veraltete** Kopien der vier Tools. Nicht dagegen arbeiten, nicht von dort übernehmen.
- Die übrigen Seiten dort (z. B. `vwv-stvo-2025.html`, `foerderrichtlinien.html`) gibt es nur dort und sie sind aktuell.
- Der Förder-Matcher (`foerderrichtlinien.html`) ist ein eigenes Tool: nicht aus dem Fördermittel-Finder verlinken.

## Bei jeder Änderung
- Stand im Fuß hochzählen (Format z. B. „Stand 10/2026 · v44" → nächste Version).
- Ändert sich die Bedienung, die Screenshots in `hilfe/` und den Text in `so-gehts.html` mitziehen.
- Vor jeder Änderung die aktuelle Datei aus diesem Repo (`main`) nehmen, nie eine alte Kopie oder einen Upload.
- Prüfen und testen, bevor etwas committet wird: Seite öffnen, alle Wege einmal durchklicken.
- Im Zweifel einmal mehr nachfragen, statt zu raten.

## Fachlich festgelegt (nicht wieder „korrigieren")
- Fahrradstraße (Z 244.1) ist per § 12 StVZustG Saarland auf die Gemeinden übertragen. Fahrradzone (Z 244.3) nicht.
- Ein nur abmarkierter Parkstreifen gehört zur Baulast der Fahrbahn (Land/Bund), nicht zur Gemeinde.

## Fachgrundlagen
Regelwerke, Musterlösungen und die Förderrichtlinie NMOB liegen im Google-Drive-Ordner „2Rat Grundlagen". Bei fachlichen Fragen zuerst „00 Inhalt und Hinweise" lesen, dann die passende Quelle öffnen und mit Fundstelle zitieren. Rechtsstand und Förderbedingungen vor Änderungen am Tool dort gegenprüfen.
