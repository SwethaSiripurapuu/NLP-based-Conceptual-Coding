# NLP-based-Conceptual-Coding
This repository contains the code and resources for the NLP-Based Conceptual Coding project, which automates the process of assigning hierarchical codes to interview transcript data. The goal of this project is to predict NLP codes and Conceptual codes from textual data using advanced Natural Language Processing (NLP) techniques and transformer-based models.

### Project Overview
Manually coding interview transcripts is a time-intensive process. This project automates the conceptual coding process, leveraging:

Baseline Models: TF-IDF and Bag-of-Words for initial experiments.
Transformer-Based Models: Pre-trained models like RoBERTa and DeBERTa for predicting NLP codes.
Transfer Learning: A hierarchical classification model to predict Conceptual codes based on intermediate NLP code predictions.

### Data
The data for this project is a set of Excel files containing interview transcript data. These files are confidential and therefore not included in this repository. Please ensure you have access to the required data files and load them as needed during preprocessing and training.

### Prerequisites
Python 3.8+, 
Required Python libraries (Requirements.txt)

The following links may come in handy:
- [Hugging Face Transformers Library](https://huggingface.co/transformers/)
- [RoBERTa on Hugging Face](https://huggingface.co/roberta-base)
- [DeBERTa on Hugging Face](https://huggingface.co/microsoft/deberta-base)

### Contributors
- Swetha Siripurapu 
- Rishabh Bhosle
- Team Members - The Global Knowledge Lab
