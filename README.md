# 🏷️ Fine-tuning NER using PyTorch

![PyTorch](https://img.shields.io/badge/PyTorch-Latest-orange.svg)
![BERT](https://img.shields.io/badge/BERT-base--cased-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Last Update](https://img.shields.io/badge/Last%20Update-August%202024-brightgreen.svg)

## 🎯 Overview
A Named Entity Recognition (NER) model fine-tuned using PyTorch and BERT on the CoNLL-2003 dataset. The project demonstrates how to train and evaluate a state-of-the-art NER model using modern deep learning techniques.

## 🛠️ Tech Stack
- **Framework:** PyTorch
- **Model:** google-bert/bert-base-cased
- **Libraries:** 
  - transformers
  - seqeval
  - torch
- **Hardware:** NVIDIA 1650 Max-Q (4GB GPU)
- **Environment:** Jupyter Notebook + CUDA

## 📊 Dataset
Using the [CoNLL-2003 dataset](https://paperswithcode.com/dataset/conll-2003) which includes:
- **English Data:** Reuters news stories (Aug 1996 - Aug 1997)
  - Training set: End of August 1996
  - Test set: December 1996
  - Raw data: September 1996

- **German Data:** Frankfurter Rundshau newspaper
  - All sets: End of August 1992
  - Raw data: September-December 1992

## 📈 Evaluation Metrics
Using seqeval for evaluation:
- F1 Score
- Recall Score
- Precision Score



### Prerequisites
- Python 3.8+
- CUDA-capable GPU
- 4GB+ GPU Memory

