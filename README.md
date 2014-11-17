# SemVis - A Visualization Tool for the Semantic Web

## Description
Today's Web visualization tools are often doing the assumption that the
data to visualize is already well-formatted, clean and exhaustive, without
taking care of their provenance. **SemVis** is a JS library that intends
to help provide data to visualize by querying the
[Linked Open Data cloud](http://lod-cloud.net/), a set of interconnected
open-access databases (like [DBpedia](dbpedia.org/)).

It should interface with any database in the LOD cloud and its design
should make it possible to use with any visualization tool, even though
it will first strongly rely on [D3.js](http://d3js.org/). **SemVis** should
be able to retrieve, re-format and agregate RDF data according to given
properties that will be visually encoded in a chart/graph.

## TODO
* find as many examples of infographics as possible and try out SPARQL
queries formulation to gather the same data.
* first iteration: program all examples (query, D3 configuration)
* second iteration: design a program that abstracts all examples in a
framework fashion
