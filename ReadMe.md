# SiG Ontology aka RDF_TEI

The idea is to define all relevant usecase scenarios in which someone wants to transform a TEI document into RDF triples.
Accordingly different transform scenarios seem to be relevant for me.
Further we have to think which use scenarios are important.

From my point of view, a completely different topic is to formalize TEI as an ontology. 
So we shoulde name the SiG "RDF_TEI".


## Scenario 1: The whole TEI document is transformed

I'll have to try it out: https://github.com/ajstanley/TEI_to_RDF

Comment: I'm not sure if it makes much sense to transform a tree structure into a graph structure.

## Scenario 2: Already deep-structured elements are transformed to RDF

### t:biblFull SZD-project.

* http://glossa.uni-graz.at/o:szd.bibliothek/TEI_SOURCE
* http://glossa.uni-graz.at/o:szd.bibliothek/RDF


## Scenario 3: Certain semantic structures in a document are transformed to RDF

### @ana 

* http://gams.uni-graz.at/context:depcha

## Controlled Vocabularies and Linking

### Scenario 1: All references refer to extern taxonomies/vocabularies (Wikidata, GND, VIAF...etc.)

### Scenario 2: The teiHeader/structure inside the teiHeader is the authority

how can this authority can be published? reused by others?


## Further topics of interest (?)

* Ontology alignment (to Upper-Level Ontologies, between Domain-specific Ontologies)
* Publication of LOD-Data (metaphacts seems to be really cool: https://www.metaphacts.com/product)
* Analysis of Data (InfoVis etc.)
* Retrieval and Discovery od LOD 

## Tools, technologies, data standards

#### Define RDF 'inside' XML 

* RDFa: http://rdfa.info/ 

#### Transform XML to RDF

* Xtriples: https://xtriples.lod.academy/index.html
* RDFe – expression-based mapping of XML documents to RDF triples: https://www.parsqube.de/publikationen/rdfe-expression-based-mapping-of-xml-documents-to-rdf-triples/

#### Validating RDF: 

* SHACL
