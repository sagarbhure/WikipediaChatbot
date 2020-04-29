# Building a Simple Chatbot from Scratch in Python (using NLTK)

History of chatbots dates back to 1966 when a computer program called ELIZA was invented by Weizenbaum. It imitated the language of a psychotherapist from only 200 lines of code.On similar lines let's create a very basic chatbot utlising the Python's NLTK library.It's a very simple bot with hardly any cognitive skills,but still a good way to get into NLP  and get to know about chatbots.

![alt text](https://github.com/sagarbhure/WikipediaChatbot/blob/master/chatbot.PNG)

## Motivation
The idea of this project come from creating a wikepedia like bot who can specific answers based on political leaders, movie genere and raiting, and many more to let the audience know what they want without wasting time over internet sercing for their answers.

This project is into development to add intelligence to the bot to make smart interactions, and add more topics. Currently mostly it's backend ready, will work on frontend whenever frontend is ready. Reach out to me for any suggesition at [Sagar Bhure(https://sagarbhure.github.io/)


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


