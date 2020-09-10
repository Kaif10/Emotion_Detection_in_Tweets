## Emotion detetion in tweets
main code :(Emotion_detection.ipynb)



I did this project in June 2020. A time when distress was at an all-time high because of coronavirus pandemic and Anti-racism protests.
   I coded a bi-directional LSTM network trained it on emotion-detection dataset and tested it on the recent tweets of 'BlacklivesMatter' movement on twitter  which I scraped using Beautiful Soup. 
   
![alt text](https://i.ytimg.com/vi/1gQ6uG5Ujiw/maxresdefault.jpg)


#Why Bi-Directional LSTMs?
Because they solve  a very common problem of vanishing gradients in neural nets and also the are termed as 'Memory Networks' that can remember the far behind and ahead of whats in the sequence and so I consider it as the best architecture for text classification.
 ![alt text](https://i.stack.imgur.com/iIiYO.png)

extra file: In this project I have also included a file where I have scraped  tweets using Beautiful Soup.
