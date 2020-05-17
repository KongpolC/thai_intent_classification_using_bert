# thai_intent_classification_using_bert

This repository contains python code to 
Finetune BERT for Thai intent classification with GPU on Google Colab using the pretrained model from https://github.com/ThAIKeras/bert which uses data from Thai Wikipedia. This can be applied to create an advance chatbot which can be integrated with robots, websites, apps and etc.
This project is pretty much similar to https://github.com/KongpolC/Thai-Sentiment-Classification-Using-BERT so, feel free to check thi one out too.

## Data
Trained on open-source Wongnai restaurant review data. Source: https://github.com/wongnai/wongnai-corpus.git
  - Input: text review in Thai.
  - Target: rating in star from 1-5.
  
## Transfer Learning Using GPU
Main processes to fintune BERT in Thai using GPU on Google Colab include:
  - setting up Google Colab runtime with GPU acceleration.
  - installing all required libraries.
  - downloading all required files.
  - processing and verifying data.
  - tokenizing data using SentencePiece which implements BPE
  - finetuning BERT.
  - testing model's accuracy.
  
## Result
accuracy = 0.8921
  

