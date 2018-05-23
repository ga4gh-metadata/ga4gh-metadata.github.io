---
title: "Assaymetadata: Experiment and Analysis"
layout: default
date: 2018-01-01
permalink: /assaymetadata.html
category: documentation
tags:
  - ga4gh
  - documentation
  - assaymetadata
---

## {{ page.title }}

### Assaymetadata: _Experiment_ Object

_Experiment_ in the GA4GH Metadata Schema

#### Experiment attributes

Attribute | Notes
------ | ------
*id* | <ul><li>the Experiment's id</li><li>unique in the context of the server</li><li>used for referencing this Experiment</li></ul>
*name* | <ul><li>a human readable object label/identifier</li><li>not to be used for referencing</li></ul>
*description* | additional, unstructured information about this Experiment
*created* | the time the record was created, in ISO8601
*updated* | the time the record was updated, in ISO8601
*attributes* | additional, structured information

### AssayMetadata: *Analysis* Object

_Analysis_ in the GA4GH Schema

#### Analysis attributes

Attribute | Notes
--- | ---
*id* | <ul><li>the Analysis's id</li><li>unique in the context of the server</li><li>used for referencing this Analysis</li></ul>
*name* | <ul><li>a human readable object label/identifier</li><li>not to be used for referencing</li></ul>
*description* | additional, unstructured information about this Analysis
*created* | the time the record was created, in ISO8601
*updated* | the time the record was updated, in ISO8601
*attributes* | additional, structured information
