# Empathy Detection
---
This repository is a reproduction of *A Computational Approach to Understanding Empathy Expressed in Text-Based Mental Health Support* by A. Sharma, A. S. Miner, D. C. Atkins and T. Althoff (2020).  

## Requirements
This project was created as a Python notebook (`model.ipynb`) and was run on a Google Colab environment. The preprocessed datasets are loaded automatically from this repository but can be found under `/Datasets`.

## Data Preprocessing
The code to preprocess the data can be found in `dataprocessing.ipynb`. The datasets included in this repository have already been preprocessed.

## Training, Evaluation
To train and evaluate the models, run the respective cells from the `model` notebook.

## Pre-Trained Models
The pre-trained models can be accessed under `/Trained Models`. They are organized according to the communication mechanisms, namely emotional reactions (`training_empathy_ER`), explorations (`training_empathy_EX`), and interpretations (`training_empathy_IN`).
