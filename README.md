# Investigating-the-effect-of-siRNA-knock-down-of-pasilla-using-Deseq2
This repository performs a differential expression analysis using the DESeq2 package, identifies the top 10 differentially expressed genes, explores the results, writes the significant genes to a CSV file, and visualizes the results through MA-plot, plot counts, heatmap, PCA plot, and volcano plot.

# Run
You can install dependencies recorded in the lockfile using the following command:
```bash
renv::restore()
```
# Sample Input
[pasilla_gene_exp](https://raw.githubusercontent.com/lamamedhat/Investigating-the-effect-of-siRNA-knock-down-of-pasilla-using-Deseq2/main/Data/pasilla_gene_exp.csv)

[pasilla_metadata](https://raw.githubusercontent.com/lamamedhat/Investigating-the-effect-of-siRNA-knock-down-of-pasilla-using-Deseq2/main/Data/pasilla_meta.data.csv)

# Sample Output
[PDF](https://github.com/lamamedhat/Investigating-the-effect-of-siRNA-knock-down-of-pasilla-using-Deseq2/blob/main/Output/Differential_Expression.pdf)
