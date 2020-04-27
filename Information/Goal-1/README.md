# Information: Goal 1

**“I would like to learn how to do a sentiment analysis on a text with python”** 
  * **Background**: 
 * **How?** I will explore different methodologies to achieve that. Some specific libraries and machine learning algorithms can help with the process.
 
 ## **Results**
The result is in the [same notebook](https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Data/Goal-1/Codes/TWITTER%20CLEANING%20-%20Group%202.ipynb) we elaborated the twitter data cleaning because we used directly that dataframe after the cleaning, and even though we analyse the tweets, we can still consider it a kind of pre-processing step before the geographical analysis. 
  * For the analysis we used the TextBlob library. We did two analyses:
    * Subjectivity: determines how subjective is the text (0 score is a fact and +1 is an opinion)
    * Polarity: determines positivity or negativity of the tweet (-1 is the highes negative score and +1 is the highes positive score.
  * From the polarity, we categorized it into Negative, Neutral and Positive.
  * We stored it to a new csv file.
 
  ![Positive, Neutral and Negative Tweets after processing and sentiment analysis](https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Information/Goal-1/Data2/PNN_Plot.png)
