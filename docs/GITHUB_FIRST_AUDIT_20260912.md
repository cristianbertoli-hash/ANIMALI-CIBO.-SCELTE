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

## Output finali recuperati fuori da GitHub
La File Library contiene una copia reale del PDF finale:
- `Animali_Cibo_e_Scelte_2026.1_IT_MAC.pdf`

Quindi questo PDF NON deve essere ricostruito. Va recuperato dalla Library/backup e archiviato su GitHub come output persistente verificato.

## Output binari GitHub
- GitHub Releases: nessuna Release presente al momento dell'audit.
- Nel tree Git verificato non sono presenti i PDF/DOCX finali come binari, nonostante i checkpoint ne documentino la produzione.

## Azione di recupero
Per PDF/DOCX presenti in Library o sui due backup locali:
1. identificare nome/versione/data;
2. calcolare SHA-256;
3. creare branch `recovery/...` se serve associare documentazione/sorgenti;
4. archiviare l'output definitivo in GitHub Release o percorso dedicato, a seconda della dimensione;
5. aggiornare Scheda Madre con collegamento alla versione definitiva;
6. non sostituire o cancellare gli output precedenti.

## Politica generale
GitHub è la copia di riferimento del progetto. File Library e backup locali restano copie di recupero/secondarie, non l'unica fonte dei file finali.
