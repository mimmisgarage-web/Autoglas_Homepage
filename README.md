# Glaswerk NRW – Homepage

Website für [glaswerk-nrw.de](https://glaswerk-nrw.de), gehostet über GitHub Pages.

- Inhalte liegen in `site/` (statisches HTML/CSS, keine Abhängigkeiten, keine externen Dienste).
- **Verbindliche Grundlage der finalen Homepage ist der Mobile-Prototyp „Wireframe V2“** (Entscheidung D026, 26.10.2026) aus dem Projektordner (OneDrive, `Autoglas Webseite/wireframes/`), bereinigt um Prototyp-Steuerung, Platzhalter und Google Fonts.
- Jeder Push auf `main` veröffentlicht die Seite automatisch (`.github/workflows/deploy.yml`).
- Die eigene Domain ist in den Pages-Einstellungen hinterlegt (`site/CNAME` dient als Merkhilfe).

## Offene Punkte vor dem offiziellen Start

- Impressum: Inhaber/Rechtsform, USt-IdNr., ggf. Handwerksrolle
- Datenschutzerklärung vervollständigen und prüfen lassen
- Erreichbarkeit/Öffnungszeiten, Aussage zur Versicherungsabwicklung, echte Kundenbewertungen
- Logo als Vektordatei (aktuell aus Foto ausgeschnitten), Schrift „Barlow Semi Condensed“ selbst hosten

## DNS bei IONOS

| Typ   | Host | Wert |
|-------|------|------|
| A     | @    | 185.199.108.153 / .109 / .110 / .111 |
| AAAA  | @    | 2606:50c0:8000::153 / 8001 / 8002 / 8003 |
| CNAME | www  | mimmisgarage-web.github.io |

Die E-Mail-Einträge (MX, SPF, DKIM, DMARC) bleiben bei IONOS unverändert.
