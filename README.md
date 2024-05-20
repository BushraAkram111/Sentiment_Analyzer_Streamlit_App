(https://www.altexsoft.com/static/blog-post/2024/4/9f5946d6-d060-4aaa-b1c3-e64795227a1c.jpg)
<br>

# Sentiment Analyzer_App 😊😐😔😡

<br>

## About
**A sentiment analysis application built using Streamlit (an open-source framework for building web applications in Python)**

Sentiment Analysis is a prominent application of Natural Language Processing (NLP). It can be applied wherever data exists, whether it be text, audio, video, or images. Data in any form can be processed to extract sentiments. The objective of this project is to create a web application that encompasses various sentiment analysis applications, from text analysis to image sentiment assessment.

<br>

## Project Specifications

**Libraries and frameworks used in this project:**
- **Web Framework** :- Streamlit
- **Graphs and Images** :- PIL, plotly, cv2
- **Libraries for sentiment analysis** :- textblob, nltk(vader), flair, text2emotion, fer
- **Libraries for API requests** :- requests, json

<br>

## Project Components

**The project currently contains 3 applications :-**
1. **Text** - Applying sentiment analysis on user text.
2. **IMDb movie reviews** - We get review data based on movie entered by user from the IMDb API and process the same to obtain emotions of people regarding the movie.
3. **Image** - here you can check your image sentiment.

<br>

### **API specifications**
To get reviews, we will need to make 2 API calls. 
1. Get movies based on user input. Each movie received will have a unique id.
2. Get reviews for a movie by passing the unique id associated with it received from the above API call.


**Movie API** - https://imdb-api.com/en/API/SearchMovie/{apiKey}/{movieName}    
    
**Review API** - https://imdb-api.com/en/API/Reviews/{apiKey}/{id}

<br>

## Models used
There are multiple libraries available in python for sentiment analysis. Let's see them below 👇

- **TextBlob** - TextBlob is a Python library for processing textual data. It provides a simple API for diving into common (NLP) tasks such as part-of-speech tagging, noun phrase extraction, sentiment analysis, classification, translation, and more.
- **Flair** - A very simple framework for state-of-the-art NLP. It is a powerful NLP library which allows you to apply state-of-the-art natural language processing (NLP) models to your text, such as named entity recognition (NER), part-of-speech tagging (PoS), etc.
- **Vader** - VADER (Valence Aware Dictionary and Sentiment Reasoner) is a lexicon and rule-based sentiment analysis tool that is specifically attuned to sentiments expressed in social media. 
- **text2emotion** - text2emotion is the python package which will help you to extract the emotions from the content. It processes any textual message and recognize the emotions embedded in it. It is compatible with 5 different emotion categories as Happy, Angry, Sad, Surprise and Fear.

