
# Headline generation by finetuning pretrained t5 model

# Introduction
We can finetuned a summarization model for headline generation. It works as a 
Text-2-text generation task . 
First we can choose a pretrained model from huggingface , where we can find several types of models. 

# Dataset:
Collect the dataset of your need. In this case we want to generate headlines for news articles. 
You can find the dataset on kaggle or you can make a dataset by crawling the content and title of news articles.

# Training:

Here we will train the model using transformer . Consider the articles as source text and headlines as target text finetune with a pretrained model.
Detailed training procedure you can find in jupyter notebook.
