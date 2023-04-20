# CANDy 

CANDy is a workflow for the detection and annotation of protein domains in carbohydrate active enzymes (CAZymes). It is a unique assembly of several (python and non-python based) tools, packages and databases. CANDy is part of the PyEED consortium. PyEED is a Python-encoded data model of an Enzyme Engineering Database. It supports the scalable and reproducible analysis of sequence and structure data of protein families, and makes data and processes findable, accessible, interoperable, and reusable according to the FAIR data principles.

### Protein_sequences

- __protein_sequence_id__
  - Type: string
  - Description: Presented protein sequence
- __taxonomy__
  - Type: string
  - Description: Protein taxonomy
- __characterized__
  - Type: string
  - Description: Marks this protein as characterized
- __organism_name__
  - Type: string
  - Description: Name of the organism the protein is retrieved from.
- __amino_acid_sequence__
  - Type: string
  - Description: The amino acid sequence of the protein sequence object.
- __domain_architecture__
  - Type: string
  - Description: Domain architecture of the protein sequence
- __domain_locations__
  - Type: string
  - Description: Position of the found domains in the protein sequence
- __domain_databases__
  - Type: string
  - Description: Database(s) the domain(s) have been retrieved from

### Domain_assemblies 

- __protein_domain__
  - Type: string
  - Description: Unique domain composition
- __protein_sequence_id__
  - Type: string
  - Description: Identifiers of the proteins that follow the domain composition

### Domain_curation

- __domain_name__
  - Type: string
  - Description: Name of the protein domain that is used in the database
- __synonymous_domain_name__
  - Type: string
  - Description: Synonymous name(s) of the same protein domain





