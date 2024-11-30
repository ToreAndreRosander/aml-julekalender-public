# 🎄 Adventsoppgave 1: Produksjon av Arbeidsliste for Julenissen 🎅

**Ho, ho, ho!** Alarmer fra Nordpolen! Vi har mistet tilgang til arbeidslisten som viser hvor mange gaver vi må lage i år og alvene er helt ute av seg! Heldigvis har vi klart å gjenskape deler av **ønskelistene** som er sendt inn, samt **lagerlisten** over antall gaver vi allerede har produsert. Nå trenger vi din hjelp til å lage en komplett arbeidsliste.

## 📝 Oppgavebeskrivelse

Din oppgave er å:
1. **Analyser ønskelistene** og lagerlisten.
2. Beregne hvor mange av hver gave som må produseres for å dekke behovet.
3. Generere en **arbeidsliste** som følger malen definert i dette repositoriet.

Den ferdige arbeidslisten skal være i **CSV-format** og inneholde følgende kolonner:
- **Gave**: Navn på gaven.
- **Ønsket Antall**: Antall gaver som er ønsket totalt.
- **På Lager**: Antall gaver som allerede er produsert og tilgjengelig.
- **Behov**: Antall gaver som må lages.

Eksempel på CSV-format:
```csv
Gave,Ønsket Antall,På Lager,Behov
Lekebil,100,40,60
Bamse,200,150,50
Tegnesaker,50,10,40
