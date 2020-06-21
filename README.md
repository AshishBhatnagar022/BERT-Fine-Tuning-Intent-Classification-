# BERT-Fine-Tuning-Intent-Classification-
<h2>What is BERT?</h2>
<p>BERT (Bidirectional Encoder Representations from Transformers), released in late 2018, is the model we will use in this tutorial to provide readers with a better understanding of and practical guidance for using transfer learning models in NLP. BERT is a method of pretraining language representations that was used to create models that NLP practicioners can then download and use for free. You can either use these models to extract high quality language features from your text data, or you can fine-tune these models on a specific task (classification, entity recognition, question answering, etc.) with your own data to produce state of the art predictions.

This post will explain how you can modify and fine-tune BERT to create a powerful NLP model that quickly gives you state of the art results.</p>.
<h2>Data</h2>
Text classification is a supervised learning technique so we’ll need some labeled data to train our model. I’ll be using this public news classification dataset. It’s a manually labeled dataset of news articles which fit into one of 4 classes: Business, SciTech, Sports or World.<h2>Description</h2>
<p> In this project I have built a Intent classsification model using BERT. I have used transformers package from the Hugging face library.
I have fine tunned the model such that with much less data and only about traning on 6 epochs using Tesla K100 GPU, I was able to achieve 92% accuracy on test set.
It contains four classes namely Business,SciTech,World and Sports.
The raw text input was first converted into Tokens by BERT Tokenizer and then it is fed into the BERT model where the output gives the highest
probability class.</p><br>




<img src="http://www.mccormickml.com/assets/BERT/padding_and_mask.png" width="600">


<h2>Results</h2>
<p>The model able to gives 92% accuracy on the test set.
