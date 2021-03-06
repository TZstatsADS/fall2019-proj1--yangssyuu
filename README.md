# Applied Data Science @ Columbia
## Fall 2019
## Project 1: A "data story" on the lyrics of songs
![avatar](https://github.com/TZstatsADS/fall2019-proj1--yangssyuu/blob/master/figs/wordcloud.png)

### [Project Description](doc/)
This is the first and only *individual* (as opposed to *team*) this semester. 

Term: Fall 2019

+ Projec title: What's in song lyrics, such as Hip-Hop and Country
+ This project is conducted by [Siyu Yang]

+ Project summary: The goal of this project is to look deeper into the patterns and characteristics of different types of song lyrics. First, I load the raw data 'lyrics.RData' saved in data file. After text processing, I save it in output file as 'processed_lyrics.csv'.
+ steps included in the report 
  1. single word frequency (through time)
  2. positive and negative word frequency
  3. bigram words frequency
  4. comparison of sentiments of all genres
  5. important words in lyrics of different genres
+ Conclusion

1. Most lyrics would like to contain positive word "love".

2. The most frequent negative words for Country are more meaningful compared with those of Hip-hop.

3. Hip-hop likes to use two same words together and 'niggas','shit' seem to be important words in lyrics.

4. Rock expresses sentiments the strongest among all genres, while hip-hop expresses sentiments more intensively than that of Country.

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
