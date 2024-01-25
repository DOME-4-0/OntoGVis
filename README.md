# OntoGVis
An ontology Visualisation utility for DOME 4.0 
# Will inlcude the code developed by UCL in OntoManager as well as new tools developed by EPFL 

## The Pyvis based tools 

WIP (UCL) 

## The Networkx  based Tools 
WIP (UCL) 


## The Pydotplus tools

WIP (UCL)

## VIsJS native solution for the front end (native as in HTML..) 
- check https://visjs.github.io/vis-network/examples/


# The user story

- A user enters one, two, or three text keywords 
  - each keyword is interpreted as, s, p, o repsectively
  - UCL provides a sparql query that takes these keywords and returns a set of results as a json LD).
  - We assume for visualisation that we have a data of the form: Node, Arc, Node, but with multiple ARC's possible between each two nodes.
- The user is presented with a result of the query as a graph (using visjs)
- The user can focus on a node, and filter ARC's (properties)
- The user can hoover over a nod/arc and get a box with additional attributes

## TODO
see issues± 

