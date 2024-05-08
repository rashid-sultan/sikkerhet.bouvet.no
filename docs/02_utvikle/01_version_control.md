---
sidebar_position: 1
---

# Versjonskontroll

import WorkInProgress from '../_work_in_progress.mdx'

<WorkInProgress />

Informasjon rundt bruk av versjonskontroll

- Bruk versjonskontroll for prosjektet
- Sørg for at produksjons-branchen (ofte `main` eller `master`) er beskyttet
    - Sett gjerne et krav om at pull requests må ha minst to godkjenninger før den kan merges
- Hvor lagres kildekoden?
    - Versjonskontroll skal benyttes. `git` er foretrukket
- On-prem eller i skyen?
    - Backup-rutiner (også av skytjenester)
    - Tilgjengelighet
    - Autentisering
- Public eller private repository?
    - Vurderes per system
- Integrasjon med verktøy som Snyk for kode/bibliotek skanning for sårbarheter
