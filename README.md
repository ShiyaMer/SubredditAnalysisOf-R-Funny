# SubredditAnalysisOf-R-Funny
Scrapped Data and Made a Tableau Dashboard


Data Collection:
Data collected using Praw API.

Collected Top Posts
Features Collected were:
Index(['title', 'author', 'date', 'timestamp',
'score', 'upvotes', 'downvotes',
 'up_ratio', 'total_awards_received',
'golds', 'cross_posts',
 'No.of.comments' ]dtype='object')

 
Data PreProcessing:
Cleaning: Removal of Missing Values
For making a word cloud in Dashboard, I
had to preprocess text which included
1)Punctuation Removal
2)Stopward Removal
3)Tokenization
4)Lemmatization
Also Time was in utc format,since I
needed only year for analysis converted
that.
Also Performed Sentiment anlysis by
using SentimentIntensityAnalyzer of
nltk.sentiment.vader
By which my feature set had these
additional features {cleaned_headlines',
'Negative_Sentiment',
 'Positive_Sentiment',
'Neutral_Sentiment', 'compound', 'Label'}



