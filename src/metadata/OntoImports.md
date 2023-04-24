---
layout: ontology_detail
id: OntoImports
title: External imports ontology
jobs:
  - id: https://travis-ci.org/OpenLHS/OntoImports
    type: travis-ci
build:
  checkout: git clone https://github.com/OpenLHS/OntoImports.git
  system: git
  path: "."
contact:
  email: 
  label: 
  github: 
description: External imports ontology is an ontology...
domain: stuff
homepage: https://github.com/OpenLHS/OntoImports
products:
  - id: OntoImports.owl
    name: "External imports ontology main release in OWL format"
  - id: OntoImports.obo
    name: "External imports ontology additional release in OBO format"
  - id: OntoImports.json
    name: "External imports ontology additional release in OBOJSon format"
  - id: OntoImports/OntoImports-base.owl
    name: "External imports ontology main release in OWL format"
  - id: OntoImports/OntoImports-base.obo
    name: "External imports ontology additional release in OBO format"
  - id: OntoImports/OntoImports-base.json
    name: "External imports ontology additional release in OBOJSon format"
dependencies:
- id: bfo
- id: ro
- id: obi
- id: iao

tracker: https://github.com/OpenLHS/OntoImports/issues
license:
  url: http://creativecommons.org/licenses/by/3.0/
  label: CC-BY
activity_status: active
---

Enter a detailed description of your ontology here. You can use arbitrary markdown and HTML.
You can also embed images too.

