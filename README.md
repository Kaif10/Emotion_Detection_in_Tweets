# Friends_emotion-detection-with-NLP
main file(Emotion_detection.ipynb)

I did this project in June 2020. A time when distress was at an all-time high because of coronavirus pandemic and Anti-racism protests. A lot of protests were conducted all across the globe. People displayed grief on Twitter and Social Media was filled with grief because of racial in-equality cases and police brutality. So i decided to check on my friends and Twitter CEO Jack Dorsey (who was posting a lot of great stuff regarding importance of Racial-Equality and protests) by scraping their tweets with 'twitter_scraper'  and extracting emotion from it with Neural Nets.
   
   I coded a bi-directional LSTM network trained it on emotion-detection dataset and tested it on the recent tweets of 'BlacklivesMatter' movement on twitter. In this project I have also included a file where I have scraped  tweets using Beautiful Soup.
   
[alt text](https://blog.skyl.ai/hs-fs/hubfs/Twitter-sentiment-analysis-1.jpg?width=2138&name=Twitter-sentiment-analysis-1.jpg)

#Why Bi-Directional LSTMs?
Because they solve  a very common problem of vanishing gradients in neural nets and also the are termed as 'Memory Networks' that can remember the far behind and ahead of whats in the sequence and so I consider it as the best architecture for text classification.
 ![alt text](https://i.stack.imgur.com/iIiYO.png)
