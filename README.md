# Benchmark Study on The Effect of Preprocessing on Short Document Clustering
Abstract: Document clustering has gained popularity due to social media and its
large volume. Natural Language Processing is able to extract information
from unstructured data which can be powerful for businesses. Social media,
customer reviews and even military messages are all very short and therefore
harder to handle than longer texts. Cluster analysis is essential in gaining
insight from these unlabeled texts. Preprocessing often removes words, which
can become risky in short texts, where the main message is made of only
a few words. The effect of preprocessing and feature extraction on these
short documents is therefore analyzed in this paper. Six different levels of
text normalization are combined with four different feature extraction methods. 
These setting are all applied on K-means clustering and tested on three
different datasets. Anticipated results can not be concluded, however other
findings are insightful in terms of the connection between text cleaning and
feature extraction.


This study implements:
* TF-IDF
* TF-IDF with n-grams
* Word2Vec
* GloVe
* K-means clustering
* various degrees of text cleaning

Datasets used are from Amazon, Yelp and DBpedia found via "Xiang Zhang, Junbo Zhao, and Yann LeCun. Character-level convolutional
networks for text classification. In Advances in neural information processing
systems, pages 649{657, 2015"

This paper has been accepted in the Jounal Archives of Data Science: https://publikationen.bibliothek.kit.edu/1000121376
