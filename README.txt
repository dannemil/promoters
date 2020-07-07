Code and data in support of:

Dannemiller, JL (2020) Mutual information reveals a homonucleotide bias at 6 bp distance in promoters. Manuscript submitted to Bioinformatics - Oxford University Press, July, 2020.

contact: dannemil at rice dot edu

Unzip the file Rpromoter.zip in a directory that will hold the R script and data files. This will also create three subdirectories:

functions/
heatmaps/
plots/

The R script is:

all-heatmaps.R

The R script all-heatmaps.R expects to find the following FASTA data files in the same directory as the script:

filename		  Species			Number of sequences
promoters1099Hs-EPD.fa  # Homo sapiens			16454			
promoters1099Dm-EPD.fa  # Drosophila melanogaster	13399  
promoters1099Sc-EPD.fa  # Saccharomyces cerevisiae	5117
promoters1099Mm-EPD.fa  # Mus musculus			20203

Each sequence is 1100 bp in width (-1000 to +99) aligned at their putative TSS (+1). Sequences were downloaded from the Eukaryotic Promoter Database. 

