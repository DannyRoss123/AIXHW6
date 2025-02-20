# AIXHW6

# Mechanistic Interpretability of Transformer Circuits

## Overview
This repository contains a Jupyter notebook that implements key findings from the paper *A Mathematical Framework for Transformer Circuits* by Neel Nanda. The paper presents a theoretical framework for understanding the OV matrix in transformer circuits, and this project demonstrates a practical implementation of extracting and analyzing the OV matrix using a one-layer attention-only transformer model.

## Key Findings Implemented
* **OV Matrix Extraction**: The notebook implements the extraction of the OV matrix, which represents the relationship between attention keys and values in a transformer.
* **Singular Value Decomposition (SVD)**: The SVD of the OV matrix is computed, and the results are visualized through the singular values, left singular vectors, and right singular vectors.
* **Reconstruction of OV Matrix**: A low-rank approximation of the OV matrix is computed using the top singular values, demonstrating how much information can be retained with reduced complexity.

## Files and Content
* **AIXHW6.ipynb**: The Jupyter notebook containing the implementation and visualizations. The notebook includes code to extract the OV matrix, compute its SVD, and visualize key components.

## Installation
To run the notebook, make sure to have the following libraries installed:
* PyTorch
* NumPy
* Matplotlib
* Seaborn

## Key Insights
* The analysis of the OV matrix's singular values and vectors offers a practical demonstration of transformer interpretability.
* By reducing the matrix to its top singular values, we show how the transformer model can be approximated with lower-rank matrices while still capturing essential information.

## Challenges and Extensions
* This implementation uses a simplified transformer model. Future work could involve testing this technique with more complex models or applying it to different types of transformer architectures, such as multi-head attention.
