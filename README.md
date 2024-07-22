# A Computational Analysis of Incel Hate Speech Across Reddit with Sentiment Analysis and LLM's

## About this project
This project uses Natural Language Processing (NLP) and Machine Learning (ML) techniques to detect, analyze, and track misogynistic hate speech in communities on Reddit. I focus on the banned "Incels" subreddit and its spin-offs subreddits, employing:

- Hate speech detection using fine-tuned BERT models
- Sentiment analysis to gauge emotional trends
- Vector space analysis for visualizing linguistic patterns
- Temporal analysis to track the evolution of incel rhetoric post ban

Our dataset comprises 5,000 posts from the banned "Incels" subreddit and 10,000 posts from other subreddits. This research aims to provide insights into the dynamics of online hate speech and contribute to more effective content moderation strategies.


## Important Note
I originally built this project in 2021 while I was getting my masters. With all the advancements in LLM's I wanted to revisist the project, and display some findings that I think are interesting. 

Back when I originally worked on this project, the __Reddit Pushshift API was still available__. Since I was dealing with millions of posts, I relied heavily on the API and did not save most of my data :( I did save around 5,000 posts as a small sample dataset, and am using this data. Thus, if you are wondering why I am using spark for 5,000 data points, it is because orgiginally (and hopefully at some point in the future) I was dealing with millions of rows of data.

One day, when I have time, I will go through the Pushshift dumps and extract the data I need!
