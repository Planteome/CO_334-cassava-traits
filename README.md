# ibp-cassava-traits

This ontology results in the collaboration of Cassavabase, BMS and Crop Ontology
-------------------------------
Cassava Trait Ontology is maintained by http://www.cropontology.org and https://cassavabase.org

Request new traits/variables by submitting a new issue in this github repo, or by filling the trait request form http://submit.rtbbase.org

-------------------------------

Crop specific trait ontologies enhance the interoperability and effectiveness of data exchange between the data sources which adopt it, 
by providing standard concepts that are use to describe phenotypes stored in those sources. 
As one of them, the Cassava Ontology is actively used and shared in different databases used by RTB 
such as the BMS (Breeding Management system) of the IBP or the CassavaBase. 

phenotypes of other RTB crops such as Banana, Sweet Potato, and Yam are stored in these RTB databases. 
It is thus of prime importance to agree on and share a common methodology to maintain these ontologies.
This requires regular interactions between the people using it and the developers of the Crop Ontology project, 
who participated from the beginning of the building and the curation of those ontologies.


The following guidelines are the result of the collaboration between CropOntology, Bioversity, and CassavaBase.
It is important to follow these guidelines in order to maintain one ontology which is compatibel with all databases.


- Cross product terms and variable:
Variable is a notion that has been introduced recently in the Crop Ontology. 
A variable is composed by the unique combination of one Trait, one Method and one Scale and will annotate the measurement in a database. 
Therefore, there is now a clear distinction between the trait and the variable. 
The introduction of the notion of variables as consequences on the current version of the Cassava Ontology. 
We agreed on:


1. Normalization of variable names
 Variable names should be unique, and not the same as the trait name. 
 A good variable name should have the method and scale as part of its name, 
 an explicit definition which includes all aspects of measuring the variable.
 The name should be easy to interpret by the users (breeders in the field). 
 Breeders may use acronyms, or concatenation of the name of the trait, the method and the scale. Such names are best implemented as synonyms of the variable, since these might not be self-explanatory to other users of the ontology.

2. Identifiers
 ID ranges for new traits and variables are between 0000001-0009999
 mew methods 0010000-0099999
 new scales  0100000-0999999
 
3. Requesting new terms
 To avoid overloading the same ontology IDs only curators should add new terms 
 * To request new terms please use the github issue tracker of this repository  https://github.com/Planteome/ibp-cassava-traits/issues
  or by filling the trait request form http://submit.rtbbase.org



