# Schede tecniche MRC Ingegneria

Pacchetto generato il 2026-04-30 dal Gestore Schede MRC v2.

## Contenuto
- `index.html` — indice navigabile delle schede
- `schede/{id}/index.html` — pagina di destinazione di ciascuna scheda (1 totali)
- `registro.json` — snapshot dei dati sorgente (per backup e re-import)

## Pubblicazione su GitHub Pages

**ATTENZIONE — errore comune**: quando estrai questo ZIP, il sistema operativo crea una
cartella-contenitore con il nome del ZIP (es. `mrc-schede_YYYY-MM-DD/`). NON caricare
quella cartella sulla repo, altrimenti le pagine finiranno al path sbagliato e i QR
restituiranno 404.

### Procedura corretta
1. Estrai l'archivio (doppio click)
2. **Apri** la cartella estratta (entraci dentro)
3. Vai sulla tua repo GitHub: `Add file → Upload files`
4. **Seleziona i 4 elementi DENTRO la cartella** (non la cartella): `schede/`, `index.html`, `registro.json`, `README.md`
5. Trascinali nell'area di upload di GitHub
6. Scrivi un messaggio di commit e conferma
7. Dopo 1-2 minuti le pagine saranno accessibili agli URL dei QR

### Se hai caricato male
Vai sulla repo, trova la cartella-contenitore sbagliata (quella col nome del ZIP),
clicca sul nome, menu "…" in alto a destra → "Delete directory", commit. Poi rifai
l'upload seguendo la procedura corretta.

## Backup
Il file `registro.json` contiene tutti i dati sorgente. Conservalo per poter
reimportare il registro nel tool.
