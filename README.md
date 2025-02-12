# NLP Sentiment Analysis 

## Project Description

This repository includes two separate projects demonstrating the use of NLP and LLM models. 
1. **NLP-GPT2**: Classifying the tonality of texts using BERT and generating responses based on GPT-2.  
2. **NLP-LLAMA**: Classifying text tones using BERT and generating responses based on LLAMA 3.2.

## Dataset used
[IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews) 

---

## NLP-GPT2

### Brief Description
This project implements:
1. **Tone classification** of texts from the IMDB dataset using the BERT model.
2. **Generation of responses** based on classification results using GPT-2.

### Main features:
- Data preprocessing (cleaning emoji, HTML tags, links, etc.).
- Use of custom Dataset for data preparation.
- Pipeline implementation with BERT training and evaluation for tone classification.
- Text generation using GPT-2 based on classification results.
- Metrics: accuracy on training ~91.72%, accuracy on validation ~89.56%.

---

## NLP-LLAMA

### Brief Description
This project implements:
1. **Tone classification** of texts from the IMDB dataset using the BERT model.
2. **Generation of responses** based on classification results using LLAMA 3.2.

### Main features:
- Data preprocessing (cleaning emoji, HTML tags, links, etc.).
- Use of custom Dataset for data preparation.
- Pipeline implementation with BERT training and evaluation for tone classification.
- Text generation using LLAMA 3.2 based on classification results.
- Metrics: accuracy on training and validation are similar to NLP-GPT2 results.

---

### Installation and startup

### Requirements:
- Python >= 3.9
- PyTorch >= 1.12
- Hugging Face Transformers >= 4.30
- CUDA support installed (recommended)
