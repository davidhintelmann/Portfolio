# David Hintelmann's Portfolio
Below is a collection of work that I have done, mostly Data Science related with machine learning, natural language processing, neural netowrks, an event driven FOREX trading app, and some minor web development for HTML/CSS/Javascript knowledge.

<br>
# Machine Learning

### [Supervised Machine Learning Project: Predicting Heart Disease](https://github.com/davidhintelmann/Heart-Disease)  

Cardiovascular diseases (CVDs) or heart diseases are the most prevalent disease globally. According to the World Health Organization (WHO), heart disease is the primary cause of death around the world and is estimated to cause about 17.9 million deaths a year, with four out of five deaths due to heart attacks and strokes

This is notebook was created investigate heart disease using a heart disease dataset from UC Irvine Machine Learning Repository. I will be using the processed Cleveland dataset since it has already been recduced from the original 76 attributes to 14. The goal is to predict if a patient has heart disease or not based on 13 features by creating multiple supervised machine learning models. Before this is done the data will be cleaned to find any missing values and potentially scaled or transformed to improved the ML model.

---

### [Portugal Hotel Booking Demand](https://github.com/davidhintelmann/Portugal-hotels)

This jupyter notebook has one dataset that has two different hotels from Portugal. This data will be analyzed to find any trends or patterns with guests booking into either hotel to try and find a way to minimize the amount of canceled bookings. A machine learning model will also be developed to attempt at predicting if a guest will cancel there booking before checking in.

There is a resort hotel in this dataset, found in the Algarve region of Portugal (southern Portugal), and a city hotel found in the captial Lisbon. Data was acquired directly from hotel's Property Managment System (PMS) SQL according to the paper which the data is originally from. The article is called, "Hotel Booking Demand Datasets", written by Nuno Antonio, Ana Almeida, and Luis Nunes for Data in Brief, Volume 22, February 2019. The artice can be found [here](https://www.sciencedirect.com/science/article/pii/S2352340918315191#bib5)

Dataset can also be found on [Kaggle](https://www.kaggle.com/jessemostipak/hotel-booking-demand)

---

### [Predictive Model on Spotify Dataset](https://github.com/davidhintelmann/Spotify-HitorNot)  

Spotify’s Web API includes interesting Audio Analysis data for tracks played on [Spotify](https://developer.spotify.com/documentation/web-api/reference/tracks/get-audio-analysis/​) and the intention is to use this low-level audio analysis for all the tracks in the entire Spotify Catalog. We are only using a sliver of the catalog that has been obtained from [Kaggle’s](https://www.kaggle.com/theoverman/the-spotify-hit-predictor-dataset) dataset, “The Spotify Hit Predictor Dataset (1960-2019)”. Features (columns) of this dataset are listed in the Data Preparation section below in greater detail and used to develop a machine learning model to predict if a track will be a “hit” or “flop”, making this a binary classification challenge.

---

### [Natural Language Processing](https://github.com/davidhintelmann/Natural-Language-Processing)
This notebook starts by using PRAW, "The Python Reddit API Wrapper" which will be used to download comments from the subreddit r/news/. PRAW can be used to create chat bots on reddit or just to scrap data from it to gain insights into online social media. I will use to Scapy to then perform natural language processing since this python library already have pretain models for this task. We will try to create an algorithm to detect online harassment, and in particular to flag if a comment has a high likihood of containing hate speech.

---

### [Yelp Dataset](https://github.com/davidhintelmann/Yelp_Investigation)
This dataset is a small portion of Yelp's businesses, reviews, and user data. It was originally put together for the Yelp Dataset Challenge which is a chance for students to conduct research or analysis on Yelp's data and share their discoveries. In the dataset you'll find information about businesses across 11 metropolitan areas in two countries.  
More information can be found at [Yelp](https://www.yelp.com/dataset/documentation/main).  
Some dataset examples can be found on their [GitHub](https://github.com/Yelp/dataset-examples)

<br>
# Neural Networks

### [Cactus-neural](https://github.com/davidhintelmann/Cactus-neural)
Neural Network to detect if an image has a cactus in it or not. Dataset can be found [here](https://www.kaggle.com/c/aerial-cactus-identification)

---

### [FashionMNIST-neural](https://github.com/davidhintelmann/FashionMNIST-neural)
Predicting the image's classification using fashion MNIST dataset and the PyTorch Library for Neural Networks.

---

### [Simple Neural Network](https://github.com/davidhintelmann/Simple-neural)
First neural network, very simple approach to classifying CIFAR-10 images.

---

<br>
# FOREX Trading App

### [Oanda REST API example](https://github.com/davidhintelmann/Oanda-REST-V20)

This link has two small apps developed for interfacing with [Oandas REST API](http://developer.oanda.com). Specifically using Oandas V-20 REST API.

Oanda-first only has downloading historical data prices for 'EUR_USD' FOREX prices, and scaling two different currencies.  

While Oanda-Event is an intro to an event driven software for streaming live prices from Oanda as well building on what was learned from Oanda-first to begin data collection for backtesting. Inspiration for the event driven software written in python comes from [Quant Start](https://www.quantstart.com/articles/Forex-Trading-Diary-1-Automated-Forex-Trading-with-the-OANDA-API/).
**Warning, this is for educational purposes only.**

<br>
# Minor Web Development

### [bootstrap.github.io](https://github.com/davidhintelmann/bootstrap.github.io)
Learning CSS and Bootstrap

---

### [Google-Api-Ex](https://github.com/davidhintelmann/Google-Api-Ex)

Simple Example using Google Javascript API One form that asks user to enter two locations to find directions between the two points entered.
