# Building a Simple Chatbot from Scratch in Python (using NLTK)

![Alt text](https://cdn-images-1.medium.com/max/800/1*pPcVfZ7i-gLMabUol3zezA.gif)

History of chatbots dates back to 1966 when a computer program called ELIZA was invented by Weizenbaum. It imitated the language of a psychotherapist from only 200 lines of code. You can still converse with it here: [Eliza](http://psych.fullerton.edu/mbirnbaum/psych101/Eliza.htm?utm_source=ubisend.com&utm_medium=blog-link&utm_campaign=ubisend). 

On similar lines let's create a very basic chatbot utlising the Python's NLTK library.It's a very simple bot with hardly any cognitive skills,but still a good way to get into NLP and get to know about chatbots.


# Outline
* [Motivation](#motivation)
* [Blogpost](#blogpost)
* [Pre-requisites](#pre-requisites)
* [How to run](#how-to-run)


## Motivation
The idea of this project was not to create some SOTA chatbot with exceptional cognitive skills but just to utilise and test my Python skills.This was one of my very first projects, created  when I just stepped into the world of NLP and I thought of creating a simple chatbot just to make use of my newly acquired knowledge.


## Inspiration

### BlogPost
For detailed overview, here is the accompanying blog titled:**[Building a Simple Chatbot in Python (using NLTK)](https://medium.com/analytics-vidhya/building-a-simple-chatbot-in-python-using-nltk-7c8c8215ac6e)**

### Credit
[parulnith's chatbot.ipynb](https://github.com/parulnith/Building-a-Simple-Chatbot-in-Python-using-NLTK/blob/master/Chatbot.ipynb) 



## Pre-requisites
**NLTK(Natural Language Toolkit)**

[Natural Language Processing with Python](http://www.nltk.org/book/) provides a practical introduction to programming for language processing.

For platform-specific instructions, read [here](https://www.nltk.org/install.html)

### Installation of NLTK
```
pip install nltk
```
### Installing required packages
After NLTK has been downloaded, install required packages
```
import nltk
from nltk.stem import WordNetLemmatizer
nltk.download('popular', quiet=True) # for downloading popular packages
nltk.download('punkt') 
nltk.download('wordnet') 
```

## How to run
* Jupyter Notebook [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dnzengou/Building-a-Simple-Chatbot-in-Python-using-NLTK/master?urlpath=https%3A%2F%2Fgithub.com%2Fdnzengou%2FBuilding-a-Simple-Chatbot-in-Python-using-NLTK%2Fblob%2Fmaster%2FChatbot.ipynb)
```
https://hub.gke.mybinder.org/user/dnzengou-buildi-thon-using-nltk-iilsjoko/https://github.com/dnzengou/Building-a-Simple-Chatbot-in-Python-using-NLTK/blob/master/Chatbot.ipynb

https://mybinder.org/v2/gh/parulnith/Building-a-Simple-Chatbot-in-Python-using-NLTK/master 
```

You can run the [chatbot.ipynb](https://github.com/dnzengou/Building-a-Simple-Chatbot-in-Python-using-NLTK/blob/master/Chatbot.ipynb) which also includes step by step instructions.
* Through Terminal
```
python chatbot.py
```

### Data & other sources
![CovidQA on CORD-19](https://raw.githubusercontent.com/castorini/pygaggle/master/data/kaggle-lit-review-0.1.json)
![Rapidly Bootstrapping a Question Answering Dataset for COVID-19: Here](https://cord-19.apps.allenai.org/?q=dataset&o=0&sz=10)
![and here](https://www.semanticscholar.org/paper/Rapidly-Bootstrapping-a-Question-Answering-Dataset-Tang-Nogueira/0f995b05821b58b02e914422b56fba615d0e8d7f)
![Allen Institute for AI- Kaggle challenge for COVID-19 NLP](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge)
