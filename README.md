# genomic_fine_tuning-
Genomics DNA Classifier

A beginner-friendly bioinformatics and machine learning project exploring fine-tuning of a pretrained DNA language model for coding vs non-coding transcript classification.

Project Overview

This project investigates how pretrained genomic language models can learn to distinguish protein-coding and non-coding RNA sequences.

We will use DNABERT-2 as our pretrained model and fine-tune it using labelled transcript sequences.

Objectives
Understand DNA and RNA sequence representations.
Explore coding and non-coding transcript datasets.
Learn genomic sequence preprocessing and tokenisation.
Fine-tune a pretrained DNA language model.
Evaluate classification performance.
Explore applications of deep learning in genomics.
Technologies
Python
Jupyter Notebook
PyTorch
Hugging Face Transformers
DNABERT-2
Pandas and NumPy
Scikit-learn
Matplotlib and Seaborn
Project Structure
text
genomics-dna-classifier/
├── data/
├── notebooks/
├── src/
├── results/
├── models/
├── README.md
├── requirements.txt
└── .gitignore

Dataset

We plan to explore the CPC2 dataset, which contains labelled protein-coding and non-coding transcript sequences.

Dataset source: http://cpc2.gao-lab.org/

Workflow
Dataset exploration
Sequence preprocessing
DNA/RNA tokenisation
Pretrained model loading
Model fine-tuning
Model evaluation
Current Status

Project setup and initial dataset exploration.

Disclaimer

This is an educational research project. Model predictions should not be interpreted as clinical or biological evidence without independent validation.

Author

Created as a personal learning project in bioinformatics and deep learning.
