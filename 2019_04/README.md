# Understanding Sentiment and Intent: Transfer learning for Natural Language

| Presenter | Date | Slides | Code | Interactive |
|:---------:|:----:|:------:|:----:|:----:|
| Nikhil Deshmukh | 2019-04-18 | [slides](understanding_sentiment_and_intent_slides.pdf) | [code](KnoxData_Language_Modeling.ipynb) | [colab](https://colab.research.google.com/drive/1rX98Bcm-DRlwEpRD4UM0O_-U2yb33rAs) |

## Abstract

Text data is meaningful in many contexts, but can also be difficult to work with for machine learning because of its complexity and ambiguity. Until recently, the state of the art for natural language processing was to use word embeddings, converting each word to a fixed length vector that preserves the semantic meaning. This past year researchers [[1]](https://arxiv.org/pdf/1801.06146.pdf) have found that they could train general purpose deep language models and then apply these models in a variety of NLP tasks such as summarization, text classification, named entity recognition, question answering and many many more using transfer learning. This a watershed moment for NLP, on par with the impact of pre-trained deep neural classifiers for ImageNet that revolutionized the field of computer vision over the last 7 years.

This talk will provide some historical context on embeddings and language modeling, as well as a demo of how to adapt a deep language model pretrained on millions of sentences from Wikipedia to perform sentiment analysis and intent classification with very small sets of novel training data.  

1. Howard, Jeremy, and Sebastian Ruder. "Universal language model fine-tuning for text classification." *arXiv preprint arXiv:1801.06146* (2018). https://arxiv.org/pdf/1801.06146.pdf

[Paper](1801.06146.pdf)

## About Speaker

Nikhil Deshmukh is an independent data science consultant who has applied his expertise to everything from embedded low-power computer vision for autonomous vehicles, optimizing HR processes for Fortune 500 companies, and developing IoT solutions for precision agriculture in rural India. Nikhil received his PhD in Neuroscience and Molecular Biology from Princeton University, where he studied the neural circuitry in the retina that converts light into electrical signals.