# Machinelearning Capstone

## Introduction

This project analyzes the Credit Card data and flags fraudent transactions.

## Data

Data is collected from Kaggle. The data can be found in [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud). To download the data a name/key value needs to be generated from Kaggle. If the value is generated then it can be downloaded. The method to upload key and download the data is mentioned in the Collab notebook shared. Apart from that a set of data us uploaded in the Elasticsearch [index](http://51.158.98.31:59200/credit_card_data)

## Libraries used

Following libraries are used:

- kaggle
- pandasticsearch
- elasticsearch
- imblearn
- fastai
- PyCUDA
- torch
- numba
- Tensorflow

If using the Collab workplace please use TPU run time. The TPU runtime has slow network but the execution of the models are quite fast, almost 10 times fast.

Additional reference links are provided in the report.

## Code

Code is in google [Collab](https://colab.research.google.com/drive/19zCrjOdddOFbY6r1fahtRblUccX9zV7U).

For now I have shared the code with all. Once review is done I will remove share.
