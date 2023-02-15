# PyEED Data Model

PyEED is a Python-encoded data model of an Enzyme Engineering Database. It supports the scalable and reproducible analysis of sequence and structure data of protein families, and makes data and processes findable, accessible, interoperable, and reusable according to the FAIR data principles.

### ProteinSequence

- __protein_sequence_id__
  - Type: string
  - Description: Presented protein sequence
- __name__
  - Type: string
  - Description: Systematic name of the protein.
- __amino_acid_sequence__
  - Type: string
  - Description: The amino acid sequence of the protein sequence object.
- __protein_database_name__
  - Type: [ProteinDatabase](#ProteinDatabase)
  - Description: Data base ID
- __protein_organism_id__
  - Type: [Organism](#Organism)
  - Description: Corresponding organism 

### ProteinDatabase

- __database__
  - Type: string
  - Description: Position in the sequence where the domain starts
- __link_to_database__
  - Type: string
  - Description: Position in the sequence where the domain ends

### Organism

- __organism_name__
  - Type: string
  - Description: Organism name
- __ncbi_taxonomy_id__
  - Type: string
  - Description: NCBI Taxonomy ID to identify the organism
