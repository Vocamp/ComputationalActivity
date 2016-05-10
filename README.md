# Computational Activity Ontology Design Pattern

An [ontology design pattern](http://ontologydesignpatterns.org/wiki/Main_Page) to capture the notion of a activity performed by a computational agent (I.E. Software Agent). The idea is to model a particular occurrence of an actual computational processing activity (rather than a recipe/template/etc. for how to conduct a computation). We include the word "processing" because we focus specifically on computational activities that process input data to produce output data. Computational activities that do not do this are out of scope. A complementary pattern to Computational Activity that captures the notion of a Computational Environment that provides affordances (to model the hardware, operating system, and software present) for a Computational Activity is also included as a separate pattern. The pattern was developed using High Energy Physics analysis workflows as a reference pattern application. It is also designed to be compatible with the W3C Prov-O Ontology [Specification](https://www.w3.org/TR/prov-o/).

Initial development of the pattern was conducted during the [VocampND2015](http://vocamp.org/wiki/VoCampND2015) Vocamp as part of the NSF funded [DASPOS](https://daspos.crc.nd.edu/) effort.

A [concept map](https://github.com/Vocamp/ComputationalActivity/blob/master/concept-map/computationalActivity.pdf) is in the concept-map folder and outlines the basic classes that are part of the pattern. Implementation of the pattern in RDF-XML OWL, Turtle and JSON-LD context file is in the pattern subdirectory.