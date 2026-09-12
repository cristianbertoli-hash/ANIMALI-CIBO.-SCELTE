# GitHub-first audit — Animali, cibo e scelte — 2026-09-12

## Regola di conservazione
Nessuna versione/documento storico viene cancellato. Ogni recupero o sviluppo usa un branch separato.

## Stato repository
Branch live verificati:
- `main`
- `ops/global-repository-governance-20260912`
- `ops/github-first-consolidation-20260912`

## Materiale presente su `main`
Sono presenti e versionati:
- `docs/BIBLIOGRAFIA_MASTER_2026.md`
- `docs/SCHEDA_MADRE_PROGETTO.md`
- checkpoint globali/manuale/V2
- `docs/COMANDO_RIPRESA_PROGETTO.md`
- `docs/PDF_MASTER_V0.2.md`
- specifiche immagini/formato
- storyboard
- piani e specifiche di progetto
- sito web (`index.html`, CSS, JS)
- test del contenuto sito.

## Output binari
- GitHub Releases: nessuna Release presente al momento dell'audit.
- Nel tree verificato non sono presenti i file PDF/DOCX finali come binari, nonostante i checkpoint ne documentino la produzione.

## Azione di recupero
I PDF/DOCX presenti sui backup locali/dischi esterni devono essere confrontati con i checkpoint e poi caricati senza sostituire le versioni esistenti:
1. identificare nome/versione/data;
2. calcolare SHA-256;
3. creare branch `recovery/...` se il file non è già tracciato;
4. archiviare l'output definitivo in Release o percorso dedicato del repository, a seconda della dimensione;
5. aggiornare Scheda Madre con collegamento alla versione definitiva.

## Politica generale
GitHub è la copia di riferimento del progetto. Backup locali restano una seconda/terza copia, non l'unica fonte dei file finali.
