# OWL2-Ontology-for-THOTH

This ontology was created for THOTH, aiming to provide data structure needed for THOTH - Training by Highly Ontology-oriented Tutoring Host. THOTH deals with OAV triples to return knowledge about some object of interest, previously stored in the ontology. Created in Protege, this ontology has classes, object properties, datatype properties and individuals. Information can be retrieved by SPARQL queries in the SPARQL endpoint available at http://93.188.163.112/sparql/.

Classes:
- Object
- Attribute
- Value
- Answer
- Question

Object Properties:
- hasObject
- hasAttribute
- hasValue
- hasAnswerAttribute
- nasQuestion

Datatype Properties:
- hasName
- hasText
- hasAuthor
- hasYear
- hasPrefix
