# IFT6269_Project : Phylogenetic HMM for genome annotation
This Notebook presents an implementation the Gene finder Phylo-HMM model from the article : 
Siepel, A. and Haussler, D. Phylogenetic hidden markov models. Statistical Methods in Molecular Evolution, 3(3):325—-351, 2005.

# I - Phylogenetic model and HMM algorithms
## I.1 - Felsenstein algorithm
Dyn. programming algorithm for efficiently computing the likelihood of observations (alignment of DNA sequences) given a phylogenetic model
## I.2 - Viterbi algorithm
Dynamic programming algo for computing the maximum likelihood path, given observations in a HMM

# II - Simulation algorithms
## Step1 - Synthetic data generation
Generate a synthetic dataset of alignments of DNA sequences based on a phyloHMM model
## Step2 - Predictions
predict genes positions using Viterbi/Felsenstein algos, with phylo-HMM and standard HMM

# III - Tests on synthetic data
Implement and test the implemented phyloHMM model 
## III.1 - Model Parameters
### HMM model
### Phylogenetic Tree

## III.2 - Test on 1 sample
### Generate data
### Predict genes

## III.3 Impact of nb of species - Phylo-HMM vs HMM
## III.4 Sensitivity to model parameters
Test the sensitivity to different background nucleotides frequencies

