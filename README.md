# ProductSentimentAnalysis
Homework # 4 for the course **Advanced Data Mining and Language Technologies**

## Brief description
The assignment consists in the analysis of customer ratings and comments for a set of products and constructing a language model that can classify a customer's comments as negative or positive.

Of the following dataset we quantize the 4 possible `ratings` into a binary feature (positive or negative comment) that we use as a label for implementing supervised models and consider `title` and `review_text` as the only informative features for classification. 

<img width="891" alt="dataset2" src="https://github.com/Engrima18/ProductSentimentAnalysis/assets/93355495/6f2f185b-05f2-41ec-ada4-f6672376d972">


The model we prefer is a Neural Network model based on a BERT pre-trained model for the embedding part fine-tuned with a simple _Fit Foward Neural Network_.



