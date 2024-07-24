# A Computational Analysis of Hate Speech Across Reddit with Sentiment Analysis and LLM's

## About this project
This project uses Natural Language Processing (NLP) and Machine Learning (ML) techniques to detect, analyze, and track misogynistic hate speech in communities on Reddit. I focus on the banned "Incels" subreddit and its spin-offs subreddits, employing:

- Subreddit classification through speech detection using Large Language Models [[Writeup](writeup-LLM.md)]
- Sentiment analysis to gauge emotional trends and vector space analysis for visualizing linguistic patterns [[Code](sentiment-vectorspace.ipynb)]


## Important Note
I originally built this project in 2021 while I was getting my masters. With all the advancements in LLM's I wanted to revisist the project, and display some findings that I think are interesting. 

Back when I originally worked on this project training LLMs, the __Reddit Pushshift API was still available__. Since I was dealing with millions of posts, I relied heavily on the API and did not save most of my data :( 
I did save a small subset of the data, and am using this subset for the sentiment and vector space analysis

One day, when I have time, I will go through the Pushshift dumps and extract the data I need!
