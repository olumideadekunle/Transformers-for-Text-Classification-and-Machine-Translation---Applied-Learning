## NLP Files in Repository
File	Description

Key Learnings

Hugging Face simplifies fine tuning of large NLP models.

Transfer learning drastically reduces the required data and compute.

Domain-specific fine-tuning enhances translation accuracy.

Evaluation metrics (Accuracy, BLEU) are essential for model validation.

 Future Work

Expand fine-tuning dataset to multiple domains (finance, legal, etc.).

Deploy the fine tuned model via an API endpoint (e.g., FastAPI + Gradio).

Experiment with multilingual models like mBERT or NLLB for cross-language tasks.


### Transformers for Text Classification and Machine Translation
## Applied Learning Assignment

Course: Applied Machine Learning with Transformers
Author: Olumide Buari
Date: November 2025

 Project Overview

This project applies Transformer based models from the Hugging Face 🤗
 library to two real world Natural Language Processing (NLP) tasks:

Text Classification: Fine tuning a pretrained BERT model on a sentiment classification dataset.

Machine Translation: Using MarianMT to translate English to French and exploring fine tuning using domain-specific vocabulary.

These experiments demonstrate how transfer learning enables efficient adaptation of large language models (LLMs) for specific NLP applications.

 Objectives
Assignment 1: Text Classification

Fine-tune a pretrained transformer (BERT) for sentiment classification.

Use the IMDb dataset for binary classification (positive/negative).

Evaluate model performance after training.

Assignment 2: Machine Translation

Apply the MarianMT model for English → French translation.

Fine tune the model on a small domain specific dataset (medical context).

Compare translation results before and after fine-tuning.

 Tools & Libraries
Library	Purpose
transformers	Pretrained models & tokenizers
datasets	Loading and preprocessing datasets
torch	Deep learning backend
Hugging Face Hub	Model and dataset source
Google Colab	Development and training environment
 Dataset
Text Classification

Dataset: IMDb Reviews

Source: Hugging Face Datasets - IMDb

Labels: 0 = Negative, 1 = Positive

Machine Translation

Model: Helsinki-NLP/opus-mt-en-fr

Domain: Medical English-to-French vocabulary created manually for demonstration.

 Implementation Steps
Assignment 1: Text Classification

Load dataset (imdb)

Tokenize using BERT base uncased

Fine-tune the model using Hugging Face Trainer

Evaluate accuracy and loss

Assignment 2: Machine Translation

Load MarianMT model (opus-mt-en-fr)

Translate sample sentences (pre-finetuning)

Fine tune using small custom dataset

Translate again (post-finetuning) and evaluate contextual improvement

 Results Summary
Task	Model	Dataset	Accuracy / BLEU	Observation
Text Classification	BERT-base-uncased	IMDb	~90% Accuracy	BERT effectively distinguishes sentiment
Machine Translation	MarianMT	English → French	Improved contextual fluency post-finetuning	Handles medical vocabulary better

👨🏽‍💻 Author

Olumide Buari

📧 buariolumide@gmail.com

🔗 LinkedIn: https://www.linkedin.com/olumide-b-adekunle

💻 GitHub: https://www.github.com/olumideadekunle

# Transformers for Text Classification and Machine Translation — Applied Learning
These experiments demonstrate how transfer learning enables efficient adaptation of large language models (LLMs) for specific NLP applications.
