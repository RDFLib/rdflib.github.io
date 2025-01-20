---
layout: slim
title: "Home"
permalink: /
---
![](images/RDFlib-250.png)

# RDFlib
RDFLib is a pure Python package for working with [RDF](http://www.w3.org/RDF/). RDFLib contains most things you need to work with RDF, including:

* parsers and serializers for RDF/XML, N3, NTriples, N-Quads, Turtle, TriX, Trig, JSON-LD and even HexTuples
* a Graph interface which can be backed by any one of a number of Store implementations
* Store implementations for in-memory, persistent on disk (Berkeley DB) and remote SPARQL endpoints
    * additional Stores can be supplied via plugins 
* a SPARQL 1.1 implementation - supporting SPARQL 1.1 Queries and Update statements
* SPARQL function extension mechanisms

Many 3rd party packages support additional Stores, parsers etc.

## RDFLib Family of packages
The RDFLib community maintains many RDF-related Python code repositories with different purposes. Most of the currently
operating packages are shown here:

![](images/rdflib-packages.png)  

* **Core**:
    * [rdflib](https://github.com/RDFLib/rdflib) - the rdflib core

* **Stores**:   
    * RDFLib:  
       * [rdflib-sqlalchemy](https://github.com/RDFLib/rdflib-sqlalchemy) - RDFLib store using SQLAlchemy dbapi as back-end
       * [rdflib-hdt](https://github.com/RDFLib/rdflib-hdt) - A Store back-end for rdflib to allow for reading and querying HDT documents
       * [rdflib-zodb](https://github.com/RDFLib/rdflib-zodb) - RDFLib Store backed by ZODB3
       * [rdflib-kyotocabinet](https://github.com/RDFLib/rdflib-kyotocabinet) - RDFLib Store backed by Kyoto Cabinet
       * [rdflib-leveldb](https://github.com/RDFLib/rdflib-leveldb) - A LevelDB based Store for rdflib 
    * 3rd party:
       * [Neo4J](https://github.com/neo4j-labs/rdflib-neo4j) - using Neo4J as a back-end. Even support RDF-Star

* **Parsers/Serializers**:
   * RDFLib:
       * [pymicrodata](https://github.com/RDFLib/pymicrodata) - This a module to extract RDF from an HTML5 page annotated with microdata (archived)
       * [pyrdfa3](https://github.com/RDFLib/pyrdfa3) - RDFa 1.1 distiller/parser library: can extract RDFa 1.1 (and RDFa 1.0, if properly set via a @Version attribute) from (X)HTML, SVG, or XML (archived)
   * 3rd party:
       * [FunOWL](https://github.com/hsolbrig/funowl) - Functional Syntax

* **SPARQL tools**:
    * [sparqlwrapper](https://github.com/RDFLib/sparqlwrapper) - a simple Python wrapper around a SPARQL service to remotely execute your queries

* **OWL Reasoning & Documentation**:    
    * [OWL-RL](https://github.com/RDFLib/OWL-RL) - A simple implementation of the OWL2 RL Profile on top of RDFLib
    * [pyLODE](https://github.com/RDFLib/pyLODE) - An OWL ontology documentation tool using Python and templating, based on LODE.

* **SHACL validation**:
    * [pySHACL](https://github.com/RDFLib/pySHACL) - A Python validator for SHACL

* **Linked Data APIs**:
    * [Prez](https://github.com/RDFLib/prez) - A data-configurable Linked Data API framework that delivers profiles of Knowledge Graph data according to the [Content Negotiation by Profile](https://w3c.github.io/dx-connegp/connegp/) standard

Please see the list of all packages here:

* <https://github.com/RDFLib>


## Documentation

RDFLib's code repository, <https://github.com/rdflib/rdflib/>, contains some intro documentation in it's README page, 
which is replicated to RDFLib's PyPI page, <https://pypi.org/project/rdflib/>.

RDFLib also contains a set of documented examples in the [`example/`](https://github.com/RDFLib/rdflib/tree/main/examples)
folder within the code repository.

However, the main source of RDFLib documentation is online at <https://rdflib.readthedocs.io>. That contains pages hand written 
by RDFLib contributors and auto-generated pages from the RDFLib codes.


## Releases
7.1.3 is the current release (Jan, 2025) and a major release of a version 8 is expected in the first half of 2025.

some major historical releases of RDFLib are:

| **Release** | **Date**    | **Note**                                                                                  |
|-------------|-------------|-------------------------------------------------------------------------------------------|
| 7.1.3       | 10 Jan 2025 | Minor updates on 7.0.0 including deterministic serialisation, improved type hinting etc.  |
| 7.0.0       | 02 Aug 2023 | A major release with relatively slight breaking changes, new features and bug fixes       |
| 6.0.0       | 20 Jul 2021 | The next major update with lots of auto-update PRs from dependabot etc                    |
| 5.0.0       | 18 Apr 2020 | The first update in many years. Very compatible with 4.2.2                                |
| 4.2.2       | 30 Jan 2017 | A stable release used widely for many years                                               |
| ...         | ...         | ...                                                                                       |
| 1.1.1       | 12 Nov 2002 | First release!                                                                            |

See the [CHANGELOG](https://github.com/RDFLib/rdflib/blob/main/CHANGELOG.md) in the code repository for full details.

## Contributing
RDFLib survives and grows via user contributions! Please consider lodging Pull Requests here:

* <https://github.com/RDFLib/rdflib/pulls>

You can also raise issues here:

* <https://github.com/RDFLib/rdflib/issues>


## Support & Contacts
For general "how do I..." queries, please use https://stackoverflow.com and tag your question with `rdflib`.
Existing questions:

* <https://stackoverflow.com/questions/tagged/rdflib>

If you want to contact the RDFLib maintainers, please do so via:

* the rdflib-dev mailing list: <https://groups.google.com/group/rdflib-dev>
* the chat, which is available at [gitter](https://gitter.im/RDFLib/rdflib) or via matrix [#RDFLib_rdflib:gitter.im](https://matrix.to/#/#RDFLib_rdflib:gitter.im)
