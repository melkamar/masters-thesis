# Martin Melka
## Framework for mobile applications using Linked Data and the RÚIAN registry

The contents of this repository/folder form my Master's Thesis for the Faculty of Information Technology at Czech Technical University in Prague. Academic year 2017/2018, summer semester.

The thesis advisor is RNDr. Jakub Klímek, Ph.D.

## Keywords
Czech: Linked Data, RÚIAN, Framework, RDF, Android, mapa
English: Linked Data, RÚIAN, Framework, RDF, Android, map

## Contents

- `andruian` - RDF-related data of the framework
  - `andr`
    - `LocationClassPathsSource-ruian.ttl` - the class paths source RDF resource for RÚIAN classes 
    - `schema.ttl` - the Andruian data definition RDF vocabulary
  - `example-data` - RDF data (data definitions and appropriate datasets) illustrating the usage of the framework
- `build` - build artifacts of the individual components
  - `indexer` - the index server
  - `ddfparser-*.jar` - the ddfparser library
  - `viewlink-*.apk` - the ViewLink Android application
- `ddfparser` - sources of the ddfparser library
- `indexer` - sources of the index server
  - `docker` - Docker-related setup files
  - `docs` - generated documentation
  - `solr` - configuration files for Solr
  - `src` - source code of the index server
- `stress-data` - data used for stress-testing the framework
- `thesis` - the source of the thesis document
- `viewlink` - sources of the Android application
- `thesis.pdf` - the thesis
- `thesis-assignment.pdf` - the assignment of the thesis

## Online
- The thesis is publicly available on:
  - [GitHub](https://github.com/melkamar/masters-thesis) as soon as it is formally defended in June of 2018.
  - [CTU digital library](https://dspace.cvut.cz/). Search for the thesis title.