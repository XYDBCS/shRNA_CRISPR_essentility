# This is the code for the manuscript "Systematic comparison of CRISPR and shRNA screens to identify essential genes using a graph-based unsupervised learning model"
 The file "Step 1" predicts the essentiality probability of each gene.
The file "Step 2" gets the essential genes and non-essential genes based on the predicted results from Step 1.
The file "Step 3" shows the convergence of the unsupervised model.
The file "Step 4" compares the distribution of essential genes under high and low expression.
The file "Step 5" shows the scatter plot of the gene essentiality score and gene expression with marginal density plots and the kernel density estimate
The file "Step 6" shows the comparison of all the essential and nonessential genes identified by shRNA and CRISPR under 8 groups.

#ENVIRONMENT

#Python 3.6.13

Tensorflow 1.14

numpy 1.17.0

scipy 1.5.2
