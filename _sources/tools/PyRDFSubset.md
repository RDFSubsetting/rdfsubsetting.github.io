PyRDFSubset
===========
PyRDFSubset is a tool to extract a subset of a RDF graph. It is written in Python and uses the RDFLib and PyShex library.

# Installation
'pip install pyrdfsubset'

# Usage
pyrdfsubset contains two functions:
* rdfsubset: This function takes a RDF graph and a Shape Expression as input and returns a subset of the RDF graph that conforms to the Shape Expression.
* sparqlsubset: This function takes a SPARQL query and a Shape Expression as input and return a subset of the RDF graph that contains the return values of the SPARQL query and conforms to the Shape Expression.

# Links
Pypi: https://pypi.org/project/pyrdfsubset/
Github:https://github.com/micelio/PyRDFSubSet

# Future work
* Add support for closed subsets
* Add support for more complex or hierarchial Shape Expressions
* Identify ShEx patterns from many RDF graphs that can be used as building blocks for Shape Expressions that in turn can be used in subsetting
* Provide Jupyter Notebooks that show how to use PyRDFSubset

# Acknowledgements
This work started during the Biohackathon in Japan in 2023. 
