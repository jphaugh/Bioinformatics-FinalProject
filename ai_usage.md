We utilized ChatGPT (v.5) and, to a lesser degree, Gemini in Colab to assist with study design and coding. 

Prompts included (e.g.):
"write me code for the Mac command line that can utilize the NCBI datasets comman line tool to download genes by gene symbol and taxon"
"write me Colab-ready code to compile our three MHC gene datasets into one file that can be used as an input for BLASt database creation"
"write me code for Bridges2 to run a BLASTP analysis using the Marmoset FASTA as the query and the Old World MHC database as the subject"
"determine and justify e-value and percent identity thresholds for our BLAST hits"

Results were verified by testing the code and viewing outputs, looking to make sure it made biological sense and that the genes provided 
from BLAST were, indeed, MHC genes (searching via NCBI gene databases).

These datasets, including human genomes contain no information linked to any individual and are intended for research and comparative genomics. Use of these NCBI data complies with public-use agreements, and all original sources are properly cited. Analyses are limited to evolutionary and comparative questions (e.g., MHC orthology and sequence conservation) and do not make inferences about the health, traits, or identities of any individual. Results are interpreted in a cross-species context, avoiding overgeneralization to humans.
