# nlpcw

We designed a system to categorize offensive tweets as part of the Semeval-2018 challenge. We achieved our best performance with GloVe embeddings fed into a neural network consisting of a two convolutional layer feature extractor and five dense layers for classification. The fully connected layers also received the tweet's sentiment as input.

For an overview of our final model (and the method we used to design it), please see
model_design_and_bayesian_optimization.ipynb. 
