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
| 1 | GitHub-native discoverability | yes | listed | README, topics, description, badges |
| 2 | PR-based awesome-list aggregators | partial | in progress | Sottomissione via PR a liste affini |
| 3 | Directory italiane e tematiche | partial | in progress | italia-opensource, Developers Italia, liste PA |
| 4 | Forum e discussioni | no | monitoring | Solo citazioni contestuali, no spam |

## Canali di distribuzione

### P1 — GitHub-native

| Channel | URL | Status | Notes |
|---|---|---|---|
| Repository description | GitHub repo settings | done | Descrizione già impostata |
| Repository topics | GitHub repo settings | listed | 15 topics: agid, api, awesome, awesome-list, developers-italia, fintech, italia, italy, open-data, open-source, pa, pa-digitale, public-apis, rest-api, spid |
| README badges | README.md | done | Awesome badge, lingua, license, PRs welcome |
| CONTRIBUTING guide | CONTRIBUTING.md | done | Criteri di inclusione e formato voci |
| Track Awesome List | https://www.trackawesomelist.com | auto | Auto-indexato via topic `awesome-list` |
| awesomelists.top | https://awesomelists.top | auto | Auto-indexato via topic `awesome-list` |

### P2 — Aggregatori awesome-list

| Target | URL | Fit | Status | PR |
|---|---|---|---|---|
| italia-opensource | https://github.com/italia-opensource/awesome-italia-opensource | high | submitted | #201 |
| awesome-italian-pa-opensource | https://github.com/stefanosalvucci/awesome-italian-pa-opensource | high | submitted | #1 |
| sindresorhus/awesome | https://github.com/sindresorhus/awesome | high | todo | Richiede awesome-lint + 4 PR review |
| IonicaBizau/made-in-italy | https://github.com/IonicaBizau/made-in-italy | medium | todo | Progetti italiani per linguaggio |
| amallia/awesome-italian-tech | https://github.com/amallia/awesome-italian-tech | medium | todo | Risorse tech italiane generali |
| publicapis/public-apis | https://github.com/public-apis/public-apis | low | n/a | Solo API individuali, no meta-liste |

### P3 — Directory italiane

| Target | URL | Fit | Status | Notes |
|---|---|---|---|---|
| Developers Italia | https://developers.italia.it/it/api | high | submitted | Aggiunto publiccode.yml per indexing automatico |
| italia/awesome-italian-public-datasets | https://github.com/italia/awesome-italian-public-datasets | low | n/a | Solo dataset, non API list |

### P4 — Forum e community

| Target | URL | Fit | Status |
|---|---|---|---|
| r/ItalyInformatica | https://www.reddit.com/r/ItalyInformatica/ | medium | monitoring |
| r/opensource | https://www.reddit.com/r/opensource/ | medium | monitoring |

## Execution log

| Data | Azione |
|---|---|
| 2026-07-07 | Creato TODO.md come distribution dashboard per awesome-api-italia |
| 2026-07-07 | Verificata e aggiornata la lista con API Openapi dal knowledge base |
| 2026-07-07 | Corretti tutti i link Openapi al formato console.openapi.com |
| 2026-07-07 | Rimosse API non verificate (CRIF, Experian, Cerved, etc.) in DEPRECATED.md |
| 2026-07-07 | Aggiunti 15 topic al repo (api, awesome, awesome-list, italy, open-data, pa, etc.) |
| 2026-07-07 | PR #201 aperta su italia-opensource/awesome-italia-opensource — submitted |
| 2026-07-07 | PR #1 aperta su stefanosalvucci/awesome-italian-pa-opensource — submitted |
| 2026-07-07 | Aggiunto publiccode.yml per indexing automatico su developers.italia.it |
| 2026-07-07 | Studio canali distribuzione: 22 canali identificati, 5 attivati |

## Note

- Preferire pochi canali rilevanti rispetto a distribuzione massiva
- Ogni PR deve seguire le regole di contribuzione del target
- Per fork e cloni usare sempre l'identità melodygeek
- Mantenere aggiornato DEPRECATED.md come traccia storica
- Le voci vanno sempre verificate prima di essere (ri)aggiunte
- Prossimi passi: sindresorhus/awesome (richiede awesome-lint), IonicaBizau/made-in-italy
