---
layout: slim
title: "Home"
permalink: /
---
![](images/RDFlib-250.png)

# RDFlib
RDFLib is a pure Python package for working with [RDF](http://www.w3.org/RDF/). RDFLib contains most things you need to work with RDF, including:

* parsers and serializers
    * for RDF/XML, N3, NTriples, N-Quads, Turtle, TriX, Trig and JSON-LD & HexTuples
* a Graph interface which can be backed by any one of a number of Store implementations
* many store implementations 
    * in-memory, persistent on disk (Berkeley DB) and remote SPARQL endpoints
* a SPARQL 1.1 implementation
    * supporting SPARQL 1.1 Queries and Update statements
* SPARQL function extension mechanisms

Many 3rd party packages support additional stores, parsers etc.

## RDFlib Family of packages
The RDFlib community maintains many RDF-related Python code repositories with different purposes. Most of the currently
operating packages are shown in Figure 1.

![](images/rdflib-packages.png)  
**Figure 1**: Packages within the RDFlib family.

* **Core**:
    * [rdflib](https://github.com/RDFLib/rdflib) - the rdflib core

* **Parsers/Serializers**:
   * RDFlib:
       * [pymicrodata](https://github.com/RDFLib/pymicrodata) - This a module to extract RDF from an HTML5 page annotated with microdata
       * [pyrdfa3](https://github.com/RDFLib/pyrdfa3) - RDFa 1.1 distiller/parser library: can extract RDFa 1.1 (and RDFa 1.0, if properly set via a @Version attribute) from (X)HTML, SVG, or XML
   * 3rd party:
       * [FunOWL](https://github.com/hsolbrig/funowl) - Functional Syntax

* **Stores**:   
    * RDFlib:  
       * [rdflib-hdt](https://github.com/RDFLib/rdflib-hdt) - A Store back-end for rdflib to allow for reading and querying HDT documents
       * [rdflib-zodb](https://github.com/RDFLib/rdflib-zodb) - RDFLib Store backed by ZODB3
       * [rdflib-kyotocabinet](https://github.com/RDFLib/rdflib-kyotocabinet) - RDFLib Store backed by Kyoto Cabinet
       * [rdflib-leveldb](https://github.com/RDFLib/rdflib-leveldb) - A LevelDB based Store for rdflib
       * [rdflib-sqlalchemy](https://github.com/RDFLib/rdflib-sqlalchemy) - RDFLib store using SQLAlchemy dbapi as back-end
    * 3rd party:
       * [Neo4J](https://github.com/neo4j-labs/rdflib-neo4j) - using Neo4J as a back-end. Even support RDF-Star

* **SPARQL tools**:
    * [sparqlwrapper](https://github.com/RDFLib/sparqlwrapper) - a simple Python wrapper around a SPARQL service to remotely execute your queries

* **OWL Reasoning & Documentation**:    
    * [OWL-RL](https://github.com/RDFLib/OWL-RL) - A simple implementation of the OWL2 RL Profile on top of RDFLib
    * [pyLODE](https://github.com/RDFLib/pyLODE) - An OWL ontology documentation tool using Python and templating, based on LODE.

* **SHACL validation**:
    * [pySHACL](https://github.com/RDFLib/pySHACL) - A Python validator for SHACL

* **Linked Data APIs**:
    * [pyLDAPI](https://github.com/RDFLib/pyLDAPI) - A very small module to add Linked Data API functionality to a Python Flask installation

* **Derived tools**:  
    * [VocPrez](https://github.com/RDFLib/VocPrez) - A tool (API and web front-end), based on pyLDAPI, for the read-only delivery system of SKOS vocabularies.

Please see the list of all packages here:

* <https://github.com/RDFLib>


## Documentation
See <https://rdflib.readthedocs.io> for our documentation built from the code.


## Releases
*rdflib 6.1.1 is the current release and small releases with small improvements are planned every other month*

**Release** | **Date** | **Note**
--- | --- | ---
**7.0.0** | **01 Aug 2023** | **Major Stable release**<br /> Current [`master` branch in GitHub](https://github.com/RDFLib/rdflib/)* <br />Documentation: [readthedocs/latest](https://rdflib.readthedocs.io/en/latest/)
6.3.2 | 26 Mar 2023 | Patch Stable release<br /> Release of `master` as of 26 Mar 2023. <br />Documentation: [readthedocs/6.3.2](https://rdflib.readthedocs.io/en/6.3.2/)
6.3.1 | 18 Mar 2023 | Patch Stable release<br /> Release of `master` as of 18 Mar 2023. <br />Documentation: [readthedocs/6.3.1](https://rdflib.readthedocs.io/en/6.3.1/)
6.3.0 | 16 Mar 2023 | Minor Stable release<br /> Release of `master` as of 16 Mar 2023. <br />Documentation: [readthedocs/6.3.0](https://rdflib.readthedocs.io/en/6.3.0/)
6.2.0 | 16 Jul 2022 | Minor Stable release<br /> Release of `master` as of 16 Jul 2022. <br />Documentation: [readthedocs/6.2.0](https://rdflib.readthedocs.io/en/6.2.0/)
6.1.1 | 12 Dec 2021 | Minor Stable release<br />Release of `master` as of 12 Dec 2021. <br />Documentation: [readthedocs/stable](https://rdflib.readthedocs.io/en/6.1.1/)
6.0.2 | 10 Oct 2021 | Patch stable release<br />Release of `master` as of 10 Oct 2021. <br />Documentation: [readthedocs/6.0.1](https://rdflib.readthedocs.io/en/6.0.2/)
6.0.1 | 17 Sep 2021 | Patch stable release<br />Release of `master` as of 17 Sep 2021. <br />Documentation: [readthedocs/6.0.1](https://rdflib.readthedocs.io/en/6.0.1/)
6.0.0 | 20 Jul 2021 | Major stable release<br />Release of `master` as of 20 Jul 2021. <br />Documentation: [readthedocs/6.0.0](https://rdflib.readthedocs.io/en/6.0.0/)
5.0.0 | 18 Apr 2020 | Previous stable release<br />Release of `master` contents as of 18 Apr 2020<br />Last release with Python 2 & 3.4 support<br />Documentation: [readthedocs/5.0.0](https://rdflib.readthedocs.io/en/5.0.0/)
5.0.0RC1 | 04 Apr 2020 | This was a pre-release of all changes in `master` as of 04 Apr 2020
4.2.2 | 30 Jan 2017 | Previous stable release<br />Documentation: [readthedocs/4.2.2](https://rdflib.readthedocs.io/en/4.2.2/)
... | ... | ...
1.1.1 | 12 Nov 2002 | First release!


## Contributing
rdflib survives and grows via user contributions! Please consider lodging Pull Requests here:

* <https://github.com/RDFLib/rdflib/pulls>

You can also raise issues here:

* <https://github.com/RDFLib/rdflib/issues>


## Support & Contacts
For general "how do I..." queries, please use https://stackoverflow.com and tag your question with `rdflib`.
Existing questions:

* <https://stackoverflow.com/questions/tagged/rdflib>

If you want to contact the rdflib maintainers, please do so via:

* the rdflib-dev mailing list: <https://groups.google.com/group/rdflib-dev>
* the chat, which is available at [gitter](https://gitter.im/RDFLib/rdflib) or via matrix [#RDFLib_rdflib:gitter.im](https://matrix.to/#/#RDFLib_rdflib:gitter.im)
