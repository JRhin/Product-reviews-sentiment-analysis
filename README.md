# ProductSentimentAnalysis
Homework # 4 for the course **Advanced Data Mining and Language Technologies**

## Brief description
The assignment consists in the analysis of customer ratings and comments for a set of products and constructing a language model that can classify a customer's comments as negative or positive.

Of the following dataset we quantize the 4 possible `ratings` into a binary feature (positive or negative comment) that we use as a label for implementing supervised models and consider `title` and `review_text` as the only informative features for classification. 

<img width="891" alt="dataset2" src="https://github.com/Engrima18/ProductSentimentAnalysis/assets/93355495/6f2f185b-05f2-41ec-ada4-f6672376d972" align="center">


The model we prefer is a Neural Network model based on a BERT pre-trained model for the embedding part fine-tuned with a simple _Feedfoward Neural Network_.

<img width="830" alt="finetune" src="https://github.com/Engrima18/ProductSentimentAnalysis/assets/93355495/2c1decfb-5adc-40a4-b42c-870b8f4093f5" align="center">

## Model selection

In the first part of the homework we try different combinations of encoding techniques and machine learning models to compare them. Go to the notebook for further information abouot our choices. <a target="_blank" href="https://colab.research.google.com/github/Engrima18/ProductSentimentAnalysis/blob/main/ADMLT2023_HW4_notebook.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

TF-IDF + Complement Naive Bayes            |  Word2Vec + RandomForest        | BERT + XGBoost
:-------------------------:|:-------------------------: |:-------------------------:
<img width="385" alt="cm1" src="https://github.com/Engrima18/ProductSentimentAnalysis/assets/93355495/91bf54af-0bfd-4c01-84eb-be322a61a8d1">
 | <img width="490" alt="jelly" src="https://user-images.githubusercontent.com/93355495/234046309-ee59d22a-ee97-467d-a5ba-06b2656240ed.png"> | <img width="490" alt="jelly" src="https://user-images.githubusercontent.com/93355495/234046309-ee59d22a-ee97-467d-a5ba-06b2656240ed.png">
<br />


