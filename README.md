# forhonorontology
An ontology and knowledge base project for the domain of the For Honor universe

Ontology in the domain of the Ubisoft title [For Honor](https://www.ubisoft.com/en-GB/game/for-honor/). We assume that we are in this fictional universe and we ask about:

- the sorts of entities which exist
- the sorts of relations there are between them. 

We construct a knowledge base about a number of instances falling under the categories we introduce in order to represent knowledge about this domain. 

## Status 

This is a starting prototype for which we carried out:

- informal ontological analysis (or conceptual modelling) 
- superficial knowledge acquisition based on available documentation and in-game content
- a first design of an ontology that could be encoded using the tool Protege and OWL. 

## Content of the repository 

- pictures of conceptual modelling on paper, [page 1](doc/FHO-InitialInformalConceptualModelling-Part1.jpg) and [page 2](doc/FHO-InitialInformalConceptualModelling-Part2.jpg)
- initial OWL encoding covering the sub-categories of Person and the ascription of specific categories to a Faction (instance). This was guided by a graphical formalisation on [paper](doc/FHO-InitialPreOWLEncodingFormalisation.jpg). The initials versions are in the [owl](ontology/owl) directory. Screenshots of FHO-v0.0.3 in Protege illustrate the [class hierarchy](doc/fho-003-ExampleOfClassesAndInstances.png), some instances and a relation as well as a case of [DL query](doc/fho-003-ExampleOfInference.png) where the classes of persons associated with a given factions are derived. 

We used concepts derived from the foundational ontology BFO. 

## TODO 

- Weapons (we could create a database to record a number of relations) 
- Processes (generic actions and move-sets) 

## Open issues 

- Abilities and feats 

## Contributors

fgrenon 
pgrenon

Copyright @ 2017 



