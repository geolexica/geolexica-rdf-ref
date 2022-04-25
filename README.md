
## Geolexica in SKOS/RDF

  

This repository contains the Geolexica Multi-lingual Glossary represented in RDF and SKOS, for both the ISO/TC 211 glossary, and the OSGeo glosssary. The separate resources each form a knowledge graph through ontologies, extensions, and instance data. Data can be imported into a graph triplestore, and queried with SPARQL. Design of the graph is modular, using separate files and named graphs. Files are also available in content-negotiable formats: RDF/XML, TTL, JSON-LD,  and JSON.

There are two main directories:

  

-  **mlgt**: for the ISO/TC 211 Multilingual Glossary of Terms

(https://isotc211.geolexica.org/concepts/)

-  **osgeo**: for the OSGeo Glossary (Geolexica) (https://osgeo.geolexica.org/concepts/).

  

and sub-directories organizing all files.

*******************************************

**ISO/TC 211 Multilingual Glossary of Terms**

  

The MLGT Glossary of Terms is defined by a core ontology, several extensions and supporting instance data. MLGT has its own namespace, prefixes and related administrative data.

  

Directory: **mlgt**

  

| Directory/File | Description |
|--|--|
| /core/geolexica-ontology.ttl | The MLGT Geolexica ontology, defining classes, object & data properties. |
| /core/mlgt-concepts.ttl | Instance data of all MLGT concepts in one file. |
| /core/concept-info.ttl | Instance data of term-related info for each resource (i.e., classification, clause, date accepted, entry status, & source). |
| /core/concept-reviews.ttl | Instance data of review info for each resource (i.e., review date, decision, event, notes, & status). |
| /core/languages-data.ttl | Ontology extension for languages; references Registries, ISO 639-1 two-letter abbreviation, labels, & notes. |
| /core/linked-data-apis.ttl | Instance data of linked data representations for each resource (i.e., json, json-ld, rdf/xml, and ttl formats). |
| /core/sources.ttl | Instance data of authoritative reference(s) for each resource (i.e., ISO documents) |
| /core/notes.ttl | Ontology extension of explanatory notes available for each resource (i.e., missing definitions, notes, translations, or examples for a given language). |
| /core/csv/ | Contains CSV representations of the ontology, extensions, and supporting data. |
| /core/mlgt-graph/ | Contains full graph representations of the ontology, extensions, and data. |
| /concepts/ | Contains all JSON, JSON-LD, RDF/XML, and TTL files for each concept in the glossary. |
| /queries/ | Example SPARQL queries and results. |

----------

**OSGeo Glossary (Geolexica)**

  
  

The OSGeo Glossary is defined with the same ontology structure as MLGT, except it is within its own namespace, has updated prefixes and related administrative data.

  

Directory: **osgeo**

  
  

| Directory/File | Description |
|--|--|
| /core/osgeo-ontology.ttl | The OSGeo Geolexica ontology, defining classes, object & data properties. |
| /core/osgeo-concepts.ttl | Instance data of all OSGeo concepts in one file. |
| /core/osgeo-info.ttl | Instance data of term-related info for each resource (i.e., classification, clause, date accepted, entry status, & source). |
| /core/osgeo-reviews.ttl | Instance data of review info for each resource (i.e., review date, decision, event, notes, & status). |
| /core/osgeo-lang-data.ttl | Ontology extension for languages; references Registries, ISO 639-1 two-letter abbreviation, labels, & notes. |
| /core/osgeo-lapi.ttl | Instance data of linked data representations for each resource (i.e., json, json-ld, rdf/xml, and ttl formats). |
| /core/osgeo-sources.ttl | Instance data of authoritative reference(s) for each resource (i.e., ISO documents) |
| /core/osgeo-notes.ttl | Ontology extension of explanatory notes available for each resource (i.e., missing definitions, notes, translations, or examples for a given language). |
| /core/csv/ | Contains CSV representations of the ontology, extensions, and supporting data. |
| /core/osgeo-graph/ | Contains full graph representations of the ontology, extensions, and data. |
| /concepts/ | Contains all JSON, JSON-LD, RDF/XML, and TTL files for each concept in the glossary. |
| /queries/ | Example SPARQL queries and results. |
