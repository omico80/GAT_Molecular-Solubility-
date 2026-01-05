# GAT_Molecular-Solubility-

# Project Overview

This repository presents a detailed study demonstrating the applicability of Graph Attention Networks (GATs) for molecular property prediction.

In this work, molecules are modelled as undirected graphs, where atoms are represented as nodes and chemical bonds as edges. Each atom is described by a vector of physicochemical and biophysical properties, which together form a comprehensive molecular representation used by the model.

# Dataset

The model is trained and evaluated using the ESOL dataset from the MoleculeNet benchmark, a widely used reference dataset in cheminformatics. The ESOL dataset contains 1,125 compounds and focuses on predicting aqueous solubility, a key physicochemical property relevant to drug discovery.

# Methodology

Prior to model training, exploratory data analysis (EDA) was conducted to understand the distribution and characteristics of the dataset. The Graph Attention Network was implemented using PyTorch Geometric and standard Python scientific libraries.

The attention mechanism allows the model to learn the relative importance of neighbouring atoms, enabling more expressive and interpretable molecular representations compared to traditional graph convolutional approaches.

# Technologies Used

Python

PyTorch

PyTorch Geometric

MoleculeNet (ESOL dataset)
