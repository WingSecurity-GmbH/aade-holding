# AADE Holding AG - Firmen-Informations-Homepage

Moderne, responsive Firmen-Informations-Homepage ("Simple aber schön") für die **AADE Holding AG** mit allen offiziellen Daten des Handelsregisters des Kantons Aargau (UID: CHE-164.799.808).

## 🏢 Unternehmensdaten auf einen Blick

- **Firma**: AADE Holding AG
- **Rechtsform**: Aktiengesellschaft (AG)
- **UID**: CHE-164.799.808
- **CH-ID**: CH-400.3.456.629-6
- **EHRA-ID**: 1689412
- **Sitz & Domizil**: Winterhaldenweg 6a, 4852 Rothrist, Schweiz
- **Kanton**: Aargau (AG)
- **Zuständiges Handelsregisteramt**: Handelsregisteramt des Kantons Aargau (Bahnhofplatz 3c, 5000 Aarau)
- **Tagebuch**: Nr. 5257 vom 14.04.2025
- **SHAB-Publikation**: 17.04.2025 (Meldungs-Nr. 1006312153)
- **Statutendatum**: 31.03.2025
- **Aktienkapital**: CHF 100'000.00 (Liberierung: CHF 50'000.00, 1'000 Namenaktien zu CHF 100.00)
- **Verwaltungsrat**: Silvio Daniele Aresti (von Rothrist, in Rothrist, Einzelunterschrift)
- **Revisionsstelle**: Verzicht auf Revision (Opting-out)
- **Offizieller Auszug**: https://ag.chregister.ch/cr-portal/auszug/auszug.xhtml?uid=CHE-164.799.808#

---

## 🚀 Schnelle Inbetriebnahme

### Option 1: Direkt im Browser öffnen
Keine Installation oder Node.js erforderlich. Die Datei `index.html` kann direkt mit jedem modernen Webbrowser (Chrome, Edge, Firefox, Safari) geöffnet werden:
- Windows Explorer: Doppelklick auf `index.html`
- WSL / Linux: `explorer.exe index.html`

### Option 2: Lokaler Webserver (empfohlen für JSON-Export & vollständige Leaflet-Funktionalität)
In diesem Verzeichnis:
```bash
# Mit Python:
python3 -m http.server 8080

# Oder mit Node.js:
npx serve .
```
Anschliessend im Browser öffnen: **http://localhost:8080**

---

## ✨ Enthaltene Features

- **Modernes Swiss-Corporate Design**: Hochwertige Typografie (*Plus Jakarta Sans*), Schweizer Wappen-/Rot-Akzente, saubere Karten und klare Hierarchien.
- **Dark & Light Mode**: Nahtloser Theme-Wechsel mit automatischer Speicherung (`localStorage`).
- **1-Klick Clipboard-Funktion**: UID, CH-ID und Adresse können mit einem Klick kopiert werden (inklusive Toast-Meldung).
- **Interaktive Karte**: OpenStreetMap & Leaflet Integration mit exakter Position des Firmendomizils (*Winterhaldenweg 6a, 4852 Rothrist*) und direkter Google-Maps-Routenplanung.
- **JSON Datenblatt-Export**: Direkter Download aller Stammdaten als strukturierte `company-data.json`.
- **Druck- & PDF-Optimierung**: Integriertes Print-Stylesheet (`@media print`), das beim Ausdrucken (Ctrl+P) eine saubere amtliche Auszugsseite ohne Navigationsleisten formatiert.
- **SEO & Schema.org**: Strukturierte Metadaten (`Corporation`, `Organization`) für Suchmaschinen und Social Media Vorschauen.
- **Direktlinks zu Registern**: Schneller Absprung zum Aargauer Handelsregisterportal (`ag.chregister.ch`), Zefix und SHAB.