# Biopython assigment

Create a script that does the following:

1. Get the full sequence of human GAPDH transcript 'NM_002046.7' from NCBI.
2. Find the two most common 5-mers in this sequence. 
3. For each of those kmers, find all instances of the kmer in the original sequence,
and extract subsequences with 10 leading and 10 trailing bases. 
4. Save these subsequences to a fasta file.  

## Challenge

Write a script that does the same as above, _but_

* takes the accession number as an argument
* optionally writes the fasta file to a user-supplied destination. 
* Performs a pairwise alignment between the first two subsequences.

E.g. the user should run: `python script.py --output subsequences.fa NM_anumber`

   
