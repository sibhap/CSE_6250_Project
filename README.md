# KSI framework | Team D1 | CSE-6250 - Fall 2022
This repository contains code forked from Knowledge Source Intergration (KSI) framework in the paper
* **Bai, T., Vucetic, S., Improving Medical Code Prediction from Clinical Text via Incorporating Online Knowledge Sources, The Web Conference (WWW'19), 2019.**

I used the following environment for the implementation:
* python==3.7.0
* numpy==1.21.6
* sklearn==0.19.2
* tensorflow==2.9.0
* keras==2.9.0

The data files "NOTEEVENTS.csv" and "DIAGNOSES_ICD from MIMIC-III are already part of the repository. 

Open KSI_TeamD1.ipynb

Run the cells in order to create the datasets. (The preprocessing scripts "preprocessing1.py", "preprocessing2.py", "preprocessing3.py" from the original repository need to be run to prepare the datasets.)

The basic CNN model will be saved as *cnn_20_epochs.h5*
