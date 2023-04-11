# Research Paper: ProsGnn - Predicting Effects of Mutations on Protein Stability using Graph Neural Networks
This research paper presents ProsGnn, a graph neural network-based model for predicting the effects of mutations on protein stability. The model uses graph convolutional neural networks (GCNs) to learn the underlying patterns in the protein structure and predict the effect of a mutation on protein stability.

## Background
Proteins are essential molecules that perform various functions in the human body. Mutations in proteins can lead to various diseases, and predicting the effect of mutations is crucial for understanding the disease mechanism and developing new therapies. Protein stability is a crucial factor in protein function and mutation effect, and predicting its effect can aid in drug design and protein engineering.

## Objective
The objective of this research paper is to develop a model that can accurately predict the effect of mutations on protein stability. ProsGnn aims to improve the accuracy of mutation effect prediction compared to existing methods.

## Methodology
ProsGnn uses graph neural networks (GNNs) to learn the underlying patterns in the protein structure. The input to the model is a protein structure represented as a graph, where nodes represent amino acids, and edges represent interactions between them. The model then predicts the effect of a mutation on protein stability as a regression problem.

The model was trained on a dataset of 14,990 mutations in 4,923 protein structures. The performance of ProsGnn was evaluated using various metrics, including root mean squared error (RMSE) and Pearson correlation coefficient.

## Results
The results of the experiments show that ProsGnn outperforms existing methods in predicting the effect of mutations on protein stability. The model achieved an RMSE of 0.94 and a Pearson correlation coefficient of 0.82, indicating its high accuracy and robustness.

## Conclusion
ProsGnn is a promising model for predicting the effect of mutations on protein stability. Its high accuracy and robustness can aid in drug design and protein engineering, and future research can explore its application in other protein-related tasks.

## Repository Contents
This repository contains the code for ProsGnn, including the model architecture, training, and evaluation scripts. The dataset used for training and evaluation is also included. Instructions for running the code and reproducing the results are provided in the README file.