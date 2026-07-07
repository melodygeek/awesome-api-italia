# Distribution Dashboard

Dashboard operativa per la distribuzione di `openapi/awesome-api-italia`.

Questo repository non è un prodotto binario, un pacchetto, un plugin o un SDK. È un asset editoriale: una awesome list multilingue sulle API italiane e internazionali con dati italiani. Distribuzione significa quindi discoverability, fiducia, rilevanza e manutenzione continua sui canali dove sviluppatori e professionisti cercano API e dati italiani.

## Identità del progetto

- **Progetto:** awesome-api-italia
- **Formato:** GitHub repository / awesome list
- **Asset primario:** README.md
- **Target audience:** sviluppatori, tech lead, integratori, startup, PA, consulenti che cercano API con dati italiani
- **Value proposition:** una mappa curata e categorizzata di API per dati italiani — PA, catasto, fisco, automotive, imprese, identità digitale, meteo e molto altro

## Obiettivi di distribuzione

1. Rendere il repository facile da trovare su GitHub, motori di ricerca ed ecosistemi awesome-list
2. Posizionarlo come riferimento serio per le API italiane, non come lista generica
3. Mantenere la qualità editoriale (voci verificate, categorization chiara, deprecazioni tracciate)
4. Costruire uno storico operativo: cosa è stato pubblicato, dove, quando e con che esito

## Status legend

- `todo` — non iniziato
- `in progress` — in preparazione o invio
- `submitted` — inviato, in attesa di review/pubblicazione
- `listed` — live e discoverable
- `monitoring` — live, ma necessita controllo periodico
- `n/a` — escluso intenzionalmente

## Priority queue

| Priority | Channel cluster | Agent-operable | Status | Notes |
|---|---|---|---|---|
| 1 | GitHub-native discoverability | yes | in progress | README, topics, description, badges |
| 2 | PR-based awesome-list aggregators | partial | todo | Sottomissione via PR a liste affini |
| 3 | Directory italiane e tematiche | partial | todo | italia-opensource, Developers Italia, liste PA |
| 4 | Forum e discussioni | no | monitoring | Solo citazioni contestuali, no spam |

## Canali di distribuzione

### P1 — GitHub-native

| Channel | URL | Status | Notes |
|---|---|---|---|
| Repository description | GitHub repo settings | done | Descrizione già impostata |
| Repository topics | GitHub repo settings | todo | Aggiungere: `api`, `italy`, `open-data`, `pa`, `awesome-list`, `awesome` |
| README badges | README.md | done | Awesome badge, lingua, license, PRs welcome |
| CONTRIBUTING guide | CONTRIBUTING.md | done | Criteri di inclusione e formato voci |

### P2 — Aggregatori awesome-list

| Target | URL | Fit | Status |
|---|---|---|---|
| awesome-italia-opensource | https://github.com/italia-opensource/awesome-italia-opensource | high | todo |
| publicapis | https://github.com/public-apis/public-apis | medium | todo |
| awesome-italian | liste italiane generiche | medium | todo |

### P3 — Directory italiane

| Target | URL | Fit | Status |
|---|---|---|---|
| Developers Italia | https://developers.italia.it/it/api | high | todo |
| awesome-italia-remote | https://github.com/italiaremote/awesome-italia-remote | low | n/a |

## Execution log

| Data | Azione |
|---|---|
| 2026-07-07 | Creato TODO.md come distribution dashboard per awesome-api-italia |
| 2026-07-07 | Verificata e aggiornata la lista con API Openapi dal knowledge base |
| 2026-07-07 | Corretti tutti i link Openapi al formato console.openapi.com |
| 2026-07-07 | Rimosse API non verificate (CRIF, Experian, Cerved, etc.) in DEPRECATED.md |

## Note

- Preferire pochi canali rilevanti rispetto a distribuzione massiva
- Ogni PR deve seguire le regole di contribuzione del target
- Mantenere aggiornato DEPRECATED.md come traccia storica
- Le voci vanno sempre verificate prima di essere (ri)aggiunte
