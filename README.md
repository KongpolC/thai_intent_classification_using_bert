# Thai Intent Classification Using BERT

This repository contains python code to 
Finetune BERT for Thai intent classification with GPU on Google Colab using the pretrained model from https://github.com/ThAIKeras/bert which uses data from Thai Wikipedia. This can be applied to create an advance chatbot which can be integrated with robots, websites, apps and etc.

This project is pretty much similar to https://github.com/KongpolC/Thai-Sentiment-Classification-Using-BERT so, feel free to check thi one out too.

## Data
Trained on truevoice-intent dataset which was provided by [TrueVoice](http://www.truevoice.co.th/). This dataset contains text transcriptions from customer service phone calls and there destination intents (TrueVoice's [Mari](http://www.truevoice.co.th/en/true-voice-mari/)). Source: https://github.com/PyThaiNLP/truevoice-intent
  - Input: phone call text transcriptions in Thai.
  - Target: phone call intents which includes:
    - billing and payment
    - promotions
    - internet
    - other queries
    - international dialing
    - true money
    - lost and stolen
  
## Transfer Learning Using GPU
Main processes to fintune BERT in Thai using GPU on Google Colab include:
  - setting up Google Colab runtime with GPU acceleration.
  - installing all required libraries.
  - downloading all required files.
  - tokenizing data using SentencePiece which implements BPE
  - finetuning BERT.
  - testing model's accuracy.
  
## Result
2 epochs: accuracy = 0.8921

![confusion_matrix](https://github.com/KongpolC/thai_intent_classification_using_bert/blob/master/images/confusion_matrix.png)

  

