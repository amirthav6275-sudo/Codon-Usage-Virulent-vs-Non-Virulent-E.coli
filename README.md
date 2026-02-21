# Codon-Usage-Virulent-vs-Non-Virulent-E.coli
Analysis of codon usage bias in selected genes from pathogenic E.coli O157:H7 and non-pathogenic E.coli K12 strains

# Introduction
This project studies the codon usage bias between virulent and non- virulent strains of E.coli and find codon frequency in both strains

# Organism and genes studied
Pathogenic strain: E. coli O157 (genes studied - stx2A, eaeA, espA )
Non-pathogenic strain: E. coli K12 (genes studied - recA, rpoB, gapA )

# Analysis
Gene sequences were collected from the NCBI database
3 housekeeping genes from non-virulent strain and 3 virulence genes from virulent strain were analyzed
Codon frequencies were calculated.
Codon usage patterns were compared.
Bar graph was plotted for GC3 content comparison 

# Tools Used
NCBI 
Jupyter Notebook 
Matplotlib 

# Result
GC3 content in percentage
Virulent  stx2A, eaeA, espA  -  31.54, 39.36, 50.20     Lower overall, more variable
Non-Virulent  recA, rpoB, gapA  -  62.99, 59.05, 52.41    Higher overall, more uniform 

Virulence genes had lower and more variable GC3 compared to the higher GC3 and relatively uniform rate for non-virulent housekeeping genes. 
Horizontally acquired or specialized genes, such as virulence factors, tend to have a different codon composition than core genome genes.
genes encoding virulence factors seemed to choose

# Conclusion
Genes encoding virulence factors seemed to choose virulence-associated codons, including some terminating in G/C, while exhibiting barriers or rare codons in stx2A and eaeA. 
Codon usage bias serves to optimize translational efficacy and gene expression. 
In contrast, housekeeping genes exhibited codon balance that reflects their cellular necessity 


