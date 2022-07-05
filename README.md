# Awesome Ontology

A curated list of ontology things. Your contribution is welcome!

## Contents

* [Ontology Editors](#ontology-editors)
* [Ontology Tools](#ontology-tools)
* [Datastore](#datastore)
* [Languages](#languages)
* [Ontologies and Vocabularies](#ontologies-and-vocabularies)
  * [Upper-level](#upper-level-ontologies)
  * [Mid-level](#mid-level-ontologies)
  * [Cross-domain](#cross-domain-ontologies)
  * [Domain](#domain-ontologies)
  * [Vocabularies](#vocabularies)
* [Alignment & Matching](#alignment--matching)
* [Logics](#logics)
* [Reasoners](#reasoners)
* [Querying](#querying)
* [Rule and Schema Definition](#rule-and-schema-definition)
* [Programming](#programming)
* [Communities](#communities)
* [Related](#related)

## Ontology Editors

* [Fluent Editor](https://www.cognitum.eu/Semantics/FluentEditor/) - An award winning comprehensive tool for editing and manipulating complex ontologies that uses Controlled Natural Language.
* [OntoME](https://ontome.net/) - Designed for any object-oriented structured data model to build, manage and align your ontology, or to simply browse through the existing ontologies. ([GitHub](https://github.com/Semantic-Data-for-Humanities/OntoME) for issues)
* [OntoStudio](https://www.semafora-systems.com/ontobroker-and-ontostudio-x) (formerly OntoEdit) - A most widespread commercial modeling environment for creating and maintaining ontologies.
* [OWLGrEd](http://owlgred.lumii.lv/) - A UML Style Graphical Editor for OWL.
* [Protégé](https://protege.stanford.edu/) - A free, open-source ontology editor and framework for building intelligent systems.
* [TopBraid Composer](https://www.topquadrant.com/tools/modeling-topbraid-composer-standard-edition/) Series - A powerful Integrated Development Environment (IDE) for implementing Knowledge Graph/Linked Data services by TopQuadrant, Inc.
* [Vitro](https://github.com/vivo-project/Vitro) - A general-purpose web-based ontology and instance editor with customizable public browsing.
* [VocBench](http://vocbench.uniroma2.it/) and [Semantic Turkey](http://semanticturkey.uniroma2.it/) - VocBench is a web-based, multilingual, collaborative development platform for managing OWL ontologies, SKOS(/XL) thesauri, Ontolex-lemon lexicons and generic RDF datasets. Its backend, Semantic Turkey is a RDF service platform for Knowledge Management and Acquisition.

Archived or inactive:

* [Apollo](http://apollo.open.ac.uk/) (last updated ~2005) - A user-friendly knowledge modelling application.
* [NeOn Toolkit](http://neon-toolkit.org/wiki/Main_Page.html) (last updated 2011) - A state-of-the-art, open source multi-platform ontology engineering environment, which provides comprehensive support for the ontology engineering life-cycle.
* [Knoodl](https://web.archive.org/web/20190703092924/http://knoodl.com/) (last updated ~2017) - An ontology-driven "Distributed Information Management System" (DIMS) by Revelytix, Inc.
* [SWOOP](https://github.com/ronwalf/swoop) (last updated 2007) - An OWL Ontology browser/editor that takes the standard Web browser as the basic UI paradigm.
* [WebODE](https://github.com/oeg-upm/webODE) (discontinued in 2006) - An extensible ontology-engineering suite based on an application server.

See also:

* [List of ontology editors](https://en.wikipedia.org/wiki/Ontology_(information_science)#Editors) in Wikipedia
* [A List of Ontology Engineering Tools (Ontology Editors)](https://web.archive.org/web/20170827085837/http://www.hozo.jp/OntoTools/) by the Hozo group

## Ontology Tools

* [LODE](https://essepuntato.it/lode/) - Java ontology documentation generator to convert OWL ontologies into HTML human-readable pages.
* [obonet](https://github.com/dhimmel/obonet) - Python library to convert OBO-formatted ontologies to networkx graphs.
* [OnToology](https://github.com/OnToology/OnToology) - Online tool to automatically generate documentation and evaluation for Ontologies hosted on GitHub.
* [Ontospy](http://lambdamusic.github.io/Ontospy/) - Python library and command-line interface for inspecting and visualizing RDF models.
* [OWLTools](https://github.com/owlcollab/owltools) - Java API and command-line utilities on top of the OWL API.
* [pyLODE](https://github.com/RDFLib/pyLODE) - Python ontology documentation generator inspired by LODE.
* [ROBOT](http://robot.obolibrary.org/) - Java library and CLI tool for working with ontologies, particularly Open Biomedical Ontologies. It also provides a bridge to Python by Py4J.
* [WebVOWL](https://github.com/VisualDataWeb/WebVOWL) - Web application for visualizing ontologies on the Web.
* [yamlpyowl](https://github.com/cknoll/yamlpyowl) - Python based YAML-to-OWL-converter.

Generic RDF tools:

* [Tarql](https://tarql.github.io/) - Python tool to turn CSV into RDF using SPARQL syntax.
* [VocPrez](https://github.com/RDFLib/VocPrez/) - Python tool (API and web front-end) for the read-only delivery system of SKOS vocabularies.

## Datastore

* [SciGraph](https://github.com/SciGraph/SciGraph) - Neo4j backed ontology store.

## Languages

* [Common Logic (CL)](https://en.wikipedia.org/wiki/Common_Logic) - A language with an abstract syntax and semantics which are given in the ISO standard.
  * Common Logic Interchange Format (CLIF)
  * Conceptual Graph Interchange Format (CGIF)
  * eXtended Common Logic Markup Language (XCL)
* [CycL](http://www.cyc.com/documentation/ontologists-handbook/cyc-basics/syntax-cycl/) - A language with a concrete syntax based on first-order predicate calculus and Lisp.
* Knowledge Interchange Format (KIF) -
* [OBO Format (OBOF)](http://purl.obolibrary.org/obo/oboformat/spec.html) - A language used in the OBO Foundry with a concrete syntax and semantics which maps the language to OWL2-DL.
* [OWL 2 Web Ontology Language](https://www.w3.org/TR/owl2-overview/) - A language with [an abstract syntax](https://www.w3.org/TR/owl2-syntax/) and [semantics](https://www.w3.org/TR/owl2-direct-semantics/). It has a few defined (reserved) vocabulary terms (see [2.4, Table 3](https://www.w3.org/TR/owl2-syntax/) and [2.2](https://www.w3.org/TR/owl2-direct-semantics/)). The language is compatible with RDF by [the mapping between the OWL 2 language and the RDF language](https://www.w3.org/TR/owl2-mapping-to-rdf/). It can be extended with Description Logics (see [Logics](#logics)).
  * Manchester Syntax
  * OWL/XML
* [RDF (Resource Description Framework) 1.1](https://en.wikipedia.org/wiki/Resource_Description_Framework) - A language with [an abstract syntax (a data model)](https://www.w3.org/TR/rdf11-concepts/) based on the subject-predicate-object triple and [semantics](https://www.w3.org/TR/rdf11-mt/). For no vocabulary is defined in itself, it is used with RDF Schema vocabulary (see [Vocabularies](#vocabularies)).
  * [HDT](http://www.rdfhdt.org/) (2010~)
  * [JSON-LD](https://en.wikipedia.org/wiki/JSON-LD) (2010~)
  * [Notation3](https://en.wikipedia.org/wiki/Notation3) (N3) (2008~)
  * [N-Quads](https://en.wikipedia.org/wiki/N-Triples#N-Quads) (2014~)
  * [N-Triples](https://en.wikipedia.org/wiki/N-Triples) (2001/2014~)
  * [RDFa](https://en.wikipedia.org/wiki/RDFa) (2004~)
  * [RDF/XML](https://en.wikipedia.org/wiki/RDF/XML) (2002/2004~)
  * [TriG](https://en.wikipedia.org/wiki/TriG_(syntax)) (2007/2014~)
  * [TriX](https://en.wikipedia.org/wiki/TriX_(serialization_format)) (2004~, inactive)
  * [Turtle](https://en.wikipedia.org/wiki/Turtle_(syntax)) ([2004](https://www.w3.org/TeamSubmission/2008/SUBM-turtle-20080114/#sec-acks)/2014~)
  * [RDF*](https://w3c.github.io/rdf-star/) (generic extension of RDF, 2019~)

Archived or inactive:

* KL-ONE
* [Loom](https://www.isi.edu/isd/LOOM/)
* [Nanotation](https://www.w3.org/community/rww/wiki/Nanotation) (2014, inactive)

See also:

* [Logics](#logics) section of this list
* [Ontology language](https://en.wikipedia.org/wiki/Ontology_language) in Wikipedia

## Ontologies and Vocabularies

See also:

* [Lists of ontologies](https://www.w3.org/wiki/Lists_of_ontologies) in W3C Wiki - A short meta-list of lists of ontologies.
* [Ontology List](http://info.slis.indiana.edu/~dingying/Teaching/S604/OntologyList.html) by Ying Ding.
* [Protege Ontology Library](https://protegewiki.stanford.edu/wiki/Protege_Ontology_Library) in Protege Wiki - Listing 100+ ontologies.
* [KBS/Ontology Projects Worldwide](http://www.cs.utexas.edu/users/mfkb/related.html) - A List of 300+ ontologies and related resources, maintained by [Peter Clark](http://www.cs.utexas.edu/users/pclark/).
* [Linked Open Vocabularies](https://lov.linkeddata.es/dataset/lov/) -
* [prefix.cc](https://prefix.cc/) - Namespace lookup for RDF developers.
* [The Linked Open Data Cloud](https://lod-cloud.net/) -
* [BARTOC (Basel Register of Thesauri, Ontologies & Classifications)](https://bartoc.org) - Database of Knowledge Organization Systems and KOS related Registries, developed by the Basel University Library, Switzerland.
* <http://www.ontologydesignpatterns.org/ont/> in [OntologyDesignPatterns.org](http://ontologydesignpatterns.org/) (ODP)

### Upper-level Ontologies

* [BFO (Basic Formal Ontology)](http://basic-formal-ontology.org/) - A small, upper level ontology that is designed for use in supporting information retrieval, analysis and integration in scientific and other domains.
* [DBpedia Ontology](https://wiki.dbpedia.org/services-resources/ontology) - A shallow, cross-domain ontology, which has been manually created based on the most commonly used infoboxes within Wikipedia.
* [DOLCE (Descriptive Ontology for Linguistic and Cognitive Engineering)](http://www.loa.istc.cnr.it/dolce/overview.html) - A foundational ontology originally developed in WonderWeb project. ([old page](https://web.archive.org/web/20180716182415/http://www.loa.istc.cnr.it/old/DOLCE.html))
* [GFO (General Formal Ontology)](http://www.onto-med.de/ontologies/gfo/) - A top-level ontology for conceptual modeling, which is being constantly further developed by Onto-Med.
* [KYOTO 3 Top](http://kyoto-project.eu/xmlgroup.iit.cnr.it/kyoto/index8d0f.html?option=com_content&view=article&id=390&Itemid=155) - An ontology which extends DOLCE-Lite Plus (DLP). It consists of ~50 classes.
* [SUMO (Suggested Upper Merged Ontology)](http://www.adampease.org/OP/) -
* [YAMATO (Yet Another More Advanced Top-level Ontology)](http://download.hozo.jp/onto_library/upperOnto.htm) -

Archived or inactive:

* [UMBEL (Upper Mapping and Binding Exchange Layer)](http://umbel.org/) Vocabulary (UMBEL ontology) (merged to KBpedia in 2019) - An ontology consists of ~70 classes.

### Mid-level Ontologies

* [KYOTO 3 Middle](http://kyoto-project.eu/xmlgroup.iit.cnr.it/kyoto/index8d0f.html?option=com_content&view=article&id=390&Itemid=155) - An ontology which consists of ~350 classes.
* [MILO (Mid-Level Ontology)](https://github.com/ontologyportal/sumo/blob/master/Mid-level-ontology.kif) in [SUMO](http://www.adampease.org/OP/) -
* [UMBEL (Upper Mapping and Binding Exchange Layer)](http://umbel.org/) Reference Concepts (Reference Concepts ontology) -

### Cross-domain Ontologies

#### Large

* [ConceptNet](http://conceptnet.io/) - An open, multilingual knowledge graph.
* [Cyc](https://www.cyc.com/) ([OpenCyc](http://www.cyc.com/opencyc/)/[ResearchCyc](http://www.cyc.com/researchcyc/)) - A knowledge base which contains more than 630,000 concepts.
* [DBpedia](https://wiki.dbpedia.org/) - A crowd-sourced community effort to extract structured content from the information created in various Wikimedia projects.
* [KBpedia](http://kbpedia.org/) - A comprehensive knowledge structure for promoting data interoperability and knowledge-based artificial intelligence (KBAI). It combines Wikipedia, Wikidata, schema.org, DBpedia, GeoNames, OpenCyc, and UMBEL.
* [Mosaic Knowledge Graphs](https://mosaickg.apps.allenai.org/) - ATOMIC + ConceptNet combination by AllenAI.
* [NELL ontology and knowledge base](http://nell-ld.telecom-st-etienne.fr/) - An ontology developed by the Never-Ending Language Learning (NELL) project.
* [Wikidata](https://www.wikidata.org/) - A free and open knowledge base that can be read and edited by both humans and machines. It contains more than 55,000,000 data items.
* [WordNet](https://wordnet.princeton.edu/) - A large lexical database of English. It consists of ~117,000 synsets (groups of synonyms).
* [YAGO](https://www.mpi-inf.mpg.de/departments/databases-and-information-systems/research/yago-naga/yago/) - A huge semantic knowledge base, derived from Wikipedia WordNet and GeoNames. It has knowledge of more than 10 million (10,000,000) entities.
* [Xlore](https://xlore.org/) - A large-scale multilingual knowledge graph by structuring and integrating Chinese Wikipedia, English Wikipedia, French wikipedia, and Baidu Baike.

Without explicit classes:

* [Billion Triple Challenge (BTC) 2019 Dataset](https://zenodo.org/record/2634588) - A result of a large-scale RDF crawl (accepting RDF/XML, Turtle and N-Triples) conducted from 2018/12/12 until 2019/01/11 using LDspider.

Archived or inactive:

* [Freebase](https://developers.google.com/freebase/) (shut down in 2016) -
* [MindNet](https://www.microsoft.com/en-us/research/project/mindnet/) (~2001?) - ... by Microsoft.
* [SENSUS](https://www.isi.edu/natural-language/resources/sensus.html) -
* [Mikrokosmos]() -

See also:

* [Open Multilingual Wordnet](http://compling.hss.ntu.edu.sg/omw/) - A list of open wordnets in a variety of languages, all linked to the Princeton WordNet of English (PWN).

#### Small to Medium

* [KYOTO 3 Domain](http://kyoto-project.eu/xmlgroup.iit.cnr.it/kyoto/index8d0f.html?option=com_content&view=article&id=390&Itemid=155) - An ontology which consists of ~1900 classes.

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
* [FoodOn](https://foodon.org/) - An ontology built to interoperate with the OBO Library and to represent entities which bear a "food role".

#### Geography

* [Geographical Entity Ontology](http://www.obofoundry.org/ontology/geo.html) - An ontology of geographical entities implemented in OWL 2 and based on Basic Formal Ontology (BFO).

#### Humanities

See:

* [CLARIAH/awesome-humanities-ontologies](https://github.com/CLARIAH/awesome-humanities-ontologies) - A curated list of ontologies for Digital Humanities.

#### Legal

See:

* [Liquid-Legal-Institute/Legal-Ontologies](https://github.com/Liquid-Legal-Institute/Legal-Ontologies) - A list of selected resources, methods, and tools dedicated to legal data schemes and ontologies.

#### News

* [rNews](http://dev.iptc.org/rNews) - An approved standard for using semantic markup to annotate news-specific metadata in HTML documents.

#### People

* [Friend Of A Friend (FOAF)](http://www.foaf-project.org/) - A computer language defining a dictionary of people-related terms that can be used in structured data.
* [vCard Ontology](https://www.w3.org/TR/vcard-rdf/) - An ontology for describing people and organizations. A mapping of the vCard specification (RFC6350) to RDF/OWL.

### Vocabularies

> A vocabulary is a set of terms for a language.

* [Dublin Core Metadata Element Set](http://dublincore.org/documents/dces/) - A vocabulary of fifteen properties for use in resource description.
* [DCMI Metadata Terms](http://dublincore.org/documents/dcmi-terms/) - An extension of the Dublin Core Metadata Element Set.
* [IMI (Infrastructure for Multilayer Interoperability) Core Vocabulary](https://imi.go.jp/goi/imi-about-en) - A Japanese controlled vocabulary consists of roughly 60 class concepts, 250 property concepts and words associated to them.
* [Open Graph protocol](http://ogp.me/) -
* [RDF Schema (RDFS) 1.1](https://www.w3.org/TR/rdf-schema/) - A data-modelling RDF vocabulary used for defining RDF vocabularies.
* [SKOS (Simple Knowledge Organization System)](https://www.w3.org/TR/skos-reference/) - An RDF vocabulary for representing semi-formal knowledge organization systems (KOSs), such as thesauri, taxonomies, classification schemes and subject heading lists.
* [Schema.org Schemas](https://schema.org/docs/full.html) -

## Alignment & Matching

- [AgreementMakerLight (AML)](https://github.com/AgreementMakerLight/AML-Project) - Ontology matching system developed by LASIGE (FCUL, Portugal) in collaboration with the ADVIS Lab (UIC, USA).
- [LogMap](https://github.com/ernestojimenezruiz/logmap-matcher) - Highly scalable ontology matching system with "built-in" reasoning and inconsistency repair capabilities.
- [OntoEMMA](https://github.com/allenai/ontoemma) -  Ontology matcher by AllenAI.

See also:

- [Ontology Matching](http://www.ontologymatching.org/index.html) website - Hosting OM (International Workshop on Ontology Matching) and OAEI (Ontology Alignment Evaluation Initiative).
- [Alignment API](http://alignapi.gforge.inria.fr/) - Ontology Alignment API specification. (implemented in Java)

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
* [Hoolet](http://owl.man.ac.uk/hoolet/) (last updated 2004) - An implementation of an OWL-DL reasoner that uses a first order prover. It uses the Vampire prover for reasoning purposes. Other reasoners could also be used; communication with the reasoner is via the TPTP format which is understood by a number of theorem provers.
* [KAON2](http://kaon2.semanticweb.org/) reasoner (last updated 2008) - A DL reasoner for the SHIQ(D) subset of OWL-DL, based on novel algorithms which reduce a SHIQ(D) knowledge base to a disjunctive datalog program. (proprietary, Java)
* [Pellet 2](https://github.com/stardog-union/pellet) (last updated ~2015) - An open source OWL DL reasoner for Java. Pellet 3 (proprietary) is embedded in the [Stardog](https://www.stardog.com/) platform. (Java)

See also:

* [How does a reasoner work?](http://ontogenesis.knowledgeblog.org/1486) - An introductory article by Uli Sattler, Robert Stevens, and Phillip Lord

## Querying

* [DL Query (class expression)](https://protegewiki.stanford.edu/wiki/DLQueryTab) - A query language supported by the DL Query tab plugin for Protégé based on the Manchester OWL syntax.
* [SPARQL 1.1](https://www.w3.org/TR/sparql11-query/) - A set of specifications that provide languages and protocols to query and manipulate RDF graph content on the Web or in an RDF store.
  * [SPARQL-DL](http://ceur-ws.org/Vol-258/paper14.pdf) - A substantial subset of SPARQL that can be covered by the standard reasoning services OWL-DL reasoners provide. It is implemented in the Pellet reasoner.
  * [SPARQL-OWL algorithm](http://ceur-ws.org/Vol-796/owled2011_submission_4.pdf) - A sound and complete algorithm for answering SPARQL-OWL, SPARQL queries under the OWL 2 Direct Semantics entailment regime.
  * [SPARQL*](https://w3c.github.io/rdf-star/#sparql-query-language) - An RDF*-aware extension of the RDF query language SPARQL.

See also:

* [[protege-user] which is the best query language for owl ontologies?](https://mailman.stanford.edu/pipermail/protege-user/2016-August/004995.html)

## Rule and Schema Definition

* [SHACL (Shapes Constraint Language)](https://en.wikipedia.org/wiki/SHACL)
* [ShEx (Shape Expressions)](https://en.wikipedia.org/wiki/ShEx)
* [SWRL (Semantic Web Rule Language)](https://www.w3.org/Submission/SWRL/) - A rule markup language which extends the logical expressivity of the OWL language.

Archived or inactive:

* [SPIN (SPARQL Inferencing Notation)](http://spinrdf.org/) (virtually succeeded by SHACL, see [From SPIN to SHACL](https://spinrdf.org/spin-shacl.html))

## Programming

See also: [Ontology Tools](#ontology-tools) section.

### OWL-aware libraries

* [Apache Jena Ontology API](https://jena.apache.org/documentation/ontology/) -
* [OWL API](http://owlcs.github.io/owlapi/) - A Java API for creating, manipulating and serializing OWL Ontologies.
* [Owlready2](https://owlready2.readthedocs.io/) - A module for ontology-oriented programming in Python.

Archived or inactive:

* [OPPL](http://oppl2.sourceforge.net/) - An abstract formalism that allows for manipulating ontologies written in OWL.

## Communities

* [Ontology Alignment Evaluation Initiative](http://oaei.ontologymatching.org/) (OAEI)
* [Association for Ontology Design & Patterns](http://ontologydesignpatterns.org/wiki/ODPA) (ODPA)

## Related

* [semantalytics/awesome-semantic-web](https://github.com/semantalytics/awesome-semantic-web) - A curated list of various semantic web and linked data resources.
* [jbenner-radham/awesome-semantic-web](https://github.com/jbenner-radham/awesome-semantic-web) - A curated list of various semantic web and linked data resources.
* [totogo/awesome-knowledge-graph](https://github.com/totogo/awesome-knowledge-graph) - A curated list of Knowledge Graph related learning materials, databases, tools and other resources.
* [Materials-Data-Science-and-Informatics/awesome-fair-data](https://github.com/Materials-Data-Science-and-Informatics/awesome-fair-data) - A curated list of awesome stuff around the FAIR principles for (scientific) data, i.e that data is findable, accessable, interoperable and re-usable.
* [pysemtec/semantic-python-overview](https://github.com/pysemtec/semantic-python-overview) - A (subjective) overview of projects which are related both to python and semantic technologies (RDF, OWL, Reasoning, ...).

Archived or inactive:

* [buaaliuming/Awesome-Knowledge-Bases](https://github.com/buaaliuming/Awesome-Knowledge-Bases) - Available knowledge bases, Ontology, Knowledge Graph or taxonomy.
* [costezki/awesome-semantic-tools](https://github.com/costezki/awesome-semantic-tools) - List of projects related to Ontology engineering and Semantic Web technologies that make a geek smile for they exist.
* [KMax/awesome-semantic-web-business](https://github.com/KMax/awesome-semantic-web-business) - A curated list of awesome resources that feature usages of Semantic Web technologies in business cases (applications).
