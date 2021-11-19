# Tuesday morning, exercise 0: Run Blast on the command line

## Blast fundamentals

* What do we do when we blast a sequence?
  - Alignment
  - The types of homology: orthology and paralogy
  - Homology is black and white
* The "flavours" of Blast: `blastn`, `blastp`, `blastx` etc.
* The two steps of Blast: Index lookup & extension

## Running Blast from the command line

1. Create an indexed database with sequences you want to search *in*: "target database"
2. Create a fasta file with sequences you want to search *with*: "subject database", e.g. `subjects.fna` and `subjects.faa` respectively for nucleotide and protein sequences.

### Creating a Blast database

* Protein sequences: `makeblastdb -in targets.faa -out targetprot -dbtype prot`
* Nucleotide sequences: `makeblastdb -in targets.fna -out targetnucl -dbtype nucl`

### Running Blast

* Each "flavour" of Blast is implemented in its own program: `blastp`, `blastn` etc.
* Search for protein sequences in a protein database: `blastp -db targetprot -query subjects.faa`
* Search for nucleotide sequences in a nucleotide database: `blastn -db targetnucl -query subjects.fna`

### Running Blast against preformatted standard databases at UPPMAX
