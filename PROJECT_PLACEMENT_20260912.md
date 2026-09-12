# Project placement — Animali, Cibo e Scelte — 2026-09-12

## Obiettivo
Portare nel repository corretto i PDF finali gia salvati nella Recovery Vault centrale, senza cancellare o sovrascrivere versioni storiche.

## Stato Recovery Vault
I PDF sono gia archiviati nel repository `cristianbertoli-hash/braincore`, release `recovery-vault-20260912-phase3-animali`.

Asset verificati:
- `Animali_Cibo_e_Scelte_2026.1_IT_MAC.pdf` — sha256 `28b9986d4d73d2dd96b4eb9882cac46af51ca2a98deccb30515a2f4e04e89697`
- `Animali_Cibo_e_Scelte_2026.1_MANUALE_111_PRINT.pdf` — sha256 `47b032ed3d55cf28541363eacc01fb8c7b5d6a450f5296b5e89d6fca377efae5`
- `Animali_Cibo_e_Scelte_2026.1_MANUALE_IT.pdf` — sha256 `ffd2ee7314e316c5b16ba72aac51cca0e8ed830f96cc1f89c18fe847125d979a`
- `Animali_Cibo_e_Scelte_2026.2_MANUALE_ESTESO_248_A4_IT.pdf` — sha256 `0c4c895607c2b4eeae1d956f338b550dda05eaac7eb84db74e680d90d2e47755`
- `Animali_Cibo_e_Scelte_2026.2_MANUALE_ESTESO_248_A4_ILLUSTRATO_IT-variant-A-1fdcb95d.pdf` — sha256 `1fdcb95d7dc7626f126d0e7b648725aefa987180ada740d32a20caadffba4c51`
- `Animali_Cibo_e_Scelte_2026.2_MANUALE_ESTESO_248_A4_ILLUSTRATO_IT-variant-B-3c36bffc.pdf` — sha256 `3c36bffc4f5aeeebede30d4f2475b8a1b097391e561548a8b41c769ef64102d2`

## Destinazione corretta
- Sorgenti, bibliografia, Scheda Madre, checkpoint e sito: repository `animali-cibo-scelte`.
- PDF finali: GitHub Release del repository `animali-cibo-scelte`.
- Recovery Vault centrale: mantenuta come seconda copia di sicurezza.

## Regole
- Nessuna versione storica viene cancellata.
- Le due varianti illustrate restano entrambe conservate finche non viene identificata una versione canonica.
- Ogni asset trasferito nel repository progetto deve mantenere il digest SHA-256 verificato.
- Nessun documento personale o PDF esterno di riferimento viene incluso nella release del progetto.

## Stato operativo
Branch di riordino: `ops/project-placement-20260912`.
La copia dei PDF nella release progetto verra eseguita solo dopo disponibilita di un runner autorizzato per questo repository o altro metodo verificato senza costi inattesi.
