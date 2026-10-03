# POS-BanglaT5-Translation

Official implementation of "POS-Augmented BanglaT5 for Bangla Dialect-to-Standard Neural Machine Translation."

This repository contains the PyTorch and Google Colab implementation for translating five regional Bangla dialects (Mymensingh, Barishal, Sylhet, Chittagong, and Noakhali) into Standard Bangla. The proposed architecture injects explicit Part-of-Speech (POS) embeddings into a pre-trained BanglaT5 encoder to resolve structural ambiguities in morphologically rich dialects.

## Dataset
The model is trained and evaluated on the Vashantor dataset. 
* **Download the dataset here:** [Vashantor: A Large-scale Multilingual Benchmark Dataset for Automated Translation of Bangla Regional Dialects to Bangla Language - Mendeley Data](https://data.mendeley.com/datasets/bj5jgk878b/2)

## How to Run (Google Colab)
1. Open the provided Jupyter Notebook in Google Colab.
2. Ensure your runtime is set to **GPU** (Runtime > Change runtime type > T4 GPU).
3. Install the required dependencies (e.g., `transformers`, `bnlp-toolkit`).
4. Run the notebook sequentially. The execution outputs have been preserved in this repository to verify the final evaluation metrics.

## Requirements
* `torch`
* `transformers`
* `bnlp-toolkit`
* `pandas`
