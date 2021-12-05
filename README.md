# Empathy Detection
---
This repository is a reproduction of *A Computational Approach to Understanding Empathy Expressed in Text-Based Mental Health Support* by A. Sharma, A. S. Miner, D. C. Atkins and T. Althoff (2020).  

## Requirements

### Datasets
In the original work, there are 3 different datasets from Sub-Reddit blogs for emotional reactions, explorations and interpretations. All datasets used in this code can be found under `/Datasets`. 

### Source Code
This project is implemented using Python, TensorFlow and we use  Google Colab environment to run (`dataprocessing.ipynb`,`Pre-training.ipynb`,`model.ipynb`) notebooks. 

**Note:**  Google account is needed to run the code and save datasets and models in google drive directory .  

## Data Preprocessing
The code to preprocess the data can be found in `dataprocessing.ipynb`. The datasets included in this repository named `processed_emotionalreactions.csv`,`processed_explorations-reddit.csv`,`processed_interpretations-reddit.csv` is the result from pre-processing of `emotionalreactions.csv`,`explorations-reddit.csv`,`interpretations-reddit.csv` .

## Pre-trained Language Model

The code to implement pre-trained language model based on empathy context using BERT can be found in `Pre-training.ipynb`. We use `emotional-reactions_Test-reddit.csv`, `explorations_Test-reddit.csv`,`interpretations_Test-reddit.csv` datasets as test files to evaluate our masked language model.

## Pre-Trained Models
The pre-trained models can be accessed under `/Trained Models`. They are organized according to the communication mechanisms, namely emotional reactions (`training_empathy_ER`), explorations (`training_empathy_EX`), and interpretations (`training_empathy_IN`).

## Bi-encoder Model Training and Evaluation
To train, test and evaluate the models, you need to run the respective cells from the `model` notebook.

