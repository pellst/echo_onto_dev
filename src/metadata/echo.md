---
layout: ontology_detail
id: echo
title: echo onto dev
jobs:
  - id: https://travis-ci.org/pellst/echo
    type: travis-ci
build:
  checkout: git clone https://github.com/pellst/echo.git
  system: git
  path: "."
contact:
  email: 
  label: 
  github: 
description: echo onto dev is an ontology...
domain: stuff
homepage: https://github.com/pellst/echo
products:
  - id: echo.owl
    name: "echo onto dev main release in OWL format"
  - id: echo.obo
    name: "echo onto dev additional release in OBO format"
  - id: echo.json
    name: "echo onto dev additional release in OBOJSon format"
  - id: echo/echo-base.owl
    name: "echo onto dev main release in OWL format"
  - id: echo/echo-base.obo
    name: "echo onto dev additional release in OBO format"
  - id: echo/echo-base.json
    name: "echo onto dev additional release in OBOJSon format"
dependencies:
- id: bfo
- id: ro
- id: uberon

tracker: https://github.com/pellst/echo/issues
license:
  url: http://creativecommons.org/licenses/by/3.0/
  label: CC-BY
activity_status: active
---

Enter a detailed description of your ontology here. You can use arbitrary markdown and HTML.
You can also embed images too.

