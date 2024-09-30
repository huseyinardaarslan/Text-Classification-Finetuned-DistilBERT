# Text-Classification-Finetuned-DistilBERT

This project focuses on fine-tuning the DistilBERT model for text classification tasks using the AG News dataset. 
The model is designed to classify news articles into four categories: World, Sports, Business, and Science/Technology.

## Project Overview

In this project, we leverage the Hugging Face Transformers library to implement and fine-tune the DistilBERT model, a lightweight version of BERT, for the task of text classification. The goal is to classify news articles into predefined categories effectively.

## Getting Started

To get started with this project, you will need to have Python and several libraries installed. Follow the installation instructions below.

## Dataset

The AG News dataset consists of 120,000 training samples and 7,600 test samples, covering four news categories. The dataset is publicly available and can be accessed through the Hugging Face Datasets library.

## Model Architecture

We use the DistilBERT model for sequence classification. DistilBERT is a smaller and faster version of BERT, designed to retain most of BERT's language understanding capabilities while being more efficient.

## Installation

Ensure you have Python 3.6 or later installed. You can install the required packages using pip:
pip install torch torchvision transformers datasets matplotlib seaborn

## Training

The model is trained using the following parameters:

Epochs: 2
Batch Size: 16
Evaluation Strategy: Evaluation at the end of each epoch
The model will save the fine-tuned weights to the ./finetuned_distilbert directory upon completion.

## Evaluation

The model's performance is evaluated on a separate test dataset. Key metrics include accuracy, F1 score, precision, and recall.

## Results

The results of the evaluation show the performance of both the pretrained and fine-tuned models, including any improvements gained through fine-tuning.
