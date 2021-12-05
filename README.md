# Empathy Detection
---
This repository is a reproduction of *A Computational Approach to Understanding Empathy Expressed in Text-Based Mental Health Support* by A. Sharma, A. S. Miner, D. C. Atkins and T. Althoff (2020).  

## Requirements

### Datasets
In the original work, there are 3 different datasets for emotional reactions, explorations and interpretations. All datasets used in this code can be found under `/Datasets`. 

### Source Code
This project is implemented in Python and we use  Google Colab environment to run (`dataprocessing.ipynb`,`Pre-training.ipynb`,`model.ipynb`) notebooks. 

**Note:**  Google account is needed to run the code and save datasets and models in google drive directory .  

## Data Preprocessing
The code to preprocess the data can be found in `dataprocessing.ipynb`. The datasets included in this repository have already been preprocessed.

## Training, Evaluation
To train and evaluate the models, run the respective cells from the `model` notebook.

## Pre-Trained Models
The pre-trained models can be accessed under `/Trained Models`. They are organized according to the communication mechanisms, namely emotional reactions (`training_empathy_ER`), explorations (`training_empathy_EX`), and interpretations (`training_empathy_IN`).
