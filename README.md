# Text-Classification-with-Pre-Trained-Language-Models

This project involves creating a dataset for text classification, fine-tuning a pre-trained language model, and evaluating its performance. The dataset and models focus on distinguishing between categories such as cities, football players, and books.

## Dataset
- Custom Dataset: Created with at least 2000 words, spanning three categories with a minimum of 100 examples per category. The dataset includes text samples such as paragraphs or excerpts from books and has been generated using web scraping, personal documents, and ChatGPT.

- Categories:
  - Cities
  - Football Players
  - Books

## Project Overview
- Dataset Preparation:
Curated a dataset with a minimum of 2000 words.
Split the dataset into training (at least 240 examples) and test (at least 60 examples) sets.
- Model Training:
Fine-tuned a pre-trained BERT model from the Hugging Face Transformers library using the custom dataset.
Employed PyTorch for model training and evaluation.
- Evaluation:
Reported test accuracy and discussed potential improvements for better performance.

