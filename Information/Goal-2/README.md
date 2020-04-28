# Information: Goal 2

**“I would like to get more confident and do nice data visualizations (with python if possible)”**. 
 * **Background**: I have some experience with maps and plots, specially with GIS softwares like ArcGIS or QGIS. I have not much experience with maps and plots in Python nor ArcGIS Online.  
 * **How?** I will analyse the twitter and weather datasets and try to find patterns and correlations. I will represent the results in plots and some maps elaborated with python.
 
## Results
I ended up doing a lot of the cartographic work from the different analysis.

* **Python**
  * In Python I mostly did graphs and plot visualizations, however I also tried to do some simple maps. 
  
* **QGIS**
  * In QGIS, firstly, I read the output CSV files from the pre-processing and cleaning to geolocalize all the tweets in order to analyse them.
  <details>
    <summary><b>QGIS Maps</b> (click to expand)</summary>
 
  <!-- toc -->
  |                  Title                 |  Map  | Elaboration                                            |
  |:---------------------------------------:|:-------:| ----------------------------------------------------------------- |
  |Total tweets by Hexagonal Grid  |[<img src="https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Information/Goal-2/Qgis/Tweets_Hex_Grid.png" width=50% />](https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Information/Goal-2/Qgis/Tweets_Hex_Grid.png)| Hexagonal Grid elaborated with MMQIS plugin. Then, "Count points in Polygon". 3D visualization elaborated with Qgis2threejs. |
  |Tweets by Building |[<img src="https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Information/Goal-2/Qgis/TweetsByBuilding2.png" width=50% />](https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Information/Goal-2/Qgis/TweetsByBuilding2.png)|Queried the buildings from QuickOSM plugin. Then, "Count points in Polygon. Used CartoDbDarkMatter background and inversed Viridis color ramp |
  |Positive and Negative Tweets by Land Use Type |[<img src="https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Information/Goal-2/Qgis/LanduseType_Tweets.png" width=50% />](https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Information/Goal-2/Qgis/LanduseType_Tweets.png)|Downloaded the land use types from [Amsterdam Open Data](https://data.amsterdam.nl/), then I used the tool "Join Attributes by Location" with the tweet points.|
  |Positive and Negative Tweets Clusters|[<img src="https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Information/Goal-2/Qgis/positive_tweets_cluster.png" width=50% />](https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Information/Goal-2/Qgis/positive_tweets_cluster.png) [<img src="https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Information/Goal-2/Qgis/negative_tweets_cluster.png" width=50% />](https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Information/Goal-2/Qgis/negative_tweets_cluster.png)|To do this map, I created an squared/rectagonal grid over the tweets area. Then, I counted the points in polygons and I created centroids from the grid squares. I used the size assistant to use the flannery scale method.|
  <!-- tocstop -->
  
  </details>
  
* **ArcGIS Pro and ArcGIS Online**
  * Since we wanted to present our project in an [ArcGIS StoryMap](https://storymaps.arcgis.com/stories/9af24266f96e42e4aae1daf34ad4ac3e) that included cartographical visualizations, I thought it would be a good oportunity to practise with ArcGIS Pro and ArcGIS Online. 
  <details>
    <summary><b>ArcGIS Maps</b> (click to expand)</summary>
 
  <!-- toc -->
  |                  Title                 |  Map  | Elaboration                                            |
  |:---------------------------------------:|:-------:| ----------------------------------------------------------------- |
  |Positive and Negative Tweets by Land Use Type  |[<img src="https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Information/Goal-2/Qgis/Tweets_Hex_Grid.png" width=50% />](https://github.com/gerardathletics/SmartEnvironments-PersonalPortfolio/blob/master/Information/Goal-2/Qgis/Tweets_Hex_Grid.png)| Downloaded the land use type from [Amsterdam Open Data](https://data.amsterdam.nl/), then|

  <!-- tocstop -->
  
  </details>
