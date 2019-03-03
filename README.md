# Awesome Ontology

> A curated list of ontology things.

## Contents

* [Ontology Editors](#ontology-editors)
* [Languages](#languages)
* [Vocabularies](#vocabularies)
* [Ontologies](#ontologies)
  * [Upper-level](#upper-level-ontologies)
  * [Mid-level](#mid-level-ontologies)
  * [Large](#large-ontologies)
  * [Domain](#domain-ontologies)
* [Logics](#logics)
* [Reasoners](#reasoners)
* [Querying](#querying)
* [Rule and Schema Definition](#rule-and-schema-definition)
* [Related](#related)

## Ontology Editors

* [Fluent Editor](https://www.cognitum.eu/Semantics/FluentEditor/) - An award winning comprehensive tool for editing and manipulating complex ontologies that uses Controlled Natural Language.
* [Knoodl](http://knoodl.com/) - 
* [OntoStudio](http://www.semafora-systems.com/en/products/ontostudio/) (formerly OntoEdit) - A most widespread commercial modeling environment for  creating and maintaining ontologies.
* [OWLGrEd](http://owlgred.lumii.lv/) - A UML Style Graphical Editor for OWL.
* [Protégé](https://protege.stanford.edu/) - A free, open-source ontology editor and framework for building intelligent systems.
* [Semantic Turkey](http://semanticturkey.uniroma2.it/) - A RDF service platform for Knowledge Management and Acquisition.
* [TopBraid Composer](https://www.topquadrant.com/tools/modeling-topbraid-composer-standard-edition/) Series - 
* [Vitro](http://vitro.mannlib.cornell.edu/) - A general-purpose web-based ontology and instance editor with customizable public browsing.
* [VocBench](http://vocbench.uniroma2.it/) - A web-based, multilingual, collaborative development platform for managing OWL ontologies, SKOS(/XL) thesauri, Ontolex-lemon lexicons and generic RDF datasets.

Archived or inactive:

* [Apollo](http://apollo.open.ac.uk/) (last updated ~2005) - A user-friendly knowledge modelling application.
* [NeOn Toolkit](http://neon-toolkit.org/wiki/Main_Page.html) (last updated 2011) - A state-of-the-art, open source multi-platform ontology engineering environment, which provides comprehensive support for the ontology engineering life-cycle.
* [SWOOP](https://github.com/ronwalf/swoop) (last updated 2007) - An OWL Ontology browser/editor that takes the standard Web browser as the basic UI paradigm.
* [WebODE](https://github.com/oeg-upm/webODE) (discontinued in 2006) - An extensible ontology-engineering suite based on an application server.

See also:

* [List of ontology editors](https://en.wikipedia.org/wiki/Ontology_(information_science)#Editor) in Wikipedia
* [A List of Ontology Engineering Tools (Ontology Editors)](https://web.archive.org/web/20170827085837/http://www.hozo.jp/OntoTools/) by the Hozo group

## Languages

* [Common Logic (CL)](https://en.wikipedia.org/wiki/Common_Logic) - A language with an abstract syntax and semantics which are given in the ISO standard.
  * Common Logic Interchange Format (CLIF)
  * Conceptual Graph Interchange Format (CGIF)
  * eXtended Common Logic Markup Language (XCL)
* [CycL](http://www.cyc.com/documentation/ontologists-handbook/cyc-basics/syntax-cycl/) - A language with a concrete syntax based on first-order predicate calculus and Lisp.
* KL-ONE -
* Knowledge Interchange Format (KIF) -
* [Loom](https://www.isi.edu/isd/LOOM/) -
* [OBO Format (OBOF)](http://purl.obolibrary.org/obo/oboformat/spec.html) - A language used in the OBO Foundry with a concrete syntax and semantics which maps the language to OWL2-DL.
* [OWL 2 Web Ontology Language](https://www.w3.org/TR/owl2-overview/) - A language with [an abstract syntax](https://www.w3.org/TR/owl2-syntax/) and [semantics](https://www.w3.org/TR/owl2-direct-semantics/). It has a few defined (reserved) vocabulary terms (see [2.4, Table 3](https://www.w3.org/TR/owl2-syntax/) and [2.2](https://www.w3.org/TR/owl2-direct-semantics/)). The language is compatible with RDF by [the mapping between the OWL 2 language and the RDF language](https://www.w3.org/TR/owl2-mapping-to-rdf/). It can be extended with Description Logics (see [Logics](#logics)).
  * Manchester Syntax
  * OWL/XML
* [RDF (Resource Description Framework) 1.1](https://en.wikipedia.org/wiki/Resource_Description_Framework) - A language with [an abstract syntax (a data model)](https://www.w3.org/TR/rdf11-concepts/) based on the subject-predicate-object triple and [semantics](https://www.w3.org/TR/rdf11-mt/). For no vocabulary is defined in itself, it is used with RDF Schema vocabulary (see [Vocabularies](#vocabularies)).
  * JSON-LD
  * Notation3 (N3)
  * N-Quads
  * N-Triples
  * RDFa
  * RDF/XML
  * Turtle
  * TriG

See also:

* [Logics](#logics) section of this list
* [Ontology language](https://en.wikipedia.org/wiki/Ontology_language) in Wikipedia

## Vocabularies

> A vocabulary is a set of terms for a language.

* [Dublin Core Metadata Element Set](http://dublincore.org/documents/dces/) - A vocabulary of fifteen properties for use in resource description.
* [DCMI Metadata Terms](http://dublincore.org/documents/dcmi-terms/) - An extension of the Dublin Core Metadata Element Set.
* [IMI (Infrastructure for Multilayer Interoperability) Core Vocabulary](https://imi.go.jp/goi/imi-about-en) - A Japanese controlled vocabulary consists of roughly 60 class concepts, 250 property concepts and words associated to them.
* [Open Graph protocol](http://ogp.me/) - 
* [RDF Schema (RDFS) 1.1](https://www.w3.org/TR/rdf-schema/) - A data-modelling RDF vocabulary used for defining RDF vocabularies.
* [SKOS (Simple Knowledge Organization System)](https://www.w3.org/TR/skos-reference/) - An RDF vocabulary for representing semi-formal knowledge organization systems (KOSs), such as thesauri, taxonomies, classification schemes and subject heading lists.
* [Schema.org Schemas](https://schema.org/docs/full.html) - 

## Ontologies

See also:

* [Lists of ontologies](https://www.w3.org/wiki/Lists_of_ontologies) on W3C Wiki - A short meta-list of lists of ontologies.
* [Ontology List](http://info.slis.indiana.edu/~dingying/Teaching/S604/OntologyList.html) by Ying Ding

### Upper-level Ontologies

* [BFO (Basic Formal Ontology)](http://basic-formal-ontology.org/) - A small, upper level ontology that is designed for use in supporting information retrieval, analysis and integration in scientific and other domains.
* [DBpedia Ontology](https://wiki.dbpedia.org/services-resources/ontology) - A shallow, cross-domain ontology, which has been manually created based on the most commonly used infoboxes within Wikipedia.
* [DOLCE (Descriptive Ontology for Linguistic and Cognitive Engineering)](http://www.loa.istc.cnr.it/old/DOLCE.html) - 
* [SUMO (Suggested Upper Merged Ontology)](http://www.adampease.org/OP/) - 
* [UMBEL (Upper Mapping and Binding Exchange Layer)](http://umbel.org/) Vocabulary (UMBEL ontology) - An ontology consists of ~70 classes.
* [YAMATO (Yet Another More Advanced Top-level Ontology)](http://download.hozo.jp/onto_library/upperOnto.htm) - 

### Mid-level Ontologies

* [UMBEL (Upper Mapping and Binding Exchange Layer)](http://umbel.org/) Reference Concepts (Reference Concepts ontology) -

### Large Ontologies

* [Cyc](https://www.cyc.com/) ([OpenCyc](http://www.cyc.com/opencyc/)/[ResearchCyc](http://www.cyc.com/researchcyc/)) - 
* [DBpedia](https://wiki.dbpedia.org/) - 
* [Wikidata](https://www.wikidata.org/) - A free and open knowledge base that can be read and edited by both humans and machines.
* [WordNet](https://wordnet.princeton.edu/) - A large lexical Database of English.
* [YAGO](https://www.mpi-inf.mpg.de/departments/databases-and-information-systems/research/yago-naga/yago/) - A huge semantic knowledge base, derived from Wikipedia WordNet and GeoNames.

Archived or inactive:

* [Freebase](https://developers.google.com/freebase/) - 

### Domain Ontologies

#### Biology

* [Gene Ontology (GO)](http://geneontology.org/) -  The world’s largest source of information on the functions of genes.

#### Commerce

* [GoodRelations](http://www.heppnetz.de/projects/goodrelations/) - The Web vocabulary for e-commerce.
* [Product Types Ontology](http://www.productontology.org/) - High-precision identifiers for product types based on Wikipedia.

#### Community

* [SIOC (Semantically Interlinked Online Communities)](http://sioc-project.org/) - An ontology of terms that can be used to describe online communities on the Web of Data.

#### Culture

* [CIDOC CRM (Conceptual Reference Model)](http://www.cidoc-crm.org/) - An ontology for cultural heritage information, which describes the explicit and implicit concepts and relations relevant to the documentation of cultural heritage.

#### Food and Drink

* [Wine Ontology](https://www.w3.org/TR/owl-guide/wine.rdf) - An example used in [W3C OWL Guide](https://www.w3.org/TR/owl-guide/).
* [Food Ontology](https://www.w3.org/TR/2004/REC-owl-guide-20040210/food.rdf) - An example used in [W3C OWL Guide](https://www.w3.org/TR/owl-guide/).

#### Geography

* [Geographical Entity Ontology](http://www.obofoundry.org/ontology/geo.html) - An ontology of geographical entities implemented in OWL 2 and based on Basic Formal Ontology (BFO).

#### News

* [rNews](http://dev.iptc.org/rNews) - An approved standard for using semantic markup to annotate news-specific metadata in HTML documents.

#### People

* [Friend Of A Friend (FOAF)](http://www.foaf-project.org/) - A computer language defining a dictionary of people-related terms that can be used in structured data.
* [vCard Ontology](https://www.w3.org/TR/vcard-rdf/) - An ontology for describing people and organizations. A mapping of the vCard specification (RFC6350) to RDF/OWL.

## Logics

> A logic is a language with a proof theory (e.g., axioms and inference rules).

* [Description Logics (DLs)](https://en.wikipedia.org/wiki/Description_logic) -
* [F-Logic](https://en.wikipedia.org/wiki/F-logic) family -

See also:

* [Description Logic Complexity Navigator](http://www.cs.man.ac.uk/~ezolin/dl/) by Evgeny Zolin

## Reasoners

> A reasoner is a program which infers explanatory or new facts and detects inconsistencies in ontology and knowledge base based on the logic associated.

* [CEL](https://julianmendez.github.io/cel/) - A lightweight Description Logic (EL+) reasoner for large-scale biomedical ontologies. (Common Lisp+Java)
* [ELK](https://github.com/liveontologies/elk-reasoner) - An ontology reasoner that aims to support the OWL 2 EL profile. (Java)
* [EYE](https://github.com/josd/eye) - A reasoning engine which performs semibackward chaining and supports Euler paths. (Prolog)
* [FaCT++](http://owl.man.ac.uk/factplusplus/) - The new generation of the well-known [FaCT](http://www.cs.man.ac.uk/~horrocks/FaCT) OWL-DL reasoner which uses optimised tableaux algorithms. (C++)
* [Flora-2 (Ergo Lite)](http://flora.sourceforge.net/) - A F-logic based reasoning system. (Prolog)
* [HyLAR](https://github.com/ucbl/HyLAR-Reasoner) - A rule-based incremental reasoner for the Web. (JavaScript)
* [jcel](https://github.com/julianmendez/jcel) - A reasoner for the description logic EL+. (Java)
* [Openllet](https://github.com/Galigator/openllet) - An OWL DL reasoner build on top of Pellet 2. (Java)
* [OWL-RL](https://github.com/RDFLib/OWL-RL) - A simple implementation of the OWL2 RL Profile, as well as a basic RDFS inference, on top of RDFLib. (Python)
* [Racer](https://www.ifis.uni-luebeck.de/~moeller/racer/) - A knowledge representation system that implements a highly optimized tableau calculus for the description logic SRIQ(D). (Common Lisp+Java)

Archived or inactive:

* [cwm](https://www.w3.org/2000/10/swap/doc/cwm.html) (last updated 2005) - A forward chaining RDF reasoner. (Python)
* [HermiT](http://www.hermit-reasoner.com/) (last updated ~2013) - The first publicly-available OWL reasoner based on a novel “hypertableau” calculus which provides much more efficient reasoning than any previously-known algorithm. (Java)
* [KAON2](http://kaon2.semanticweb.org/) reasoner (last updated 2008) - A DL reasoner for the SHIQ(D) subset of OWL-DL, based on novel algorithms which reduce a SHIQ(D) knowledge base to a disjunctive datalog program. (proprietary, Java)
* [Pellet 2](https://github.com/stardog-union/pellet) (last updated ~2015) - An open source OWL DL reasoner for Java. Pellet 3 (proprietary) is embedded in the [Stardog](https://www.stardog.com/) platform. (Java)

See also:

* [How does a reasoner work?](http://ontogenesis.knowledgeblog.org/1486) - An introductory article by Uli Sattler, Robert Stevens, and Phillip Lord

## Querying

* [SPARQL 1.1](https://www.w3.org/TR/sparql11-query/) - A set of specifications that provide languages and protocols to query and manipulate RDF graph content on the Web or in an RDF store.

## Rule and Schema Definition

* [SHACL (Shapes Constraint Language)](https://en.wikipedia.org/wiki/SHACL) -
* [ShEx (Shape Expressions)](https://en.wikipedia.org/wiki/ShEx) -
* [SPIN (SPARQL Inferencing Notation)](http://spinrdf.org/) -
* [SWRL (Semantic Web Rule Language)](https://www.w3.org/Submission/SWRL/) - A rule markup language which extends the logical expressivity of the OWL language.

## Related

* [Awesome-Knowledge-Bases](https://github.com/buaaliuming/Awesome-Knowledge-Bases) - Available knowledge bases, Ontology, Knowledge Graph or taxonomy.
* [awesome-semantic-tools](https://github.com/costezki/awesome-semantic-tools) - 
List of projects related to Ontology engineering and Semantic Web technologies that make a geek smile for they exist.
* [semantalytics/awesome-semantic-web](https://github.com/semantalytics/awesome-semantic-web) - A curated list of various semantic web and linked data resources.
* [jbenner-radham/awesome-semantic-web](https://github.com/jbenner-radham/awesome-semantic-web) - A curated list of various semantic web and linked data resources.
* [awesome-semantic-web-business](https://github.com/KMax/awesome-semantic-web-business) - A curated list of awesome resources that feature usages of Semantic Web technologies in business cases (applications).
