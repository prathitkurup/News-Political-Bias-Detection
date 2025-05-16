# News-Political-Bias-Detection

Deep Learning Final Project

Zero Shot Zealots: Albert Tang, Prathit Kurup, Sandesh Ghmire

## Abstract:

We created a model for detecting political bias of news articles based on headlines and content. We trained on the [Qbias dataset](https://github.com/irgroup/Qbias). Qbias is a dataset of over 21 thousand news articles classified as left-, center-, or right-leaning with their headlines, tags, source, and text. These news articles are sourced and rated for bias by professionals at US-based news aggregator [AllSides](https://www.allsides.com/unbiased-balanced-news).

## To Run:

To run our training-testing pipeline, run the notebook cells (in News_Bias_Detector.ipynb) in order. To train any one of the LSTM, TF-IDF, or BERT models, look for the relevant section and run all cells in the section in order. Refer to comments in the notebook for further guidance on functionality.

## Milestone 1:

In this milestone, we loaded the data, processed it, and ran some basic data epxloration. We have defined an X and y to use in training and testing.

## Milestone 2:

In this Milestone, we trained our baseline LSTM model on our data and evaluated its accuracy, precision, recall, and F1.

## Final Models:

Our first model is a custom LSTM baseline. This model achieved an accuracy of nearly 99%.
For our second model we used a term frequency–inverse document frequency (TF-IDF) model to experiment with another type of model with increased complexity. This model only achieved around 91% accuracy.
Our final model is a finetuned BERT model using the pre-trained bert-medium-en-uncased. This model performed just as well with an accuracy nearing 99%.
