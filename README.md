# BIO-463: Project in Genomics and Bioinformatics

EPFL, May 2020

Paper 8: *Predicting effects of noncoding variants with deep learning-based sequence model* by Zhou & Troyanskaya (2015).

This repository contains the code to produce the results from the accompanying individual report. The original output files of DeepSEA are 7.5 GB and available upon [request](mailto:lisa.dratva@epfl.ch). Instead, pickle files are provided to run the final analysis.

## Repository
* [`TF.py`](TF.py) lists the investigated transcription factors (TFs)
* [`analyzeChipSeq.ipynb`](analyzeChipSeq.ipynb) to analyze ChIP-seq data for the TFs
* [`analyzeResults.ipynb`](analyzeResults.ipynb) to analyze the DeepSEA output files
* [`performanceCheck.ipynb`](performanceCheck.ipynb) to compare DeepSEA results to experimental ChIP-seq data and produce the final figure
* [`chipSeq2.xlsx`](chipSeq2.xlsx) contains the raw ChIP-seq data for all TFs
* [`ChIPseq_chr8_final10_low.pkl`](ChIPseq_chr8_final10_low.pkl) contains the output of the [`analyzeChipSeq.ipynb`](analyzeChipSeq.ipynb) notebook
* [`predicted_TFBS_normalized_0-9_final10_low.pkl`](predicted_TFBS_normalized_0-9_final10_low.pkl) contains the output of the [`analyzeResults.ipynb`](analyzeResults.ipynb) notebook

## Dependencies
* [`pandas`](https://pandas.pydata.org/)
* [`sklearn`](https://scikit-learn.org/stable/)
* [`matplotlib`](https://matplotlib.org/)

## Reproduction
1. Clone or fork the repository
2. Install [Jupyter Notebook](https://jupyter.readthedocs.io/en/latest/install.html)
4. Install the abovementioned libraries
5. Run [`analyzeChipSeq.ipynb`](analyzeChipSeq.ipynb) to extract ChIP-seq data
6. Run [`performanceCheck.ipynb`](performanceCheck.ipynb) to reproduce the final figure

## Author
Lisa Dratva, [lisa.dratva@epfl.ch](mailto:lisa.dratva@epfl.ch)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.