# Journal Logic - Version 0.2

Dieses Dokument definiert die Meta-Logik fuer das Befuellen, Pruefen und Bewerten des Journals.
Es ergaenzt das Template (JOURNAL_TEMPLATE.md) um Regeln, Automatisierungen und Validierungen.

---

## 1. Automatische Befuellung (approx.90%)
- Datum - Systemzeit.
- Bias-Analyse - Daten aus Workflows & Pipelines:
  - News/Earnings aus Workflow (Quelle & Klassifikation in Par_9 definiert).
  - Statistiken aus Datenpipeline (ON, PreMarket, Skew, Gap).
  - Hinweis: tagsueber teils unvollstaendig, finalisiert im Tagesabschluss.
- Trade-Ergebnisse - aus Uploads (ATAS, Tracert).
- CRV - berechnet aus Entry, Stop, TP.
- Setup-Zuordnung - automatisiert anhand Engine-Labels.
- Management - soweit erkennbar aus Verlauf (Stop-Out, Trailing).
