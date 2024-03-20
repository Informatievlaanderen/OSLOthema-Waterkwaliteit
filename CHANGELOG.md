### Aanpassingen AP-Waterkwaliteit [versie 2023-06-01](https://data.vlaanderen.be/doc/applicatieprofiel/waterkwaliteit/kandidaatstandaard/2023-06-01/) tov [versie 2022-10-17](https://data.vlaanderen.be/doc/applicatieprofiel/waterkwaliteit/kandidaatstandaard/2022-10-17/):

- Samenvatting herschreven, links toegevoegd (bvb naar ODALA, vocabularium etc).
- Klassen die naar OSLO-Datakwaliteit verwijzen hernoemd (zie changelog OSLO-Datakwaliteit hieronder), bvb Kwaliteitselement ipv DQ_Element.
- Analoog voor TemporeleEntiteit en subklassen.
- Ontbrekende (super)klassen en datatypes toegevoegd, bvb Observatieverzameling, PositioneleNauwkeurigheid, Geometrie etc.
- Verwijzingen naar andere AP's toegevoegd voor by-reference klassen, bvb voor Agent een verwijzing naar OSLO-Persoon/organisatie.
- Discrepanties tussen html en diagram weggewerkt, bvb ontbrekende attributen van Bemonsteringsobject.
- Definities & gebruiksnota's klassen/datatypes van alle gespecialiseerde klassen toegevoegd en/of verbeterd, bvb van BiotischeIndexObservatie, ChemischAgensCocentratieObservatie, ChemischAgensVrachtObservatie, HydromorfologischeIndexObservatie etc.
- Herbruikte klassen/datatypes van OSLO-ObservatiesEnMetingen en OSLO-SensorenEnBemonstering synchroon gezet qua definities edm met de laatste versies.
- [Issue28](https://github.com/Informatievlaanderen/OSLOthema-Waterkwaliteit/issues/28): Redefines herzien: Niet uitgevoerd omdat grootste deel van een andere standaard komt nl van ODALA AirAndWater.
- [Issue27](https://github.com/Informatievlaanderen/OSLOthema-Waterkwaliteit/issues/27): Hernoemen https://data.vlaanderen.be/ns/waterkwaliteit#ChemischAgensConcentratieObservatie.agens: TODO?.
- [Issue26](): Any mappen op rdfs:Resource ipv op iso:Any.: Issue Bert aangemaakt & beantwoord in de comments, uri aangepast & rerun specs.
- [Issue25](): DQ_Element: Was al opgelost in nieuwere versie, comment toegevoegd.
- [Issue24](): Property bioIndicator: Verkeerde uiri's toegekend, verbeterd & rerun specs, comment toegevoegd.
- [Issue23](): Dereferencing is niet mogelijk voor gebruikte klassen en properties - open standaarden? Foute uri's opgelost & rerun specs, antwoord voor de iso tc211 uri's, icomment toegevoegd.
- [Issue22](): Voorbeelddata BiologischeKwaliteitIndex Validatiefouten: Datavoorbeeld verbeterd en gaat nu foutloos door de JSON-LD playground + foutje in model verbeterd & rerun specs + aanpassingen gedaan aan datavoorbeeld zodat het wel valideert. comment toegevoegd. TODO: validatie overgeërfde properties.
- [Issue21](): Een emissiebron kan zowel een activiteit als een entiteit zijn: Uitgebreid antwoord in de comments, incl datavoorbeeld.
- [Issue20](): https://data.vlaanderen.be/doc/applicatieprofiel/waterkwaliteit/#EmissieType is niet gedefinieerd in het applicatieprofiel: Ap-codelist toegevoegd & rerun specs + verdere uitleg in de comments. TODO: ook voor andere codelijsten doen? DONE: terug verwijderd om consistent te zijn.
- [Issue19](): https://data.vlaanderen.be/doc/applicatieprofiel/waterkwaliteit/#MatrixType is niet gedefinieerd in het applicatieprofiel: Ap-codelist toegevoegd & rerun specs, comment toegevoegd. TODO: ook voor andere codelijsten doen? DONE: terug verwijderd om consistent te zijn.
- [Issue18](): property SF_SpatialSamplingFeature.shape verwacht een subclass van GM_Object als range: Uitgebreid beantwoord in de comments.
- [Issue17](): Toevoegen van een kenmerk aan een emissie: TODO: attribuut emissiewijze toevoegen aan Emissie? Vraag gesteld, wacht op antwoord. DONE.
- [Issue16](): https://data.vlaanderen.be/doc/applicatieprofiel/waterkwaliteit/#EmissiebronType is niet gedefinieerd: TODO ap-codelist toevoegen? Vraag gesteld, wacht op antwoord. DONE: voorlopig niet toevoegen.
- [Issue15](): https://data.vlaanderen.be/doc/applicatieprofiel/waterkwaliteit/#Observatietype is niet gedefinieerd: TODO ap-codelist toevoegen? Vraag gesteld, wacht op antwoord. DONE: voorlopig niet toevoegen.
- [Issue14](): definitie van https://data.vlaanderen.be/doc/applicatieprofiel/waterkwaliteit/#Maat is fout: Was al aangepast in de AP's Observaties en Metingen en Sensoren en Bemonstering. TODO: ook aanpassen in Waterkwaliteit. DONE.
- [Issue13](): de range van een value is een getal: Uitgebreid antwoord in de comments. TODO: Maat aanpassen zoals bij Observaties en Metingen & Sensoren en Bemonstering. DONE.
- [Issue12](): dcterms ipv cdterms: Was al opgelost in nieuwere versie, comment toegevoegd.
- [Issue11](): Diagram - vervolledigen en meer begrijpelijk daarstellen voor iedereen: Uitgebreid beantwoord in de comments.
- [Issue09](): Meetpunt: Uitgebreid beantwoord in de comments
- [Issue08](): Link naar ISO 19156:2011 gebroken: Beantwoord in de comments.
- [Issue07](): property bioIndicator heeft als range Any: Gebruiksnota toegevoegd & rerun specs + beantwoord in de comments.
- [Issue05](): de klasse BenoemdeWaarde wijkt af van sdmx: Gebruiksnota aangepast & rerun specs + beantwoord in de comments.
- [Issue04](): Is het echt de bedoeling dat er bij een BenoemdeWaarde, als range van de property waarde, exact 1 instance van een Any klasse zit?: Beantwoord in de comments.
- [Issue03](): ChemischAgensType lijkt me niet gedefinieerd: Beantwoord in de comments.
- [Issue02](): Datakwaliteit: ISO 1957 vs W3C DQLV: Voor een volgende versie, beantwoord in de comments.

### Aanpassingen VOC-Waterkwaliteit [versie 2023-06-01](https://data.vlaanderen.be/doc/vocabularium/waterkwaliteit/kandidaatstandaard/2023-06-01/) tov [versie 2022-10-17](https://data.vlaanderen.be/doc/vocabularium/waterkwaliteit/kandidaatstandaard/2022-10-17/):

- ()
