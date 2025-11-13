# Bioinformatics-FinalProject
Immunogenomics of Old World and New World primates project repository for Bioinformatics.

This Github repo contains the following files:

AI_usage.md, a short statement of the AI tools used, prompts given, and validation.

AccessionJSON1.txt, a combination of the summary files for the Old World primate MHC gene protein-coding FASTA sequences provided by NCBI.
Each dictionary entry contains information on taxa, NCBI accession number, gene, and gene description.

Marmoset_vs_OldWorldMHC_filtered.tsv, a table in the BLAST "outfmt 6" format. 
The columns are:
1	qseqid	Query sequence ID (here, the Marmoset protein ID)
2	sseqid	Subject sequence ID (here, the Old World MHC protein ID from your database)
3	pident	Percent identity between query and subject (0–100)
4	length	Alignment length (number of aligned amino acids)
5	mismatch	Number of mismatched positions in the alignment
6	gapopen	Number of gap openings in the alignment
7	qstart	Start position of the alignment on the query sequence
8	qend	End position of the alignment on the query sequence
9	sstart	Start position of the alignment on the subject sequence
10	send	End position of the alignment on the subject sequence
11	evalue	BLAST E-value, indicating significance of the match (lower = more significant)
12	bitscore	Bit score, a normalized score for alignment quality (higher = better match)
Each row is a single BLASTP hit between one Marmoset protein and one Old World MHC protein. If a Marmoset protein hits multiple Old World MHC proteins, it will appear in multiple rows. Likewise, a single Old World MHC gene can appear multiple times if multiple Marmoset proteins match it.

MarmosetAccessionJSON.txt, the summary file for the marmoset protein-coding FASTA sequence provided by NCBI.

OldWorldNCBI-TerminalCode.txt, the code input to the MacOS command line terminal to access and download specific MHC gene FASTA files.

ProjectPythonCode-Colab.ipynb, a copy of our Colab notebook containing all other code and analyses, including those done iniitally in Bridges2.



