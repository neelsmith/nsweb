
# Overview of Some of My Active `Github` Repositories #

The repositories linked below provide access to current versions and history of projects that have been published as [nexus artifacts here][nexus].

[nexus]: http://beta.hpcc.uh.edu/nexus


## The CITE Architecture ##


-  [cite][1]:  a JVM library for working with CTS URNs, CTS TextInventories, and CITE Object URNs
- [citeservlet][2]:  the CITE services suite implemented in a servlet, and using a SPARQL endpoint for source data.  It is build on top of four implementations of the CITE suite, each using a SPARQL endpoint for source data:
    - sparqlcts: an implementation of CTS
    - [sparqlcc][14]:  an implementation of CITE Collection services
    - [sparqlimg][13]:  an implementation of the CITE Image extension to Collections
    - graph:  a CITE graph server
- [citemgr][4]:  an automated build system (using gradle) for managing CTS, CITE Collection, CITE Image and CITE Index repositories, built on top of the following libraries:
    - [hocuspocus][3]: a system for managing a CTS archive
    - [prestochango][7]:  a system for managing a CITE Collection archive
    - [nysi][8] ("now you see it"): a system for managing a CITE Image archive
    - [abracadabra][9]:  a system for managing a CITE Index archive
 - [ctsvalidator][15]: an automated test suite for evaluating the compliance of a CTS instance with the CTS specification

### Utilities for Writing With URNs ###

Work in progress on `citedown`, that is, markdown extended to support scholarly citation using CITE URNs.  Not yet published as nexus artifacts.

- cd2md:  a generic JVM citedown to markdown utility
- cdweb: a gradle build system using [Christopher Blackwell's CITEkit  library][12] to generate formatted web sites from citedown source 


[12]: https://bitbucket.org/Eumaeus/citekit

[11]: https://github.com/neelsmith/cdweb

[10]: https://github.com/neelsmith/cd2md

### Related Utilities ###

- [greekutils][6]: a JVM library for working with Greek text in various transcription systems, in plain text or as text nodes of XML content

## The Homer Multitext Project ##

- [Archival repository][5]: archival data from the Homer Multitext project.


[15]: https://github.com/neelsmith/ctsvalidator

[14]: https://github.com/neelsmith/sparqlcc

[13]:  https://github.com/neelsmith/sparqlimg

[9]: https://github.com/neelsmith/abracadabra

[8]: https://github.com/neelsmith/nysi

[7]: https://github.com/neelsmith/prestochango

[6]: https://github.com/neelsmith/greekutils

[5]: https://github.com/neelsmith/hmtarchive

[4]: https://github.com/neelsmith/citemgr

[3]: https://github.com/neelsmith/hocuspocus

[1]: https://github.com/neelsmith/cite

[2]: https://github.com/neelsmith/citeservlet