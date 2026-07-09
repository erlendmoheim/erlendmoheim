**Sommeren 2026** har jeg sommerjobb hos **Vegdata i Vestland fylkeskommune**, der jeg har laget to interne verktøy. Selve koden ligger ikke offentlig, siden den tilhører fylkeskommunen, men kort om hva jeg bygde:

- **Uttrekksverktøy mot Visma.** Henter regnskaps- og prosjektdata fra økonomisystemet via et OAuth-autentisert REST-API. Grafisk grensesnitt (Tkinter) for å velge kolonner, periode og år, og eksport til Excel og CSV. Pakket som en enkelt .exe så kolleger uten utviklingsmiljø kan bruke det.
- **Innmelding til NVDB.** Bygger endringssett for skredpunkt langs fylkesvegene og sender dem inn via skrive-API-et til Nasjonal vegdatabank, med validering, logging og en oppsummeringsrapport.
