
## Geolexica in SKOS/RDF

This repository tracks the Geolexica Multi-lingual Glossary in RDF and SKOS, as an organizational framework. 

There are two directories, "mlgt", for the ISO/TC 211 Multilingual Glossary of Terms (https://isotc211.geolexica.org/concepts/), and "osgeo", for the OSGeo Glossary (Geolexica) (https://osgeo.geolexica.org/concepts/). 

----------
**ISO/TC 211 Multilingual Glossary of Terms**

The MLGT Glossary of Terms is defined with a primary ontology, several extensions and supporting instance data. MLGT has its own namespace, prefixes and related administrative data. 

Folder: **mlgt**
| File | Description |
|--|--|
| geolexica-ontology.ttl | The MLGT Geolexica ontology, defining classes, object & data properties. |
| mlgt-concepts.ttl | Serialization (dataset) of all MLGT concepts. |
| concept-info.ttl | Serialization of term-related info for each resource (i.e., classification, clause, date accepted, entry status, & source). |
| concept-reviews.ttl | Serialization of review info for each resource (i.e., review date, decision, event, notes, & status). |
| languages-data.ttl | Ontology extension for languages; references Registries, ISO 639-1 two-letter abbreviation, labels, & notes. |
| linked-data-apis.ttl | Serialization of linked data representations for each resource (i.e., json, json-ld, rdf/xml, and ttl formats). |
| sources.ttl | Serialization of authoritative reference(s) for each resource (i.e., ISO documents) |
| notes.ttl | Ontology extension of explanatory notes available for each resource (i.e., missing definitions, notes, translations, or examples for a given language). |
| concept-6.ttl | Example of a single concept with all relevant metadata and values. |
| concepts folder | Contains all JSON, JSON-LD, RDF/XML, and TTL files for each concept in the glossary. |
| api folder | Contains all JSON, JSON-LD, and RDF/XML files for the ontology, extensions, and supporting data. |
----------
**OSGeo Glossary (Geolexica)**


The OSGeo Glossary is defined with the same ontology structure as MLGT, except it is within its own namespace, has updated prefixes and related administrative data.

Folder: **osgeo**
| File | Description |
|--|--|
| osgeo-ontology.ttl | The OSGEO Glossary (Geolexica) ontology, defining classes, object & data properties. |
| osgeo-concepts.ttl | Serialization (dataset) of all OSGeo concepts. |
| osgeo-info.ttl | Serialization of term-related info for each resource (i.e., classification, clause, date accepted, entry status, & source). |
| osgeo-reviews.ttl | Serialization of review info for each resource (i.e., review date, decision, event, notes, & status). |
| osgeo-lang-data.ttl | Ontology extension for languages; references Registries, ISO 639-1 two-letter abbreviation, labels, & notes. |
| osgeo-ldapi.ttl | Serialization of linked data representations for each resource (i.e., json, json-ld, rdf/xml, and ttl formats). |
| osgeo-sources.ttl | Serialization of authoritative reference(s) for each resource (i.e., ISO documents) |
| osgeo-notes.ttl | Ontology extension of explanatory notes available for each resource (i.e., missing definitions, notes, translations, or examples for a given language).  |
| concepts folder | Contains all JSON, JSON-LD, RDF/XML, and TTL files for each concept in the glossary. |
| api folder | Contains all JSON, JSON-LD, and RDF/XML files for the ontology, extensions, and supporting data. |