# Douyin Comment Sentiment Analysis

## Description
This is the repository for Capstone project Douyin Comment Sentiment Analysis, which aims to analyze the sentiment of comments on Douyin. Using a BERT-based model, we classify comments into positive, neutral, and negative categories. 

## Installation
To set up the project environment:

1. Clone the repository:

2. Install required packages:
pip install -r requirements.txt

Now you should be able to run all the notebooks in the Notebooks file.

## Data

## Data Acquisation

The review is scraped by MediaCrawler: https://github.com/NanmiCoder/MediaCrawler

## Data Description 

The number of original scraped comments is 77,330. These comments were derived from 173 videos, with 83 attributed to Li and 90 to Aito. The timeframe of the comment’s spans from March 2020 to April 2024. The scraped raw data includes critical columns such as Comment (the raw text of the comment), comment time, comment IP (publicly available in China), video link, video title, and video topic.

In the file Data:

Li_Comments.xlsx is the raw comments scraped from videos related Li.

Aito_Comments.xlsx is the raw comments scraped from videos related Aito.

Li_Video.xlsx is the video information of scraped videos related Li.

Aito_Video.xlsx is the video information of scraped videos related Aito.

annotated_li_comment.xlsx is the cleaned data for Li with sentiment label annotated with ChatGPT

annotated_aito_comment.xlsx is the cleaned data for Aito with sentiment label annotated with ChatGPT

annotated_translated_li_comment.xlsx is the data for Li with ChatGPT translation translated by ChatGPT

annotated_translated_aito_comment.xlsx is the data for Aito with ChatGPT translation translated by ChatGPT

## Notebooks

Data_Cleaning_N_EDA.ipynb shows the data cleaning and EDA process

Chatgpt_label.ipynb shows the process of ChatGPT annotation 

Chatgpt_translation.ipynb shows the process of ChatGPT translation

Translation_ cleaning.ipynb shows the process of cleaning translation

Finetine_Chinese_Bert.ipynb shows the process of finetuning Chinese BERT

Finetine_English_Bert.ipynb shows the process of finetuning English BERT

Sentiment_Analysis.ipynb shows the process of Sentiment Analysis

## TTF file 
STFangSong.ttf is the file for Chinese wordcloud.

## Credits
This project was developed by Changzhou Li. I acknowledge the contributions from Jesse Blocher for his invaluable feedback.
