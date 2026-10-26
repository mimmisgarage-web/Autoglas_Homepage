# Glaswerk NRW – Homepage

Statische Homepage für [glaswerk-nrw.de](https://glaswerk-nrw.de), gehostet über GitHub Pages.

- Inhalte liegen in `site/` (HTML und CSS, keine Abhängigkeiten).
- Jeder Push auf `main` baut und veröffentlicht die Seite automatisch (`.github/workflows/deploy.yml`).
- Die eigene Domain steht in `site/CNAME`.

## DNS bei IONOS

| Typ   | Host | Wert                     |
|-------|------|--------------------------|
| A     | @    | 185.199.108.153          |
| A     | @    | 185.199.109.153          |
| A     | @    | 185.199.110.153          |
| A     | @    | 185.199.111.153          |
| AAAA  | @    | 2606:50c0:8000::153      |
| AAAA  | @    | 2606:50c0:8001::153      |
| AAAA  | @    | 2606:50c0:8002::153      |
| AAAA  | @    | 2606:50c0:8003::153      |
| CNAME | www  | mimmisgarage-web.github.io |

Die MX-Einträge (E-Mail über IONOS) bleiben unverändert.
