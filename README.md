# youtube-analysis

# 1. Sentiment analysis on Youtube comments

The first analysis is regarding a database with comments from multiple YouTube videos.<br>
I used TextBlob, a NLP library to perform the sentiment analysis and Wordcloud library to present the most common words, in positive and negative comments, in a visual and appealing way.<br>Since emojis are so common nowaday, I also did some analysis regarding emojis in the comments.<br>

File: YT_comments_sentiment_analysis.ipynb<br>

## Sentiment Analysis
For the sentiment analysis, using TextBlob, I only considerer the high positive (polarity=1) and high negative(polarity=-1).<br>

| | Count | Percentage of total |
| -------- | ------- | ---------- |
| High Positive | 19391 | 6.22% |
| High Negative | 3508 | 0.51% |

<br>
The most common words for each were:<br>
High Positive<br>
![High Positive Words](images/positive.png "a title")<br>

High Negative<br>
![High Negative Words](images/negative.png "a title")


## Emoji Analysis

# 2. Youtube Category Analysis

[Objetivo da analise]

File: YT_category_analysis.ipynb

[Conclusões por alto]