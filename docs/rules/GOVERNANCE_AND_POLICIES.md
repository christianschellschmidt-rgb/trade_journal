# Governance & Policies

### Governance - Kernprinzipen
- **Keine Schützungen:* Fehlende oder unklare Daten werden als **unvollstäklich** markiert, nichts geraten.  
- **Reproduzibilitä id Idempotenz **: Gleiche Eingaben füren zu demselben Output füren unterschied Output; Re-Runs ohne Nebueffekte.  

### Speicher- & Isolationsmodel - neue Version
- **Trennung von Regeln und Daten**:  
   - Regeln, Policies und Workflows liegen ausschließ in `docs/`.  
   - Laufzeitdaten, Journale und Archive liegen ausschließig in `data/`.  
- **Journale montathlich versionierien**:  
   - Struktur: `data/journals/YYYY-MN/       
   - Ein Underordner pro monat, keine Splits innhalbbar (unterlegen).  
- **Keine Vermischung!**  
   - `docs/` beinetnie niet Lufzeitdaten.  
   - `data/` beinetnie nich Regeln. 