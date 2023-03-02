# PyEED Data Model

PyEED is a Python-encoded data model of an Enzyme Engineering Database. It supports the scalable and reproducible analysis of sequence and structure data of protein families, and makes data and processes findable, accessible, interoperable, and reusable according to the FAIR data principles.

### ProteinSequence

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


### ProteinDomains

- __protein_domain__
  - Type: string
  - Description: Name of protein domain
- __protein_database__
  - Type: string
  - Description: Database the domain has been found




