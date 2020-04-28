# DATA: GOAL 1 

**“Learning and improving how to properly and effectively clean data”** 
  * **Background**: Since now in most of the courses we’re given already clean datasets and I don’t have much experience.
 * **How?** Writing a clear code to clean effectively the twitter and weather data sets
(and possible more) with python.

## Results
**Codes**

I mainly worked in the weather data cleaning, however, I also colaborated in some parts of the twitter cleaning.
* [Weather Data Cleaning](https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Data/Goal-1/Codes/WEATHER%20DATA%20CLEANING%20-%20Group%202.ipynb)
  * This code cleans the [weather data set](https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Data/Goal-1/Data/KNMI_weather_data_cleaning.csv) from the KNMI.
  * It changes the name of the columns to make the process more understandable.
  * It selects useful information and drops the one we are not going to use.
  * It changes units of some variables (for example from 0.1ºC to ºC).
  * It converts the hourly data to daily data by making daily averages (for temperature for example), sums (sun hours for example) and other convenient conditions. Resulting in this [daily weather](https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Data/Goal-1/Data/dailyweather.csv) data set.
  * From the created daily weather conditions, it creates descriptive labels. Resulting in this [daily labels](https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Data/Goal-1/Data/weatherlabels.csv) data set.

* [Twitter Data Cleaning](https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Data/Goal-1/Codes/TWITTER%20CLEANING%20-%20Group%202.ipynb)
  * Personally, I didn't focus in this dataset but I collaborated in some parts and helped when needed. 
  * This code contains the preprocessing (cleaning) part of the tweets as well as the sentiment analysis, however, only the first mentioned part applies to this goal.
  * Basically, this code cleans the tweets, it removes innecessary symbols and irrelevant words for our analysis. It detects the languages and we only keep the english tweets. It also elaborates a "Tokenization", "Stemmization and "Lemmatization". 
  * The last part of the code elaborates the sentiment analysis, but this is for the information part.

* [Weather and Twitter Merging](https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Data/Goal-1/Codes/TWEET-WEATHER%20DATA%20MERGE%20-%20group%202.ipynb)
  * I created wrote this code to combine the two previous datasets in order to analyse them and extract some possible conclusions from the relationship between weather, tweets and locations.
  * It resulted in this [data frame](https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Data/Goal-1/Data/tweets_and_weather.rar) (it's in a RAR file because it's too heavy).
