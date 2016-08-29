# rbcL
rbcL sequence database for plant metabarcoding applications 

data provided as a .csv file (~41.8 MB)

rbcL data from GenBank, updated March 11 2016
columns are:
- name ("Name")
- GenBank ID ("GID")
- GenBank Accession # ("Accession")
- species in Latin binomial format ("Organism")
- sequences ("FASTA")

redundancies removed:
- one record per 'Organism' name (based on longest sequence, following UTAX and RDP)
- FASTA files of length zero / NAs removed
- one record per database identifier

code and database in repository
