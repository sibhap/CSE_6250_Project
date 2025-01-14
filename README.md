# KSI framework | Team D1 | CSE-6250 - Fall 2022
This repository contains code forked from Knowledge Source Intergration (KSI) framework in the paper
* **Bai, T., Vucetic, S., Improving Medical Code Prediction from Clinical Text via Incorporating Online Knowledge Sources, The Web Conference (WWW'19), 2019.**

## Environment for the implementation:
* python==3.7.0
* numpy==1.21.6
* sklearn==0.19.2
* tensorflow==2.9.0
* keras==2.9.0

## Data
Before running the program, you need to apply for MIMIC-III dataset and put two files "NOTEEVENTS.csv" and "DIAGNOSES_ICD.csv" under the same folder of the project. 

Path to download the data - https://physionet.org/content/mimiciii/1.4/

## Steps to execute
Copy data and the code to preprocess data to a Google Drive folder CS6250. The file path would look like */My Drive/CS6250*.

### Exploratory Data Analysis

Open KSI_TeamD1_EDA.ipynb in colab and run the cells.

### CNN base model and CNN + KSI

Open KSI_TeamD1.ipynb in colab.

Run the cells in order to create the datasets. (The preprocessing scripts "preprocessing1.py", "preprocessing2.py", "preprocessing3.py" from the original repository need to be run to prepare the datasets.)

The basic CNN model will be saved as *cnn_20_epochs.h5*

### LSTM Base Model and LSTM + KSI

Open KSI+LSTM.ipynb in colab and execute the code in order
