# Knowboard Demo Workspace

This demo shows some of the capabilities of [Knowboard](https://knowboard.dev)
 for organizing a knowledge base.

Once you have [installed Knowboard](https://www.knowboard.dev/tutorial/install/) you can load this demo to explore it features.

## Overview

The information is organized around sample projects:
- [[write-project-documentation]]
- [[record-demo-video]]

There are also documents on reading materials like the [[practical-rdf]] book, and the [[diataxis]] framework for technical documentation.

Projects, books, and articles are each linked to topics like [[documentation]] and [[knowledge-graphs]] which can be used to associate related material.

## [Querying](https://knowboard.dev/tutorial/querying/)

Example SPARQL queries in `queries/` demonstrate patterns for looking up information like [related reading by project](queries/related-reading-by-project.rq).

## Metadata

The `meta/` folder contains files describing the structure of the workspace data.

### [Shapes](https://knowboard.dev/tutorial/shapes/)
`shapes.ttl` - describes the properties used for different types, and what information to show in document previews

### [Context](https://www.knowboard.dev/reference/context/)
`context.yamlld` - provides shorthand names to simplify writing document properties
