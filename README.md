# Law Typesetting

## Vision

To build an active community engaged in improving Indian laws through
use of a model law typesetting software and to promote legal research
and thinking.

## Principles and guidelines of writing law

The software should follow these principles and guidelines.

* Structured
* Consistent
* Citable
* Portable

## Web presentation

* HTML5 and Javascript
* Resolve cross references and hyperlink them
* Mark amendments
* Offer timeline of amendments
* Pop-up definitions
* Table of contents
* Versioning
* Constitutionality References?

## Print typesetting

* LaTeX PDF output
* Word/ODT

## Backend

### 1. XML Standard: http://www.akomantoso.org/

* Laws will be written in XML using Akomantoso standard as stored as
  valid XML documents.
* Backend engine will process these documents and convert them into
  HTML and LaTeX code.

### 2. Version Control

* Each version of law will be versioned.
* Front-end should be able to list differences between different
  versions based on entities which changed. This is different from
  doing a regular line-based `diff` which tells a user text lines
  which changed.

### 3. Handle Amendment Bills

* Amendment Bills will be passed by the parliament while existing
  versions are getting worked upon by the community. A separate branch
  in version control will keep track of the latest version of the law
  passed in parliament.
