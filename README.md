


# Transformers for Natural Language Processing
This is the code repository for [Transformers for Natural Language Processing](https://www.packtpub.com/product/transformers-for-natural-language-processing/9781800565791), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.

* **Paperback**: 384 pages
* **ISBN-13**: 9781800565791
* **Date Of Publication**: January 2021

[<img src="./.other/cover.png" width="248">](https://www.amazon.com/Transformers-Natural-Language-Processing-architectures-ebook/dp/B08S977X8K/)

## Links

* [Amazon](https://www.amazon.com/Transformers-Natural-Language-Processing-architectures-ebook/dp/B08S977X8K/)

* [Packt Publishing](https://www.packtpub.com/product/transformers-for-natural-language-processing/9781800565791)

## About the Book
Transformers for Natural Language Processing investigates in vast detail the deep learning for machine translations, speech-to-text, text-to-speech, language modeling, question answering, and many more NLP domains in context with the Transformers.

The book takes you through Natural language processing with Python and examines various eminent models and datasets in the transformer technology created by pioneers such as Google, Facebook, Microsoft, OpenAI, Hugging Face, and other contributors.

The book trains you in three stages. The first stage introduces you to transformer architectures, starting with the original Transformer, before moving on to RoBERTa, BERT, and DistilBERT models. You will discover training methods for smaller Transformers that can outperform GPT-3 in some cases. In the second stage, you will apply Transformers for Natural Language Understanding (NLU) and Generation. Finally, the third stage will help you grasp advanced language understanding techniques such as optimizing social network datasets and fake news identification.

By the end of this NLP book, you will understand transformers from a cognitive science perspective and be proficient in applying pre-trained transformer models by tech giants to various datasets.

## Things you will learn
* Use the latest pretrained transformer models
* Grasp the workings of the original Transformer, GPT-2, BERT, T5, and other transformer models
* Create language understanding Python programs using concepts that outperform classical deep learning models
* Use a variety of NLP platforms, including Hugging Face, Trax, and AllenNLP
* Apply Python, TensorFlow, and Keras programs to sentiment analysis, text summarization, speech recognition, machine translations, and more
* Measure the productivity of key transformers to define their scope, potential, and limits in production

## Instructions and Navigation
All of the code is organized into folders that are named chapter-wise, for example: `Chapter02`.

The code will look like the following:
```python
#@title Activating the GPU
# Main menu->Runtime->Change Runtime Type
import tensorflow as tf
device_name = tf.test.gpu_device_name()
if device_name != ‘/device:GPU:0’:
  raise SystemError(‘GPU device not found’)
print(‘Found GPU at: {}’.format(device_name))
```

## Software Requirements

Check this file for the hardware and software requirements: [technical_requirements.md](./.other/technical_requirements.md)

## Related Products

* [Python Machine Learning - Third Edition](https://www.packtpub.com/product/python-machine-learning-third-edition/9781789955750)
* [Hands-On Explainable AI (XAI) with Python - Second Edition](https://www.packtpub.com/product/hands-on-explainable-ai-xai-with-python/9781800208131)

### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781800565791">https://packt.link/free-ebook/9781800565791 </a> </p>