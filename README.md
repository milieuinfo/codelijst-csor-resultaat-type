# codelijst-csor-resultaat-type

Codelijst voor het **Resultaattype** binnen het **CSOR** (Chemische Stoffen en Omgevingsparameters-Register).

## Beschrijving

Het resultaattype beschrijft de wijze waarop het resultaat van een observatie kan worden voorgesteld. Deze repository bevat de SKOS-codelijst die de toegelaten resultaattypes definieert die gebruikt worden in het CSOR-datamodel.

De codelijst is gepubliceerd als linked data onder de namespace:
`https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/resultaattype`

## Concepten

| ID   | Label                | Omschrijving          |
|------|----------------------|-----------------------|
| RT_1 | Meting               | Meting toelichting    |
| RT_2 | Classificatie        |                       |
| RT_3 | Aantal               |                       |
| RT_4 | Temporele Observatie |                       |

## Bestandsformaten

De codelijst is beschikbaar in de volgende RDF-formaten:

| Bestand                  | Formaat                        |
|--------------------------|--------------------------------|
| `resultaattypes.ttl`     | Turtle                         |
| `resultaattypes.jsonld`  | JSON-LD                        |
| `resultaattypes.nt`      | N-Triples                      |
| `resultaattypes.rj`      | RDF/JSON                       |

De bronbestanden bevinden zich in:
```
src/main/resources/be/vlaanderen/omgeving/data/id/conceptscheme/csor/resultaattype/
```

## Gebruikte standaarden

- [SKOS](https://www.w3.org/TR/skos-reference/) — Simple Knowledge Organization System
- [OWL](https://www.w3.org/OWL/) — Web Ontology Language
- [CSOR-ontologie](https://data.omgeving.vlaanderen.be/ns/csor#) — domeinspecifieke klassen en eigenschappen

## Licentie

GNU General Public License v3.0 — zie [LICENSE](LICENSE).
